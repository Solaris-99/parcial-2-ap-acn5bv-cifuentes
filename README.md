# Administración de Proyectos - Parcial II

![Logo DaVinci](DaVinci_logo.png)

- **Integrantes**:
    - Emanuel Cifuentes
- **Comisión**: ACN5AV
- **Profesor**: Sergio Medina


## Proyecto y objetivo

### Sobre el proyecto
La temática elegida para este trabajo es sobre el proyecto Pandora, que es también el proyecto para la Planificación del Seminario Final. 

Nota: Algunos artefactos de este trabajo practico se replicaron y adaptaron para ajustarse a la materia, entre ellos: Tablero de Trello, historias de usuario.

## Enlaces
- **Tablero**: [Trello](https://trello.com/b/amFLw3bq/pandora-adm-proyectos) 

### Objetivo general
Desarrollar una plataforma digital multiplataforma denominada Pandora que permita integrar artistas, usuarios y mecánicas de colección mediante un sistema donde las obras digitales puedan convertirse en cartas jugables generadas a partir de la percepción colectiva de la comunidad

### Objetivo SMART

Para el proyecto Pandora se seleccionó el enfoque de objetivos SMART en lugar de OKR (Objectives and Key Results) debido a la naturaleza y alcance del proyecto. SMART resulta más adecuado para un proyecto de desarrollo de software académico con un alcance definido, entregables concretos y un período de implementación limitado.
En el caso de Pandora, el objetivo principal no es alcanzar indicadores comerciales como adquisición de usuarios, ingresos o posicionamiento, sino construir un producto funcional cumpliendo un conjunto específico de requerimientos técnicos y funcionales. Por esta razón, SMART ofrece una definición más precisa y controlable del alcance del proyecto.

#### S (Specific / Específico)
Construir una plataforma web y móvil que permita a artistas publicar obras digitales, recibir evaluaciones mediante un sistema de estrellas y emociones, transformar dichas evaluaciones en atributos de cartas coleccionables y utilizar esas cartas dentro de un módulo de juego básico.

#### M (Measurable / Medible)
El proyecto se considerará cumplido cuando se implementen:

Sistema de registro y autenticación.
Gestión de perfiles de artistas.
Publicación de obras con descripción narrativa.
Sistema de evaluación comunitaria.
Motor de conversión de evaluaciones a cartas.
Inventario de cartas.
Sistema básico de batalla.

Estas funcionalidades corresponden al alcance definido del proyecto, donde se incluyen módulos como explorador de arte, calificación Q2Q, conversión de cartas y colección.

#### A (Achievable / Alcanzable)
El objetivo es viable debido a que el desarrollo utilizará tecnologías conocidas para el equipo como TypeScript, React, NestJS, PostgreSQL y Java para Android. Además, el alcance inicial se limita a un sistema funcional de juego básico, evitando una complejidad similar a un videojuego completo.

#### R (Relevant / Relevante)
El proyecto responde a una problemática identificada: las plataformas actuales de arte digital permiten exposición pero poseen poca interacción funcional, mientras que los juegos de cartas mantienen la creación de contenido centralizada. Pandora busca unir ambos modelos.

#### T (Time-bound / Temporal)
Implementar un prototipo funcional durante el período académico del seminario, organizado mediante entregas incrementales utilizando metodología ágil.

## Análisis de interesados y stakeholders
Los interesados principales son aquellos actores que interactúan directa o indirectamente con la plataforma.

### Stakeholder 1: Artistas digitales
Los artistas representan uno de los pilares del sistema, ya que la propuesta busca que las obras dejen de ser contenido estático y tengan una función dentro del ecosistema del juego.

- **Descripción**: Usuarios creadores de contenido que utilizan Pandora como medio de exposición y transformación de sus obras en cartas coleccionables.
- **Necesidades**:
    - Publicar obras.
    - Obtener visibilidad.
    - Recibir retroalimentación de la comunidad.
    - Transformar sus creaciones en elementos jugables.
- **Interés en el proyecto**: Alto.

### Stakeholder 2: Usuarios jugadores / comunidad
La comunidad tiene un rol activo porque sus valoraciones influyen directamente en la generación de estadísticas y características de las cartas.
- **Descripción**: Usuarios que exploran obras, califican contenido y utilizan cartas dentro del sistema.
- **Necesidades**:
    - Descubrir contenido.
    - Participar en la evolución de las obras.
    - Coleccionar cartas.
    - Jugar partidas.
- **Interés en el proyecto**: Alto.

### Stakeholder 3: Equipo de desarrollo / administradores
El proyecto requiere integración de múltiples tecnologías, manejo de imágenes, autenticación y protección contra comportamientos abusivos como bots.

- **Descripción**: Responsables de construir, mantener y administrar la plataforma.
- **Necesidades**:
    - Arquitectura mantenible.
    - Seguridad.
    - Control del contenido.
    - Escalabilidad.
- **Interés en el proyecto**: Alto.

## Metodología ágil
Para el desarrollo del proyecto Pandora se propone utilizar una combinación de **Scrum y Kanban**, debido a que ambas metodologías se adaptan a las características del proyecto: un sistema compuesto por múltiples módulos interrelacionados, un alcance que puede evolucionar durante el desarrollo y la necesidad de entregar funcionalidades funcionales de manera progresiva. **Scrum** se selecciona como metodología principal porque **permite organizar el desarrollo mediante sprints**, donde cada período de trabajo tiene objetivos concretos y entregables verificables, mientras que **Kanban** se incorpora como **complemento para gestionar el flujo diario de tareas** técnicas y controlar el trabajo pendiente.

### Scrum

Scrum es un marco de trabajo ágil orientado a la gestión de proyectos complejos mediante entregas incrementales. Su enfoque se basa en dividir el desarrollo en períodos cortos llamados sprints, donde el equipo trabaja sobre un conjunto priorizado de funcionalidades para generar una versión funcional del producto. Scrum busca mejorar la adaptación al cambio mediante planificación continua, revisión frecuente de avances y retroalimentación constante entre los integrantes del equipo.

#### Características
- **Sprints**: períodos de trabajo definidos donde se desarrollan objetivos concretos.
- **Product Backlog**: lista priorizada de funcionalidades y necesidades del proyecto.
- **Historias de usuario**: descripción de requerimientos desde la perspectiva del usuario final.
- **Incrementos funcionales**: cada sprint debe producir una mejora o parte utilizable del sistema.
- **Reuniones periódicas**: permiten revisar avances, detectar problemas y ajustar prioridades.
- **Roles definidos**: organización del equipo mediante responsabilidades como Product Owner, Scrum Master y equipo de desarrollo.

### Kanban

Kanban es una metodología ágil enfocada en la gestión visual del trabajo y la optimización del flujo de tareas. Su objetivo principal es mejorar la organización del desarrollo permitiendo identificar rápidamente el estado de cada actividad y detectar bloqueos que puedan afectar el avance del proyecto.

#### Características:
- **Tablero visual**: representa el flujo de trabajo mediante columnas como pendiente, en desarrollo, revisión y finalizado.
- **Gestión del flujo continuo**: las tareas avanzan de manera constante sin depender necesariamente de ciclos cerrados.
- **Límites de trabajo en progreso**: evita acumular demasiadas tareas simultáneamente.
- **Priorización de tareas**: permite ordenar actividades según importancia o urgencia.
- **Adaptabilidad**: facilita incorporar nuevas tareas o cambios durante el desarrollo.
- **Transparencia**: todos los integrantes pueden visualizar el estado actual del proyecto.


## Historias de Usuario y Requermientos Funcionales

# Historias de Usuario

| ID    | Historia de usuario                                                                                                 | Prioridad | Criterios de aceptación                                                                                             | Estimación (Story Points) |
| ----- | ------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| HU-01 | Como usuario quiero registrarme en la plataforma para crear una cuenta y acceder a las funcionalidades del sistema. | Alta      | El usuario puede completar el formulario de registro, sus datos quedan almacenados y puede ingresar posteriormente. | 3                         |
| HU-02 | Como usuario quiero iniciar sesión para acceder a mi perfil y funcionalidades personalizadas.                       | Alta      | El sistema valida credenciales y permite acceder a la cuenta correspondiente.                                       | 3                         |
| HU-03 | Como artista quiero crear y administrar mi perfil para mostrar información personal y mi portafolio.                | Alta      | El artista puede editar datos de perfil, visualizar sus obras y consultar estadísticas.                             | 5                         |
| HU-04 | Como artista quiero publicar una obra digital para compartirla con la comunidad.                                    | Alta      | El artista puede cargar una imagen, asignar título y agregar una descripción o Lore.                                | 5                         |
| HU-05 | Como usuario quiero explorar una galería de obras para descubrir contenido publicado por otros artistas.            | Media     | El usuario puede visualizar obras disponibles y acceder a información asociada.                                     | 5                         |
| HU-06 | Como usuario quiero calificar obras utilizando estrellas y emociones para expresar mi percepción sobre ellas.       | Alta      | El usuario puede seleccionar una valoración y una emoción asociada a una obra.                                      | 8                         |
| HU-07 | Como sistema quiero procesar las valoraciones de la comunidad para generar atributos de cartas coleccionables.      | Alta      | El sistema calcula estadísticas como ataque, defensa, vida y rareza según los datos obtenidos.                      | 13                        |
| HU-08 | Como usuario quiero obtener cartas generadas a partir de obras para ampliar mi colección personal.                  | Alta      | Las cartas creadas aparecen disponibles en el inventario del usuario.                                               | 5                         |
| HU-09 | Como usuario quiero visualizar mi colección de cartas para gestionar los elementos obtenidos.                       | Media     | El usuario puede consultar sus cartas, características y detalles.                                                  | 5                         |
| HU-10 | Como usuario quiero abrir paquetes de cartas para obtener nuevos elementos coleccionables.                          | Media     | El sistema permite generar paquetes y asignar cartas según reglas de obtención.                                     | 8                         |
| HU-11 | Como jugador quiero utilizar mis cartas en partidas para participar del componente lúdico de la plataforma.         | Alta      | El usuario puede seleccionar cartas y ejecutar una batalla dentro del sistema.                                      | 13                        |
| HU-12 | Como administrador quiero gestionar el contenido de la plataforma para mantener la calidad y seguridad del sistema. | Media     | El administrador puede supervisar usuarios, contenido reportado y funcionamiento general.                           | 5                         |

### Requerimientos funcionales
| ID Requerimiento | Módulo / Componente   | Descripción del Requerimiento Funcional                                                                                                                | HU Asociada | Tipificación      | Alcance |
|------------------|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|-------------------|------------------|
| RF-01.1          | Gestión de Usuarios   | El sistema debe permitir el registro de nuevos usuarios recolectando credenciales y datos básicos (sea artista o no).                            | HU-01       | ABM               | Web y Mobile     |
| RF-01.2          | Gestión de Usuarios   | El sistema debe permitir la integración con proveedores de identidad externos (Google y Discord OAuth2) para el registro ágil.                   | HU-01       | ABM               | Web y Mobile     |
| RF-02.1          | Autenticación         | El sistema debe validar las credenciales de los usuarios mediante un servicio centralizado de login propio o externo.                            | HU-02       | ABM               | Web y Mobile     |
| RF-03.1          | Perfil de Artista     | El sistema debe permitir a los artistas editar su biografía, links y personalizar la visualización de su portafolio.                             | HU-03       | ABM               | Web y Mobile     |
| RF-03.2          | Perfil de Artista     | El sistema debe consolidar y mostrar estadísticas de rendimiento del creador (vistas, calificaciones recibidas).                                 | HU-03       | Reporte           | Web y Mobile     |
| RF-04.1          | Gestión de Obras      | El sistema debe permitir la carga de imágenes, asignación de títulos y una descripción narrativa opcional (Lore).                                | HU-04       | ABM               | Web y Mobile     |
| RF-04.2          | Gestión de Obras      | El sistema debe procesar, optimizar y almacenar las imágenes subidas utilizando servicios en la nube (Cloudinary / AWS S3 + Imgix).              | HU-04       | Lógica de Negocio | Backend          |
| RF-05.1          | Galería / Explorador  | El sistema debe proveer una interfaz de búsqueda, filtros (por etiquetas, artistas o fecha) y visualización de obras.                            | HU-05       | Reporte           | Web y Mobile     |
| RF-06.1          | Curaduría Cualitativa | El sistema debe disponibilizar una interfaz interactiva de 5 estrellas para la puntuación cuantitativa de obras.                                 | HU-06       | Lógica de Negocio | Web y Mobile     |
| RF-06.2          | Curaduría Cualitativa | El sistema debe proveer una interfaz gráfica basada en una Rueda de Emociones para registrar la percepción cualitativa del usuario.              | HU-06       | Lógica de Negocio | Web y Mobile     |
| RF-07.1          | Motor de Conversión   | El sistema debe ejecutar un algoritmo automatizado que procese los votos y emociones acumuladas al finalizar el período de evaluación.           | HU-07       | Lógica de Negocio | Backend          |
| RF-07.2          | Motor de Conversión   | El algoritmo debe mapear el consenso social a atributos técnicos específicos de la carta: Ataque, Defensa, Vida y Rareza.                        | HU-07       | Lógica de Negocio | Backend          |
| RF-08.1          | Generación de Activos | El sistema debe emitir e instanciar la carta coleccionable con una identidad mecánica única vinculada a la obra de origen.                       | HU-08       | Lógica de Negocio | Backend          |
| RF-09.1          | Álbum Digital         | El sistema debe listar y renderizar visualmente todas las cartas obtenidas y poseídas por el usuario autenticado.                                | HU-09       | Reporte           | Web y Mobile     |
| RF-09.2          | Álbum Digital         | El sistema debe permitir filtrar, ordenar y organizar el inventario de la colección personal del usuario.                                        | HU-09       | ABM / Reporte     | Web y Mobile     |
| RF-10.1          | Sistema de Gacha      | El sistema debe implementar un mecanismo de apertura de paquetes de cartas con lógica de asignación aleatoria basada en la rareza comunitaria.   | HU-10       | Lógica de Negocio | Web y Mobile     |
| RF-10.2          | Sistema de Gacha      | El sistema debe gestionar una rutina de reposición periódica y gratuita de paquetes para incentivar la progresión del jugador.                   | HU-10       | Lógica de Negocio | Backend          |
| RF-11.1          | Módulo de Juego       | El sistema debe proveer una interfaz táctica para seleccionar cartas del mazo/álbum e iniciar emparejamientos.                                   | HU-11       | Lógica de Negocio | Web y Mobile     |
| RF-11.2          | Módulo de Juego       | El sistema debe procesar y resolver de manera automatizada los enfrentamientos (Battle/TCG) aplicando las estadísticas de las cartas.            | HU-11       | Lógica de Negocio | Web y Mobile     |
| RF-12.1          | Administración        | El sistema debe contar con herramientas de moderación para dar de baja obras o comentarios que violen los términos de uso.| HU-12       | ABM               | Web (Backoffice) |
| RF-12.2          | Seguridad             | El sistema debe incorporar mecanismos de protección perimetral y mitigación contra ataques automatizados de bots en las votaciones.| HU-12       | Lógica de Negocio | Backend |


## Milestones del proyecto
### Milestone 1: Plataforma base de usuarios y artistas

Este Milestone establece la base sobre la cual funcionan las demás funcionalidades.

**Objetivo**: Crear la estructura inicial del ecosistema.


**Historias**:

- HU-01: Como usuario quiero registrarme para crear una cuenta.
- HU-02: Como usuario quiero iniciar sesión para acceder al sistema.
- HU-03: Como artista quiero crear mi perfil público.
- HU-07: Como sistema procesar valoraciones de la comunidad para generar atributos de cartas coleccionables.

### Milestone 2: Sistema artístico y participación comunitaria

Este milestone se enfoca en las funcionalidades principales que involucran compartir y manejar las obras de los usuarios, que es uno de los componentes críticos de Pandora.

**Objetivo**: implementar el flujo de publicación y evaluación, y manejo de obras.

**Historias**:

- HU-04: Como artista quiero cargar una obra digital.
- HU-05: Como usuario quiero explorar una galería.
- HU-06: Como usuario quiero evaluar obras con estrellas y emociones.
- HU-012: Como administrador quiero gestionar el contenido de la plataforma para mantener la calidad y seguridad del sistema


### Milestone 3: Gamificación y coleccionismo

Este Milestone se ocupa del último ciclo de vida de las obras subidas a Pandora, y su segundo componente más crítico que son los elementos de colección.

**Objetivo**: transformar obras evaluadas en cartas jugables.

**Historias**:

- HU-08: Como usuario quiero obtener cartas generadas a partir de obras para ampliar mi colección.
- HU-09: Como usuario quiero visualizar mi colección.
- HU-10: Como usuario quiero abrir paquetes de cartas.
- HU-11: Como jugador quiero utilizar cartas en batallas.

## Estimación de requerimientos

Se utiliza estimación mediante Story Points (Fibonacci) considerando complejidad, esfuerzo técnico e incertidumbre.
Sumando los puntos de historia asignados a cada HU, el mapa de esfuerzo queda distribuido de la siguiente manera:

### Milestone 1: Plataforma base de usuarios y artistas
- HU-01: Registro de usuario  3 SP
- HU-02: Inicio de sesión 3 SP
- HU-03: Perfil público de artista 5 SP
- HU-07: Motor de conversión (Aislado con datos sintéticos)  13 SP
- **Total Milestone 1: 24 SP**

### Milestone 2: Sistema artístico y participación comunitaria

- HU-04: Carga de obra y Lore  5 SP
- HU-05: Explorador de galería  5 SP
- HU-06: Evaluación con estrellas y emociones  8 SP
- HU-12: Gestión y moderación del administrador  5 SP
- **Total Milestone 2: 23 SP**

### Milestone 3: Gamificación y coleccionismo

- HU-08: Obtención de cartas generadas  5 SP
- HU-09: Visualización de la colección (Álbum)  5 SP
- HU-10: Apertura de paquetes  8 SP
- HU-11: Módulo de batallas/TCG  13 SP
- **Total Milestone 3: 31 SP**

### Resumen

**Gran total: 78 SP**

Los componentes con mayor estimación son el motor de conversión y el módulo de juego porque contienen lógica de negocio propia, cálculos dinámicos e interacción entre múltiples entidades. La publicación y gestión básica poseen menor complejidad porque corresponden principalmente a operaciones CRUD.
Suponiendo que se trabaje a una velocidad promedio de 10-12 SP por sprint, se estima que los primeros dos Milestones tardaran 2 sprints (alrededor  de 4 semanas), mientras que el último milestone (3) tardará 3 sprints (alrededor de 6 semanas)

## Ajuste a la metodología de trabajo
**Situación propuesta: Ajuste de metodología por aumento de complejidad en el motor de conversión de cartas**
Durante el desarrollo de Pandora se identifica que la funcionalidad del motor de conversión de cartas, encargada de transformar las valoraciones de la comunidad en atributos jugables (ataque, defensa, vida, rareza y características especiales), presenta una complejidad mayor a la estimada inicialmente. La lógica requiere definir reglas de cálculo, balancear estadísticas y realizar múltiples pruebas para evitar que las cartas generadas sean desbalanceadas.

Debido a esta situación, el equipo decide realizar un ajuste en la metodología de trabajo incorporando una etapa más fuerte de investigación, validación y prototipado dentro de los sprints.

### Riesgos
En esta situación se detectan los siguientes riesgos:
| Riesgo                                                                                  | Probabilidad | Impacto | Consecuencia                                                                          |
| --------------------------------------------------------------------------------------- | ------------ | ------- | ------------------------------------------------------------------------------------- |
| La complejidad del motor de generación de cartas supera la estimación inicial.          | Alta         | Alta    | Retraso en la entrega del milestone 1 y dificultad para completar el módulo de juego. |
| Las reglas de generación producen cartas desbalanceadas.                                | Media        | Alta    | La experiencia de juego pierde calidad y requiere modificaciones posteriores.         |
| Falta de claridad sobre cómo convertir emociones y puntuaciones en atributos numéricos. | Media        | Media   | Aumento de retrabajo y brainstorming/iteraciones sobre la implementación.|

### Ajuste propuesto en la metodología
Inicialmente el proyecto utiliza Scrum con sprints orientados a completar historias de usuario. Ante el riesgo detectado, se propone adaptar la metodología incorporando una fase de **Sprint de exploración técnica (Spike)** antes de desarrollar completamente la funcionalidad.

#### 1. Creación de historias técnicas de investigación

En lugar de implementar directamente el motor de conversión, se agregan tareas específicas:

- Investigar modelos posibles de cálculo de estadísticas.
- Crear prototipos de generación de cartas.
- Definir reglas de rareza.
- Validar resultados con datos simulados.

Ejemplo de historia técnica:

Como equipo de desarrollo queremos investigar diferentes modelos de conversión para definir una estrategia viable antes de implementar el motor definitivo.

#### 2. División de una historia grande en historias menores
La historia original:

    Como sistema quiero transformar evaluaciones de usuarios en cartas jugables.

| Nueva historia                                                        | Objetivo                             |
| --------------------------------------------------------------------- | ------------------------------------ |
| Como sistema quiero almacenar las evaluaciones recibidas de una obra. | Preparar datos de entrada.           |
| Como sistema quiero calcular estadísticas básicas según puntuaciones. | Crear primera versión del algoritmo. |
| Como sistema quiero asignar rareza según criterios definidos.         | Implementar clasificación.           |
| Como sistema quiero generar una carta completa.                       | Integrar todos los componentes.      |

#### 3. Mayor uso de Kanban dentro del sprint

Se aumenta el uso del tablero Kanban para controlar tareas técnicas:

- Investigación.
- Desarrollo.
- Pruebas.
- Ajustes de balance.

Esto permite visualizar bloqueos rápidamente y evitar que una tarea compleja detenga todo el avance del equipo.

### Conclusiones de este cambio
El cambio no implica abandonar Scrum, sino adaptarlo a la realidad del proyecto. La metodología ágil permite modificar la planificación cuando aparecen nuevos riesgos o información que no estaba disponible al inicio.
En este caso, continuar con la planificación original podría generar acumulación de tareas pendientes y retrasar otros módulos dependientes. Al dividir la funcionalidad y validar primero la lógica del sistema, se reduce la incertidumbre y se mejora la calidad del producto final.
Este ajuste también mantiene alineado el desarrollo con la característica principal de Pandora: transformar la percepción colectiva de los usuarios en elementos jugables, una funcionalidad innovadora que requiere pruebas y refinamiento antes de ser implementada completamente.