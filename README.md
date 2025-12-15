Sistema de Gestión de Seguridad Minera

Proyecto desarrollado como parte de la habilitación de Programación Orientada a Objetos (POO).

El sistema permite gestionar información relacionada con trabajadores, evaluaciones médicas, incidentes o accidentes y supervisores, utilizando el patrón Modelo Vista Controlador (MVC).

Arquitectura del sistema

El proyecto está organizado bajo el patrón MVC.

Modelo:
Incluye las clases Trabajador, EvaluacionMedica, IncidenteAccidente y Supervisor.
La clase GestorM se encarga de la lógica del negocio y la administración de los datos.

Vista:
Las interfaces gráficas fueron desarrolladas en Java Swing usando NetBeans.
Incluye las ventanas JFPrincipal, JFTrabajadores, JFEvaluacionesMedicas, JFAccidentes y JFSupervisores.

Controlador:
La clase Controlador gestiona los eventos generados por las vistas y coordina la comunicación con el modelo.

Funcionalidades principales

Gestión de trabajadores:
Registro de trabajadores
Eliminación de trabajadores
Consulta por nombre, identificación y cargo
Actualización de información

Gestión de evaluaciones médicas:
Registro de evaluaciones médicas
Consulta de evaluaciones por trabajador
Actualización de evaluaciones médicas

Gestión de incidentes o accidentes:
Registro de incidentes y accidentes
Actualización de incidentes
Consulta por tipo, fecha y trabajador

Gestión de supervisores:
Registro de supervisores
Actualización de supervisores
Búsqueda por nombre y cargo

Tecnologías utilizadas

Lenguaje Java
Java Swing
NetBeans
Git y GitHub

Ejecución del proyecto

El proyecto se ejecuta desde la clase principal HabilitacionPOO1_1152525.
Al iniciar la aplicación se muestra la ventana principal desde donde se accede al resto de funcionalidades.

Conceptos aplicados

Programación Orientada a Objetos
Encapsulamiento
Uso de listas dinámicas con ArrayList
Patrón Modelo Vista Controlador
Manejo de eventos con ActionListener
Separación de responsabilidades

Autor

Daniel
Estudiante de Programación Orientada a Objetos
Trabajo de habilitación académica
