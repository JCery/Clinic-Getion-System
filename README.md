# Clinic-Getion-System
Sistema de Gestion de clinica web
## Objetivo
Desarrollar un sistema web que permita gestionar de forma organizada la información principal de una clínica, incluyendo usuarios, roles, pacientes, médicos y control de acceso.

## Problema que resuelve
El sistema busca reducir la gestión manual y desorganizada de información clínica, permitiendo centralizar los datos y controlar el acceso a las funcionalidades de acuerdo con el rol de cada usuario.

## Funcionalidades principales
- Inicio de sesión.
- Gestión de usuarios y roles.
- Registro y consulta de pacientes.
- Gestión de médicos.
- Control de acceso mediante roles y permisos.
- Validación de datos.
- Organización de tareas y seguimiento técnico mediante GitHub Projects.

## Arquitectura seleccionada
Se utiliza una arquitectura MVC complementada con separación por capas.

La solución se organiza en:
- Interfaz / Vistas.
- Controladores.
- Lógica de negocio.
- Autenticación y permisos.
- Acceso a datos.
- Base de datos PostgreSQL.

## Frontend
El frontend está compuesto principalmente por Razor Views y Bootstrap.

Su responsabilidad es presentar la interfaz al usuario, mostrar formularios, recibir información y presentar los resultados generados por el sistema.

## Backend
El backend está compuesto por los controladores ASP.NET Core MVC, la lógica de negocio, autenticación, control de acceso y acceso a datos.

Entre sus responsabilidades se encuentran:
- Procesar solicitudes del usuario.
- Aplicar reglas y validaciones.
- Controlar roles y permisos.
- Gestionar operaciones sobre pacientes y médicos.
- Comunicarse con la base de datos.

## Comunicación frontend/backend
Las vistas envían las solicitudes a los controladores. Los controladores coordinan la ejecución con la lógica de negocio y, cuando es necesario, acceden a los datos mediante Entity Framework Core y Npgsql.

La información procesada es devuelta a los controladores y posteriormente presentada al usuario mediante las vistas.

## Base de datos
El sistema utiliza PostgreSQL como sistema gestor de base de datos.

El acceso a los datos se realiza mediante:
- Entity Framework Core.
- Npgsql.
- ClinicaDbContext.

## Herramientas utilizadas
- ASP.NET Core MVC.
- C#.
- Razor Views.
- Bootstrap.
- Entity Framework Core.
- PostgreSQL.
- Npgsql.
- GitHub.
- GitHub Issues.
- GitHub Projects.
- Visual Paradigm Online.

## Estado actual del proyecto
El proyecto se encuentra en una versión inicial de desarrollo.

Actualmente se han trabajado:
- Requisitos funcionales.
- Historias de usuario.
- Diagramas UML.
- Arquitectura inicial.
- Gestión del avance.
- Autenticación y control de acceso.
- Planificación de módulos de pacientes y médicos.
- Organización de pruebas y documentación.

Aún quedan pendientes actividades relacionadas con pruebas funcionales, validación final de la base de datos, mejoras de interfaz y documentación técnica.

## Registro de cambios

### Versión inicial
1. Se documentaron los requisitos funcionales y no funcionales.
2. Se elaboraron diagramas UML para representar la estructura y comportamiento del sistema.
3. Se definió una arquitectura MVC complementada con separación por capas.
4. Se organizó el desarrollo mediante GitHub Projects e Issues.
5. Se incorporó la planificación de autenticación, gestión de pacientes, médicos y validación de datos.
