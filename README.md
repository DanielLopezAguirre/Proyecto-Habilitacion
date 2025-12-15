# Sistema de Gestión de Seguridad Minera

Proyecto desarrollado como parte de la **habilitación de Programación Orientada a Objetos (POO)**.

El sistema permite gestionar información relacionada con trabajadores, evaluaciones médicas, incidentes/accidentes y supervisores, aplicando el patrón **Modelo–Vista–Controlador (MVC)**.

---

## 🧱 Arquitectura

El proyecto está estructurado bajo el patrón **MVC**:

- **Modelo (`modelo`)**
  - Contiene las clases de dominio:
    - `Trabajador`
    - `EvaluacionMedica`
    - `IncidenteAccidente`
    - `Supervisor`
  - Incluye la clase `GestorM`, encargada de la lógica del negocio y la gestión de datos.

- **Vista (`vista`)**
  - Interfaces gráficas desarrolladas con **Java Swing** y **NetBeans GUI Builder**:
    - `JFPrincipal`
    - `JFTrabajadores`
    - `JFEvaluacionesMedicas`
    - `JFAccidentes`
    - `JFSupervisores`

- **Controlador (`control`)**
  - Clase `Controlador`
  - Gestiona los eventos de las vistas y coordina la comunicación con el modelo.

---

## ⚙️ Funcionalidades

### Trabajadores
- Registrar trabajador
- Borrar trabajador
- Consultar información por:
  - Nombre
  - ID
  - Cargo
- Actualizar información

### Evaluaciones Médicas
- Registrar evaluación médica
- Consultar evaluaciones por trabajador
- Actualizar evaluación médica

### Incidentes / Accidentes
- Registrar incidente o accidente
- Actualizar incidente
- Consultar por:
  - Tipo
  - Fecha
  - Trabajador

### Supervisores
- Registrar supervisor
- Actualizar supervisor
- Buscar por:
  - Nombre
  - Cargo

---

## 🛠️ Tecnologías utilizadas

- **Java**
- **Java Swing**
- **NetBeans**
- **Git / GitHub**

---

## ▶️ Ejecución

1. Abrir el proyecto en **NetBeans**
2. Ejecutar la clase:
   ```java
   HabilitacionPOO1_1152525
