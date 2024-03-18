# DataExtractor
```metadatos
day: 2024-02-09
summary: Servicio de extracción de datos
type: note
author: [[Kevin Barroso|Kevin]]
tags: taba/dataextractor
```
## Resumen
Se debe desarrollar un extractor de datos (block), de forma unificada para los distintos esquemas de datos, esto determina el análisis, la investigación del recurso API REST por parte de la fuente de datos externa. Incorporando metadatos construidos por parte del equipo de Ing. de datos, la catalogación de los datos y el guardados de los datos en una base de datos, planteada en la arquitectura v1 del proyecto, un RDS Database de AWS. Se debe determinar el mejor servicio para garantizar la disponibilidad de las extracciones y la integridad de los datos a extraer. Determinar la frecuencia de extracción para la actualización correcta de los conjuntos de datos.
!!! info
    Block se refiere a un componente dentro del Stack, determinando una porción mas chica para el desarrollo e implementación dentro de la arquitectura completa, mucho mas eficiente para la granularidad de tareas y gestión.  
## Objetivo
El objetivo del extractor de datos es obtener información específica de la fuente de datos externa, con la necesidad de la extracción de esquemas de datos necesarios por parte de cada uno de los Stacks del proyecto. 
## Plan de acción
Por lo que se deben cumplir los siguientes lineamientos para el desarrollo, prueba e implementación del extractor:

- Modelo de extracción
- Contexto de error
- Modelo de testing
- Marco de código
- Typing
- Documentación de implementación, operación y errores
- Logs

### Backlog de tareas para el proyecto
- Diseño de extracción
- Modelo de extracción
- Marco de código
- Preparación del entorno
- Desarrollo
- Testing
- Contexto de error
- Seguridad
- Logs y observabilidad
- Documentación
- Deploy
## Roles y responsabilidades
La gestión del proyecto es determinada por el Project Manager de TABA, como también la construcción de este recurso. Se determina los siguientes perfiles y responsabilidades para el plan de acción:

- **Arquitecto de Nube**
	- Diseño y solución de la arquitectura actual
	- Selección y análisis de los servicios
	- Seguridad del entorno y los recursos
	- Preparación del entorno
	- Optimización de los costos
	- Gestión de la capacidad y escalabilidad
	- Orquestación y automatización
	- Criticidad y riesgos
	- Documentación de implementación y arquitectura
- **Ing. de datos**
	- Análisis de requisitos
	- Modelo de extracción
	- Marco de código
	- Catalogo de los datos
	- Política y seguridad de los datos
	- Resolución de problemas de datos
	- Validación de los datos
	- Documentación de los flujos de datos y modelos
- **Desarrollador ETL**
	- Diseño de proceso ETL
	- Desarrollo
	- Flujo de datos
	- Optimización de código y rendimiento
	- Contexto de errores
	- Pruebas y validaciones
	- Documentación de desarrollo y funcionalidad

## Conclusión 
Se considera determinar ajustes de tiempo debido a la asignación de tiempo y el perfil de cada uno de los roles para el desarrollo del bloque. Determinar un esquema de carga de trabajo para ajustes de tiempo y responsabilidades.
Dado la experiencia de los perfiles, la evolución del proyecto y necesidad del extracto se considera entre un marco de trabajo de 35 horas a 70 horas para el equipo en cuestión. Ya que se considera por primera vez en cuestiones de herramientas y uso de AWS de modo desarrollo.

:material-arrow-right-thick: [Atras](note.md)