# Documentación de Requisitos: Sistema de Gestión de Gimnasio

Este repositorio contiene la documentación de ingeniería de requisitos y especificación de casos de uso para un sistema integral de gestión de un gimnasio. El documento principal detalla las interacciones funcionales entre los distintos tipos de usuarios y el sistema, apoyándose en modelado UML.

## Equipo de Desarrollo / Autores
*   Juan Jiménez Jaraba
*   José Pedrajas de la Torre
*   Javier Fernández Basso
*   David Fernández Espejo

## Contenido del Proyecto

La documentación incluye un análisis detallado del comportamiento del sistema, estructurado en los siguientes apartados:

### 1. Actores del Sistema
Se han identificado e integrado en los casos de uso los siguientes perfiles de interacción:
*   **Usuario/Cliente:** Interactúa con los servicios del gimnasio.
*   **Monitor:** Gestiona actividades y rutinas.
*   **Administrador:** Controla el sistema y la gestión global.
*   **Técnico:** Encargado del mantenimiento de las instalaciones y equipos.

### 2. Diagrama de Casos de Uso General
Un diagrama unificado que muestra la visión global del sistema, ilustrando cómo cada actor se relaciona con las diferentes funcionalidades principales y cómo estas se conectan entre sí (utilizando relaciones avanzadas).

### 3. Especificación de Casos de Uso
Se detallan **14 casos de uso** documentados mediante plantillas estandarizadas en lenguaje natural. Cada especificación incluye:
*   Identificador y Nombre.
*   Precondiciones y Postcondiciones.
*   Secuencia normal (flujo principal de eventos).
*   **Escenarios alternativos y excepciones:** Se contemplan flujos secundarios para el manejo de errores o caminos alternativos en la lógica del negocio.
*   Relaciones de inclusión (`<<include>>`) y extensión (`<<extend>>`) para modularizar el comportamiento.

### 4. Diagramas de Comportamiento UML
Para complementar la especificación textual, se han modelado dinámicamente los escenarios utilizando:
*   **Diagramas de Actividad:** Para visualizar el flujo de control paso a paso y la toma de decisiones en los procesos.
*   **Diagramas de Secuencia:** Para detallar el intercambio de mensajes y la línea temporal de las interacciones entre los actores y los objetos del sistema.

## Metodología y Estándares
*   Uso de plantillas de atributos estructurados para la captura de requisitos.
*   Modelado de software basado en el estándar UML (Unified Modeling Language).
*   Enfoque en la trazabilidad funcional y el manejo de excepciones en los flujos de trabajo.
