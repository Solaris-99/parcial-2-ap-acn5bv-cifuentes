# Administración de Proyectos - Parcial II

![Logo DaVinci](DaVinci_logo.png)

- **Integrantes**:
    - Emanuel Cifuentes
- **Comisión**: ACN5AV
- **Profesor**: Sergio Medina


## Proyecto y objetivo

### Sobre el proyecto
La temática elegida para este trabajo es sobre el proyecto Pandora, que es también el proyecto para la Planificación del Seminario Final.

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


