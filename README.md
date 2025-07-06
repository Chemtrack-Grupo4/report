![UPC_logo_transparente (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2ff342be-dc34-415c-925e-1e7133e49abf)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2025-10

# DESARROLLO DE SOLUCIONES IOT

NRC 2939

Profesor: León Baca, Marco Antonio

***INFORME DE TRABAJO - TF1***

**Startup: TrackTox**

**Producto: Chemtrack**

**Integrantes**
| Nombre completo | Código        |
|----------------------------------------------|---------------|
| Amaro Villanueva, Camila Elena               | U202114248    |
| Barrial Marín, Sharon Antuanet Ivet          | U202114900    |
| García Moscoso, Andrea Joselyn               | U201291060    |
| Laguerre Challco, Fabrizzio Hernan           | U20211A950    |
| Hidalgo Bustamante, Josue Omar               | U202119880    |
| Huarcaya Quispe, Niurka Lucero               | U20221B226    |


Lima, 06 de Julio del 2025

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 24/04/2025 | Todos los integrantes del equipo  | Se desarrolló la descripción del startup Chemtrack, presentando a los integrantes del equipo, la problemática a resolver y el análisis del mercado, incluyendo a la competencia y el valor agregado que ofrece nuestra solución dentro del nicho. Además, se definieron la visión y objetivos del proyecto, el segmento objetivo y se propuso una solución tecnológica basada en IoT para el monitoreo seguro del transporte de materiales peligrosos, sentando así las bases para el desarrollo futuro del sistema. Luego se implementó los demás artefactos necesarios para realizar una base sólida para la arquitectura, implementación, validación y desarrollo de ChemTrack.   |
| 2.00 | 14/05/2025 | Todos los integrantes del equipo  | Se levantaron las correcciones de la entrega pasada, se realizaron y definieron los style guideline, las cualidades core de nuestro sistema para garantizar una interfaz interactiva y limpia, se realizaron los mockups, wireframes junto con los wireflows y userflows. Finalmente se obtuvo el prototipo de mobile, landing y desktop con el cual se planificó el sprint 1  y su respectivo desarrollo junto con el sprint backlog 1, development, execution, testing y los demás artefactos disponibles en el presente proyecto. Se desarrolló e implementó la landing page como el primer prototipo web de Chemtrack y se prosiguió con su despliegue.   |
| 3.00 | 20/06/2025 | Todos los integrantes del equipo | Se levantaron las observaciones de la entrega anterior y se desarrolló la versión final del landing page y del frontend de la página web. Además, se implementaron las funcionalidades core del sistema para asegurar una interfaz interactiva y limpia en esta primera versión de backend, edge, mobile y embebido. Finalmente, se realizó el despliegue de cada uno de los artefactos, documentándolo como parte del desarrollo del Sprint 2. También se llevaron a cabo las entrevistas de validación con Chemtrack, se aplicaron las heurísticas de evaluación, se elaboró el video "About the Product" y se actualizaron las conclusiones y recomendaciones. |
| 4.00 | 06/07/2025 | Todos los integrantes del equipo | Se levantaron las ultimas observaciones de la entrega anterior y se desarrolló la versión final del landing page y del frontend de la página web. Además, se implementaron las funcionalidades core finales del sistema para asegurar una interfaz interactiva y limpia en esta última versión de backend, edge, mobile y embebido. Finalmente, se realizó el despliegue de cada uno de los artefactos, documentándolo como parte del desarrollo del Sprint 3. También se llevaron a cabo las entrevistas de validación con Chemtrack, se aplicaron las heurísticas de evaluación, se elaboró el video "About the Product", se elaboró el video "About the team", se elaboró el prototipo fisico y se actualizaron las conclusiones y recomendaciones finales. |

---

# Project Report Collaboration Insights

**TB1:** Se han desarrollado las actividades correspondientes para la entrega TB1 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*
![image](https://github.com/user-attachments/assets/7010f212-ddcc-470e-b2df-781a12cbd85a)

**TP1:** Se han desarrollado las actividades correspondientes para la entrega TP1 en el siguiente repositorio de GitHub dentro de la organización del equipo:

Link de repositorio GitHub: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*
![image](https://github.com/user-attachments/assets/6c0adc3c-c4fb-4cff-937b-ff5b1cbc21f6)

**TB2:** Se han desarrollado las actividades correspondientes para la entrega TB2 en el siguiente repositorio de GitHub dentro de la organización del equipo:

Link de repositorio GitHub: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*

![image](https://github.com/user-attachments/assets/c7a9982a-f550-487f-ba34-fcc6bd2b2879)

**TF1:** Se han desarrollado las actividades correspondientes para la entrega TF1 en el siguiente repositorio de GitHub dentro de la organización del equipo:

Link de repositorio GitHub: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*

![image](https://github.com/user-attachments/assets/45377e9d-842d-4fa5-9c84-8babf030be20)




---

# Contenido 
## Tabla de contenidos

## [Student Outcome](#student-outcome)
## [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
## [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Journey Mapping](#233-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
## [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level](#4132-software-architecture-container-level)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: IAM](#421-bounded-context-iam)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2. Bounded Context: Management](#422-bounded-context-management)
      - [4.2.2.1. Domain Layer](#4221-domain-layer)
      - [4.2.2.2. Interface Layer](#4222-interface-layer)
      - [4.2.2.3. Application Layer](#4223-application-layer)
      - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3. Bounded Context: Records](#423-bounded-context-records)
      - [4.2.3.1. Domain Layer](#4231-domain-layer)
      - [4.2.3.2. Interface Layer](#4232-interface-layer)
      - [4.2.3.3. Application Layer](#4233-application-layer)
      - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
## [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web, Mobile and IoT Devices Style Guidelines](#512-web-mobile-and-iot-devices-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. Searching Systems](#523-searching-systems)
  - [5.2.4. SEO Tags and Meta Tags](#524-seo-tags-and-meta-tags)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-applications-uxui-design)
  - [5.4.1. Applications Wireframes](#541-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
  - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
  - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

## [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
  - [6.2.1. Sprint 1](#621-sprint-1)
    - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
    - [6.2.1.2. Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
    - [6.2.1.3. Sprint Backlog 1](#6213-sprint-backlog-1)
    - [6.2.1.4. Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
    - [6.2.1.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.1.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.1.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.1.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
  - [6.2.2. Sprint 2](#622-sprint-2)
    - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
    - [6.2.2.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.2.3. Sprint Backlog 2](#6223-sprint-backlog-2)
    - [6.2.2.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.2.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.2.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.2.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.2.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.2.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
  - [6.2.3. Sprint 3](#622-sprint-3)
    - [6.2.3.1. Sprint Planning 3](#6221-sprint-planning-3)
    - [6.2.3.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.3.3. Sprint Backlog 3](#6223-sprint-backlog-3)
    - [6.2.3.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.3.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.3.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.3.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.3.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.3.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

## [Conclusiones](#conclusiones)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)

## [Video About-the-Team](#video-about-the-team)

## [Bibliografía](#bibliografía)

## [Anexos](#anexos)


---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 5

Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas                                                                                                      | Conclusiones |
| - |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| - |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta. | **TB1**<br>**Camila Elena Amaro Villanueva**<br>Ayude en la en la elaboración de epics junto con sus respectivas user y technical stories teniendo en cuenta las necesidades identificadas en nuestros segmentos objetivos y los posibles escenarios que podrían presentarse. Esto nos permitió anticipar cómo deberíamos actuar ante diferentes situaciones. Asimismo, brindé apoyo en la creación de los impact maps correspondientes a los dos segmentos objetivos definidos.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Apoyé activamente a la identificación de eventos de dominio para mejorar la experiencia de usuario durante las interacciones con funciones centrales de nuestro sistema *Chemtrack*. Para ello, se realizó un proceso completo de event storming siguiendo un patrón de pasos preestablecidos que nos permitió visualizar la lógica correcta del sistema.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Participé en la elaboración de los segmentos objetivo, el análisis de competidores y la definición de estrategias frente a ellos, lo cual requirió coordinación constante con el equipo. Asimismo, realicé el diseño de entrevistas y el análisis de resultados, fomentando el intercambio de ideas y perspectivas para fortalecer la solución final.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Desarrollé la parte de descripción del startup del equipo, así como nuestro solution profile frente a una necesidad identificada, los antecendes que surgieron previamente a esta problemática y las solución que nuestra solución ofrece.<br><br>**Josue Omar Hidalgo Bustamante**<br>Contribuí de manera activa en el desarrollo de los arquetipos de usuarios y en la definición de sus necesidades principales, lo que permitió orientar mejor el diseño de soluciones dentro del proyecto. Además, colaboré en la preparación de los journey maps para visualizar las experiencias de los usuarios en diferentes etapas del proceso. Este trabajo facilitó la identificación de puntos críticos y oportunidades de mejora en el sistema propuesto, asegurando una propuesta de valor más ajustada a las expectativas reales.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Participé en el desarrollo de los modelos de arquitectura del sistema, así como en el Context Mapping, colaborando con el equipo para garantizar una visión unificada y estratégica del sistema. La definición de límites claros entre los contextos permitieron optimizar la comunicación entre el equipo, fomentando una colaboración efectiva que fortaleció la coherencia y robustez de la solución. <br><br> **TP1**<br>**Camila Elena Amaro Villanueva**<br>Apoye en la elaboración de los mockups y wireframes de la app web y móvil teniendo en cuenta las etiquetas planeadas para nuestras aplicaciones y el proceso lean ux realizado previamente donde captamos las necesidades de los usuarios. Asimismo, participe en el desarrollo de la primera versión de la app web. <br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Lideré la ejecución de la planificación del Sprint 1, en la cual, junto con el equipo, realizamos un análisis detallado del estado del proyecto. Durante esta sesión, identificamos las partes faltantes tanto a nivel funcional como técnico. Asimismo, organizamos y priorizamos las tareas clave para el desarrollo del proyecto, incluyendo la planificación estructurada del diseño e implementación de la landing page. Además, definimos los pasos necesarios para construir y desplegar nuestro primer prototipo web funcional, lo que marcó un hito inicial en la validación del producto.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Durante el desarrollo de esta entrega correjí y realicé la mejora de secciones clave del diseño de software, tales como Tactical-Level Software Design, General Style Guidelines y Web, Mobile and IoT Style Guide. Este trabajo fue realizado de manera colaborativa, promoviendo discusiones técnicas, consensuando decisiones de estilo y asegurando la coherencia entre los distintos componentes del sistema<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Durante esta etapa se trabajó en el diseño inicial de la landing page utilizando Figma como herramienta principal. El equipo se enfocó en definir la identidad visual del producto, seleccionando una paleta de colores, tipografías y componentes visuales coherentes con los objetivos del proyecto. Se diseñó un primer wireframe y posteriormente una propuesta de alta fidelidad que refleja la estructura, navegación y funcionalidades clave de la página de inicio del sistema. Este diseño sentó las bases para el posterior desarrollo del prototipo funcional y facilitó una visión clara y compartida entre todos los miembros del equipo.<br><br>**Josue Omar Hidalgo Bustamante**<br>La primera versión de la aplicación web fue desarrollada con mi participación directa en su implementación. Previamente, estuve involucrado en el diseño de sus interfaces, colaborando en la elaboración de mockups y wireframes tanto para la versión web como móvil. Estos se construyeron tomando en cuenta las etiquetas planificadas y los resultados del proceso de Lean UX, en el que identificamos las principales necesidades de los usuarios.<br><br>**Niurka Lucero Huarcaya Quispe**<br> Participé en la recopilación y presentación de las evidencias necesarias para la Sprint Review. Me encargué de documentar el desarrollo, las pruebas, la ejecución de funcionalidades y la documentación de los servicios. Esto permitió al equipo tener una visión clara del progreso del sprint. <br><br>**TB2**<br>**Camila Elena Amaro Villanueva**<br>Contribuyó activamente en solucionar las correcciones señaladas en frontend demostrando compromiso y colaboración constante con el equipo para alcanzar los objetivos técnicos del proyecto.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Se realizaron reuniones Scrum para identificar debilidades del proyecto y promover un trabajo en equipo eficiente, facilitando la toma de decisiones colaborativas y el avance coordinado del grupo.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Durante el desarrollo de esta entrega correjí y realicé la mejora de secciones clave del diseño de software, tales como Sprint Planning y Product Backlog. Este trabajo fue realizado de manera colaborativa, promoviendo discusiones técnicas y asegurando la coherencia entre los distintos componentes del sistema <br><br>**Fabrizzio Hernan Laguerre Challco**<br>Identificó y definió las funcionalidades clave de la versión mobile, lo que permitió guiar el desarrollo orientado a una experiencia de usuario optimizada. Su aporte fue fundamental para alinear al equipo en la construcción de una interfaz coherente, intuitiva y funcional para dispositivos móviles.<br><br>**Josue Omar Hidalgo Bustamante**<br>Colaboró activamente en la construcción de la arquitectura del backend, en la integración de los componentes edge y en el desarrollo de simulaciones en Wokwi, contribuyendo al ensamblaje técnico del sistema y asegurando su funcionamiento coordinado dentro del entorno de Chemtrack.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Brindó apoyo en la validación del servicio, participando activamente en la aplicación de heurísticas para evaluar la usabilidad del sistema. Su contribución fue clave para asegurar la calidad de la experiencia del usuario y fortalecer el proceso colaborativo de mejora continua en el equipo.<br><br> **TF1**<br>**Camila Elena Amaro Villanueva**<br>Para este último Sprint colaboré en mejorar los componentes del frontend para que cumplan con lo planteado inicialmente en las user stories. Asimismo, revisé que los endpoints se llamarán de manera adecuada y realicé entrevistas de validación con los segmentos objetivo para recopilar opiniones respecto a nuestro producto y puntos de mejora. Además, colaboré en la elaboración del prototipo iot físico. <br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Durante este sprint, asumí un rol activo en la organización y seguimiento del proyecto mediante la actualización continua del tablero en Trello, lo cual permitió al equipo tener claridad sobre el avance de cada tarea y priorizar pendientes críticos. Asimismo, lideré la edición final de los videos de entrega, asegurándome de que reflejen fielmente el desarrollo del sistema y cumplan con los criterios de revisión establecidos. Coordiné con los miembros encargados de cada componente para recopilar y validar la evidencia técnica de desarrollo, pruebas, ejecución y despliegue, facilitando una presentación clara y ordenada durante la revisión del sprint.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Apoyé al equipo en el procesamiento y sistematización de la información recogida durante las entrevistas de validación, organizando los hallazgos en categorías relevantes y facilitando su discusión en equipo para la toma de decisiones. A partir de los resultados, propuse tareas de mejora que fueron incorporadas al backlog. Además, promoví un entorno colaborativo al incentivar la participación equitativa de todos los integrantes durante la evaluación heurística, estableciendo tiempos y objetivos claros para cada etapa del análisis, asegurando así que se cumplieran dentro del sprint.<br><br>**Niurka Lucero Huarcaya Quispe**<br> Me aseguré de que las tareas críticas de cierre estuvieran correctamente distribuidas y se cumplieran dentro del sprint final. Organicé y participé en reuniones técnicas donde se definieron los objetivos relacionados a la migración del edge fuera de la nube y la inclusión de la simulación en Wokwi. Además, colaboré con el equipo de backend para aplicar las últimas validaciones, revisando cada endpoint y su consistencia con las reglas de negocio. Impulsé la planificación y ejecución del video integrador, guiando a mis compañeros en qué debía incluirse para reflejar adecuadamente el funcionamiento de cada componente del proyecto. <br><br>**Josue Omar Hidalgo Bustamante**<br> Durante este sprint final, lideré la integración completa del sistema IoT, coordinando con el equipo la actualización del punto del edge para que funcione fuera de la nube, lo cual representó un reto técnico importante. Además, propuse y ejecuté la implementación de un segundo edge en Wokwi para fines de simulación y pruebas en paralelo, facilitando el trabajo de mis compañeros en frontend y mobile. También organicé sesiones internas para revisar la lógica del backend, identificar errores y aplicar validaciones finales. Finalmente, colaboré activamente en la producción del video que demuestra todo el flujo del sistema (web, mobile, edge y Wokwi), asegurando que cada parte estuviera correctamente sincronizada y funcionando.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Me enfoqué en planificar y ejecutar la integración del prototipo con el backend, asegurando que las lecturas del microcontrolador fueran procesadas y almacenadas adecuadamente. Establecí objetivos técnicos claros y coordiné tareas con el equipo para abordar desafíos como la latencia en la transmisión de datos y la validación del flujo completo. Además, fomenté un entorno de colaboración continua mediante pruebas conjuntas, intercambio de avances y resolución colectiva de problemas técnicos, lo cual fue clave para lograr un funcionamiento estable del sistema.<br><br> | **TB1:** Como equipo, trabajamos de manera colaborativa para cubrir todas las etapas clave del desarrollo inicial de Chemtrack, desde la definición del problema y el análisis de mercado hasta la construcción de la solución tecnológica. Cada integrante asumió un rol fundamental en áreas como la elaboración de user stories, la identificación de eventos de dominio, el diseño de entrevistas, la creación de arquetipos, el mapeo de experiencias y el modelado de la arquitectura del sistema. Esta sinergia nos permitió integrar múltiples perspectivas y asegurar una base sólida, estratégica y centrada en el usuario para el desarrollo de nuestra solución. <br><br> **TP1:** Como equipo, trabajamos de manera colectiva y alineada para identificar y corregir los artefactos faltantes en nuestro proyecto. Este proceso nos permitió afinar los detalles y reforzar la definición de nuestra propuesta, asegurando una visión compartida del producto. Gracias a esta colaboración, logramos preparar y desplegar una primera muestra representativa de lo que será nuestra solución final, materializada en la publicación de la landing page y el primer prototipo funcional de la web.<br><br> **TB2:** Como equipo, trabajamos de manera colaborativa para consolidar la segunda entrega del proyecto, enfocándonos en el desarrollo integral del sistema. Se levantaron las observaciones de la entrega anterior y se implementó la versión final de la landing page y de la página web (frontend). Además, se desarrollaron las funcionalidades core del backend, edge, mobile y del sistema embebido (Wokwi), asegurando una interfaz limpia, funcional e integrada.<br><br>**TF1:** Como grupo, logramos consolidar un flujo de trabajo colaborativo y eficiente a lo largo del desarrollo del proyecto. Cada integrante asumió responsabilidades específicas en base a sus fortalezas, permitiendo una ejecución coordinada tanto del backend, frontend, como del sistema físico. Nos apoyamos constantemente mediante sesiones de revisión y pruebas cruzadas, lo que fortaleció la calidad del producto entregado. Además, tomamos decisiones conjuntas en momentos clave del desarrollo, demostrando liderazgo compartido, comunicación efectiva y compromiso colectivo con los objetivos planteados desde el inicio.<br><br>| 
| Crea un entorno colaborativo einclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1**<br>**Camila Elena Amaro Villanueva**<br>Participé de manera activa en las reuniones de planificación del proyecto, así como en su desarrollo. Además, me encargué de organizar las tareas relacionadas con la elaboración de las user stories, basándome en la información recopilada por cada integrante del equipo a través de entrevistas realizadas a usuarios pertenecientes a los segmentos objetivo.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Organicé las diferentes reuniones utilizando la metodología daily scrum hasta la entrega, donde identificamos las partes faltantes de nuestro trabajo, priorizamos tareas pendientes y coordinamos responsabilidades para asegurar el avance constante del proyecto. Donde la comunicación efectiva fue clave dentro del equipo para resolver bloqueos de forma oportuna y mantener la misma alineación.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Contribuí activamente a la creación de un entorno colaborativo, establecimos metas claras desde las fases iniciales del proyecto y organicé tareas relacionadas con el diseño táctico del software, abarcando los distintos Bounded Contexts. Coordiné la elaboración de las distintas capas arquitectónicas y diagramas técnicos, asegurando una planificación eficiente y cumplimiento de los plazos.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Desarrollé el Lean UX Process, una artefacto fundamental para identificar nuestras funciones claves, segmentos objetivos, identificación y establecimiento de nuestra solución frente a la problemática identificada brindando una gráfica ejemplar y amplia para implementar una solución completa.<br><br>**Josue Omar Hidalgo Bustamante**<br>Apoyé en la validación de requerimientos técnicos y funcionales, asegurando que cada propuesta se ajustara a los objetivos del proyecto. También colaboré activamente en la elaboración de diagramas de flujo y en la definición de entidades clave del sistema. Durante el desarrollo, participé en sesiones de retroalimentación continua, lo que permitió realizar ajustes oportunos y mantener la calidad en cada entrega parcial.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Contribuí en la creación de los modelos de arquitectura del sistema, así como en el Context Mapping, asegurando que cada nivel de arquitectura estuviera alineado con los objetivos estratégicos y técnicos. Además, en equipo, establecimos metas claras, organizamos las tareas de manera estratégica y aseguramos el cumplimiento de los objetivos del proyecto. <br><br> **TP1**<br>**Camila Elena Amaro Villanueva**<br>Participé activamente en las reuniones de planificación del proyecto y en su desarrollo. Además, coordine al grupo en la creación de la aplicación web, guiándolos con base en los mockups previamente diseñados.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Desarrollé el Sprint Backlog 1 identificando y priorizando las tareas clave (core) de nuestro sistema, enfocándome en aquellas funcionalidades esenciales que debían estar presentes en esta primera entrega del prototipo. Esta planificación permitió establecer una hoja de ruta clara para el equipo y asegurar que el prototipado inicial reflejara de manera efectiva los pilares fundamentales de nuestra solución.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Contribuí activamente a la creación de un entorno colaborativo y corrección de los documentos Tactical-Level Software Design, General Style Guidelines y Web, Mobile and IoT Style Guide. Para ello, coordiné con el equipo la definición de metas claras relacionadas con la mejora de la consistencia, calidad del diseño, revisión en función de los tiempos establecidos, y aseguré el cumplimiento de los objetivos propuestos.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>En esta primera entrega se consolidó el diseño de la landing page desarrollado en Figma. A partir de los wireframes y propuestas previas, se logró una versión pulida y funcional que cumple con los objetivos de comunicación del proyecto. El trabajo en Figma permitió una colaboración fluida entre los integrantes del equipo, permitiendo iteraciones rápidas y comentarios en tiempo real. Este diseño no solo representa visualmente el producto, sino que también guió el desarrollo del prototipo inicial. El despliegue de la landing page refleja el compromiso del equipo con la calidad visual y la experiencia del usuario desde las primeras fases del proyecto.<br><br>**Josue Omar Hidalgo Bustamante**<br>Durante el desarrollo del proyecto, asumí un rol activo tanto en la etapa de planificación como en la ejecución. Me encargué de coordinar al equipo, brindando orientación basada en los mockups definidos con anterioridad para asegurar la coherencia en el diseño de la aplicación web.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Se realizó la recolección y elaboración de las evidencias requeridas para la Sprint Review. Se promovió un entorno donde todos los miembros participaron aportando resultados del desarrollo, pruebas, ejecución, documentación de servicios y despliegue del software.<br><br>**TB2**<br>**Camila Elena Amaro Villanueva**<br>Se desarrollaron los módulos de frontend, backend y las simulaciones en Wokwi, con el objetivo de validar el funcionamiento integral del sistema, garantizando la coherencia entre interfaces, lógica de negocio y componentes físicos simulados dentro del entorno de Chemtrack.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Se aplicó Scrum para colaborar activamente en cada tarea, elaborando el video “About the Product” para comunicar el objetivo de Chemtrack y una serie de auditorias de funcionamiento de todos los artefactos desarrollados para validar su calidad.<br><br> **Andrea Joselyn Garcia Moscoso**<br>Contribuí activamente a la creación de un entorno colaborativo y corrección de los documentos en el Sprint Planning. Además, coordiné con el equipo la definición de metas claras relacionadas con la mejora de la consistencia,revisión en función de los tiempos establecidos, y aseguré el cumplimiento de los objetivos propuestos.<BR><BR>**Fabrizzio Hernan Laguerre Challco**<br>Se establecieron metas específicas para la versión mobile, asignando tareas de diseño, desarrollo e integración que facilitaron su avance estructurado y desplegado creando un apk.<br><br>**Josue Omar Hidalgo Bustamante**<br>Se logró cumplir con el desarrollo e integración del backend, el módulo edge y las simulaciones en Wokwi, asegurando su correcto despliegue, funcionamiento y conexión con el resto del sistema, lo que permitió validar su operatividad dentro del ecosistema de Chemtrack. <br><br>**Niurka Lucero Huarcaya Quispe**<br>Se documentó y aplicó evaluaciones heurísticas y validaciones con usuarios, fortaleciendo la calidad del sistema y reflejando los valores de inclusión, colaboración y mejora continua.<br><br>**TF1**<br>**Camila Elena Amaro Villanueva**<br>Revisé que la app web elaborada estuviera de acuerdo a las user stories identificadas al inicio del desarrollo del proyecto y que cumplieran con sus respectivos criterios de aceptación. Además, participé de manera activa en las reuniones de planificación y me encargue de coordinar la elaboración del front con los compañeros de mi equipo y de gestionar reuniones en caso se presentarán bugs en el desarrollo.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Me encargué de estructurar y organizar los entregables correspondientes al Sprint Review, coordinando la documentación de evidencias clave como el Sprint Backlog, pruebas realizadas, despliegue del software y servicios desarrollados. Promoví la colaboración entre los integrantes al establecer deadlines internos y alinear los esfuerzos para cumplir con los entregables a tiempo. Además, participé activamente en las reuniones de planificación, proponiendo estrategias para mejorar la gestión visual de tareas a través del Trello, lo que ayudó a optimizar el trabajo en equipo y mantener el enfoque en los objetivos del sprint.<br><br> **Andrea Joselyn Garcia Moscoso**<br>Apoyé al equipo en el procesamiento y sistematización de la información recogida durante las entrevistas de validación, organizando los hallazgos en categorías relevantes y facilitando su discusión en equipo para la toma de decisiones. A partir de los resultados, propuse tareas de mejora que fueron incorporadas al backlog. Además, promoví un entorno colaborativo al incentivar la participación equitativa de todos los integrantes durante la evaluación heurística, estableciendo tiempos y objetivos claros para cada etapa del análisis, asegurando así que se cumplieran dentro del sprint.<BR><BR>**Fabrizzio Hernan Laguerre Challco**<br>Me enfoqué en planificar y ejecutar la integración del prototipo con el backend, asegurando que las lecturas del microcontrolador fueran procesadas y almacenadas adecuadamente. Establecí objetivos técnicos claros y coordiné tareas con el equipo para abordar desafíos como la latencia en la transmisión de datos y la validación del flujo completo. Además, fomenté un entorno de colaboración continua mediante pruebas conjuntas, intercambio de avances y resolución colectiva de problemas técnicos, lo cual fue clave para lograr un funcionamiento estable del sistema.<br><br>**Josue Omar Hidalgo Bustamante**<br>Me aseguré de que las tareas críticas de cierre estuvieran correctamente distribuidas y se cumplieran dentro del sprint final. Organicé y participé en reuniones técnicas donde se definieron los objetivos relacionados a la migración del edge fuera de la nube y la inclusión de la simulación en Wokwi. Además, colaboré con el equipo de backend para aplicar las últimas validaciones, revisando cada endpoint y su consistencia con las reglas de negocio. Impulsé la planificación y ejecución del video integrador, guiando a mis compañeros en qué debía incluirse para reflejar adecuadamente el funcionamiento de cada componente del proyecto. <br><br>**Niurka Lucero Huarcaya Quispe**<br>Mi apoyo en la documentación a lo largo del proyecto ayudó a mantener una comunicación clara y accesible para todos los miembros del equipo. Esta contribución permitió organizar mejor las tareas, definir metas comunes y asegurar que cada integrante participara activamente en el cumplimiento de los objetivos. | **TB1:** El equipo demostró una sólida capacidad para colaborar de forma inclusiva, planificando estratégicamente las tareas y cumpliendo los objetivos del proyecto. A través de reuniones constantes, el uso de metodologías ágiles y una distribución clara de responsabilidades, logramos mantener una comunicación efectiva, anticipar desafíos y avanzar de manera organizada. Esto nos permitió construir una base sólida para el desarrollo de Chemtrack, alineando tanto los aspectos técnicos como los objetivos del negocio. <br><br> **TP1:** Nuevamente se evidenció una sólida capacidad de trabajo en equipo, reflejada en la distribución equitativa de las tareas y el compromiso de cada integrante para cumplir con los objetivos dentro del tiempo estimado. Esta coordinación eficiente nos permitió avanzar con fluidez en el desarrollo del prototipo, fortaleciendo tanto la dinámica grupal como el progreso del proyecto. Logrando tener el despliegue de landing page y de la web. Además de las correcciones levantadas. <br><br> **TB2:** Como equipo, aplicamos la metodología Scrum para fomentar la colaboración activa y la organización del trabajo en cada sprint. Desarrollamos e integramos los módulos de frontend, backend, edge, mobile y embebido mediante una planificación clara de tareas y metas. Usamos Wokwi para simular y validar los dispositivos, y realizamos evaluaciones heurísticas e entrevistas para asegurar una experiencia de usuario óptima. Elaboramos el video “About the Product” para comunicar el objetivo de Chemtrack a nuestros clientes y auditamos cada artefacto del sistema para garantizar su correcto funcionamiento y calidad. <br><br> **TF1:** Durante todo el proyecto, nuestro equipo mantuvo una planificación clara y compartida, utilizando herramientas como Trello, reuniones periódicas y documentación colaborativa para asegurar un avance constante. Fomentamos un entorno de trabajo inclusivo donde todas las opiniones fueron escuchadas y valoradas, lo cual enriqueció el diseño del producto. Gracias a una distribución equitativa de tareas y un enfoque orientado a objetivos, cumplimos con los entregables de cada sprint, logrando integrar satisfactoriamente todas las partes del sistema y presentar un producto funcional validado por usuarios reales. |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup que se introduce en el presente informe recibe como nombre “TrackTox”. Actualmente conformado por un conjunto de estudiantes de la Universidad Peruana de Ciencias Aplicadas, con la ambición de querer ayudar a la sociedad con nuestra grán pasión a la tecnología e informática, creamos esta startup tomando como objetivo asegurar la integridad y mejorar los procesos de trabajo de las empresas de transporte de productos peligrosos.

Como misión se plantea “Incrementar la calidad del servicio de transporte de combustibles con eficiencia, seguridad y transparencia entre conductores y empresas”. Asimismo, la visión de la startup plantea desarrollar la solución IoT más reconocida en el Perú para asegurar la integridad de los transportes de productos peligrosos.

### 1.1.2. Perfiles de integrantes del equipo



| <img src="https://github.com/user-attachments/assets/d03388b2-c106-406c-961f-3785e3fae476" width="600" alt="Foto de Camila Elena Amaro Villanueva" style="border-radius: 10px;"> | Mi nombre es Camila Elena Amaro Villanueva, cuento con conocimientos de desarrollo frontend y backend, además de lenguajes de programación como C++, Python y JavaScript. Además, entre mis habilidades, puedo resaltar la responsabilidad y creatividad que poseo para aportar en los trabajos en equipo. |
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|


---

| <img src="https://github.com/user-attachments/assets/5ceaee27-7da3-4863-9518-4910ba33e5f5" width="700" alt="Foto" style="border-radius: 10px;"> | Mi nombre es Fabrizzio Hernán Laguerre Challco, tengo 19 años, desde pequeño siempre he sentido un interés por aprender a usar ciertos dispositivos siendo uno de estos los más útiles que tenemos en la actualidad, las computadoras, por ello me esforzado en practicar y aprender ciertas habilidades en ofimática, edición de videos, programación y en aprender inglés, habilidades que puedo ofrecer para contribuir al grupo. |
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|


---

| <img src="https://github.com/user-attachments/assets/f009ea27-6761-4f18-9c34-f5d7a6501bab" width="700" alt="Foto" style="border-radius: 10px;"> | Mi nombre es Sharon Antuanet Ivet Barrial Marin, soy estudiante de Ingeniería de Software con experiencia en desarrollo de software, full-stack, diseño UI/UX y arquitectura de software. En mi tiempo libre disfruto leer, ver películas y escuchar música. Espero que mis pocas cualidades tanto técnicas como blandas pueden ayudar al equipo durante toda esta etapa de realización del proyecto.   |
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|



---

| <img src="https://github.com/user-attachments/assets/e8277566-b4e5-45d2-8cfe-a8fe04a56471" width="700" alt="Foto" style="border-radius: 10px;"> | Mi nombre es Niurka Huarcaya y actualmente estoy llevando la carrera de Ingeniería de Software. Considero que soy una persona responsable y que puedo aportar al equipo en cualquier aspecto que se requiera. De igual manera, siento que los conocimientos que he ido adquiriendo en ciclos anteriores serán de gran ayuda para llevar a cabo el presente trabajo. |
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|


---

| <img src="https://github.com/user-attachments/assets/cb84ecb3-20f0-4a5c-ba50-43888c811843" width="1000" alt="Foto" style="border-radius: 10px;"> | Soy estudiante de Ingeniería de Software y actualmente me desempeño como Cloud Backend Developer en Python. Me especializo en el desarrollo de soluciones escalables en la nube, con énfasis en eficiencia, automatización y buenas prácticas. Disfruto diseñar backends aplicando distintos tipos de arquitectura, y tengo un sólido conocimiento en la integración con interfaces frontend. Me considero proactivo, orientado a la mejora continua y con un fuerte interés en seguir aprendiendo tecnologías que impulsen la calidad del software. |
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|


---

| <img src="https://github.com/user-attachments/assets/b1bd791c-87c3-4de1-9fed-52e3382b4ca6" width="700" alt="Foto" style="border-radius: 10px;">| Actualmente estoy cursando el séptimo ciclo de mi carrera. Elegí esta carrera debido a que desde la niñez me interesó el cómo funcionan las computadoras por dentro. Poseo conocimiento en programación estructurada, POO, Python, JavaScript y C. Además, tengo habilidades en el trabajo en equipo y trabajo en tareas múltiples.|
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|


## 1.2. Solution Profile

**Product name**


El nombre elegido para nuestra solucion es ChemTrack. Este nombre transmite la idea de un camino seguro en el cuál se llevaran los productos quimicos, lo cual es el objetivo principal del sistema de detección y alerta.


**Product Description**

La solución IoT es innovadora dado que se brinda un servicio de transporte de productos peligrosos implementando la supervisión de condiciones de seguridad tanto para el mismo conductor y para el monitoreo de la empresa. Por medio de sensores incluidos en el vehículo y en el conductor, se supervisará el material de carga y se notificará en caso exista alguna fuga. También se mantendra control del estado de salud del conductor. Estos sensores varían desde fuga de gas, temperatura, presión, movimiento, etc. 


**Monetización**

El sistema tendrá una suscripción donde cubra el precio de los dispostivos IOT y el servicio de la plataforma.

### 1.2.1. Antecedentes y problemática

En los últimos años, la industria del transporte de productos peligrosos, como gases inflamables, productos químicos y materiales industriales, la seguridad es una prioridad absoluta. A lo largo de los años, ha habido numerosos incidentes que han resultado en daños graves, tanto para los trabajadores involucrados como para el medio ambiente y las comunidades cercanas. Estos incidentes se han debido principalmente a fugas, explosiones y derrames de materiales peligrosos durante el transporte.

Uno de los principales problemas radica en la detección tardía de fugas y otras condiciones peligrosas durante el transporte. La falta de un monitoreo continuo y en tiempo real dificulta la identificación oportuna de irregularidades, como cambios en la presión, temperatura o movimiento inusual del vehículo. Esta situación aumenta la probabilidad de que un problema menor se convierta en una emergencia antes de ser detectado y abordado.

Otro desafío es la fragmentación de las soluciones actuales de monitoreo. Muchas empresas dependen de sistemas manuales o tecnologías desactualizadas que no proporcionan una supervisión integral. Esta carencia de un sistema centralizado y automatizado crea brechas en la seguridad, dejando a las empresas vulnerables a incidentes que podrían haberse prevenido con un mejor monitoreo.

Además, las exigencias regulatorias en el transporte de materiales peligrosos son cada vez más estrictas. El incumplimiento de estas normativas no solo implica sanciones legales, sino también la pérdida de confianza de los clientes y daños significativos a la reputación de la empresa. Sin herramientas adecuadas para garantizar el cumplimiento, las empresas corren el riesgo de enfrentar graves consecuencias financieras y operativas.

**Herramienta 5W y 2H**

**¿Qué? (What)**

Según Lopez-Atamorors et al. (2010), nos dice que los principales riesgos dentro del servicio de transportes peligros son: Choque, Explosión y Fuga. Debido a ello, el transporte de productos peligrosos, como gases inflamables y productos químicos, significa un alto riesgo que se tiene que afrontar. La falta de monitoreo continuo y en tiempo real impide la identificación oportuna de condiciones peligrosas, como cambios en la presión, temperatura o movimiento del vehículo, también suponen unod estos problemas.

**¿Cuándo? (When)**

Este problema se presenta de manera constante durante el transporte de productos peligrosos, particularmente en situaciones de emergencia o cuando las condiciones de seguridad cambian rápidamente y no se detectan a tiempo.

**¿Dónde? (Where)**

Los problemas surgen en cualquier etapa del transporte de materiales peligrosos, ya sea en carreteras, vías ferroviarias o puertos. Estos incidentes afectan principalmente a las rutas de transporte utilizadas por empresas que manejan productos químicos, gases inflamables y otros materiales industriales peligrosos.

**¿Quién? (Who)**

Los principales afectados son las empresas de transporte de productos peligrosos, los trabajadores que manipulan estos materiales y las comunidades cercanas a las rutas de transporte. También se ven afectadas las autoridades reguladoras que deben supervisar el cumplimiento de las normas de seguridad.

**¿Por qué? (Why)**

Según Chacoón y Domingo (2021): los efectos de fugas de gases pueden aumentar el efecto invernadero, contaminación de atmosfera y otros efectos nocivos, debido a ello es importante. Además, la falta de un sistema de monitoreo eficiente y continuo. Muchos sistemas actuales son manuales o desactualizados, lo que crea brechas de seguridad. Esto se agrava con el incumplimiento de regulaciones, lo cual puede resultar en sanciones legales y pérdidas de reputación.

**¿Cómo? (How)**

La problemática se manifiesta a través de incidentes como fugas, explosiones y derrames que no son detectados a tiempo debido a la falta de monitoreo adecuado. Las empresas a menudo dependen de sistemas fragmentados que no ofrecen una supervisión integral, exponiendo a los trabajadores y al medio ambiente a riesgos significativos.

**¿Cuánto? (How Much)**

Según Soto et al. (2023), en la mayoría de países de latinoamerica, se arroja que en un año promedio se atienden más de 11,00 resportes relacionados con gas L.P y gas natural. Las pérdidas asociadas incluyen daños a la infraestructura, sanciones legales, costos de limpieza y posibles daños a la salud de los trabajadores y el público. Además, el incumplimiento de las regulaciones puede llevar a multas que varían dependiendo de la gravedad del incidente y el impacto ambiental.

**Conclusiones de las 5W + 2H**

Luego de analizar las 5W y 2H, se evidencia que la industria del transporte de productos peligrosos enfrenta desafíos críticos en la detección temprana de fugas y otros incidentes relacionados con la seguridad. La fragmentación y la falta de actualización de las tecnologías de monitoreo son factores clave que impiden una respuesta rápida y efectiva ante emergencias. Para mitigar estos riesgos, se requiere una solución integral que incluya la implementación de tecnologías de monitoreo continuo y en tiempo real, centralizando la supervisión y mejorando la capacidad de respuesta ante condiciones peligrosas. Esto no solo ayudaría a cumplir con las normativas cada vez más estrictas, sino que también protegería a los trabajadores, el medio ambiente y las comunidades circundantes.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Los productos/servicios existentes no abordan adecuadamente el problema crítico de la detección temprana de fugas de gases combustibles (GNV) durante su transporte, lo que pone en riesgo tanto la seguridad de los conductores como la reputación de las empresas.

Nuestra solución abordará esta brecha proporcionando un sistema de monitoreo en tiempo real que, a través de sensores, detectará rápidamente cualquier anomalía durante el transporte antes de que afecte al conductor o al producto transportado y se convierta en una amenaza.

Nos enfocaremos inicialmente en empresas de transporte de gases combustibles que necesiten mejorar sus medidas de seguridad y reducir riesgos operativos.

Sabremos que hemos tenido éxito cuando observemos una reducción significativa en los incidentes relacionados con fugas de gas, junto con una mejora en la percepción de seguridad por parte de los conductores y las empresas involucradas.

#### 1.2.2.2. Lean UX Assumptions

*Bussiness Outcomes:*

- Incremento de la seguridad en el transporte de gases combustibles en un 30%. 

- Reducción del riesgo de explosiones en un 40%.

*Users:*

- **Conductores:** que transportan gases combustibles y necesitan protección frente a posibles fugas.
- **Empresas de transporte:** que desean asegurar la integridad de sus conductores y proteger su carga durante el transporte.

*User Outcomes & Benefits:*

- **Conductores:** Mayor seguridad durante el transporte de gases combustibles. Notificación temprana de posibles fugas, lo que permite tomar acciones inmediatas para evitar accidentes.
- **Empresas de transporte:** Monitoreo en tiempo real de las condiciones de seguridad de sus vehículos. Reducción de riesgos y responsabilidades asociadas a accidentes por fugas de gases.

*Features Assumptions:*

- **Monitoreo en tiempo real:** de las condiciones de seguridad mediante sensores en el vehículo (detección de fugas de gas, temperatura, presión, movimiento, etc.).
- **Alertas inmediatas:** al conductor y al centro de monitoreo en caso de detectar una fuga o condición peligrosa.
- **Registro histórico de datos:** para análisis y mejoras continuas en los protocolos de seguridad.
- **Integración con sistemas de gestión:** de la flota para una visión centralizada de la seguridad en el transporte.

*User Assumptions:*

- **¿Quién es el usuario?** Los usuarios de nuestra solución son conductores de vehículos que transportan gases combustibles y las empresas que gestionan estos transportes.
- **¿Dónde encaja nuestro producto en su trabajo o vida?** Nuestro producto es esencial en el día a día de los conductores, brindándoles una herramienta que les permite realizar su trabajo de manera más segura. Para las empresas, es una solución que mejora la seguridad y eficiencia operativa.
- **¿Qué problemas tiene nuestro producto? ¿Evitar?** Un posible desafío es que los conductores no confíen plenamente en el sistema o lo consideren complejo de usar. Para evitar esto, la interfaz debe ser sencilla y las alertas deben ser claras y precisas.
- **¿Cuándo y cómo es nuestro producto? ¿Usado?** Nuestra solución se utiliza durante todo el transporte de gases combustibles, monitoreando constantemente las condiciones de seguridad y emitiendo alertas en tiempo real.
- **¿Qué características son importantes?** Las características clave incluyen la detección precisa de fugas, la notificación instantánea al conductor, el registro de datos de seguridad y la capacidad de integración con sistemas de gestión de flotas.
- **¿Cómo debe verse nuestro producto y cómo comportarse?** La interfaz debe ser intuitiva y fácil de usar para los conductores. Las alertas deben ser visibles y comprensibles, y el sistema debe responder rápidamente a cualquier cambio en las condiciones de seguridad.

*Business Assumptions:*

- Creemos que nuestros clientes necesitan una mejor manera de asegurar la seguridad en el transporte de gases combustibles.
- Estas necesidades se pueden resolver con una solución IoT que permite el monitoreo en tiempo real y la detección temprana de fugas de gases.
- El valor principal que nuestro cliente quiere de nuestro servicio es la capacidad de prevenir accidentes graves mediante una detección temprana y notificación de fugas.
- El cliente también puede obtener beneficios adicionales como la reducción de costos asociados a accidentes y la mejora en la reputación de la empresa.
- Vamos a adquirir la mayoría de nuestros clientes mediante la promoción en ferias de seguridad, campañas en redes sociales, y recomendaciones de clientes actuales.
- Haremos dinero a través de la venta de dispositivos IoT y suscripciones al servicio de monitoreo.
- Nuestra competencia principal en el mercado serán otras soluciones de monitoreo de seguridad en el transporte de materiales peligrosos.
- Los venceremos debido a la simplicidad de uso de nuestra solución y a la precisión y rapidez en la detección de condiciones peligrosas.
- El mayor riesgo es que las empresas no adopten nuestra solución por considerarla innecesaria o por resistencia al cambio.
- Resolveremos esto a través de demostraciones de la efectividad del sistema y ofreciendo soporte continuo a nuestros clientes.


#### 1.2.2.3. Lean UX Hypothesis Statements

A continuación, se plantean las hipótesis que proponen una solución a la problemática dentro de las funcionalidades de la solución tecnológica. Cada una de estas hipótesis es específica y medible para sustentar el éxito de manera objetiva. Cabe resaltar que las métricas actuales son iguales a promedios generales de soluciones ya existentes.

### Hipótesis 1:
*Creemos que los conductores necesitan una solución que les alerte rápidamente sobre posibles fugas de gases combustibles (GNV).*
*Sabremos que hemos tenido éxito cuando nuestra solución IoT se convierta en una herramienta esencial para la seguridad diaria de los conductores.*

**Métricas:**
1. *Frecuencia de Uso Diario:* Porcentaje de conductores que utilizan el sistema de monitoreo IoT diariamente.
   - Métrica actual: 20%
   - Meta deseada: 60%

2. *Retención a Largo Plazo:* Porcentaje de conductores que siguen utilizando la solución después de 3 meses.
   - Métrica actual: 50%
   - Meta deseada: 70%

---

### Hipótesis 2:
*Creemos que las empresas de transporte necesitan monitorear en tiempo real las condiciones de seguridad de los vehículos que transportan gases combustibles.*
*Sabremos que hemos tenido éxito cuando las empresas adopten nuestra solución para todos sus vehículos de transporte de materiales peligrosos.*

**Métricas:**
1. *Implementación en la Flota:* Porcentaje de vehículos equipados con nuestro sistema IoT.
   - Métrica actual: 10%
   - Meta deseada: 80%

2. *Reducción de Incidentes:* Disminución del número de incidentes relacionados con fugas de gases en los vehículos que usan la solución.
   - Métrica actual: 2 incidentes mensuales
   - Meta deseada: 0 incidentes mensuales

---

### Hipótesis 3:
*Creemos que las empresas de transporte necesitan datos precisos para mejorar sus protocolos de seguridad.*
*Sabremos que hemos tenido éxito cuando las empresas utilicen los datos de nuestra solución para optimizar sus operaciones.*

**Métricas:**
1. *Uso de Datos para la Mejora Continua:* Número de empresas que reportan mejoras en sus protocolos de seguridad basadas en los datos recopilados por el sistema.
   - Métrica actual: 2 empresas
   - Meta deseada: 10 empresas

2. *Reducción en Costos de Seguro:* Porcentaje de reducción en los costos de seguro para las empresas que adoptan nuestra solución.
   - Métrica actual: 5% de reducción
   - Meta deseada: 20% de reducción

---

### Hipótesis 4:
*Creemos que las empresas de transporte deben evaluar constantemente la efectividad de los protocolos de seguridad implementados.*
*Sabremos que hemos tenido éxito cuando la calificación de seguridad de las empresas mejore significativamente gracias a nuestra solución.*

**Métricas:**
1. *Calificación de Seguridad:* Evaluación anual de seguridad por parte de las aseguradoras.
   - Métrica actual: 7/10
   - Meta deseada: 9/10

2. *Feedback de Conductores:* Porcentaje de conductores que reportan sentirse más seguros al utilizar el sistema.
   - Métrica actual: 60%
   - Meta deseada: 90%

---

### Hipótesis 5:
*Creemos que los sensores IoT mejorarán la seguridad en el transporte de gases combustibles.*
*Sabremos que hemos tenido éxito cuando los registros de alertas generadas por los sensores muestren una reducción en los riesgos de fugas.*

**Métricas:**
1. *Alertas por Fugas:* Número de alertas emitidas por fugas detectadas.
   - Métrica actual: 15 alertas mensuales
   - Meta deseada: 5 alertas mensuales

2. *Satisfacción del Cliente:* Estrellas promedio en una escala de 1 a 5 basada en la satisfacción con la solución IoT.
   - Métrica actual: 4.0 estrellas promedio
   - Meta deseada: 4.8 estrellas promedio


#### 1.2.2.4. Lean UX Canvas


![image](https://github.com/user-attachments/assets/206cc4de-3194-4e2d-b4c5-7eb92febd4eb)



## 1.3. Segmentos objetivo

| Tipo de Usuario | Conductores que transportan gases combustibles | Empresas de transporte que operan con materiales peligrosos | 
| - | - | - |
| **Geográfico** | País: Perú <br> Zona de operación: Zonas urbanas y rurales, especialmente aquellas asociadas a rutas de transporte de gases inflamables. | País: Perú <br> Zona de operación: Regiones que abarcan trayectos donde se movilizan materiales peligrosos.|  
| **Psicográfico** | Clase Social: Media <br> Estilo de Vida: Conductores experimentados en el manejo de materiales peligrosos, enfocados en la seguridad y la reducción de riesgos durante sus actividades laborales. | Clase social: No es relevante dado que puede incluir pequeñas empresas de transporte o grandes corporaciones. <br> Estilo de vida: Empresas orientadas a garantizar la seguridad y la eficiencia en el transporte de materiales peligrosos, con interés en la innovación y mejora continua de sus protocolos. |  
| **Demográfico** | Edad: 25 a 55 años <br> Nivel de Ingreso: No determinante; enfocado en conductores profesionales con trayectoria en el manejo de vehículos pesados. | Edad: 30 a 60 años <br> Nivel de ingreso: No es un factor clave; dirigido a empresas que administran flotas dedicadas al transporte de materiales peligrosos. |

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 15%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 18%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th rowspan="2">¿Por qué llevar a cabo este análisis?</th>
<th colspan="5">Se hace este analisis para conocer las debilidades y fortalezas y compararlas con el producto solución propuesto</th>
</tr>
<tr class="odd">
<th colspan="5">Permite reconocer las ventajas competitivas y áreas de mejora de "Chemtrack" frente a competidores clave, facilitando el diseño de estrategias eficaces para destacarse en el sector agrícola y atraer a agricultores y comerciantes.</th>
</tr>
<tr class="header">
<th></th>
<th></th>
<th>Chemtrack</th>
<th>Grupo Caresny</th>
<th>Dachser</th>
<th>Cargo & Transport</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil</th>
<th>Overview</th>
<th>Plataforma tecnológica integral con sensores IoT para alertar y monitorear condiciones críticas durante el transporte de materiales peligrosos.</th>
<th>Empresa tradicional del rubro logístico, enfocada en soluciones personalizadas.</th>
<th>Multinacional con cobertura global y servicios de transporte terrestre, marítimo y aéreo.</th>
<th>Especialista en carga pesada y bienes industriales, con enfoque en mercados en crecimiento.</th>
</tr>
<tr class="header">
<th>Ventaja competitiva</th>
<th>Seguridad en tiempo real con sensores que detectan fugas, temperatura, presión y movimiento</th>
<th>Amplia red de transporte y servicios integrados.</th>
<th>Gran infraestructura global y experiencia en logística compleja.</th>
<th>Capacidad para operar en entornos difíciles y con cargas especiales.</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil de Marketing</th>
<th>Mercado Objetivo</th>
<th>Empresas del sector químico, petrolero y otras que gestionan transporte de materiales peligrosos.</th>
<th>Negocios que buscan servicios logísticos a medida, principalmente retail y consumo masivo.</th>
<th>Empresas internacionales con operaciones logísticas complejas.</th>
<th>Industrias pesadas y proyectos de infraestructura en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Estrategias de marketing</th>
<th>Promoción de seguridad y cumplimiento normativo como elementos diferenciadores.</th>
<th>Contratos duraderos y atención personalizada.	</th>
<th>Uso de infraestructura avanzada y tecnología para la cadena de suministro.</th>
<th>Reputación de fiabilidad y capacidad para manejar operaciones complejas.</th>
</tr>
<tr class="odd">
<th rowspan="3">Perfil de Producto</th>
<th>Productos &amp; Servicios</th>
<th>Monitoreo IoT especializado en transporte seguro de productos peligrosos.	</th>
<th>Servicios de transporte terrestre, almacenamiento y logística.</th>
<th>Transporte multimodal y soluciones integradas de cadena de suministro.</th>
<th>Transporte de gran escala, logística para proyectos industriales.</th>
</tr>
<tr class="header">
<th>Precios y Costos</th>
<th>Modelo por suscripción ajustable según cantidad de sensores y funcionalidades.</th>
<th>Tarifas competitivas y adaptables al tipo de servicio.	</th>
<th>Costos variables según la complejidad y cobertura requerida.</th>
<th>Costos determinados por tipo de carga y nivel de dificultad.</th>
</tr>
<tr class="odd">
<th><p>Canales de distribución</p>
<p>(Web y/o Móvil)</p></th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
</tr>
<tr class="header">
<th rowspan="5">Análisis SWOT</th>
<th colspan="5">Realice esto para su startup y sus competidores. Sus
fortalezas deberían apoyar sus oportunidades y contribuir a lo que
ustedes definen como su posible ventaja competitiva.</th>
</tr>
<tr class="odd">
<th>Fortalezas</th>
<th>Alta innovación tecnológica, monitoreo en tiempo real, y plataforma digital robusta.</th>
<th>Red logística consolidada, relaciones sólidas con clientes.</th>
<th>Cobertura internacional, experiencia en logística avanzada.</th>
<th>Capacidad para manejar cargas especiales, presencia fuerte en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Debilidades</th>
<th>Alta dependencia tecnológica, posibles costos iniciales elevados.</th>
<th>Falta de innovación frente a competidores modernos.</th>
<th>Costos altos, fuerte presencia en mercados maduros más que emergentes.</th>
<th>Cobertura global limitada frente a otras multinacionales.</th>
</tr>
<tr class="odd">
<th>Oportunidades</th>
<th>Mayor demanda por soluciones seguras, posibilidad de expansión internacional.	</th>
<th>Potencial para adoptar nuevas tecnologías y expandirse.	</th>
<th>Crecimiento en mercados emergentes, enfoque sostenible.	</th>
<th>Posibilidad de ingresar a nuevos sectores y alianzas tecnológicas.</th>
</tr>
<tr class="header">
<th>Amenazas</th>
<th>Competencia con grandes corporaciones con más recursos, cambios en la regulación.	</th>
<th>Presión de empresas más tecnológicas y competitivas.	</th>
<th>Volatilidad económica global, competencia en mercados emergentes.	</th>
<th>Restricciones ambientales más estrictas, competencia en precios.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

| Estrategia/ Táctica                          | Medidas a tomar                                         |
|----------------------------------------------|---------------------------------------------------------|
| Diferenciación en implementación IoT | \- Destacar la ventaja de la implementación de sensores junto con una aplicación    |
|                                              | \- Resaltar el uso de sensores durante todo el transporte           |
|                                              | \- Alianzas con empresas de transporte |
| Enfoque en la seguridad                    | \- Priorizar la seguridad de los conductores         |
|                                              | \- Ofrecer a las empresas los detalles obtenidos por los sensores en tiempo real         |
| Publicidad mediante redes sociales         | \- Resaltar funcionalidades IoT            |
|                                              | \- Publicitar la solución IoT mediante Facebook, Instagram y Google Ads.           |

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas.

A continuación, se diseñaron entrevistas dirigidas a los dos segmentos objetivos definidos para el proyecto. Las preguntas fueron elaboradas con el fin de generar respuestas abiertas y detalladas por parte de los entrevistados, permitiendo así obtener información valiosa que nos ayude a comprender mejor sus necesidades. Cabe mencionar que las preguntas de introducción no están incluidas en esta lista; sin embargo, se realizarán al inicio de cada entrevista.

**Segmento objetivo: Transportistas**

El objetivo de las preguntas del segmento objetivo de los transportistas es identificar las necesidades, desafíos y preferencias de los transportistas en relación con la seguridad y el monitoreo de cargas peligrosas, con el propósito de diseñar una solución tecnológica que mejore su eficiencia y protección durante el transporte.

**Preguntas de introducción**

- ¿Cúal es tu nombre?
- ¿Cuantos años tienes?
- ¿En que distrito vives actualmente?

**Preguntas prinicipales**

- ¿Qué sistemas de seguridad utilizas actualmente para evitar incidentes durante el transporte de gases inflamables?

- ¿Has vivido alguna situación relacionada con fugas de gas u otro tipo de incidente? En caso afirmativo, ¿cómo respondiste ante ello?

- ¿Qué dificultades o problemas encuentras con mayor frecuencia en tu labor como transportista?

- ¿Cuentas con alguna tecnología o dispositivo que te permita monitorear la seguridad de tu carga mientras estás en ruta? ¿Qué ventajas y desventajas has percibido?

- ¿Estarías dispuesto a incorporar una solución tecnológica que permita supervisar en tiempo real las condiciones del cargamento? ¿Cuál sería tu motivación?

- ¿Qué tipos de sensores consideras adecuados para el monitoreo de combustibles durante el transporte en vehículos?

- ¿Qué clase de notificaciones o alertas crees que serían más efectivas para prevenir posibles fugas de gases durante el traslado?

- ¿Cuál sería tu canal preferido para recibir este tipo de alertas (por ejemplo, app móvil, SMS, entre otros)?

- ¿Qué obstáculos crees que podrían dificultar la incorporación de nuevas tecnologías de monitoreo en tu trabajo diario?

- ¿Qué funcionalidades considerarías imprescindibles en una solución tecnológica emergente para adoptarla como parte de tu rutina?

- ¿Cuál es tu opinión sobre las tecnologías actuales que existen en el mercado enfocadas en la seguridad del transporte de materiales peligrosos?

- ¿Qué mejoras consideras necesarias en estas soluciones para que resulten más eficientes y útiles?

- ¿Tu vehículo cuenta con una pantalla que permita la interacción con algún sistema operativo?

- ¿Qué dispositivos usas con mayor frecuencia durante tus jornadas laborales?

**Segmento objetivo: Empresas de transporte de productos peligrosos**

El objetivo de las preguntas del segmento objetivo de las empresas de transporte de productos peligrosos es evaluar las estrategias de seguridad, tecnologías actuales y disposición de las empresas de transporte para adoptar soluciones IoT, con el fin de identificar oportunidades de mejora y diseñar una herramienta que optimice la gestión y seguridad de las operaciones logísticas.

**Preguntas de introducción**

- ¿Cúal es tu nombre?
- ¿Cuantos años tienes?
- ¿En que distrito vives actualmente?

**Preguntas prinicipales**

- ¿Qué medidas de seguridad aplica tu empresa para proteger tanto al personal como a la carga durante el traslado de productos peligrosos?

- ¿Cómo se lleva a cabo la formación del personal en temas de prevención de incidentes y actuación ante emergencias?

- ¿Qué tecnologías o herramientas están actualmente en uso en tu empresa para supervisar la seguridad de las cargas peligrosas?

- ¿Qué tipos de sensores consideras más apropiados para el monitoreo de combustibles en vehículos?

- ¿Tu empresa estaría interesada en adoptar una solución IoT para supervisar en tiempo real la seguridad de los cargamentos? ¿Por qué razón?

- ¿Qué beneficios esperas lograr mediante la implementación de una tecnología IoT enfocada en la seguridad?

- ¿Qué inquietudes podrían surgir respecto a la adopción de esta solución en tu organización?

- ¿De qué forma prefieres que tu empresa reciba alertas sobre posibles riesgos durante el transporte?

- ¿Cómo impactarían estas notificaciones en las decisiones operativas de tu empresa?

- ¿Consideras que una solución de monitoreo basada en IoT podría convertirse en una ventaja competitiva? ¿De qué manera?

- ¿Qué características clave debería tener esta solución para destacar frente a otras propuestas tecnológicas del mercado?

### 2.2.2. Registro de entrevistas

**Segmento objetivo: Transportistas**

***Primera Entrevista:***

Nombres y apellidos: Carolina Torres Torres

Edad: 27

Inicio: 0:00

Fin: 5:07

Duración: 5:07

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114248_upc_edu_pe/ESJ2p17qJopCnR5y_ExwldIBFC13m5znCcQtlcKynGLgHw?e=0XxBFT&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista1t](https://i.imgur.com/0MFB9Rr.png)

Resumen:

- Carolina es una transportista de productos reactivos y actualmente cuenta con un sistema de GPS y un monitoreo de temperatura básico instalado en su vehículo. Ella nos comentó que su principal motivación para incorporar una solución tecnológica adicional es mejorar su seguridad, ya que esto le permitiría prevenir un mayor número de accidentes que podrían poner en riesgo tanto su integridad como la de las personas a su alrededor. Además, menciona que esta solución también le brindaría mayor tranquilidad durante sus recorridos. Carolina prefiere que las notificaciones se emitan mediante alertas sonoras, ya que considera que así podrá estar más atenta a ellas mientras conduce. En cuanto a las funcionalidades que considera imprescindibles, destaca el monitoreo en tiempo real, las alertas automáticas y el acceso inmediato desde la central.


***Segunda Entrevista:***

Nombres y apellidos: Ian Perez

Edad: 25

Inicio: 25:55

Fin: 31:34

Duración: 05:39

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista2t](https://github.com/user-attachments/assets/fadb0fcb-c20a-44fd-b714-401c9a28501f)

- Hemos entrevistado a Ian Perez de 25 años de edad y vive en Ate Vitarte. Aunque no ha enfrentado incidentes graves, tuvo una experiencia cercana con una fuga de gas menor, en la que reaccionó de acuerdo con los protocolos de seguridad. Entre sus principales frustraciones están la incertidumbre sobre el estado de la carga y la falta de comunicación eficiente en algunas rutas. Actualmente, usa un sistema básico de rastreo GPS que le ofrece algunas ventajas, pero señala que no proporciona suficiente información sobre la seguridad de la carga. Está dispuesto a utilizar una solución tecnológica de monitoreo en tiempo real para mejorar la seguridad, siempre que sea fácil de usar y no represente una distracción. Considera esenciales los sensores de nivel de líquidos, presión y gases para monitorear combustibles, y prefiere recibir notificaciones a través de una pantalla en el vehículo o mediante una aplicación móvil. Utiliza principalmente el GPS y su teléfono móvil durante su jornada de trabajo.

***Tercera Entrevista:***

Nombres y apellidos: Luis Cornejo

Edad: 25

Inicio: 31:34

Fin: 39:17

Duración: 07:43

![Captura de pantalla 2024-09-06 171745](https://github.com/user-attachments/assets/6570a2ce-794a-41f8-870c-1fa46d93ea19)


Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

- Hemos entrevistado a Luis Cornejo de 25 años de edad y vive en San Borja. Nos cuenta que tienemedidas de seguridad como extintores, un sistema de detección de fugas y equipo de comunicación para reportar problemas. Aunque no ha enfrentado incidentes graves, tuvo una fuga menor que gestionó siguiendo los protocolos de seguridad. Entre sus principales frustraciones están la incertidumbre sobre el estado de la carga y la falta de comunicación eficiente en rutas complicadas. Actualmente, solo usa un sistema básico de rastreo que no le brinda información detallada sobre la seguridad de la carga. Está interesado en adoptar una solución tecnológica de monitoreo en tiempo real, especialmente con sensores de nivel de líquidos, presión y gases, para mejorar la prevención de fugas y peligros.



**Segmento objetivo: Empresas de transporte de productos peligrosos**

***Primera Entrevista:***

Nombre: Paolo Checa

Inicio: 0:00

Fin: 4:30

Duración: 4:30

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista2e](https://github.com/user-attachments/assets/a8db29a9-6d0b-473a-992b-9c071af4750c)

- Hemos entrevistado a Paolo Checa, quien explicó que actualmente cuentan solo con un sistema de GPS para monitorear los vehículos, y un seguro de vida para los transportistas, sin medidas específicas adicionales para su protección. La capacitación se limita a recomendaciones básicas como evitar exponer la carga a fuego o movimientos bruscos, y prefieren contratar transportistas experimentados. Aparte del GPS y los teléfonos proporcionados por la empresa, no disponen de otras tecnologías para la seguridad de las cargas.


***Segunda Entrevista:***

Nombre: Lissane Mareni

Inicio: 4:30

Fin: 8:48

Duración: 4:18

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista3e](https://github.com/user-attachments/assets/8c7c6c22-70f1-4775-9212-80a7b8fb3c28)

- Hemos entrevistado a Lisanne, quien mencionó que actualmente solo cuentan con un sistema de GPS para rastrear los vehículos y proporcionan un seguro de vida a los transportistas, pero no implementan medidas adicionales específicas para protegerlos. La capacitación que se ofrece es básica, enfocándose en evitar que la carga esté expuesta a fuentes de calor o movimientos bruscos, y se prefiere contratar conductores con experiencia. Además del GPS y los teléfonos entregados por la empresa, no utilizan tecnologías adicionales para garantizar la seguridad de las cargas.
  


***Tercera Entrevista:***

Nombre: Jose Luis Castillo

Inicio: 8:48

Fin: 14:38

Duración: 5:50

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista1e](https://github.com/user-attachments/assets/ade12b09-87c0-4c4e-8ddb-7cf14e5a830c)

- Hemos entrevistado Jose Luis Castillo de 22 años de edad que vive en Santiago de Surco, quien mencionó que implementan protocolos rigurosos para garantizar la seguridad de los transportistas y la carga, como la señalización adecuada, límites de velocidad, rutas seguras y revisiones periódicas de los vehículos. La capacitación de los transportistas incluye entrenamiento regular en el manejo de materiales peligrosos, procedimientos de emergencia y el uso de equipos de protección personal.
  
### 2.2.3. Análisis de entrevistas

Las entrevistas realizadas tanto a conductores como a representantes de empresas que transportan productos peligrosos han permitido identificar patrones comunes que subrayan la necesidad de fortalecer la seguridad, incorporar monitoreo en tiempo real y adoptar nuevas tecnologías, especialmente aquellas basadas en IoT. A continuación, se detallan los principales hallazgos:

- Actualmente, muchas empresas dependen principalmente de la experiencia del conductor y de acciones reactivas como el uso de extintores o la comunicación básica para manejar emergencias. Esto evidencia una oportunidad para reforzar los protocolos de seguridad a través de capacitaciones más completas y el uso de herramientas tecnológicas que permitan anticiparse a posibles incidentes.

- El uso de dispositivos tecnológicos como sensores de gas, temperatura y presión aún es escaso, lo cual representa una limitación significativa. Tanto las empresas como los transportistas podrían beneficiarse ampliamente de implementar soluciones IoT que proporcionen monitoreo constante y en tiempo real del estado de la carga, aumentando así los niveles de seguridad.

- Existe un marcado interés en adoptar tecnologías IoT, ya que se perciben como medios eficaces para mejorar la seguridad, hacer más eficientes los procesos logísticos y cumplir con normativas vigentes. Esta disposición abre la puerta a la introducción de soluciones que cubran estas necesidades específicas.

- No obstante, pese al interés, existen ciertos obstáculos que dificultan su adopción. Entre ellos destacan los costos asociados a la inversión inicial y los posibles problemas de conectividad en zonas remotas. Por ello, es esencial que las empresas proveedoras de estas tecnologías garanticen soluciones confiables, accesibles y fáciles de operar.

- La necesidad de recibir alertas en tiempo real es una demanda clave. Cualquier sistema basado en IoT debe incluir notificaciones precisas y oportunas, que no interfieran con las actividades del conductor, pero que faciliten la toma de decisiones inmediatas en caso de riesgo.

- La integración de tecnologías emergentes representa una oportunidad para que las empresas de transporte se posicionen como referentes en seguridad dentro del sector. Aquellas que adopten estas innovaciones de forma anticipada no solo optimizarán sus procesos, sino que también podrán atraer más clientes al ofrecer servicios más seguros y confiables.

![image](https://github.com/user-attachments/assets/59ec18cf-bdea-47e8-8ca3-e3801edbbf28)

En resumen, los testimonios obtenidos reflejan una necesidad concreta de actualizar los sistemas de seguridad actuales y apostar por soluciones tecnológicas como el IoT. Aunque el interés es alto, es fundamental abordar las preocupaciones sobre costos y conectividad. Las empresas que logren implementar estas tecnologías de forma efectiva obtendrán una ventaja competitiva y podrán mejorar considerablemente la seguridad en sus operaciones.

## 2.3. Needfinding
En esta sección, se buscarán las necesidades implícitas y explícitas de las personas o segmentos para poder diseñar y adaptar el producto solución de manera apropiada.

### 2.3.1. User Personas

Se realiza las User Persona, personaje ficticio para reflejar al cliente ideal, estos user persona son creados en base a la investigación de capitulos previos para identificar a los diferentes tipos de clientes que podrían usar el producto solución. Se utilizó la herramienta UXPressia.

**Transportistas de combustibles peligrosos**

![361573775-97d571cf-7016-4d0d-9b38-ed6343c98e6f](https://github.com/user-attachments/assets/d045a6b1-433a-47e3-ab11-df173cd3438d)


**Empresas de transporte de productos peligrosos**

![Carlo Galavis](https://github.com/user-attachments/assets/fb10e06a-0889-4d9b-a8d0-d005574d1eb8)

### 2.3.2. User Task Matrix

A continuación, se muestra el User Task Matrix para los siguientes segmentos objetivo:


<table>
  <tr>
    <th></th>
    <td colspan="2">TRANSPORTISTAS</td>
    <td colspan="2">EMPRESAS</td>
  </tr>
  <tr>
    <td>TASK</td>
    <td>FREQUENCY</td>
    <td>IMPORTANCE</td>
    <td>FREQUENCY</td>
    <td>IMPORTANCE</td>
  </tr>
  <tr>
    <td>Registrar los envíos de productos combustibles</td>
    <td>Low </td>
    <td>Low</td>
    <td>High</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Coordinar con los demás transportistas detalles acerca del cargamento</td>
    <td>Often</td>
    <td>High</td>
    <td>Rare</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>Trazar la ruta que se tiene que recorrer y sus peligros </td>
    <td>Always</td>
    <td>Medium</td>
    <td>Always</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Evaluar calidad de los vehiculos de transporte</td>
    <td>Always</td>
    <td>High</td>
    <td>Always</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Evaluar demanda y tendencias</td>
    <td>Often</td>
    <td>High</td>
    <td>Always</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Revisar el estado del cargamento</td>
    <td>Rare</td>
    <td>Low</td>
    <td>Always</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Inspeccionar la condición del cargamento previo al transporte</td>
    <td>Often</td>
    <td>Low</td>
    <td>Often</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Monitorear la velocidad del transportista</td>
    <td>Rare</td>
    <td>Low</td>
    <td>Always</td>
    <td>High</td>
  </tr>
</table>

**Tareas con Mayor Frecuencia e Importancia:**
- Frecuencia:

> Respecto al segmento objetivo de transportistas, las tareas que se realizan con mayor 
> frecuencia incluyen trazar la ruta que se tiene que recorrer y sus peligros, coordinar con los demás transportistas detalles acerca del cargamento, 
> y evaluar la calidad de los vehículos de transporte. Por otro lado, para el segmento de empresas de transporte de productos peligrosos, las tareas más
> frecuentes son evaluar la calidad de los vehículos de transporte, revisar el estado del cargamento, y trazar la ruta y sus peligros.

- Importancia:

> Para el segmento de empresas de transporte, las tareas más importantes incluyen registrar los 
> envíos de productos combustibles, evaluar la calidad de los vehículos de transporte, y monitorear la velocidad del transportista. 
> En el caso de los transportistas, las tareas de mayor relevancia son coordinar detalles acerca del cargamento, evaluar la 
> calidad de los vehículos de transporte, y trazar la ruta que se tiene que recorrer.

Principales Diferencias y Coincidencias:

Una de las principales diferencias entre los dos segmentos objetivo es que las empresas de transporte tienen una mayor responsabilidad en la supervisión y monitoreo del cargamento, como lo demuestra la alta importancia y frecuencia asignada a tareas como revisar el estado del cargamento y monitorear la velocidad del transportista. Por otro lado, los transportistas se centran más en la planificación de rutas y la coordinación con otros transportistas, lo que refleja su rol más operativo y menos gerencial.

Tanto los transportistas como las empresas coinciden en la alta importancia de la evaluación de la calidad de los vehículos de transporte y la necesidad de trazar rutas seguras y eficientes. Ambas audiencias reconocen la importancia crítica de estas tareas para garantizar la seguridad y la eficiencia en el transporte de productos peligrosos.

### 2.3.3. Journey Mapping

<img src="https://i.imgur.com/b1FuQz1.png" style="width:80%">
<img src="https://i.imgur.com/SEZ5r2H.png" style="width:80%">

### 2.3.4. Empathy Mapping

**Transportistas de combustibles peligrosos**

![Empathy map](https://github.com/user-attachments/assets/ed0e74aa-de6d-4e8f-9ca6-e235f146f6c7)

**Empresas de transporte de productos peligrosos**

![Empathy map (1)](https://github.com/user-attachments/assets/ef04d9c0-99cf-47e2-8c70-5f579319d6f7)

### 2.3.5. As-is Scenario Mapping

![image](https://github.com/user-attachments/assets/753224a7-ec79-412f-9fe9-7a5cf13b7c0b)
![image](https://github.com/user-attachments/assets/233c4c8e-0a59-472f-863e-d9023194cdc5)

## 2.4. Ubiquitous Language

Términos y Definiciones

**Dashboard (Panel de Control)**
Un panel de control es un componente de la interfaz de usuario que proporciona una visión general del estado del transporte, incluyendo datos en tiempo real de sensores de gas y temperatura. Permite a los operadores monitorear alertas de seguridad y la ubicación de la carga.

**Incident List (Listado de Incidentes)**
Una pantalla que presenta una lista de todos los incidentes reportados durante los servicios de transporte. Incluye detalles como niveles de gas peligrosos detectados, cambios de temperatura anormales y acciones correctivas tomadas.

**Incident Notification (Notificación de Incidentes)**
El proceso por el cual los transportistas y empresarios son informados de forma automática y en tiempo real sobre fugas de gas, temperaturas fuera del rango seguro u otros problemas detectados por los sensores IoT instalados en los vehículos de transporte.

**Monitoring Package (Monitoreo de Carga)**
Seguimiento en tiempo real del estado de la carga, utilizando sensores IoT para registrar niveles de gas, temperatura y otros parámetros críticos para evitar accidentes durante el transporte de productos peligrosos.

**Transport Service (Servicio de Transporte)**
El conjunto de operaciones logísticas, incluyendo el monitoreo en tiempo real y la detección temprana de riesgos, destinados a transportar bienes peligrosos como gasolina o gas desde un punto de origen hasta su destino final.

**Transporters (Transportistas)**
Personas o empresas responsables de supervisar los vehículos equipados con sensores IoT para garantizar un transporte seguro de productos peligrosos.

**Business Owner (Empresario)**
Persona o entidad encargada de gestionar la logística y la coordinación del transporte de bienes peligrosos, supervisando las métricas de seguridad proporcionadas por la solución IoT.

**Incident Report (Reporte de Incidente)**
Documento generado automáticamente que detalla un incidente detectado por los sensores IoT, como fugas de gas o incrementos bruscos de temperatura. Incluye la causa, impacto y medidas correctivas tomadas.

**Sensor Alerts (Alertas de Sensores)**
Notificaciones automáticas enviadas a través de la plataforma cuando los sensores IoT detectan condiciones peligrosas como niveles altos de gas o temperaturas fuera del rango seguro.

**Transporter Rating (Calificación de Transportistas)**
Evaluación de la calidad del servicio ofrecido por los transportistas basada en su capacidad de respuesta a alertas de seguridad y su cumplimiento con los estándares de manejo de bienes peligrosos.

**Transporter Registration (Registro de Transportistas)**
Proceso mediante el cual un transportista se registra en la plataforma para vincular su flota de vehículos con sensores IoT y ofrecer servicios de transporte seguro.

**Login (Iniciar Sesión)**
El proceso mediante el cual un usuario accede a su cuenta en la plataforma para monitorear, gestionar o responder a alertas relacionadas con el transporte de bienes peligrosos.

**Authentication Policy (Política de Autenticación)**
Conjunto de reglas que garantizan que solo usuarios autorizados, como transportistas y empresarios, puedan acceder a la plataforma y monitorear los datos IoT.

**Transport Route (Ruta de Transporte)**
El trayecto definido que debe seguir el transportista, monitoreado en tiempo real para garantizar el cumplimiento de condiciones seguras a lo largo del recorrido.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
![image](https://github.com/user-attachments/assets/c5d9bbff-01ac-4111-8638-5a62cc7b1e40)

![image](https://github.com/user-attachments/assets/8027d267-90bf-4513-8589-bc8096e62f76)


## 3.2. User Stories

| **Epic ID** | **Epic**                                             | **Descripción**                                                                           |
|-------------|-------------------------------------------------------|--------------------------------------------------------------------------------------------|
| EP01        | Gestión de Transportistas y Documentación de Cumplimiento | Gestión y mantenimiento de perfiles de transportistas, verificación de permisos, y certificaciones. |
| EP02        | Gestión de Solicitudes de Transporte                 | Publicación y administración de solicitudes de transporte por parte de las empresas.       |
| EP03        | Seguimiento en Tiempo Real            | Monitoreo en tiempo real del transporte de productos peligrosos.|
| EP04        | Acciones de prevención            | Acciones a realizar como respuesta ante posibles incidentes que puedan ocurrir con la carga.|

---

| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** |
|---------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** 
| US01                | Monitoreo del Vehículo                             | Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.                                                         | **Escenario 1: Realizar monitoreo**. Dado que el transportista necesite asegurar el estado del vehículo, cuando inicie la función de monitoreo, entonces el sistema presentará un reporte con el estado del vehículo. **Escenario 2: Error en el monitoreo**. Dado que el sistema presenta un error durante la verificación del estado del vehículo, cuando el transportista intente iniciar la función de monitoreo, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo realizar el monitoreo y sugerir intentar nuevamente o contactar soporte. | EP03                          |
| US02                | Notificaciones de Mantenimiento Preventivo         | Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.                                                                  | **Escenario 1: Notificación de mantenimiento**. Dado que el vehículo se acerque a la fecha de mantenimiento, cuando el sistema detecte la proximidad de esta fecha, entonces se enviará una notificación al transportista. **Escenario 2: Error en la notificación**. Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el transportista revise el sistema, entonces este deberá mostrar un mensaje indicando que hubo un problema y permitir al transportista revisar manualmente las fechas de mantenimiento programadas.         | EP04                          |
| US03                | Verificación de Rutas Seguras                      | Como transportista, quiero verificar rutas seguras antes de iniciar un viaje, para minimizar riesgos.                                                                                                         | **Escenario 1: Verificar ruta**. Dado que el transportista necesite planificar una ruta, cuando el sistema identifique rutas peligrosas, entonces sugerirá rutas alternativas más seguras. **Escenario 2: Error al verificar ruta**. Dado que el sistema no puede cargar las rutas, cuando el transportista intente verificar rutas seguras, entonces el sistema deberá mostrar un mensaje de error e indicar al transportista que intente más tarde o contacte soporte técnico.                                                           | EP03                          |
| US04                | Reporte de Estado del Vehículo                     | Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.                                                                                    | **Escenario 1: Generar reporte**. Dado que el transportista complete la revisión del vehículo, cuando se complete la revisión, entonces el sistema permitirá generar un reporte que puede ser enviado al supervisor. **Escenario 2: Error al generar reporte**. Dado que el sistema falle en generar el reporte, cuando el transportista intente crear el reporte después de la revisión, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo generar el reporte y sugerir reintentar o guardar los datos manualmente. | EP03                          |
| US05                | Seguimiento en Tiempo Real de los Transportes Activos| Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.          | **Escenario 1: Seguimiento del Transporte en Tiempo Real**. Dado que hay un transporte activo en curso, cuando la empresa accede a la sección de seguimiento de transportes, entonces el sistema muestra la ubicación actual, la velocidad y el estado del transporte en tiempo real en un mapa. **Escenario 2: Error en el seguimiento en tiempo real**. Dado que el sistema falle en actualizar la ubicación del transporte, cuando la empresa intente realizar el seguimiento en tiempo real, entonces el sistema deberá mostrar un mensaje indicando que no se puede obtener la ubicación y permitir reintentar o contactar al transportista directamente. | EP03                          |
| US06                | Verificación de Permisos de Transportistas         | Como empresa de transporte de productos peligrosos, quiero verificar los permisos y certificaciones de los transportistas antes de contratarlos.                                                              | **Escenario 1: Verificación de Permisos y Certificaciones**. Dado que la empresa busca contratar un transportista, cuando selecciona un transportista de la lista de disponibles, entonces el sistema muestra un detalle de los permisos, certificaciones y calificaciones del transportista. **Escenario 2: Error al verificar permisos**. Dado que el sistema no pueda cargar los detalles del transportista, cuando la empresa intente verificar permisos y certificaciones, entonces el sistema deberá mostrar un mensaje de error y sugerir intentar más tarde o contactar soporte. | EP02                          |
| US07                | Recibir Notificaciones de Incidentes en Tiempo Real | Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).                     | **Escenario 1: Recepción de Notificaciones de Incidentes**. Dado que un transporte está en curso, cuando ocurre un incidente o evento inesperado, entonces el sistema envía una notificación en tiempo real a la empresa con detalles del incidente y posibles acciones a tomar. **Escenario 2: Error al recibir notificación de incidente**. Dado que el sistema falle en enviar la notificación de incidente, cuando la empresa espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje indicando que no se pudo enviar la notificación y sugerir verificar el estado del transporte manualmente o contactar al transportista. | EP04                          |
| US08                | Registro de Transportista de Combustibles Peligrosos| Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.          | **Escenario 1: Validación del Registro de Transportista**. Dado que el transportista accede a la página de registro, cuando completa todos los campos requeridos y adjunta los documentos de certificación, entonces el sistema valida la información y confirma el registro si todos los datos son correctos. **Escenario 2: Error al registrar transportista**. Dado que el sistema falle en procesar el registro, cuando el transportista intente registrarse, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo completar el registro y sugerir reintentar o contactar soporte técnico.                   | EP01                          |
| US09                | Notificación de Nuevas Solicitudes de Transporte    | Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.                                                                                                           | **Escenario 1: Recepción de Notificación de Nueva Solicitud**. Dado que una empresa de transporte publica una nueva solicitud de transporte de combustibles, cuando el transportista tiene los permisos adecuados y disponibilidad, entonces el transportista recibe una notificación y puede optar por aceptar o rechazar la solicitud. **Escenario 2: Error al recibir notificación de nueva solicitud**. Dado que el sistema falle en enviar la notificación, cuando el transportista espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje de error y sugerir revisar manualmente las solicitudes publicadas o contactar a la empresa de transporte. | EP02                          |
| US10                | Actualización de Estado del Transporte              | Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).                                                                     | **Escenario 1: Actualización del Estado del Transporte en Curso**. Dado que el transportista ha aceptado un trabajo y está en ruta, cuando hay un cambio en el estado del transporte, entonces el transportista puede actualizar el estado y la empresa recibe una notificación con el estado actualizado. **Escenario 2: Error al actualizar estado del transporte**. Dado que el sistema falle en procesar la actualización del estado del transporte, cuando el transportista intente actualizar el estado, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo actualizar el estado y sugerir reintentar o contactar a la empresa directamente. | EP02                          |
| US11                | Publicación de Solicitudes de Transporte de Productos Peligrosos | Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.                              | **Escenario 1: Publicación de Solicitud de Transporte**. Dado que la empresa accede a la sección de solicitud de transporte, cuando completa el formulario de solicitud con toda la información requerida, entonces la solicitud se publica y los transportistas calificados reciben notificaciones. **Escenario 2: Error al publicar solicitud de transporte**. Dado que el sistema falle en procesar la solicitud de transporte, cuando la empresa intente publicar la solicitud, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo publicar la solicitud y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US12                | Visualización de Transportistas Disponibles         | Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.                   | **Escenario 1: Visualización de Transportistas Calificados**. Dado que la empresa ha publicado una solicitud de transporte, cuando hay transportistas calificados disponibles, entonces el sistema muestra una lista de transportistas con sus detalles de calificación, precio, y disponibilidad. **Escenario 2: Error al visualizar transportistas disponibles**. Dado que el sistema falle en cargar la lista de transportistas disponibles, cuando la empresa intente visualizar transportistas calificados, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar la lista y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US13                | Acceso a Historial de Transportes Realizados        | Como transportista de combustibles peligrosos, quiero acceder a un historial de todos los transportes que he realizado, con detalles sobre la carga, rutas, y tiempos de entrega.                            | **Escenario 1: Visualización del Historial de Transportes**. Dado que el transportista está en su panel de control, cuando selecciona la opción de historial de transportes, entonces el sistema muestra una lista de transportes realizados con detalles relevantes como fechas, rutas, tipos de combustible transportado, y tiempos de entrega. **Escenario 2: Error al visualizar historial de transportes**. Dado que el sistema falle en cargar el historial de transportes, cuando el transportista intente acceder a su historial, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar el historial y sugerir reintentar o contactar soporte técnico. | EP01                          |
| US14                | Control de tiempos de conducción de transporte       | Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento de las horas de conducción por los transportistas activos para evitar manejen en estado de cansancio.                                                      | **Escenario 1: Visualización del tiempo de conducción en curso**. Dado que hay un transporte actualmente en operación, cuando la empresa acceda a la sección de seguimiento de transportes, entonces el sistema deberá mostrar el total de horas que el conductor ha estado manejando durante la jornada actual. **Escenario 2: Fallo en la obtención del tiempo de conducción**. Dado que el sistema no puede recuperar la información sobre las horas de conducción del transportista, cuando la empresa intente acceder al seguimiento en tiempo real, entonces el sistema deberá mostrar un mensaje de error indicando que no fue posible obtener los datos, y ofrecer la opción de reintentar o contactar directamente al conductor.      | EP03                          |
| US15                | Notificación de tiempo de conducción de transporte en exceso        | Como transportista de combustibles peligrosos, quiero recibir una notificación en caso de excederme el total de horas seguidas recomendadas de conducción por día para evitar posibles accidentes al manejar en estado de cansancio.                                                      | **Escenario 1: Visualización del tiempo de conducción en curso**. Dado que el transportista ha excedido la cantidad de horas seguidas recomendadas de conducción por día, cuando el sistema detecte el exceso de tiempo de conducción, entonces se enviara una notificación al conductor que le indique que debe parar sus turnos por el día y que realice un relevo en la conducción con otro conductor del sistema. **Escenario 2: Error en la visualización de la notificación**. Dado que el sistema no logra mostrar correctamente la notificación al transportista, cuando el transportista haya superado el máximo de horas, entonces generará automaticamente una alerta sonora dentro del vehículo.      | EP04                          |
| US16                | Landing Page responsive       | Como visitante, deseo visitar la landing page desde cualquier dispositivo.                                                      | **Escenario 01**: Dado que el visitante necesita una aplicación web o móvil para mejorar su servicio, cuando busque en el navegador "Monitorear productos peligrosos", entonces accede a la landing page y visualiza las funcionalidades que le ofrece la aplicación web o móvil. **Escenario 02**: Dado que el visitante desea una aplicación web o móvil con características puntuales de seguridad de transporte de productos peligrosos, cuando navegue por la landing page y se encuentre en la sección de beneficios y funcionalidades, entonces visualizará la funcionalidad que se desea y se decide en usar la aplicación web o móvil.      | EP01                          |
| US17                | Visualización de características de la aplicación web o móvil en Landing Page | Como visitante, deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo.                                  | **Escenario 01**: Dado que el visitante accede a la landing page desde su celular, cuando visite la landing page desde el navegador de su celular, entonces la landing page con su diseño responsive puede visualizarse adecuadamente en el navegador del dispositivo móvil. **Escenario 02**: Dado que el visitante recomienda la landing page mediante un dispositivo móvil, cuando el otro visitante recomendado acceda a la landing page desde otro dispositivo móvil con resolución diferente, entonces la landing page se mostrará completamente visible y ordenada dado que es responsive.            | EP01                          |
| US18                | Botón Call to Action       | Como visitante, deseo ir a la aplicación web o móvil desde un solo botón desde la landing page.                                    | **Escenario 01**: Dado que el visitante desea usar la aplicación web o móvil, cuando esté en la sección donde se encuentre el botón call to action y lo use, entonces será dirigido a la aplicación web o móvil. **Escenario 02**: Dado que el visitante quedó satisfecho con la información brindada en la landing page, cuando desee empezar a usar la aplicación web o móvil, entonces puede acceder a ella de forma rápida mediante el botón call to action            | EP01                          |
| **TS-01** | Implementación de Monitoreo del Vehículo           | Como desarrollador, quiero implementar la funcionalidad de monitoreo del vehículo para que los transportistas puedan verificar el estado del vehículo antes de iniciar un viaje. | **Background:** Implementar el endpoint `GET /api/vehicle-monitoring/{vehicleId}` para obtener el estado actual del vehículo.<br><br>**Scenario 01: Obtener estado del vehículo**<br>Dado que el transportista quiere verificar el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo existe en la base de datos, entonces el sistema devuelve un `response` con `status 200` y los detalles del estado del vehículo en el `Response Body`.<br><br>**Scenario 02: Error al obtener estado del vehículo**<br>Dado que el sistema falla en obtener el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo no existe o hay un problema en el sistema, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP03**                   |
| **TS-02** | Implementación de Notificaciones de Mantenimiento Preventivo | Como desarrollador, quiero implementar el sistema de notificaciones de mantenimiento preventivo para alertar a los transportistas cuando se acerque la fecha de mantenimiento del vehículo. | **Background:** Configurar un sistema de notificaciones automáticas que envíe alertas a través de `POST /api/notifications/maintenance`.<br><br>**Scenario 01: Envío de notificación de mantenimiento**<br>Dado que la fecha de mantenimiento del vehículo se acerca, cuando el sistema detecta que faltan X días para la fecha de mantenimiento, entonces se envía una notificación al transportista y se devuelve un `response` con `status 200` confirmando el envío exitoso.<br><br>**Scenario 02: Error en el envío de notificación de mantenimiento**<br>Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el sistema intenta enviar la notificación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP04**                   |
| **TS-03** | Implementación de Verificación de Permisos de Transportistas | Como desarrollador, quiero implementar la funcionalidad para verificar los permisos y certificaciones de los transportistas, para que las empresas puedan tomar decisiones informadas al contratarlos. | **Background:** Crear un endpoint `GET /api/transporters/{transporterId}/certifications` que devuelva los permisos y certificaciones de un transportista específico.<br><br>**Scenario 01: Obtener permisos y certificaciones del transportista**<br>Dado que la empresa necesita verificar los permisos de un transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, y el transportista tiene permisos registrados, entonces el sistema devuelve un `response` con `status 200` y los detalles de las certificaciones en el `Response Body`.<br><br>**Scenario 02: Error al obtener permisos y certificaciones**<br>Dado que el sistema falla en obtener los permisos del transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP02**                   |
| **TS-04** | Implementación de Monitoreo en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad de monitoreo en tiempo real utilizando la Edge API, para que los dispositivos IoT puedan enviar datos de ubicación, velocidad, estado y horas de conducción directamente desde el transporte. | **Background:** Configurar un endpoint en la Edge API `POST /edge/vehicle-monitoring` que reciba datos en tiempo real desde dispositivos IoT instalados en los vehículos.<br><br>**Scenario 01: Recepción de datos en tiempo real**<br>Dado que el vehículo está en movimiento, cuando el dispositivo IoT envía datos de ubicación, velocidad, estado y horas de conducción al endpoint `/edge/vehicle-monitoring`, entonces la Edge API procesa y almacena los datos en la base de datos central, devolviendo un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de datos**<br>Dado que el sistema IoT falla en enviar los datos al Edge API, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/vehicle-monitoring` y ocurre un error de conexión o datos corruptos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP03**                   |
| **TS-05** | Implementación de Notificaciones de Incidentes en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT envíen notificaciones de incidentes en tiempo real a través de la Edge API, para que la empresa pueda reaccionar rápidamente a situaciones críticas. | **Background:** Configurar un endpoint en la Edge API `POST /edge/incident-notifications` que reciba alertas de incidentes desde los sensores IoT del vehículo.<br><br>**Scenario 01: Recepción de notificación de incidente**<br>Dado que ocurre un incidente durante el transporte, cuando el dispositivo IoT detecta un evento crítico (accidente, desviación, etc.) y envía datos al endpoint `/edge/incident-notifications`, entonces la Edge API procesa la alerta, notifica a la empresa, y devuelve un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de notificación de incidente**<br>Dado que el sistema IoT falla en enviar la notificación de incidente, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/incident-notifications` y ocurre un error de comunicación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP04**                   |
| **TS-06** | Implementación de Actualización de Estado del Vehículo desde Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT en el vehículo actualicen el estado del transporte en tiempo real a través de la Edge API, para que la empresa siempre tenga información precisa sobre el progreso del viaje. | **Background:** Configurar un endpoint en la Edge API `PUT /edge/vehicle-status/{vehicleId}` que permita a los dispositivos IoT actualizar el estado del vehículo (en camino, retraso, entregado, etc.).<br><br>**Scenario 01: Actualización de estado exitosa**<br>Dado que el vehículo cambia su estado (por ejemplo, llega al destino), cuando el dispositivo IoT envía una actualización de estado al endpoint `/edge/vehicle-status/{vehicleId}`, entonces la Edge API actualiza la información en el sistema central y devuelve un `response` con `status 200` para confirmar la actualización exitosa.<br><br>**Scenario 02: Error en la actualización del estado del vehículo**<br>Dado que el sistema IoT falla en actualizar el estado del vehículo, cuando el dispositivo IoT intenta enviar una actualización al endpoint `/edge/vehicle-status/{vehicleId}` y ocurre un error de transmisión o de datos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP02**                   |


## 3.3. Impact Mapping

**Transportistas de combustibles peligrosos**

![Impact map Transportista](https://i.imgur.com/isPyVui.png)

**Empresas de transporte de productos peligrosos**

![Impact map Empresa de tansportes](https://i.imgur.com/5o4y4SJ.png)



## 3.4. Product Backlog

A continuación, se mostrará la herramienta Product Backlog, lista de trabajo ordenado por la prioridad para el equipo de desarrollo de GreatMinds.

|**#Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :-: | :-: | :-: | :-: | :-: |
|01|US17|Visualización de características de la aplicación web o móvil web en Landing Page|Como visitante deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo|5|
|02|US16|Landing Page responsive| Como visitante deseo visitar la landing page desde cualquier dispositivo.|5|
|03|US18|Botón Call to Action|Como visitante deseo ir a la aplicación web o móvil web desde un solo botón desde la landing page |5|
|04|US11|Publicación de Solicitudes de Transporte de Productos Peligrosos|Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.|5|
|05|US09|Notificación de Nuevas Solicitudes de Transporte|Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.|8|
|06|US01|Monitoreo del Vehículo|Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.|8|
|07|US03|Verificación de Rutas Seguras|Como transportista, quiero verificar rutas seguras antes de iniciar un viaje, para minimizar riesgos.|5|
|08|US12|Visualización de Transportistas Disponibles|Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.|5|
|09|US10|Actualización de Estado del Transporte|Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).|8|
|10|US08|Registro de Transportista de Combustibles Peligrosos|Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.|8|
|11|US06|Verificación de Permisos de Transportistas|Como empresa de transporte de productos peligrosos, quiero verificar los permisos y certificaciones de los transportistas antes de contratarlos.|3|
|12|US07|Recibir Notificaciones de Incidentes en Tiempo Real|Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).|5|
|13|US15|Notificación de tiempo de conducción de transporte en exceso|Como transportista de combustibles peligrosos, quiero recibir una notificación en caso de excederme el total de horas seguidas recomendadas de conducción por día para evitar posibles accidentes al manejar en estado de cansancio.|5|
|14|US05|Seguimiento en Tiempo Real de los Transportes Activos|Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.|2|
|15|US13|Control de tiempos de conducción de transporte|Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento de las horas de conducción por los transportistas activos para evitar manejen en estado de cansancio.|2|
|16|US14|Reporte de Estado del Vehículo|Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.|2|
|17|US04|Reporte de Estado del Vehículo|Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.|3|
|18|US02|Notificaciones de Mantenimiento Preventivo|Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.|3|

# Capítulo IV: Solution Software Design

## 4.1 Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
Durante la fase de *Event Storming*, el equipo de desarrollo llevó a cabo una sesión colaborativa en la que se compartieron ideas sobre funcionalidades y características que se deseaban incorporar en el proyecto. 

Para realizar esta dinámica se hizo uso de la plataforma *MIRO* como soporte visual y de organización. *Ver ANEXO A*

**Step 1: Unstructured exploration**

En esta fase, se lograron definir los eventos más relevantes que reflejan las acciones clave dentro de la solución tecnológica logrando así los primeros borarradores de los *bounded context*.

![image](https://github.com/user-attachments/assets/20a8a668-6e4e-4d80-90fe-b87d6e609bff)

**Step 2: Timelines**

En esta etapa, los eventos detectados se organizaron en conjuntos más pequeños, considerando tanto las rutas ideales o exitosas *(happy paths)* como aquellas que representan fallos o situaciones no deseadas *(unhappy paths)*. Esta clasificación permitió estructurar mejor la información y entender las distintas secuencias dentro del sistema de forma más clara.

![image](https://github.com/user-attachments/assets/3873cf40-8ccf-4aa3-a3a8-dd4e10f9014a)

**Step 3: Paint Points**

En este proceso se detectaron *paint points*, es decir, áreas problemáticas donde los usuarios podrían enfrentar dificultades al interactuar con nuestro sistema. Identificarlos es clave para mejorar la experiencia de uso y optimizar el diseño de la aplicación.

![step3](https://github.com/user-attachments/assets/f84f6a50-bde3-46fe-8577-3a862380ec8c)


**Step 4: Pivotal Points**

Durante esta fase se identificaron *pivotal points*, es decir, eventos clave que representan momentos cruciales en el flujo de la plataforma, con un fuerte impacto en el comportamiento del sistema o la experiencia de usuario.

![image](https://github.com/user-attachments/assets/7d6160ab-2489-4c5e-9206-7b69ddd0b90b)

**Step 5: Commands**

En este proceso, a cada evento se le asignó un comando específico que lo activa y un actor responsable de ejecutarlo, lo que le permitió comprender mejor la interacción de los usuarios con el sistema.

![step5](https://github.com/user-attachments/assets/511ac749-892d-4f8e-9ab5-c175d36c27bc)

**Step 6: Policies**

En esta etapa se definieron las políticas relevantes para cada contexto del sistema, incluyendo reglas de negocio, validaciones y restricciones específicas. 

![step6](https://github.com/user-attachments/assets/cd03c448-e0cf-42f4-b22b-d49c73f8ec9a)

**Step 7: Read Models**

En esta fase se diseñaron y desarrollaron los modelos de lectura correspondientes a cada contexto del sistema, grantizando que ofrecieran la información necesaria de forma clara, eficiente y alineada con las necesidades de usuario.

![step7](https://github.com/user-attachments/assets/c3698437-46d0-42c1-98f2-0a2feefa6a73)

**Step 8: External Systems**

Durante el transcurso de este proceso se identificaron los sistemas externos con los que la plataforma debe interactura y dse dfinieron las interfaces necesarias para lograr una integracion efectiva.

![step8](https://github.com/user-attachments/assets/43c6e6a4-103b-4425-94e1-60daccd9f8b6)


**Step 9: Aggregates**

En el transcurso de esta etapa se definieron los *aggregates* para cada contexto del sistema, con el objetivo de representar adecuadamente las transacciones y operaciones que deben mantenerse coherentes.

![step9](https://github.com/user-attachments/assets/4129de72-61c2-4287-8e04-6e7a03dd6f7c)

**Step 10: Bounded Contexts**

Por último, gracias a la identificación y definición de cada uno de los elementos se pudo lograr la resolución de los *bounded contexts*, espacios centrales de funcionamiento diferentes, pero necesarios.

![bcts](https://github.com/user-attachments/assets/33a1784f-b1aa-4c31-b0b2-3d7891c702b8)

**[Enlace del MIRO para mayor visualización del Event Storming](https://miro.com/welcomeonboard/ZDUyWkh5OTlpSVF4RGdTNG9tdkI0N0FnS1F5VUtRczM0dXJkS2dSZHRDeW1yWm54RW02c3EybHBKYzdIaGkxRjZUb2lwNHB2a0RKelJzRmJNUDd3NEoyNVE3Wk1Uc2U5MUFySzEyZFNBZ0pSa011QkVnQy93aVprVXUyVGFsQ2pNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=980476835383)**

#### 4.1.1.1 Candidate Context Discovery

Para priorizar el desarrollo del núcleo funcional del sistema aplicamos la técnica *start-with value*, con el objetivo de tener una visión más clara y enfocada del producto desde sus bases.

- **Identificación de valores del negocio:** Se realizó un análisis de los principales valores que aporta la aplicación. Tales como mejorar la experiencia de nuestros usuarios durante la monitorización de cargas, el registro eficiente de incidentes sucedidos durante el transporte, la calificación a nuestros usuarios transportistas luego de cada viaje relaixado y la optimización en la gestión de usuarios en Chemtrack.
- **Identidicación de funcionalidades clave:** Se definieron las funcionalidades fundamentales que sostienen el objetivo de nuestro sistema. Incluyendo la autenticación y registro de usuarios *(IAM)*, el monitoreo y notificación de incidentes *(MANAGEMENT)* y las operaciones de registro y reporte de incidentes *(RECORDS)*. Todas ellas alineadas directamente con el valor agregado del negocio.

**Candidate para Bounded Context: *IAM***

![iamBC](https://github.com/user-attachments/assets/60d88854-4c28-49c2-ab1c-b5df1bef1907)

**Candidate para Bounded Context: *MANAGEMENT***

![managementBC](https://github.com/user-attachments/assets/4f17b55d-9a8e-4d5e-8c82-2915430d7488)

**Candidate para Bounded Context: *RECORDS***

![recordsBC](https://github.com/user-attachments/assets/673b12d5-0db6-4d8a-8ef5-f9edd020ff22)

**Vista Completa**

![bcs](https://github.com/user-attachments/assets/9b91cbb8-8664-49b3-92bb-9342524bc4fb)

#### 4.1.1.2 Domain Message Flows Modeling

**Iniciar sesión:** El flujo de autenticación comienza con la entrada de las credenciales del usuario, las cuales son validadas por el sistema; si son correctas, el flujo continúa hacia el panel principal del usuario; en caso contrario, el flujo se detiene y se muestra un mensaje de error.
<img src="https://i.imgur.com/xMhtNnf.png" style="width:80%">

**Visualización de historial de transportes:** El flujo permite al usuario acceder a una vista que carga dinámicamente los registros de transporte desde la base de datos, con la opción de aplicar filtros para refinar los resultados; cada elemento del historial es interactuable para obtener detalles adicionales del transporte.
<img src="https://i.imgur.com/MdgpWkT.png" style="width:80%">

**Monitoreo real de transporte:** El flujo de monitoreo en tiempo real utiliza un mapa interactivo que actualiza constantemente la ubicación de los vehículos, integrando datos en vivo mediante APIs de geolocalización, y ofreciendo notificaciones en caso de eventos relevantes como desvíos o retrasos.
<img src="https://i.imgur.com/ZrJcw9H.png" style="width:80%">

#### 4.1.1.3 Bounded Context Canvases 

**Iniciar sesión:** El usuario accede al sistema ingresando sus credenciales en una interfaz simple que valida la autenticidad antes de redirigirlo al panel principal.
<img src="https://i.imgur.com/iagavZb.png" style="width:80%">


**Visualización de historial de transportes:** El usuario puede consultar una lista detallada de transportes previos, con opciones de filtrado y visualización de información específica de cada registro.
<img src="https://i.imgur.com/kiryIY9.png" style="width:80%">

**Monitoreo real de transporte:** El sistema muestra en tiempo real la ubicación y estado de los vehículos en un mapa interactivo, permitiendo supervisión y respuesta inmediata ante eventualidades.
<img src="https://i.imgur.com/vXip4Oq.png" style="width:80%">

### 4.1.2. Context Mapping

Este diagrama muestra la interacción entre los contextos delimitados IAM, Records y Management en Chemtrack. IAM y Management se conectan mediante un Shared Kernel, compartiendo lógica para autenticación y gestión de transporte. Records usa un ACL con Management e IAM para preservar la integridad de los datos y evitar contaminación. IAM actúa como Supplier para Records, proporcionando servicios de autenticación, mientras Records los consume para gestionar incidentes. Esto fomenta una arquitectura modular y cohesiva en el sistema.

<a href="https://ibb.co/wZts5VFt"><img src="https://i.ibb.co/sp7H8nd7/contextmapping.png" alt="contextmapping" border="0"></a>

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

En el diagrama se identifican dos usuarios principales: el Driver (Conductor) y el Manager (Gerente), quienes interactúan directamente con el sistema Chemtrack para gestionar el transporte y responder ante posibles riesgos. A su vez, el sistema Chemtrack utiliza un Alert System, un servicio de notificaciones, para enviar alertas y mantener informados a los usuarios ante cualquier evento relevante durante el proceso de transporte.

<a href="https://ibb.co/4Rz65xL1"><img src="https://i.ibb.co/DfhxSnFr/landscapecontext.png" alt="landscapecontext" border="0"></a>

#### 4.1.3.2. Software Architecture Context Level Diagrams

Este diagrama contextualiza cómo el sistema Chemtrack se integra en su entorno y qué actores externos (personas o sistemas) interactúan con él, resaltando el flujo de información crítica como el monitoreo, las alertas y la gestión de incidentes en situaciones de riesgo.

![image](https://github.com/user-attachments/assets/c2df48b0-dada-401d-aed2-dac8f42f14e2)


#### 4.1.3.2. Software Architecture Container Level 

El diagrama representa la arquitectura de software a nivel de contenedores del sistema de mitigación de riesgos de productos químicos reactivos. Incluye actores como Driver y Manager, que interactúan con componentes como Mobile App, Landing Page, Web Application, Edge Application, IoT Embedded App, Alert System, Web API, Edge Database y Web Database. Las conexiones muestran flujos de datos y notificaciones, como monitoreo, alertas de incidentes y consultas, integrando aplicaciones móviles, web y de borde con bases de datos para gestionar datos en tiempo real. Los bounded context están incluidos y son los de IAM, Management y Records.

![image](https://github.com/user-attachments/assets/a37540be-ea8e-4bc4-b4e4-a07c649fcce0)


#### 4.1.3.3. Software Architecture Deployment Diagrams

El diagrama de despliegue muestra la arquitectura de software del sistema Chemtrack para la mitigación de riesgos de productos químicos reactivos. Detalla los contenedores y nodos de despliegue: Landing Page (HTML/CSS, Github Pages), Web Application (Angular/Springboot, Netlify), Web API y Edge API Application (Springboot, Azure), Mobile App (Flutter, dispositivos móviles), IoT Embedded App (Python, dispositivos IoT), Web Database (MySQL, Azure) y Edge Database (MySQL, Azure). Las conexiones indican flujos de datos, como monitoreo, transferencia de datos IoT y lecturas/escrituras en bases de datos.

<a href="https://ibb.co/G4zcw7sy"><img src="https://i.ibb.co/8L163Mzq/deployment.png" alt="deployment" border="0"></a>

## 4.2. Tactical-Level Domain-Driven Design

Este apartado describe el diseño orientado a dominios a nivel táctico, un enfoque que estructura el software basado en los dominios del negocio. Se centra en modelos, entidades, objetos de valor y servicios que reflejan las necesidades y reglas del dominio, facilitando una implementación más alineada con los requisitos del sistema Chemtrack para la mitigación de riesgos de productos químicos reactivos.

### 4.2.1. Bounded Context: IAM

**Descripción:** Este contexto se encarga de controlar la autenticación, autorización y gestión de los roles asignados a los usuarios del sistema. Permite una administración centralizada de usuarios, abarcando su creación, actualización y eliminación, además de definir y aplicar las políticas de acceso a los distintos servicios y datos que ofrece la plataforma.

#### 4.2.1.1. Domain Layer

## Aggregate 1: Usuario
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Usuario</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Modela un usuario del sistema Chemtrack, gestionando su información de acceso, roles y certificaciones para garantizar una autenticación y autorización seguras.</td>
    </tr>
</table>

### Atributos de Usuario

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>Long</td>
        <td>Private</td>
        <td>Identificador único del usuario</td>
    </tr>
    <tr>
        <td>userName</td>
        <td>String</td>
        <td>Private</td>
        <td>Nombre de usuario</td>
    </tr>
     <tr>
        <td>email</td>
        <td>String</td>
        <td>Private</td>
        <td>Correo electrónico del usuario</td>
    </tr>
     <tr>
        <td>password</td>
        <td>String</td>
        <td>Private</td>
        <td>Contraseña del usuario</td>
    </tr>
     <tr>
        <td>role</td>
        <td>String</td>
        <td>Private</td>
        <td>Rol del usuario</td>
    </tr>
    <tr>
        <td>createdAt</td>
        <td>DateTime</td>
        <td>Private</td>
        <td>Fecha de creación de cuenta del usuario</td>
    </tr>
</table>

### Métodos de Usuario

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Construye una entidad User con los datos proporcionados</td>
    </tr>
    <tr>
        <td>authenticate</td>
        <td>Boolean</td>
        <td>Public</td>
        <td>Autentica al usuario basándose en su email y contraseña</td>
    </tr>
    <tr>
        <td>updateProfile</td>
        <td>Void</td>
        <td>Public</td>
        <td>Actualiza la dirección de correo electrónico del usuario</td>
    </tr>
     <tr>
        <td>assignRole</td>
        <td>Void</td>
        <td>Public</td>
        <td>Asigna un rol al usuario</td>
    </tr>
</table>

## Aggregate 2: Rol
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Rol</td>
        <td>Value Object</td>
        <td colspan="2">Especifica el rol de un usuario (DRIVER o MANAGER) dentro de Chemtrack, permitiendo la asignación de permisos y responsabilidades según su función.</td>
    </tr>
</table>

### Atributos de Rol

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>value</td>
        <td>String</td>
        <td>Private</td>
        <td>Enum value ("DRIVER" o "MANAGER")</td>
    </tr>
</table>

### Métodos de Rol

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Construye una entidad Rol con los datos proporcionados</td>
    </tr>
    <tr>
        <td>equals</td>
        <td>Boolean</td>
        <td>Public</td>
        <td>Compara con otro: Rol para igualar</td>
    </tr>
</table>

## Aggregate 3: Certificación
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Certificación</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Registra y gestiona las certificaciones asociadas a un usuario en Chemtrack, asegurando que cumplan con los requisitos de validez para operar en el sistema.</td>
    </tr>
</table>

### Atributos de Certificación

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>UUID</td>
        <td>Private</td>
        <td>Identificador único de la certificación</td>
    </tr>
    <tr>
        <td>certName</td>
        <td>String</td>
        <td>Private</td>
        <td>Nombre de la certificación</td>
    </tr>
     <tr>
        <td>issueDate</td>
        <td>Date</td>
        <td>Private</td>
        <td>Fecha de expedición de la certificación</td>
    </tr>
     <tr>
        <td>expirationDate</td>
        <td>Date</td>
        <td>Private</td>
        <td>Fecha de caducidad de la certificación</td>
    </tr>
</table>

### Métodos de Certificación

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Constructor de una certificación con información proveída</td>
    </tr>
</table>

## Aggregate 4: Permiso
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Permiso</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Establece los permisos específicos de un usuario en Chemtrack, controlando su acceso a funcionalidades y datos según su rol.</td>
    </tr>
</table>

### Atributos de Permiso

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>UUID</td>
        <td>Private</td>
        <td>Identificador único del permiso</td>
    </tr>
    <tr>
        <td>name</td>
        <td>String</td>
        <td>Private</td>
        <td>Nombre del permiso</td>
    </tr>
</table>

### Métodos de Certificación

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Constructor de un permiso con información proveída</td>
    </tr>
    <tr>
        <td>definePermission</td>
        <td>Void</td>
        <td>Public</td>
        <td>Define el nombre del permiso</td>
    </tr>
</table>

#### 4.2.1.2. Interface Layer

## Controller 1: AuthController
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>AuthController</td>
        <td>Controller</td>
        <td colspan="2">Maneja las solicitudes HTTP para autenticar usuarios y gestionar sus cuentas en Chemtrack, incluyendo inicio de sesión, registro y actualizaciones.</td>
    </tr>
</table>

### Atributos de AuthController

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>userService</td>
        <td>UserService</td>
        <td>Private</td>
        <td>Servicio para aplicar reglas de negocio y lógica de autenticación</td>
    </tr>
    <tr>
        <td>userMapper</td>
        <td>UserMapper</td>
        <td>Private</td>
        <td>Mapeador para transformar entidades de usuario en DTO y viceversa</td>
    </tr>
</table>

### Métodos de AuthController

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>authenticateUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Autentica un usuario usando credenciales y JWT</td>
    </tr>
    <tr>
        <td>registerUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Registra un nuevo usuario en el sistema</td>
    </tr>
    <tr>
        <td>getAllUsers</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Devuelve la lista de usuarios registrados</td>
    </tr>
     <tr>
        <td>updateUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Actualiza la información de un usuario existente</td>
    </tr>
    <tr>
        <td>deleteUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Elimina un usuario por ID</td>
    </tr>
</table>

#### Controller 2: PermissionController

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| PermissionController | Controller | Gestiona solicitudes HTTP para asignar y remover permisos de usuarios en Chemtrack, asegurando un control de acceso granular. |

**Atributos de PermissionController:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| permissionService | PermissionService | Private | Servicio para aplicar las reglas de negocio |

**Métodos de PermissionController:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| getAllPermissions | ResponseEntity | Public | Retorna la lista de todos los permisos |
| assignPermissionToUser | ResponseEntity | Public | Asigna el permiso para cada user |
| removePermissionFromUser | ResponseEntity | Public | Quita el permiso para cada user |

#### 4.2.1.3. Application Layer

## Service 1: UserService
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>UserService</td>
        <td>Service</td>
        <td colspan="2">Implementa la lógica de negocio para la gestión de usuarios en Chemtrack, incluyendo autenticación, registro y manejo de perfiles.</td>
    </tr>
</table>

### Atributos de UserService

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>userRepository</td>
        <td>UserRepository</td>
        <td>Private</td>
        <td>Repositorio para las operaciones CRUD de los usuarios</td>
    </tr>
    <tr>
        <td>passwordEncoder</td>
        <td>passwordEncoder</td>
        <td>Private</td>
        <td>Se utiliza para codificar las contraseñas de los usuarios</td>
    </tr>
    <tr>
        <td>jwtHandler</td>
        <td>JwtHandler</td>
        <td>Private</td>
        <td>Manejador para autenticación y autorización JWT</td>
    </tr>
</table>

### Métodos de UserService

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>authenticateUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Autentica un usuario usando credenciales y JWT</td>
    </tr>
    <tr>
        <td>registerUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Registra un nuevo usuario en el sistema y cifra la contraseña</td>
    </tr>
    <tr>
        <td>getAllUsers</td>
        <td>List</td>
        <td>Public</td>
        <td>Devuelve la lista de usuarios registrados</td>
    </tr>
     <tr>
        <td>updateUser</td>
        <td>User</td>
        <td>Public</td>
        <td>Actualiza la información de un usuario existente</td>
    </tr>
    <tr>
        <td>deleteUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Elimina un usuario por ID</td>
    </tr>
    <tr>
        <td>loadUserByUsername</td>
        <td>UserDetails</td>
        <td>Public</td>
        <td>Carga un usuario por nombre de usuario para la autenticación</td>
    </tr>
</table>

#### Service 2: PermissionService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| PermissionService | Service | Aplica la lógica de negocio para la gestión de permisos en Chemtrack, permitiendo asignar y revocar accesos a usuarios. |

**Atributos de PermissionService:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| permissionRepository | PermissionRepository | Private | Repositorio para operaciones CRUD de permisos|

**Métodos de PermissionService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| getAllPermissions | List<Permission> | Public | Devuelve la lista de todos los permisos |
| assignPermissionToUser | ResponseEntity | Public | Asigna un permiso al usuario |
| removePermissionFromUser | ResponseEntity | Public | Elimina el permiso de un usuario |

#### 4.2.1.4. Infrastructure Layer

#### Repository 1: UserRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| UserRepositoryImpl | Repository | Facilita las operaciones de persistencia de usuarios en Chemtrack, interactuando con la base de datos para operaciones CRUD. |

**Métodos de UserRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findById | User | Public | Recupera usuario de la base de datos por id |
| findByEmail | User | Public | Recupera el usuario de la base de datos por correo electrónico |
| save | Void | Public | Guarda usuario |
| existsByEmail | Boolean | Public | Verifica si el usuario existe por email |

#### Repository 2: PermissionRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| PermissionRepositoryImpl | Repository | Administra la persistencia de permisos en Chemtrack, permitiendo operaciones CRUD en la base de datos. |

**Métodos de PermissionRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findByName | Optional<Permission> | Public | Recupera el permiso de la base de datos por nombre |
| save | Permission | Public | Guarda el permiso en la base de datos |
| deleteById | Void | Public | Elimina el permiso en la base de datos por id|

### External Service

#### Service 1: EmailService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| EmailService | Service | Gestiona el envío de notificaciones y correos electrónicos a usuarios de Chemtrack a través de un servidor SMTP externo. |

**Métodos de EmailService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| sendEmail | Void | Public | Envía un correo electrónico al destinatario |

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

El IAM Bounded Context administra identidad y acceso para Drivers y Managers en Chemtrack. Componentes como AuthController, UserService y PermissionService manejan autenticación y permisos. EmailService, Certification y UserRepositoryImpl gestionan notificaciones y persistencia de usuarios. Se integra con un External Email System y una base de datos relacional para almacenamiento.

![image](https://github.com/user-attachments/assets/3178abf8-7494-4cde-8c7a-14583a51c3ef)


#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

A continuación se incluirán las secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram para el Bounded Context de IAM.

#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de la capa de dominio muestra el contexto delimitado de gestión de usuarios en Chemtrack. Incluye clases como UserAggregate, que contiene User y Certification, con métodos para agregar certificaciones y validar usuarios. AuthenticationService genera tokens y hashes de contraseñas, mientras UserRepository gestiona operaciones CRUD. La relación "has" con Role define roles como DRIVER y MANAGER, integrando permisos y autenticación.

![image](https://github.com/user-attachments/assets/7870fb53-32b9-449f-944c-dad16c11f427)


#### 4.2.1.6.2. Bounded Context Database Design Diagram

El diagrama de diseño de base de datos representa la estructura relacional del contexto delimitado IAM. La tabla User almacena id, role_id y password_hash, con una relación "tiene" hacia Certification. Role contiene name y se asocia con User_Role_Permission mediante asignado_a y tiene relaciones. Permission define name único, conectando con User_Role_Permission para gestionar accesos.

![image](https://github.com/user-attachments/assets/5be6bc52-8caf-4531-b0da-45991ff25087)


### 4.2.2. Bounded Context: Management

**Descripción:** Este módulo se ocupa de organizar y manejar todo lo relacionado con la generación, envío y monitoreo de notificaciones sobre incidentes o eventos importantes. Su objetivo es mantener informados en tiempo real a transportistas, operadores y supervisores, facilitando la transmisión oportuna de alertas y actualizaciones sobre el estado de dichos sucesos.

#### 4.2.2.1. Domain Layer

#### Entity 1: Transporte

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| Transporte | Entity | Modela y gestiona una operación de transporte químico en Chemtrack, incluyendo su estado, conductor asignado y datos de inicio. |

**Atributos de Transporte:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único del transporte |
| driverId | UUID | Private | ID del Conductor asignado |
| status | TransportStatus | Private | Estado del transporte (PENDIENTE, EN_PROCESO) |
| startTime | DateTime | Private |  Hora de inicio del transporte |

**Métodos de Transporte:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un Transporte con id|
| updateStatus | Void | Public | Actualiza el estado del transporte |
| assignDriver | Void | Public | Asigna un driverId |

#### Entity 2: SensorReading

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| SensorReading | Entity | Registra y gestiona las lecturas de sensores durante un transporte en Chemtrack, capturando datos como niveles de gas y temperatura. |

**Atributos de SensorReading:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único de la lectura |
| type | String | Private | Tipo de lectura del sensor |
| gasLevel | Float | Private | Medida del nivel de gas |
| temperature | Float | Private | Medida de temperatura |
| timestamp | DateTime | Private | Tiempo de la lectura |

**Métodos de SensorReading:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un SensorReading con ID |

#### Value Object 1: TransportStatus

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportStatus | Value Object | Define y categoriza los estados posibles de un transporte en Chemtrack, como PENDIENTE o EN_PROCESO, para seguimiento operativo. |

**Atributos de TransportStatus:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| value | String | Private | Valor Enum |

**Métodos de TransportStatus:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un TransportStatus con valor |
| equals | Boolean | Public | Compara con otros: TransportStatus para la igualdad |

#### 4.2.2.2. Interface Layer

#### Controller 1: TransportController

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportController | Controller | Procesa solicitudes HTTP para gestionar operaciones de transporte en Chemtrack, como inicio, actualización y consulta de estados. |

**Atributos de TransportController:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| transportService | TransportService | Private | Servicio para aplicar reglas de negocio de transporte |

**Métodos de TransportController:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| startTransport | ResponseEntity | Public | Inicializa transporte con transportId |
| updateStatus | ResponseEntity | Public | Actualiza el estado del transporte con transportId |
| getAllTransports | ResponseEntity | Public | Devuelve la lista de todos los transportes |

#### 4.2.2.3. Application Layer

#### Service 1: TransportService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportService | Service | Implementa la lógica de negocio para la gestión de operaciones de transporte en Chemtrack, coordinando inicios, actualizaciones y consultas. |

**Atributos de TransportService:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| transportRepository | TransportRepository | Private | Repositorio para operaciones CRUD de transporte |

**Métodos de TransportService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| startTransport | ResponseEntity | Public | Inicia el transporte con transportId |
| updateTransportStatus | ResponseEntity | Public | Actualiza el transporte con transportId |
| getAllTransports | List<Transport> | Public | Devuelve la lista de todos los transportes |

#### 4.2.2.4. Infrastructure Layer

#### Repository 1: TransportRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportRepositoryImpl | Repository | Administra la persistencia de datos de transporte en Chemtrack, permitiendo operaciones CRUD en la base de datos. |

**Métodos de TransportRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findById | Transport | Public | Recupera el transporte de la base de datos por id |
| save | Void | Public | Guarda el transporte a la base de datos |

### External Service

#### Service 1: IoTDeviceService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IoTDeviceService | Service | Obtiene y procesa datos de sensores de dispositivos IoT en Chemtrack para monitoreo en tiempo real durante el transporte. |

**Métodos de IoTDeviceService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| fetchSensorData | SensorData | Public | Recupera datos del dispositivo con deviceId |

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

El diagrama del Management Bounded Context muestra la gestión de transporte y monitoreo en Chemtrack. Incluye TransportController, TransportService e IoTDeviceService para procesar datos de sensores IoT. Transport y SensorReading envían notificaciones vía SMTP, mientras TransportRepositoryImpl persiste datos. Se integra con una base de datos y un IoT System para monitoreo en tiempo real.

![image](https://github.com/user-attachments/assets/8b6ee048-e773-49e0-9fb4-092c47885f70)


#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

A continuación se incluirán las secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram para el Bounded Context de Management.

#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Management Bounded Context modela transporte en Chemtrack. TransportAggregate contiene Transport y SensorReading, con métodos como addSensorReading y validateTransport.MonitoringService procesa datos de sensores y genera alertas, mientras TransportRepository gestiona persistencia.TransportStatus define estados como PENDING, IN_PROGRESS y COMPLETED, asignados a Transport.

![image](https://github.com/user-attachments/assets/7458ce29-30be-407f-a661-d9983f5c246d)


#### 4.2.2.6.2. Bounded Context Database Design Diagram

El esquema de base de datos del Management Bounded Context organiza datos de transporte. La tabla Transport almacena driver_id y status_id, vinculada a SensorReading por transport_id. TransportStatus define estados únicos, mientras SensorReading registra value y timestamp. Las claves primarias y foráneas aseguran relaciones entre transporte, sensores y estados.

![image](https://github.com/user-attachments/assets/5c8a4a18-9b40-46af-99be-d76661ef4c6f)


### 4.2.3. Bounded Context: Records

**Descripción:** Este contexto tiene como propósito coordinar y controlar los servicios vinculados al transporte y la carga. Incluye funciones como el monitoreo de recursos, la planificación de rutas y la actualización de información relacionada con los servicios activos. Asimismo, respalda la toma de decisiones operativas con base en el estado actual de las operaciones logísticas.

#### 4.2.3.1. Domain Layer

#### Entity 1: Incident

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| Incident | Entity | Representa y gestiona un incidente relacionado con un transporte en Chemtrack, capturando su tipo, tiempo y estado para seguimiento y resolución. |

**Atributos de Incident:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único de un incidente |
| transportId | UUID | Private | ID del transporte relacionado |
| type | IncidentType | Private | Tipo de incidente |
| timestamp | DateTime | Private | Timestamp del incidente |

**Métodos de Incident:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructs de un incidente con id |
| updateDetails | Void | Public | Actualiza los detalles de un incidente |
| resolve | Void | Public | Marca el incidente como resuelto |

#### Entity 2: CorrectiveAction

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| CorrectiveAction | Entity | Define y registra una acción correctiva asociada a un incidente en Chemtrack, incluyendo su descripción y estado de resolución. |

**Atributos de CorrectiveAction:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único de la acción |
| actionDescription | String | Private | Descripción de la acción. |
| timestamp | DateTime | Private | Timestamp de la acción |

**Métodos de CorrectiveAction:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Contructor de CorrectiveAction con id |

### Value Objects

#### Value Object 1: IncidentType

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentType | Value Object | Clasifica los tipos de incidentes en Chemtrack, como fugas de gas o anomalías de temperatura, para categorización y análisis. |

**Atributos de IncidentType:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| value | String | Private | Valor enum |

**Métodos de IncidentType:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un IncidentType |
| equals | Boolean | Public | Compara con otro: IncidentType para igualdad |

#### 4.2.3.2. Interface Layer

#### Controller 1: IncidentController

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentController | Procesa solicitudes HTTP para gestionar incidentes en Chemtrack, incluyendo reportes, resoluciones y consultas de incidentes. |

**Atributos de IncidentController:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| incidentService | IncidentService | Private | Servicio de aplicación de reglas de negocio de incidencias |

**Métodos de IncidentController:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| reportIncident | ResponseEntity | Public | Informa de un nuevo incidente con incidentData |
| resolveIncident | ResponseEntity | Public | Resuelve el incidente con incidentId |
| getAllIncidents | ResponseEntity | Public | Devuelve la lista de todos los incidentes |

#### 4.2.3.3. Application Layer

#### Service 1: IncidentService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentService | Service | Aplica la lógica de negocio para la gestión de incidentes en Chemtrack, incluyendo reportes, resoluciones y recuperación de datos históricos. |

**Atributos de IncidentService:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| incidentRepository | IncidentRepository | Private | Repositorio para operaciones CRUD de incidentes |

**Métodos de IncidentService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| reportIncident | ResponseEntity | Public | Informa de un nuevo incidente con incidentData |
| resolveIncident | ResponseEntity | Public | Resuelve el incidente con incidentId |
| getAllIncidents | List<Incident> | Public | Devuelve la lista de todos los incidentes |

#### 4.2.3.4. Infrastructure Layer

#### Repository 1: IncidentRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentRepositoryImpl | Repository | Gestiona la persistencia de incidentes en Chemtrack, permitiendo operaciones CRUD en la base de datos para datos históricos. |

**Métodos de IncidentRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findById | Incident | Public | Recupera el incidente de la base de datos por id |
| save | Void | Public | Guarda el incidente: Incidente en la base de datos |

### External Service

#### Service 1: NotificationService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| NotificationService | Service | Gestiona el envío de notificaciones de incidentes en Chemtrack a sistemas externos, asegurando alertas en tiempo real. |

**Métodos de NotificationService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| sendNotification | Void | Public | Envía notificación al destinatario |

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

El Records Bounded Context gestiona incidentes y reportes históricos en Chemtrack. Incluye IncidentController, IncidentService y NotificationService para manejar reportes y alertas. Corrective Action envía acciones correctivas vía SMTP, mientras IncidentRepositoryImpl persiste datos. Se integra con un Alert System y una base de datos relacional para almacenamiento.

![image](https://github.com/user-attachments/assets/11cc8bdf-878c-432a-ac20-36c2bfb03060)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

A continuación se incluirán las secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram para el Bounded Context de Records.

#### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Records Bounded Context modela incidentes en Chemtrack. IncidentAggregate contiene Incident y CorrectiveAction, con métodos como addAction y validateIncident. ReportingService genera reportes, mientras IncidentRepository gestiona persistencia de incidentes. IncidentType define tipos como GAS_LEAK y TEMPERATURE_ANOMALY, asociados a Incident.

![image](https://github.com/user-attachments/assets/db74f044-9b00-48a5-87dc-6095170426bb)


#### 4.2.3.6.2. Bounded Context Database Design Diagram

El esquema de base de datos del Records Bounded Context organiza datos de incidentes. La tabla Incident almacena transport_id y type_id, vinculada a CorrectiveAction por incident_id. IncidentType define tipos únicos, mientras CorrectiveAction registra action_description y completed_date. Las claves primarias y foráneas aseguran relaciones entre incidentes, tipos y acciones.

![image](https://github.com/user-attachments/assets/db160ad5-988c-49e9-aa79-d3a18edcde06)


# Capítulo V: Solution UX Design
## 5.1 Style Guidelines

Mediante la solución IoT Chemtrack busca ofrecer a sus usuarios una interfaz que transmita profesionalismo, formalidad y un diseño minimalista que inspire confianza y facilidad de uso al momento de monitorear la carga, así como brindar una respuesta ágil ante posibles emergencias. Por ello, el equipo optó por utilizar elementos visuales que atraigan la atención del público objetivo y que, a la vez, sean de fácil reconocimiento. Como parte de la estrategia, se seleccionaron colores llamativos y contrastantes, junto con tipografías de distintos tamaños y espaciados amplios, con el fin de brindar una experiencia visual agradable y garantizar una lectura clara. Es importante resaltar que no se emplearán texturas, ya que se busca preservar una estética limpia y minimalista.

**Brand Overview**

Chemtrack surge como respuesta a la necesidad de optimizar la seguridad en el transporte de sustancias peligrosas, así como elevar los estándares de servicio en las empresas dedicadas a esta labor. Para lograrlo, se plantea una solución integral basada en tecnologías IoT que permiten el monitoreo en tiempo real de la carga de combustible, entre otras funcionalidades orientadas a satisfacer estas demandas.

El concepto de marca se refuerza a través de un mensaje directo y poderoso: proteger el flujo logístico en entornos críticos, asegurando tanto la eficiencia operativa como la seguridad en cada etapa del transporte. Esto no solo mejora la reputación de las empresas que adoptan Chemtrack, sino que también genera confianza entre todos los involucrados. En definitiva, Chemtrack representa una promesa de fiabilidad en un sector donde la seguridad y la eficiencia son fundamentales.

**Brand Name**

El nombre Chemtrack condensa de manera clara la misión principal de la solución IoT: garantizar un transporte seguro de materiales peligrosos. La fusión conceptual entre "Chemical" y "Track" comunica de inmediato dos pilares esenciales: la vigilancia constante del trayecto y el compromiso con altos estándares de seguridad.

Esta denominación no solo refleja el enfoque en la protección, sino que también transmite eficiencia, control y confiabilidad para empresas y transportistas. Así, Chemtrack se posiciona como un sinónimo de resguardo tanto para quienes manipulan estas cargas como para el entorno en el que operan, transmitiendo tranquilidad a los operadores y a los clientes finales por igual.

![image](https://github.com/user-attachments/assets/6c59f1b3-31a8-449c-946d-72f20d8edca5)


**Colores**:

**Colores de la marca:** Estos colores representan la identidad visual de Chemtrack. El Primario / #67F43 es un verde vibrante que simboliza crecimiento, seguridad y energía, usado en elementos clave para destacar la marca. El Secundario / #086D36, un verde oscuro profundo, complementa al primario aportando contraste y profesionalidad, ideal para fondos o acentos secundarios.

![image](https://github.com/user-attachments/assets/dbde0ec8-3785-4815-a979-1f7019a8209f)

**Colores de estado:** Utilizados para comunicar diferentes estados en la interfaz. Info / #909EC4 es un azul-gris suave para mensajes informativos, transmitiendo calma. Success / #B4F0F0, un verde claro, indica acciones exitosas, generando confianza. Warning / #F3CB52, un amarillo cálido, alerta sobre situaciones de precaución. Error / #DF333C, un rojo intenso, resalta errores o problemas críticos para acción inmediata.

![image](https://github.com/user-attachments/assets/ef0f079a-175c-42d3-b9d5-15a49c2fd59e)

**Colores negros:** Diseñados para contraste y legibilidad. Black 1 / #000000 es un negro puro para textos o fondos de alta visibilidad. Black 2 / #1D1D1D, un negro más suave, se usa en fondos o bordes sutiles. Black 3 / #282828, un tono intermedio, equilibra elementos secundarios. White / #FFFFFF, un blanco puro, ofrece claridad y modernidad en fondos o resaltados.

![image](https://github.com/user-attachments/assets/884260e4-02cd-4d98-aa74-716989d466e7)

**Colores grises:** Aportan neutralidad y estructura. Gray 1 / #333333, un gris oscuro, es ideal para textos o acentos sofisticados. Gray 2 / #4F4F4F, un gris medio, se usa en textos secundarios. Gray 3 / #828282, un gris más claro, sirve para divisores o resaltados sutiles. Gray 4 / #BDBDBD, un gris suave, y Gray 5 / #E0E0E0, un gris muy claro, se emplean en fondos o estados inactivos para mantener una interfaz limpia.

![image](https://github.com/user-attachments/assets/ca2e7567-a1c6-489d-9ee1-66be386ecafa)


**Tipografia:**

El equipo seleccionó la fuente de letra Montserrat, un estilo tradicional y fácil de leer. La separación del interletraje es de 0,15 px, el interlineado es de 0,5 px y el tamaño de la fuente varía dependiendo de la finalidad de uso, por ejemplo, para los títulos se opta por un tamaño de 56 px, y para el texto redactado por el usuario 20 px. 

![image](https://github.com/user-attachments/assets/3cc9bde1-e4ef-4da1-9f0b-c6ae23a7ae30)

![image](https://github.com/user-attachments/assets/84e79341-333b-4c01-89df-b2ddd5fd1274)


**Iconografía:**

La sección de Iconografía establece reglas claras para el uso de íconos en el diseño. Define un área activa de 20 px para interacción, un área segura de 2 px para evitar solapamientos y un tamaño total de 24 px por ícono. Además, presenta dos conjuntos de íconos: "Outline Icons" con estilo de contorno y "Fill Icons" en estilo relleno, ambos incluyendo símbolos como relojes, lápices y marcadores.

![image](https://github.com/user-attachments/assets/df7edf25-94d2-49d9-8428-4d3a1ef68d25)

**Sistema Grid:**

Los Sistemas de Grid definen configuraciones para distintos dispositivos, asegurando un diseño adaptable. Para Desktop HD, el frame es de 1440 px con 12 columnas de 90 px; para Desktop, 1024 px con 6 columnas de 50 px; para Tablet, 768 px con 6 columnas de 88 px; y para Mobile, 320 px con 2 columnas de 130 px, garantizando alineación y proporción en cada formato.

![image](https://github.com/user-attachments/assets/a0a301a2-a0c7-4ac6-b560-48bd34fc48c3)

**Espaciado:**

El apartado de Espaciado proporciona una escala de valores para mantener consistencia en el diseño. Los niveles van desde 8 px hasta 120 px, incluyendo medidas intermedias como 16 px, 24 px, 32 px, 40 px, 56 px, 72 px, 80 px y 96 px. Estos valores, representados con cuadros grises de tamaño creciente, se aplican a márgenes, padding y otros elementos de diseño.

![image](https://github.com/user-attachments/assets/dad1029a-0d31-444a-aefc-41bae5e2c7dd)

### 5.1.2 Web, Mobile and IoT Style Guidelines

Estándares de Interfaz para Dispositivos Web, Móviles e IoT
Esta sección describe los lineamientos visuales y de interacción que debe seguir la interfaz de Chemtrack en cada una de sus plataformas: web, aplicación móvil y dispositivos IoT. La experiencia del usuario debe mantenerse coherente y fluida, adaptando los elementos visuales y funcionales al tipo de dispositivo para lograr una interacción efectiva y accesible.

### Web Responsive Design

La interfaz web de Chemtrack ha sido diseñada bajo principios de diseño responsive, lo que permite su correcta visualización desde pantallas grandes (escritorio) hasta dispositivos móviles. Se emplea un enfoque de Flat Design, que favorece una navegación clara, intuitiva y moderna. Además, se sigue el patrón Z como guía de distribución visual, asegurando que los elementos clave (logo, menú, CTA) estén posicionados estratégicamente.

**Componentes principales:**

Dashboard: Estructura central con una barra lateral de navegación (menú principal) y una barra superior para acceso rápido al perfil, notificaciones y ajustes.

**Lineamientos técnicos:**
- Grid System: Se adopta un sistema de 12 columnas para organizar los elementos de forma flexible.

- Breakpoints:
    - Móviles: 320px – 480px
    - Tablets: 481px – 768px
    - Escritorio: 769px en adelante

- Tipografía: Escalable con un mínimo de 16px en móviles para garantizar la legibilidad.

- Colores: Paleta uniforme con variaciones para estados interactivos (hover, focus, active).

- Botones y links: Tamaño mínimo de 44px de altura para facilitar la interacción táctil.

- Iconografía: Se emplean íconos universales y reconocibles que apoyan la navegación.

### Mobile Application Interface

La interfaz de la aplicación móvil está diseñada para priorizar la usabilidad táctil, manteniendo una estructura sencilla, clara y centrada en la acción. Se utiliza un diseño de columna única, ideal para mostrar contenido de forma lineal, y se implementan componentes adaptados a pantallas pequeñas.

**Componentes principales:**
- Navegación inferior (Bottom Navigation): Acceso directo a secciones clave como Dashboard, Dispositivos, Riego, Análisis de Suelo y Reportes.

- Floating Action Button (FAB): Acceso inmediato a la acción principal desde cada vista, ubicado en la esquina inferior derecha.

- Overlays: Capas superpuestas para mostrar detalles sin abandonar la pantalla actual.

**Lineamientos técnicos:**

- Botones táctiles: Tamaño mínimo de 48x48px, con retroalimentación visual inmediata (por ejemplo, cambio de color al presionar).

- Tipografía: Mínimo de 16px para asegurar buena lectura en todo tipo de dispositivos móviles.

- Gestos y navegación fluida: Compatibilidad con gestos nativos para mejorar la experiencia.

### IoT Application Interface
En el caso de la interfaz para la solución embebida IoT, se prioriza la visualización clara de datos operativos en tiempo real y el control rápido de los dispositivos. Aunque no se contempla un diseño de interfaz complejo, se establecen elementos clave para garantizar una experiencia funcional y eficiente.

**Componentes principales:**
- Widgets visuales: Gráficos de barras, líneas y medidores que permiten interpretar de forma inmediata el estado de los dispositivos.

- Alertas: Notificaciones visuales con codificación por colores:

    - Crítico: Rojo (#FF4B4B)

    - Normal/operativo: Verde (#6BBE44)

- Controles simples: Interruptores, sliders y botones grandes que permitan ejecutar acciones directas sin confusión.

**Lineamientos técnicos:**
- Compatibilidad con pantallas pequeñas (embedded): Interfaces compactas, con mínima carga visual.

- Accesibilidad: Íconos y textos suficientemente grandes para ser visibles de un vistazo.


## 5.2 Arquitectura de la Información

Esta sección detalla cómo está organizada la solución IoT, considerando a cada grupo de usuarios. Asimismo, se describe la estructura de navegación implementada en las distintas interfaces del sistema.

### 5.2.1 Sistemas de Organización

Se presentan los tipos de agrupación de información y cómo estos se adaptan a cada grupo objetivo a través de esquemas visuales.

**Grupo objetivo: Conductores de transporte de sustancias peligrosas**

- **Estructura Jerárquica**  
  El conductor tendrá acceso a información de seguridad (como sensores de gas, presión o temperatura) presentada por niveles de prioridad, desde los más críticos hasta los más informativos.

- **Estructura Secuencial**  
  El proceso de respuesta ante alertas seguirá una secuencia lógica: notificación, validación de la amenaza, y ejecución de medidas como activar protocolos de emergencia.

- **Estructura Matricial**  
  El historial de eventos del vehículo se mostrará en formato de tabla cruzada, permitiendo filtrar por fecha, tipo de incidente o gravedad, facilitando así el análisis.

**Grupo objetivo: Empresas de transporte de sustancias peligrosas**

- **Estructura Jerárquica**  
  Las empresas podrán visualizar y priorizar la seguridad de sus flotas mediante una vista estructurada, desde el panorama general hasta el detalle por unidad.

- **Estructura Secuencial**  
  El análisis y mejora de protocolos se realizará paso a paso, apoyado por datos históricos que ayuden a detectar fallas y aplicar mejoras.

**Elementos comunes para ambos grupos**

- **Estructura Jerárquica**  
  En la página principal, la información estará dividida en bloques que van desde una introducción general del sistema hasta especificaciones técnicas.

- **Estructura Matricial**  
  El menú principal ofrecerá diversas funcionalidades (monitoreo, alertas, registros), disponibles sin un orden rígido pero organizadas para facilitar su acceso.

---

### 5.2.2 Sistemas de Etiquetado

Aquí se describen los nombres y etiquetas empleados para identificar y organizar la información de manera clara.

**Landing Page**

- **Inicio / Home**  
  Vista inicial con una frase que representa la solución, logo y objetivo principal.

- **Sobre Nosotros / About Us**  
  Detalles del equipo, su misión, visión y propósito.

- **Servicios / Services**  
  Funcionalidades clasificadas según el grupo de usuarios (conductores o empresas).

- **Contáctanos / Contact Us**  
  Canales de comunicación y soporte disponibles.

**Etiquetas específicas para Conductores**

- **Inicio / Home**  
  Panel de control para conductores.

- **Mis viajes**  
  Gestión de rutas activas y programadas.

- **Registro de incidentes**  
  Formulario para reportar problemas surgidos durante el trayecto.

- **Historial**  
  Registro de viajes pasados e incidentes resueltos.

**Etiquetas específicas para Empresas**

- **Inicio / Home**  
  Vista general para monitoreo empresarial.

- **Incidentes publicados**  
  Gestión de reportes generados por los conductores.

- **Reportes**  
  Generación y análisis de datos sobre seguridad y desempeño.

- **Monitoreo de viajes**  
  Supervisión en tiempo real del estado de la flota.

---

### 5.2.3 Etiquetas SEO y Meta Tags

Estas etiquetas permiten mejorar la visibilidad del sitio y diferenciar la plataforma en los motores de búsqueda.

**Para la página web principal:**

- **Title**: TrackTox
- **Description**: TrackTox - Página oficial de Chemtrack
- **Keywords**: transporte peligroso, monitoreo, gestión de incidentes, seguridad vial  
- **Authors**: Equipo Chemtrack

**Para la aplicación web:**

- **Title**: TrackTox
- **Description**: TrackTox - Plataforma Web Oficial  
- **Keywords**: transporte seguro, flotas, monitoreo, gestión de emergencias  
- **Authors**: Chemtrack

**Para la app móvil:**

- **Title**: TrackTox
- **Description**: TrackTox - Aplicación Móvil Oficial  
- **Keywords**: seguridad de transporte, monitoreo móvil, gestión de incidentes  
- **Authors**: Chemtrack

---

### 5.2.4 Sistemas de Búsqueda

Se explican las opciones de búsqueda disponibles en cada plataforma del sistema.

**En la página web principal**  
Los usuarios podrán navegar fácilmente entre las secciones mediante una barra interactiva que alterna entre contenido para conductores y para empresas.

**Aplicación web y móvil**

- **Conductores**  
  - *Mis viajes*: Búsqueda por destino, fecha o estado.  
  - *Registro de incidentes*: Filtro por tipo, gravedad o fecha del evento.

- **Empresas**  
  - *Monitoreo de viajes*: Filtrado por unidad, conductor, fecha o estado del trayecto.  
  - *Incidentes publicados*: Filtro por tipo, estado (resuelto o pendiente), y fecha.

**Funcionalidades compartidas**  
- *Reportes y análisis*: Los usuarios podrán generar informes personalizados a partir de filtros como tipo de incidente, fechas o métricas de monitoreo.

---

### 5.2.5 Sistemas de Navegación

La navegación ha sido diseñada para facilitar el acceso a la información en todas las plataformas.

**Landing Page**  
Contará con un menú horizontal fijo en la parte superior con enlaces a cada sección. El usuario podrá hacer clic en cada encabezado y desplazarse automáticamente a la información deseada.

**Aplicación Web**  
El menú principal estará adaptado al tipo de usuario y permitirá navegar entre páginas como viajes, incidentes o reportes, usando también filtros internos para una mejor experiencia.

**Aplicación Móvil**  
La navegación se optimiza mediante carruseles en la pantalla de inicio y una barra de navegación inferior (bottom navigation bar) con accesos rápidos a secciones clave como "Mis viajes", "Alertas" o "Reportes", con opciones diferenciadas según el tipo de usuario.


## 5.3. Landing Page UI Design
Durante el diseño de la interfaz de la página de inicio (landing page), uno de los pasos más importantes al comienzo es crear un "wireframe". Este es como un boceto básico que muestra la estructura y distribución de los elementos principales que tendrá la página. En este caso, se incluyen secciones como la barra de navegación (dentro del área principal), el encabezado (Hero), los servicios, información sobre la empresa, testimonios, la opción de descarga y el pie de página.

### 5.3.1. Landing Page Wireframe

Hero:

![image](https://github.com/user-attachments/assets/8995e159-15f6-4bf4-9a9f-2cbe0e68860d)

Services:

![image](https://github.com/user-attachments/assets/c7ce2413-f6b9-4359-804d-d6f6d48ea7a9)

About us:

![image](https://github.com/user-attachments/assets/a2140cd0-fa6d-46d0-bd69-046f8b9668b4)

Testimonials:

![image](https://github.com/user-attachments/assets/9cc4d581-7022-4e76-8dfd-df58706562cc)

Download:

![image](https://github.com/user-attachments/assets/88aad065-1a17-4217-b814-b2ebb3b36da3)

Footer:

![image](https://github.com/user-attachments/assets/4c0265b9-db50-401e-97cf-a08bf8dd5114)

### 5.3.2. Landing Page Mock-up

Hero:

![image](https://github.com/user-attachments/assets/89f42efd-c555-426c-ab67-a89d68fd4d36)

Services:

![image](https://github.com/user-attachments/assets/1185c8ba-d63f-4267-a5ac-f3b655a710b7)

About us:

![image](https://github.com/user-attachments/assets/e7d26a9d-8e06-43af-999f-1381fc0ded28)

Testimonials:

![image](https://github.com/user-attachments/assets/16b6e8ac-4b0f-4f8d-bd81-f81e532be8d4)

Download:

![image](https://github.com/user-attachments/assets/6cbbe3c0-e59f-4e4e-b9fd-054db6526844)

Footer:

![image](https://github.com/user-attachments/assets/12ee1743-0d86-43fa-8d52-ba26b9a8f389)

## 5.4 Applications UI/UX Design
Esta sección incluye secciones internas donde presentamos la propuesta visual y de interacción para nuestras web y mobile application, considerando la experiencia de usuario con los productos.

### 5.4.1 Applications Wireframes
En esta sección se pueden encontrar los wireframes relacionados a nuestra aplicación web y móvil Chemtack.

**Wireframes Web Application:**

![Wireframes Web App](https://i.imgur.com/CswDZjd.png)

**Wireframes Web Application Responsive:**
![Wireframes Web App Responsive](https://i.imgur.com/dV2z3Vz.png)

**Wireframes Mobile:**

![Wireframes Mobile App](https://github.com/user-attachments/assets/1d66d831-2319-4cc4-9eb5-27a1d815defa)

[Enlace para acceder al Figma.](https://www.figma.com/design/c7g8w481pDMJGjvVyiU6F1/Chemtrack?node-id=87-44&t=Nj0ZnQTSve38LPvz-1 "Enlace para acceder al Figma.")


### 5.4.2 Applications Wireflow Diagrams
En esta sección, se presentan los Wireflows, donde se mostrarán las rutas que los usuarios pueden tener al momento de usar la aplicación web y móvil. Para su realización se utilizó la herramienta LucidChart.

**Wireflow Diagrams Web Application:**

**User goal, usuario inicia sesion y se registra**

**Descripción:**
Al iniciar la aplicación, el usuario se encuentra en la página de opciones, donde puede iniciar sesión. Si el usuario no posee una cuenta puede registrar una nueva utilizando su correo electrónico.

![Wireflow Web Application 1](https://i.imgur.com/3NlrAHP.jpeg)

**User goal, usuario transportista ve servicios disponibles**

**Descripción:**
Cuando el transportista haya terminado de completar su perfil y este interesado en aceptar una entrega ingresa a la opción "Publication", envía su solicitud al servicio de su interés y si es aceptado en alguna podrá proceder a visualizar las notificaciones y la opción de rutas.

![Wireflow Web Application 2)](https://i.imgur.com/QsE9k1q.jpeg)

**User goal, usuario administrador publica servicios**

**Descripción:**
Una vez que el administrador haya terminado de completar su perfil se le mostrará un formulario para publicar un servicio y si es aceptado por algún transportista podrá visualizar la opción de "Solicitation".

![Wireflow Web Application 3)](https://i.imgur.com/QP2utY2.jpeg)

**User goal, usuario administrador visualiza perfil de transportista**

**Descripción:**
El administrador podrá ver todas las solicitudes de transportistas a su publicación de servicio desde la opción "Solicitation" y desde dicha vista podrá decidir si aceptarlos o visualizar previamente su perfil donde si incluye los datos de su CV.

![Wireflow Web Application 4)](https://i.imgur.com/qUWePu3.jpeg)

---

**Wireflow Diagrams Mobile Application:**
**User goal, usuario inicia sesion y se registra**

**Descripción:**
Al iniciar la aplicación, el usuario se encuentra en la página de opciones, donde puede iniciar sesión. Si el usuario no posee una cuenta puede registrar una nueva utilizando su correo electrónico.

![Wireflow Mobile Application 1](https://i.imgur.com/QvX5QtC.jpeg)

**User goal, usuario transportista acepta servicio e inicia recorrido**

**Descripción:**
Cuando el transportista haya aceptado el servicio y comience con la ruta presiona en la app la opción de iniciar recorrido, donde le figurará detalles acerca del recorrido y la carga a transportar y parámetros brindados por los sensores.

![Wireflow Mobile Application 2](https://i.imgur.com/FojRu3F.jpeg)

**User goal, usuario transportista reporta incidente**

**Descripción:**
El usuario puede reportar incidentes que hayan ocurrido durante el recorrido para que de ese modo el administrador permanezca atento de ello.

![Wireflow Mobile Application 3](https://i.imgur.com/GqzxViA.jpeg)

**User goal, usuario administrador añade nueva ruta a monitorear**

**Descripción:**
Desde la app el admnistrador tiene la opción de poder añadir nuevos servicios a monitorear para que así pueda ir monitoreando remotamente como se encuentran los parámetros de los sensores.

![Wireflow Mobile Application 4](https://i.imgur.com/rrNCCir.jpeg)

**User goal, usuario administrador visualiza reportes de incidentes**

**Descripción:**
El usuario administrador puede visualizar los reportes de incidentes brindados por los transportistas al igual de los parámetros de monitoreo que dejaron los sensores en dicho momento.
![Wireflow Mobile Application 5](https://i.imgur.com/HaLPhcx.jpeg)

[Enlace para acceder a LucidChart.](https://lucid.app/lucidchart/78d14ebd-5614-4c11-be07-705631141f25/edit?viewport_loc=-3238%2C-2725%2C14392%2C6984%2Cz.Le~yULM6Za&invitationId=inv_efb1a0e4-2462-43d2-805c-6c06dbb66383 "Enlace para acceder a LucidChart.")


### 5.4.3 Applications Mock-ups
En esta sección se pueden encontrar los Mock-ups relacionados a nuestra aplicación web y móvil Chemtrack.

**Web Application Mock-up**

![Mock-up Web Application](https://i.imgur.com/yqDNN8S.png)

**Web Application Responsive Mock-up**
![Mock-up Web Application Responsive](https://i.imgur.com/etnXnd4.png)


**Mobile Application Mock-ups:**

![Mock-up Mobile Application](https://i.imgur.com/B0GUcoa.png)

[Enlace para acceder al Figma.](https://www.figma.com/design/c7g8w481pDMJGjvVyiU6F1/Chemtrack?node-id=87-45&t=Nj0ZnQTSve38LPvz-1 "Enlace para acceder al Figma.")


### 5.4.4 Applications User Flow Diagrams

En esta sección, se presentan los User Flows, donde se mostrarán las Happy y Unhappy paths que los usuarios pueden tener al momento de usar la aplicación web y móvil. Para su realización se utilizó la herramienta LucidChart.

**User Flow Diagrams Web Application:**
**User goal, usuario inicia sesion y se registra**

**Task Flow:**

- Primero el usuario debe estar en la pantalla Sign In
- Luego, si quiere crear un nuevo usuario va a la pantalla Sign Up donde puede elegir entre ser transportista o administrador
- Dependendiendo de su tipo de cuenta se le redirige a la sección Home correspondiente

![User Flow Web Application 1](https://i.imgur.com/GN4AKVH.jpeg)


**User goal, usuario transportista ve servicios disponibles**

**Task Flow:**

- Si el transportista está interesado en aceptar una entrega
- Entra a la sección de "Solicitation"
- Y se visualiza los servicios
  
![image](https://i.imgur.com/7wLkgEV.jpeg)


**User goal, usuario administrador publica servicios**

**Task Flow:**

- Si el usuario autenticado como administrador se encuentra en la sección
- Entonces se le muestra un formulario para publicar un servicio
- Si es aceptado, entonces es mostrado en la interfaz de los transportistas
  
![image](https://i.imgur.com/AcVcOS4.jpeg)


**User goal, usuario administrador visualiza perfil de transportista**

**Task Flow:**

- Si el administrador desea verificar el perfil del transporista
- Al aceptar un envío, el administrador puede ver el perfil
- Si es así, entonces se le muestra el perfil a detalle

![image](https://i.imgur.com/NhsskSA.jpeg)

---

**User Flow Diagrams Mobile Application:**

**User goal, usuario inicia sesion y se registra**

**Task Flow:**

- Primero el usuario debe estar en la pantalla Sign In
- Luego, si quiere crear un nuevo usuario va a la pantalla Sign Up donde puede elegir entre ser transportista o administrador
- Dependendiendo de su tipo de cuenta se le redirige a la sección Home correspondiente

![image](https://i.imgur.com/6Yz3Npo.jpeg)

**User goal, usuario transportista acepta servicio e inicia recorrido**

**Task Flow:**

- Si el transportista ha aceptado un servicio
- Entonces podrá ingresar a la sección "Monitoring" para iniciar el recorrido
- Si selecciona una ruta, se le muestran los detalles del viaje y de la carga
- Si desea añadir una nueva ruta, se le muestra un formulario para completarla
- Al iniciar el recorrido, se muestran los datos de monitoreo en tiempo real
- Entonces puede seguir la ruta y finalizar la entrega desde la interfaz

![image](https://i.imgur.com/SsocVaB.jpeg)

**User goal, usuario transportista reporta incidente**

**Task Flow:**

- Si el transportista se encuentra realizando un recorrido
- Entonces puede acceder a la sección "Incidents" desde el menú
- Si decide registrar un nuevo incidente, se le muestra un formulario
- Al completar los campos requeridos, puede enviar el reporte
- Entonces el incidente queda registrado y visible para el administrador

![image](https://i.imgur.com/7bxJw1e.jpeg)

**User goal, usuario administrador añade nueva ruta a monitorear**

**Task Flow:**

- Si el administrador accede a la sección "Monitoring"
- Entonces puede seleccionar la opción para añadir una nueva ruta
- Si decide continuar, se le muestra un formulario para completar los datos
- Al guardar la información, la nueva ruta queda registrada
- Entonces podrá monitorear los parámetros de los sensores en esa ruta

![image](https://i.imgur.com/7BzRtg9.jpeg)

**User goal, usuario administrador visualiza reportes de incidentes**

**Task Flow:**

- Si el administrador accede a la sección "Incidents"
- Entonces se le muestra la lista de reportes enviados por los transportistas
- Si selecciona un reporte, se visualiza el detalle del incidente
- Entonces también se muestran los parámetros de monitoreo asociados al evento

![image](https://i.imgur.com/aFCOnRN.jpeg)



[Enlace para acceder a LucidChart](https://lucid.app/lucidchart/78d14ebd-5614-4c11-be07-705631141f25/edit?viewport_loc=-7647%2C-2992%2C14024%2C6805%2C0_0&invitationId=inv_efb1a0e4-2462-43d2-805c-6c06dbb66383 "Enlace para acceder a LucidChart"). 

## 5.5 Applications Prototyping

En esta sección, se puede acceder al prototipo en la herramienta Figma. Asismismo se pueden evidenciar los principios de arquitectura de información, esto hace que la aplicación se vea lo más eficiente posible.

Principio de elección: Procuramos que las aplicaciones web y móvil posean una cantidad de secciones a todo momento, por lo que en ambas se cuenta con la barra superior siempre con 4 secciones, las cuales podrán acceder a las funcionalidades rapidamente desde cualquier pantalla.

Principio de divulgación: La información presentada se separa por partes, de tal manera que el usuario encuentre lo que desee. 

Video de presentación del prototipo:

**Prototipo Web Application**
Timing: 0:00
Duración: 03:31

![image](https://i.imgur.com/bMplMmA.png)

**Prototipo Mobile Application**
Timing: 03:32
Duración: 03:51

![image](https://i.imgur.com/H1gB1R8.png)

[Link al video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114248_upc_edu_pe/Eb7QckaAXOZHqCAdbBh9b1cB-LXKRizGLBlfKQjgbgPFjQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=60MG8p "Link al video").

# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
  
Se utilizarán principalmente los editores Visual Studio Code y WebStorm, configurados para evitar conflictos con carpetas personalizadas. Para el desarrollo de Web APIs, se optará por IntelliJ IDEA.

El stack tecnológico incluye la última versión de Node.js, Angular v13 para el frontend, y Angular Material como biblioteca de diseño. Java será el lenguaje usado para el backend. Angular se instalará con `nvm` en su versión compatible con Windows.

Para el desarrollo móvil, se usará Visual Studio con un emulador y el SDK actualizado de Flutter, lo que brinda soporte para extensiones y una experiencia completa de desarrollo.

### Herramientas SaaS y de apoyo:

- **GitHub**: Control de versiones y trabajo colaborativo.
- **Trello**: Planificación y seguimiento del Product Backlog.
- **Vertabelo**: Modelado de bases de datos.
- **Codegram**: Creación de diagramas de clases.
- **LucidChart**: Diagramación adicional.

### Desarrollo Embedded:

- **Wokwi**: Simulador de proyectos IoT usando C++.

### Landing Page:

Se desarrollará usando HTML, JavaScript y CSS, apoyándose en:

- **VS Code**: Por su versatilidad y extensión de soporte.
- **Git/GitHub**: Estándares actuales en control de versiones.
- **Live Server**: Visualización inmediata de cambios.

### Herramientas de Comunicación:

- **Discord, WhatsApp, Zoom**: Canales de coordinación para reuniones, actualizaciones y soporte.

### Recolección de Requisitos:

- **Miro**: Colaboración visual para planificación.
- **Google Docs**: Documentación compartida en línea.

### Diseño UX/UI:

- **Figma**: Prototipado y diseño colaborativo.
- **UXPressia**: Creación de mapas de experiencia y perfiles de usuarios.
- **LucidChart**: Diagramas de flujo y clases para user flows.

### Desarrollo de Software:

- **VS Code**: Entorno cómodo y personalizable.
- **Git**: Para control de versiones.

### Documentación:

- **GitHub**: Almacenamiento de código y documentación colaborativa.

### Testing:

- **Lenguaje Gherkin**: Para escribir pruebas de aceptación con herramientas como Cucumber.

---



### 6.1.2. Source Code Management

Se usará GitHub como repositorio principal bajo una organización del equipo, distribuyendo los proyectos en:

- Repositorio Landing Page: https://github.com/Chemtrack-Grupo4/Landing-Page.git
- Repositorio App Web: https://github.com/Chemtrack-Grupo4/chemtrack-webapp.git
- Repositorio Backend: https://github.com/Chemtrack-Grupo4/chemtrack-backend
- Repositorio Testing  https://github.com/Chemtrack-Grupo4/chemtrack-testing
---

### 6.1.3. Source Code Style Guide & Conventions
#### HTML (W3Schools HTML Style Guide)

- Declarar tipo de documento.
- Usar minúsculas en etiquetas y atributos.
- Cerrar todas las etiquetas.
- Colocar comillas en valores de atributos.
- Incluir siempre atributos `alt`, `width`, `height` en imágenes.
- No omitir etiquetas clave ni metadatos.

#### CSS (Google HTML/CSS Style Guide)

- Nombres de clases generales y cortos.
- Separación con guiones.
- Evitar selectores por ID.
- Uso de propiedades abreviadas.

#### JavaScript (W3C JS Best Practices)

- Nombres claros y legibles para variables y funciones.
- Evitar `var` global.
- Comentar código complejo.
- Empleo de notaciones simples.

#### Gherkin (Gherkin Conventions for Readable Specifications)

- Identación clara de bloques `Given-When-Then`.
- Uso de tablas en pasos complejos.
- Comillas simples para parámetros.
- Comentarios para separar escenarios.

Se seguirán las guías de estilo de Google para HTML, CSS y JavaScript. Angular será usado con HTML5, CSS3 y TypeScript. Git será gestionado bajo GitFlow, commits semánticos y versionado semántico.

El diseño se basará en Material Design utilizando Angular Material como biblioteca. El backend usará Spring Boot en Java, expuesto como RESTful API. Flutter/Dart se usará para la aplicación móvil.

### 6.1.4. Software Deployment Configuration

El despliegue de la landing page y la web app se realizará a través de Netlify. El proceso consiste en:

1. Iniciar sesión en Netlify con la cuenta de GitHub.
2. Ir a la sección "Sites" y seleccionar el botón correspondiente.
3. Elegir la organización en GitHub y seleccionar el repositorio.

En el caso de la landing page, al tratarse de un sitio estático, no es necesario configurar rutas. Basta con hacer clic en "Deploy" para iniciar el despliegue.

## 6.2. Landing Page, Services & Applications Implementation
### 6.2.1. Sprint 1
#### 6.2.1.1. Sprint Planning 1

| Sprint #                         | 1                                                                                                                                                                           |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**   |                                                                                                                                                                             |
| Date                             | 2025 - 05 - 13                                                                                                                                                               |
| Time                             | 10:30 PM                                                                                                                                                                     |
| Location                         | Virtual via Discord                                                                                                                                                          |
| Prepared By                      | Barrial Marin, Sharon Antuanet Ivet                                                                                                                                          |
| Attendees (to planning meeting)  | Camila Amaro, Sharon Barrial, Andrea García, Fabrizzio Laguerre, Josue Bustamante, Niurka Huarcaya, Josue Hidalgo                                                            |
| Sprint 1 - Review Summary        | No aplica al ser el primer sprint                                                                                                                                            |
| Sprint 1 - Retrospective Summary | No aplica al ser el primer sprint                                                                                                                                            |
| **Sprint Goal & User Stories**   |                                                                                                                                                                              |
| Sprint 1 Goal                    | El objetivo del presente Sprint es en desarrollar la Landing Page y Fronted usando los wireframes y mockups diseñados previamente, además del despliegue de ambos.           |
| Sprint 1 - Velocity              | El equipo puede aceptar 35 Story Points                                                                                                                                      |
| Sprint 1 - Story Points          | La suma de los Story Points de los User Stories que se atenderá es 27 Story Points                                                                                           |

#### 6.2.1.2. Aspect Leaders and Collaborators
| Team Member | GitHub Username | Landing Page <br> Features Leader (L)/Collaborator (C) | Frontend Incidents BC <br> Features Leader (L)/Collaborator (C)  | Frontend Management BC <br> Features Leader (L)/Collaborator (C) | Frontend Shared <br> Features Leader (L)/Collaborator (C) |
|----|-----|-----|----|----|----|
|Camila Amaro | CamiAm404 | C | L | C | C |
|Sharon Barrial | SharonBarrial | C | C | C | L |
|Andrea García | Armix18 | L | C | C | C |
|Fabrizzio Laguerre | UwUInspector | C | C | C | C |
|Josue Hidalgo | Kabudence | C | C | L | C |
|Niurka Huarcaya| NLH18 | C | C | L | C |

#### 6.2.1.3. Sprint Backlog 1

Implementación del Landing Page y Frontend acorde con las User Stories.

<table>
<tbody>
    <tr>
        <th valign="top">Sprint 1</th>
        <th colspan="7" valign="top">
        Sprint: Implementar el landing page y frontend acorde a las historias redactadas. Posteriormente realizar el despliegue  </th>
    </tr>
    <tr>
        <td colspan="2" valign="top">User Story</td>
        <td colspan="6" valign="top">Work-Item / Task</td>
    </tr>
    <tr>
        <td valign="top">Id</td>
        <td valign="top">Title</td>
        <td valign="top">Id</td>
        <td valign="top">Title</td>
        <td valign="top">Description</td>
        <td valign="top">Estimation (Hours)</td>
        <td valign="top">Assigned To</td><td valign="top"><p dir="auto">Status </p><p dir="auto">(To-do/In Process/To Review /Done)</p></td>
    </tr>
    <tr>
        <td rowspan="3" valign="top">US18</td>
        <td rowspan="3" valign="top">Botón Call to Action</td>
        <td valign="top">T01</td>
        <td valign="top">Header with call-to-action/td>
        <td valign="top">Agregar componentes del header con un respectivo call-to-action</td>
        <td valign="top">2</td>
        <td valign="top">Fabrizzio Laguerre</td>
        <td valign="top">Done</td>
    </tr>
  <tr>
    <td valign="top">T-06</td>
        <td valign="top">Footer with attachments</td>
        <td valign="top">Implementar botones de acceso rápido y resumen de los apartados del landing page.</td>
        <td valign="top">3</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
  </tr>
  <tr>
    <td valign="top">T07</td>
        <td valign="top">Button download</td>
        <td valign="top">Implementar botones de llamada para descargar </td>
        <td valign="top">3</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
  </tr>
  <tr>
        <td rowspan="4" valign="top">US17</td>
        <td rowspan="4" valign="top">Visualización de características de la aplicación web o móvil en Landing Page</td>
        <td valign="top">T02</td>
        <td valign="top">Section Our services</td>
        <td valign="top">Implementar la descripción de los servicios que ofrecemos al cliente</td>
        <td valign="top">3</td>
        <td valign="top">Sharon Barrial</td>
        <td valign="top">Done</td>
    </tr>
  <tr>
    <td valign="top">T03</td>
        <td valign="top">Section for video about product</td>
        <td valign="top">Implementar un compenente para reproducir un video breve de nuestro solution profile</td>
        <td valign="top">3</td>
        <td valign="top">Sharon Barrial</td>
        <td valign="top">In process</td>
  </tr>
   <tr>
    <td valign="top">T04</td>
        <td valign="top">Section about the team</td>
        <td valign="top">Implementar información de la startup con nuetsros miembros</td>
        <td valign="top">2</td>
        <td valign="top">Camila Amaro</td>
        <td valign="top">In process</td>
  </tr>
  <tr>
    <td valign="top">T05</td>
        <td valign="top">Section for customer testimonials</td>
        <td valign="top">Implementar reseñas de usuarios que usaron nuestra app.</td>
        <td valign="top">3</td>
        <td valign="top">Fabrizzio Laguerre</td>
        <td valign="top">Done</td>
  </tr>
    <tr>
        <td rowspan="1" valign="top">US01</td>
        <td rowspan="1" valign="top"> Monitoreo del Vehículo</td>
        <td valign="top">T08</td>
        <td valign="top">Implementación de vista de monitoreo</td>
        <td valign="top">Ver el monitoreo de los transportes.</td>
        <td valign="top">5</td>
        <td valign="top">Camila Amaro</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
        <td rowspan="1" valign="top">US04</td>
        <td rowspan="1" valign="top">Reporte de Estado del Vehículo</td>
        <td valign="top">T09</td>
        <td valign="top">Implementación de vista para ver reportes recibidos por vehículo</td>
        <td valign="top">Historial de reportes recibidos por parte de los tranportistas.</td>
        <td valign="top">3</td>
        <td valign="top">Josue Hidalgo</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
        <td rowspan="1" valign="top">US06</td>
        <td rowspan="1" valign="top">Visualización de resultados</td>
        <td valign="top">T11</td>
        <td valign="top">Implementación de pantalla de búsqueda de transportistas</td>
        <td valign="top">Mostrar navbar de búsqueda para que reciba parametros que busquen transportistas.</td>
        <td valign="top">5</td>
        <td valign="top">Andrea García</td>
        <td valign="top">Done</td>
    </tr>
        <tr>
        <td rowspan="1" valign="top">US07</td>
        <td rowspan="1" valign="top">Recibir Notificaciones de Incidentes en Tiempo Real</td>
        <td valign="top">T12</td>
        <td valign="top">Implementación de vista de incidentes en tiempo real</td>
        <td valign="top">Mostrar un buzón de notificaciones</td>
        <td valign="top">5</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">In progress</td>
    </tr>
   <tr>
        <td rowspan="2" valign="top">US08</td>
        <td rowspan="2" valign="top">Recibir Notificaciones de Incidentes en Tiempo Real</td>
        <td valign="top">T13</td>
        <td valign="top">Mostrar a los transportistas registrados</td>
        <td valign="top">Listado de los transportistas registrados en la aplicación</td>
        <td valign="top">5</td>
        <td valign="top">Josue Hidalgo</td>
        <td valign="top">In progress</td>
    </tr>
  <tr>
        <td valign="top">T14</td>
        <td valign="top">Implementación de vista de inicio de sesión</td>
        <td valign="top">Los usuarios tienden a registrarse</td>
        <td valign="top">5</td>
        <td valign="top">Andrea García</td>
        <td valign="top">In progress</td>
    </tr>
  <tr>
        <td rowspan="1" valign="top">US05</td>
        <td rowspan="1" valign="top">Seguimiento en Tiempo Real de los Transportes Activos</td>
        <td valign="top">T15</td>
        <td valign="top">Implementación de vista de servicios activos</td>
        <td valign="top">Visualización de dashboard para ver los servicios activos</td>
        <td valign="top">5</td>
        <td valign="top">Sharon Barrial</td>
        <td valign="top">In progress</td>
    </tr>
  <tr>
        <td rowspan="1" valign="top">US12</td>
        <td rowspan="1" valign="top">Seguimiento en Tiempo Real de los Transportes Activos</td>
        <td valign="top">T16</td>
        <td valign="top">Implementación de vista de registro de nuevo servicio</td>
        <td valign="top">Dashboard para registrar servicio</td>
        <td valign="top">5</td>
        <td valign="top">Sharon Barrial</td>
        <td valign="top">Camila Amaro</td>
    </tr>
</tbody>
</table>

#### 6.2.1.3. Development Evidence for Sprint Review

Se presentan los commits realizados en el repositorio de GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.

- Repositorio Landing Page: https://github.com/Chemtrack-Grupo4/Landing-Page
  
<br>

- Repositorio Frontend: https://github.com/Chemtrack-Grupo4/chemtrack-webapp
  

<br>


<table  align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited on (Date)</th>
    </tr>
    <tr>
        <td rowspan=3>Landing Page</td>
        <td>develop</td>
        <td>a833922</td>
        <td>Initial files</td>
        <td>-</td>
        <td>12/05/25</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>9563255</td>
        <td>fix: footer and navbar</td>
        <td>-</td>
        <td>12/05/25</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>abcda5d</td>
        <td>fix: translation issues and margin corrections</td>
        <td>-</td>
        <td>13/05/25</td>
    </tr>
    <tr>
        <td rowspan=6>Web App</td>
        <td>feature/Shared</td>
        <td>bdf1ab6</td>
        <td>feat: add shared components</td>
        <td>-</td>
        <td>13/05/25</td>
    </tr>
    <tr>
        <td>feature/management-deliveries</td>
        <td>6a79b66</td>
        <td>feat: add Deliveries Bounded Context</td>
        <td>-</td>
        <td>13/05/25</td>
    <tr>
        <td>feature/incidents</td>
        <td>ecd4f10</td>
        <td>feat: add incidents bounded context</td>
        <td>-</td>
        <td>13/05/25</td>
    <tr>
        <td>feature/management-services</td>
        <td>c16eebb</td>
        <td>feat: Add Services Bounded Context</td>
        <td>-</td>
        <td>13/05/25</td>
    <tr>
        <td>feature/monitoring</td>
        <td>778693e</td>
        <td>feat:Added monitoring files about bounded context monitoring</td>
        <td>-</td>
        <td>13/05/25</td>
    <tr>
        <td>feature/profile</td>
        <td>a7380b9</td>
        <td>feature: Feature Profile and fixes</td>
        <td>-</td>
        <td>13/05/25</td>
</table>


#### 6.2.1.4. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-1.feature  | - | 14/05/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-2.feature  | - | 14/05/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-3.feature  | - | 14/05/2025 |


Link de repositorio: https://github.com/Chemtrack-Grupo4/chemtrack-testing

#### 6.2.1.5. Execution Evidence for Sprint Review

En el Sprint 1 se alcanzó a desarrollar una primera versión de la landing page y la primera versión del Frontend de la aplicación. A continuación se muestra lo realizado:

**1. Landing page**

<a href="https://chemtrack-grupo4.github.io/Landing-Page/"><img src="https://i.ibb.co/zVDsx58N/Captura-de-pantalla-2025-05-14-003027.png" alt="Landing page" border="0"></a>

**2. Frontend**

<a href="https://chemtrack-app.netlify.app/services"><img src="https://i.ibb.co/ZRQV6Xzy/Captura-de-pantalla-2025-05-14-021751.png" alt="Frontend" border="0"></a>

#### 6.2.1.6. Services Documentation Evidence for Sprint Review

Para el Sprint 1, se definieron los siguientes endpoints clave que permiten gestionar usuarios, entregas, servicios e incidentes dentro del sistema. Cada endpoint cumple una función específica en la arquitectura del backend.

| Endpoint | Detalles |
| - | - | 
| /user-controller| En este endpoint se almacenan la información de los usuarios, tales como username, email, password, role, photo y token | 
| /deliveries | En este endpoint se almacenan las entregas que aun no tienen ligadas un incidente | 
| /services  | En este endpoint se almacenan los servicios realizados por parte de las empresas | 
| /incidents | En este endpoint se almacenan los incidentes registrados manualmente | 

#### 6.2.1.7. Software Deployment Evidence for Sprint Review

Para el despliegue de landing page se usó GitHub Pages y para la web app  se usó Netlify, a continuación se detallará paso a paso para este Sprint 1:

Ejecutamos el comando “ng build” en la ruta de nuestro projecto en angular, nos muestra lo siguiente:

Se genera la carpeta dist, luego, se añade el archivo “netlify.toml” para que netlify pueda entender las rutas de nuestro programa en angular con la siguiente configuración.

Y pasamos la carpeta que se encuentra dentro de la carpeta dist generada en nuestro proyecto. Y se obtiene el registro del despliegue dentro de Netlify


De esta manera el avance del Sprint 1 queda desplegado.

<img src="https://i.ibb.co/ZRQV6Xzy/Captura-de-pantalla-2025-05-14-021751.png" alt="frontend" border="0">

<br>

<img src="https://i.ibb.co/qG6TWLt/Captura-de-pantalla-2025-05-14-023450.png" alt="Landing page" border="0">

<br>

Link de landing page: https://chemtrack-grupo4.github.io/Landing-Page/

Link de frontend: https://chemtrack-app.netlify.app/services

#### 6.2.1.8. Team Collaboration Insights during Sprint

**Pulse**
![image](https://github.com/user-attachments/assets/39d31df0-be02-4f36-ab3e-7dbabce2ea2e)

**Network**
![image](https://github.com/user-attachments/assets/81f0c621-67a9-4a43-9a99-d68c658aea6e)

**Contributors**
![image](https://github.com/user-attachments/assets/06d7cf2c-585b-4801-ac55-a7509aa09928)

### 6.2.2. Sprint 2
#### 6.2.2.1. Sprint Planning 2

| Sprint #                         | 2                                                                                                                                                                           |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**   |                                                                                                                                                                             |
| Date                             | 2025 - 06 - 03                                                                                                                                                               |
| Time                             | 10:00 PM                                                                                                                                                                     |
| Location                         | Virtual via Discord                                                                                                                                                          |
| Prepared By                      | Barrial Marin, Sharon Antuanet Ivet                                                                                                                                          |
| Attendees (to planning meeting)  | Camila Amaro, Sharon Barrial, Andrea García, Fabrizzio Laguerre, Josue Bustamante, Niurka Huarcaya, Josue Hidalgo                                                            |
| Sprint 2 - Review Summary        | Durante el Sprint 1, el equipo completó con éxito todas las tareas planificadas. Las principales funcionalidades implementadas incluyen el registro e inicio de sesión de usuarios, visualización y edición de perfil, y la gestión de cultivos en el landing page y la aplicación web.<br>                                                                                                                                        |
| Sprint 2 - Retrospective Summary | **Aspectos positivos** <br> - El equipo logró completar la mayoría de tareas conforme a los tiempos estimados, manteniendo una buena organización del trabajo.<br> - La distribución de tareas entre plataformas (Web, Mobile, IoT y Backend) permitió avanzar en paralelo y cumplir con funcionalidades clave del sistema.<br>**Áreas de mejora**<br> - La integración entre frontend y backend evidenció algunos retrasos por falta de endpoints definidos previamente..<br>**Acciones a implementar**<br> - Definir endpoints con mayor anticipación en el backlog técnico antes de asignar tareas dependientes.<br> - Establecer una checklist de documentación por módulo (mockup, API, lógica de validación) para agilizar el entendimiento del equipo.                                                                                                                                            |
| **Sprint Goal & User Stories**   |                                                                                                                                                                              |
| Sprint 2 Goal                    | El objetivo de este Sprint fue implementar funcionalidades claves del sistema relacionadas con la visualización de notificaciones, rutas seguras, historial de transporte, publicaciones de solicitud de transporte y control de tiempos, tanto en la versión web como móvil, backend e IoT.<br>**Logros del sprint** <br> - Implementación de interfaces de notificaciones de mantenimiento y solicitudes de transporte. <br> - Implementación del historial de transportes e incidentes para usuarios y transportistas. <br> - Publicación y filtrado de solicitudes de transporte desde la web y app móvil.<br> - Control y alertas por exceso de tiempo de conducción integrados en sensores IoT, backend y UI.           |
| Sprint 2 - Velocity              | El equipo puede aceptar 53 Story Points                                                                                                                                      |
| Sprint 2 - Story Points          | La suma de los Story Points de los User Stories que se atenderá es 31 Story Points                                                                                           |

#### 6.2.2.2. Aspect Leaders and Collaborators
| Team Member | GitHub Username | Landing Page <br> Features Leader (L)/Collaborator (C) | Frontend Web - Mobile <br> Features Leader (L)/Collaborator (C)  | Backend <br> Features Leader (L)/Collaborator (C) | IoT <br> Features Leader (L)/Collaborator (C) |
|----|-----|-----|----|----|----|
|Camila Amaro | CamiAm404 | L | C | C | C |
|Sharon Barrial | SharonBarrial | C | C | C | L |
|Andrea García | Armix18 | C | C | C | C |
|Fabrizzio Laguerre | UwUInspector | C | C | C | C |
|Josue Hidalgo | Kabudence | C | L | C | C |
|Niurka Huarcaya| NLH18 | C | C | L | C |

#### 6.2.2.3. Sprint Backlog 2

Mejora del Landing Page, Frontend(Web y Mobile) e implementación del Backend y IoT acorde con las User Stories.

<table>
<tbody>
    <tr>
        <th valign="top">Sprint 2</th>
        <th colspan="7" valign="top">
        Sprint: Implementar el landing page y frontend acorde a las historias redactadas. Posteriormente realizar el despliegue  </th>
    </tr>
    <tr>
        <td colspan="2" valign="top">User Story</td>
        <td colspan="6" valign="top">Work-Item / Task</td>
    </tr>
    <tr>
        <td valign="top">Id</td>
        <td valign="top">Title</td>
        <td valign="top">Id</td>
        <td valign="top">Title</td>
        <td valign="top">Description</td>
        <td valign="top">Estimation (Hours)</td>
        <td valign="top">Assigned To</td><td valign="top"><p dir="auto">Status </p><p dir="auto">(To-do/In Process/To Review /Done)</p></td>
    </tr>
    <tr>
        <td rowspan="4" valign="top">TS01</td>
        <td rowspan="4" valign="top"> Implementación de Monitoreo del Vehículo</td>
        <td valign="top">T01</td>
        <td valign="top">Diseño de interfaz de monitoreo</td>
        <td valign="top">Diseñar la vista web donde se mostrarán los sensores activos al usuario.</td>
        <td valign="top">4</td>
        <td valign="top">Camila Amaro</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T02</td>
    <td valign="top">Implementación de interfaz</td>
    <td valign="top">Desarrollar la vista web para mostrar sensores activos a tiempo real.</td>
    <td valign="top">5</td>
    <td valign="top">Sharon Barrial</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T03</td>
    <td valign="top">Configuración del backend</td>
    <td valign="top">Crear endpoints y lógica para generar, almacenar y enviar los datos sensores desde el backend.</td>
    <td valign="top">6</td>
    <td valign="top">Niurka Huarcaya</td>
    <td valign="top">In Progress</td>
</tr>
<tr>
    <td valign="top">T04</td>
    <td valign="top">Integración backend-frontend</td>
    <td valign="top">Consumir la API de sensores desde el frontend para mostrar los datos al usuario.</td>
    <td valign="top">4</td>
    <td valign="top">Fabrizzio Laguerre	</td>
    <td valign="top">In Progress</td>
</tr>
    <tr>
        <td rowspan="4" valign="top">US03</td>
        <td rowspan="4" valign="top"> Verificación de Rutas Seguras</td>
        <td valign="top">T05</td>
    <td valign="top">Vista de rutas seguras (Web)</td>
    <td valign="top">Implementar la interfaz que muestre rutas actuales y alertas en el mapa.</td>
    <td valign="top">5</td>
    <td valign="top">Josue Hidalgo	</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T06</td>
    <td valign="top">Mapa interactivo de rutas (Mobile)</td>
    <td valign="top">Mostrar al conductor rutas seguras y alertas en la aplicación móvil.</td>
    <td valign="top">5</td>
    <td valign="top">Andrea Garcia</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T07</td>
    <td valign="top">Sensor GPS para rutas (IoT)</td>
    <td valign="top">Configurar dispositivos IoT para detectar ubicación y posibles desvíos de ruta.</td>
    <td valign="top">6</td>
    <td valign="top">Camila Amaro</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T08</td>
    <td valign="top">API de rutas y alertas (Backend)</td>
    <td valign="top">Desarrollar endpoints para consultar rutas seguras y enviar alertas.</td>
    <td valign="top">6</td>
    <td valign="top">Sharon Barrial	</td>
    <td valign="top">In progress</td>
</tr>
    <tr>
        <td rowspan="4" valign="top">US12</td>
        <td rowspan="4" valign="top"> Visualización de Transportistas Disponibles</td>
        <td valign="top">T09</td>
        <td valign="top">Diseño de interfaz de transportistas disponibles</td>
        <td valign="top">Diseñar la vista web donde se mostrarán los transportistas disponibles.</td>
        <td valign="top">4</td>
        <td valign="top">Fabrizzio Laguerre	</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T10</td>
    <td valign="top">Implementación de interfaz</td>
    <td valign="top">Desarrollar la vista web para mostrar los transportistas disponibles.</td>
    <td valign="top">5</td>
    <td valign="top">Josue Hidalgo	</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T11</td>
    <td valign="top">Configuración del backend</td>
    <td valign="top">Crear endpoints y lógica para generar, almacenar y enviar los datos de los transportistas disponibles desde el backend.</td>
    <td valign="top">6</td>
    <td valign="top">Niurka Huarcaya	</td>
    <td valign="top">In Progress</td>
</tr>
<tr>
    <td valign="top">T12</td>
    <td valign="top">Integración backend-frontend</td>
    <td valign="top">Consumir la API de los transportistas disponibles desde el frontend para mostrar los datos al usuario.</td>
    <td valign="top">4</td>
    <td valign="top">Camila Amaro</td>
    <td valign="top">In progress</td>
</tr>
    <tr>
        <td rowspan="4" valign="top">US10</td>
        <td rowspan="4" valign="top">Actualización de Estado del Transporte</td>
        <td valign="top">T13</td>
    <td valign="top">Vista de reportes por vehículo (Web)</td>
    <td valign="top">Mostrar historial de reportes recibidos por cada transporte en la plataforma web.</td>
    <td valign="top">3</td>
    <td valign="top">Josue Hidalgo</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T14</td>
    <td valign="top">Visualización de actualización de estado (Mobile)</td>
    <td valign="top">Permitir la visualización del estado del transporte a los empresarios.</td>
    <td valign="top">4</td>
    <td valign="top">Andrea Garcia</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T15</td>
    <td valign="top">Sensor de estado del vehículo (IoT)</td>
    <td valign="top">Capturar el estado del transporte (alerta de anomalías) mediante sensores.</td>
    <td valign="top">5</td>
    <td valign="top">Sharon Barrial	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T16</td>
    <td valign="top">API de estados del transporte (Backend)</td>
    <td valign="top">Gestionar actualización, almacenamiento y consulta de estados del transporte.</td>
    <td valign="top">5</td>
    <td valign="top">Fabrizzio Laguerre	</td>
    <td valign="top">In progress</td>
</tr>
    <tr>
        <td rowspan="4" valign="top">US11</td>
        <td rowspan="4" valign="top">Publicación de Solicitudes de Transporte de Productos Peligrosos</td>
        <td valign="top">T17</td>
    <td valign="top">Búsqueda de transportistas (Web)</td>
    <td valign="top">Navbar para filtrar transportistas según parámetros específicos.</td>
    <td valign="top">5</td>
    <td valign="top">Niurka Huarcaya	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T18</td>
    <td valign="top">Formulario de solicitud (Mobile)</td>
    <td valign="top">Permitir al usuario registrar una solicitud de transporte desde su dispositivo.</td>
    <td valign="top">4</td>
    <td valign="top">Camila Amaro</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T19</td>
    <td valign="top">Validación de condiciones (IoT)</td>
    <td valign="top">Verificar si el contenedor cumple con las condiciones necesarias mediante sensores.</td>
    <td valign="top">6</td>
    <td valign="top">Sharon Barrial	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T20</td>
    <td valign="top">API de publicación de solicitudes (Backend)</td>
    <td valign="top">Crear endpoints para registrar, listar y gestionar solicitudes.</td>
    <td valign="top">5</td>
    <td valign="top">Fabrizzio Laguerre	</td>
    <td valign="top">In progress</td>
</tr>
        <tr>
        <td rowspan="4" valign="top">US13</td>
        <td rowspan="4" valign="top">Acceso a Reporte de Incidentes</td>
        <td valign="top">T21</td>
    <td valign="top">Vista de historial e incidentes (Web)</td>
    <td valign="top">Mostrar en la plataforma web el historial de viajes e incidentes asociados.</td>
    <td valign="top">5</td>
    <td valign="top">Niurka Huarcaya</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T22</td>
    <td valign="top">Historial del transportista (Mobile)</td>
    <td valign="top">Permitir al transportista ver su historial de viajes desde la app.</td>
    <td valign="top">4</td>
    <td valign="top">Josue Hidalgo	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T23</td>
    <td valign="top">Sincronización de logs (IoT)</td>
    <td valign="top">Enviar datos desde sensores al backend para guardar en historial.</td>
    <td valign="top">5</td>
    <td valign="top">Andrea Garcia</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T24</td>
    <td valign="top">API de historial (Backend)</td>
    <td valign="top">Crear endpoints para consultar historial de transportes con filtros.</td>
    <td valign="top">4</td>
    <td valign="top">Niurka Huarcaya	</td>
    <td valign="top">In progress</td>
</tr>
  <tr>
        <td rowspan="4" valign="top">US14</td>
        <td rowspan="4" valign="top">Control de tiempos de conducción de transporte</td>
        <td valign="top">T25</td>
    <td valign="top">Dashboard de tiempos (Web)</td>
    <td valign="top">Visualizar en la web los tiempos de conducción total.</td>
    <td valign="top">5</td>
    <td valign="top">Sharon Barrial</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T26</td>
    <td valign="top">Alertas de conducción (Mobile)</td>
    <td valign="top">Notificar al transportista si excede el tiempo máximo permitido.</td>
    <td valign="top">4</td>
    <td valign="top">Fabrizzio Laguerre	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T27</td>
    <td valign="top">Sensor de tiempo de conducción (IoT)</td>
    <td valign="top">Medir tiempo de conducción desde el encendido del vehículo.</td>
    <td valign="top">5</td>
    <td valign="top">Josue Hidalgo	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T28</td>
    <td valign="top">Control y lógica de alertas (Backend)</td>
    <td valign="top">Procesar y emitir alertas desde backend cuando se exceda tiempo permitido.</td>
    <td valign="top">6</td>
    <td valign="top">Camila Amaro	</td>
    <td valign="top">In progress</td>
</tr>
    <tr>
        <td rowspan="4" valign="top">US15</td>
        <td rowspan="4" valign="top">Notificación de tiempo de conducción de transporte en exceso</td>
        <td valign="top">T29</td>
        <td valign="top">Diseño de interfaz de notificaciones</td>
        <td valign="top">Diseñar la vista web donde se mostrarán las notificaciones al usuario.</td>
        <td valign="top">4</td>
        <td valign="top">Camila Amaro</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T30</td>
    <td valign="top">Implementación de interfaz</td>
    <td valign="top">Desarrollar la vista web para mostrar notificaciones del tiempo de conducción de transporte.</td>
    <td valign="top">5</td>
    <td valign="top">Sharon Barrial	</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T31</td>
    <td valign="top">Configuración del backend de notificaciones</td>
    <td valign="top">Crear endpoints y lógica para generar, almacenar y enviar notificaciones desde el backend.</td>
    <td valign="top">6</td>
    <td valign="top">Fabrizzio Laguerre	</td>
    <td valign="top">In progress</td>
</tr>
<tr>
    <td valign="top">T32</td>
    <td valign="top">Integración backend-frontend</td>
    <td valign="top">Consumir la API de notificaciones desde el frontend para mostrar los datos al usuario.</td>
    <td valign="top">4</td>
    <td valign="top">Niurka Huarcaya	</td>
    <td valign="top">In progress</td>
</tr>
  <tr>
        <td rowspan="3" valign="top">US16</td>
        <td rowspan="3" valign="top">Landing Page responsive</td>
        <td valign="top">T33</td>
        <td valign="top">Mejora del diseño responsive en dispositivos reales</td>
    <td valign="top">Realizar pruebas de la landing en diferentes tamaños de pantalla y navegadores, corrigiendo errores de diseño y visualización.</td>
    <td valign="top">2</td>
    <td valign="top">Sharon Barrial	</td>
    <td valign="top"> In progress</td>
</tr>
</tbody>
</table>

Se hizo uso de la herramienta Trello para gestionar las tareas de manera ágil y colaborativa tanto para este sprint como los que vienen en las próximas iteracciones. Como resultado se obtuvo 33 tasks para el presente sprint.

![image](https://github.com/user-attachments/assets/7191c51b-dfb7-4ec7-b3c7-c1635e23ad9b)

[Enlace de Trello](https://trello.com/invite/b/681fc71a5692939678facc66/ATTIc15614080cece153cca3c2bae0cd3505CFC7F6B0/chemtrack)

#### 6.2.2.4. Development Evidence for Sprint Review

Se presentan los commits realizados en el repositorio de GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.

- Repositorio Landing Page: https://github.com/Chemtrack-Grupo4/Landing-Page
  
<br>

- Repositorio Frontend: https://github.com/Chemtrack-Grupo4/chemtrack-webapp

<br>

- Repositorio Backend: https://github.com/Chemtrack-Grupo4/chemtrack-backend
  
<br>

- Repositorio Mobile: https://github.com/Chemtrack-Grupo4/chemtrack-mobileapp
  
<br>

- Repositorio IoT: https://github.com/Chemtrack-Grupo4/chemtrack-embedded
  
<br>

- Repositorio Edge: https://github.com/Chemtrack-Grupo4/chemtrack-edge
  
<br>

<table  align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited on (Date)</th>
    </tr>
    <tr>
        <td>Landing Page</td>
        <td>develop</td>
        <td>c833922</td>
        <td>feat: add responsive design</td>
        <td>-</td>
        <td>30/05/25</td>
    </tr>
    <tr>
        <td rowspan=6>Web app</td>
        <td>feature/shared</td>
        <td>bdf1ab6</td>
        <td>fix: fix problem with data call</td>
        <td>-</td>
        <td>30/05/25</td>
    </tr>
    <tr>
        <td>feature/shared</td>
        <td>6a79b66</td>
        <td>feat: Update toolbar</td>
        <td>-</td>
        <td>30/05/25</td>
    <tr>
        <td>feature/management</td>
        <td>ecd4f10</td>
        <td>feat: update components</td>
        <td>-</td>
        <td>30/05/25</td>
    <tr>
        <td>feature/incidents</td>
        <td>c16eebb</td>
        <td>feat: update components</td>
        <td>-</td>
        <td>30/05/25</td>
    <tr>
        <td>feature/profile</td>
        <td>778693e</td>
        <td>feat: update component</td>
        <td>-</td>
        <td>30/05/25</td>
    <tr>
        <td>feature/management</td>
        <td>a7380b9</td>
        <td>feat: update component</td>
        <td>-</td>
        <td>30/05/25</td>
    <tr>
        <td rowspan=5>Mobile</td>
        <td>feature/fix-data-call</td>
    <td>bdf1ab6</td>
    <td>fix(shared): resolve issue in data fetch call</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/toolbar-update</td>
    <td>6a79b66</td>
    <td>feat(shared): update toolbar UI and logic</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/management-ui</td>
    <td>ecd4f10</td>
    <td>feat(management): improve management screen components</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/incidents</td>
    <td>c16eebb</td>
    <td>feat(incidents): enhance incident reporting UI</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/profile-view</td>
    <td>778693e</td>
    <td>feat(profile): update profile view layout</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
        <td rowspan=5>Backend</td>
        <td>feature/fix-data-call</td>
    <td>bdf1ab6</td>
    <td>fix(api): resolve issue in data fetch logic</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/toolbar-update</td>
    <td>6a79b66</td>
    <td>feat(utils): update toolbar response metadata</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/management-module</td>
    <td>ecd4f10</td>
    <td>feat(management): update transport management APIs</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/incidents-endpoint</td>
    <td>c16eebb</td>
    <td>feat(incidents): enhance endpoint for real-time data</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/profile-update</td>
    <td>778693e</td>
    <td>feat(profile): add endpoint to update user profile</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
        <td rowspan=5>IoT</td>
        <td>feature/fix-data-call</td>
    <td>bdf1ab6</td>
    <td>fix(device-comm): correct error in MQTT data retrieval</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/update-toolbar</td>
    <td>6a79b66</td>
    <td>feat(dashboard): sync toolbar with sensor status</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/management-sync</td>
    <td>ecd4f10</td>
    <td>feat(management): update sync logic for connected devices</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/incidents-stream</td>
    <td>c16eebb</td>
    <td>feat(incidents): add stream support for incident alerts</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/profile-config</td>
    <td>778693e</td>
    <td>feat(profile): allow configuration of IoT device profile</td>
    <td>-</td>
    <td>30/05/25</td>
</tr>

<tr>
    <td rowspan=3>Edge</td>
    <td>feature/mqtt-connection</td>
    <td>d1e8f56</td>
    <td>feat(mqtt): add MQTT communication logic</td>
    <td>Integrated MQTT client and basic publish/subscribe setup for edge device.</td>
    <td>30/05/25</td>
</tr>
<tr>
    <td>feature/sensor-handler</td>
    <td>fa7b223</td>
    <td>feat(sensor): implement temperature sensor reading</td>
    <td>Added support for DHT22 sensor and periodic data capture.</td>
    <td>31/05/25</td>
</tr>
<tr>
    <td>feature/mqtt-payload</td>
    <td>a12f443</td>
    <td>feat(mqtt): format and send structured JSON data</td>
    <td>Refactored MQTT messages to follow ChemTrack data schema.</td>
    <td>01/06/25</td>
</tr>

</table>


#### 6.2.2.5. Testing Suite Evidence for Sprint Review


| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-1.feature  | - | 14/05/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-2.feature  | - | 14/05/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-3.feature  | - | 14/05/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-4.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-5.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-6.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-7.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-8.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-9.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-10.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-11.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-12.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-13.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-14.feature  | - | 14/06/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-15.feature  | - | 14/06/2025 |


Link de repositorio: https://github.com/Chemtrack-Grupo4/chemtrack-testing

#### 6.2.2.6. Execution Evidence for Sprint Review

En el Sprint 2 se alcanzó a desarrollar la última versión de la landing page, la segunda versión del Frontend del Web Application, Mobile, y la primera versión del Backend y IoT de la aplicación. A continuación se muestra lo realizado:

>**Landing page**

- Versión Final
- Estado: En producción activa
- Se accede a la página web - Frontend, desde la opción *Aplicación* cta.

<a href="https://chemtrack-grupo4.github.io/Landing-Page/"><img src="https://i.ibb.co/zVDsx58N/Captura-de-pantalla-2025-05-14-003027.png" alt="Landing page" border="0"></a>

Demostración del contenido de Landing Page y su conexión con la página web desde el botón *Call-To-Action*.
![image](https://github.com/user-attachments/assets/9e48c805-dd5f-45f9-a23c-fd81e63e2de6)

[Enlace de video](https://youtu.be/iZ1wX6IyvGI)

>**Frontend**

- Versión Final
- Estado: En producción activa

![image](https://github.com/user-attachments/assets/c81b1bf8-9ce5-450e-bdb9-995c629f16f8)
![Imagen de WhatsApp 2025-06-06 a las 21 01 36_aca33b7f](https://github.com/user-attachments/assets/cd16edf9-ba5b-48a0-bdd9-cdfc1fab861b)
![image](https://github.com/user-attachments/assets/4ce06d6c-c59c-4360-91d6-56066d9a9c23)
![image](https://github.com/user-attachments/assets/ba75656d-0b2b-4138-907f-8fa107e8c399)
![image](https://github.com/user-attachments/assets/f9631fb8-8240-4173-a67c-2a3e5bd76886)

>**Backend**

- Versión Inicial
- Estado: En producción activa

Endpoints
![image](https://github.com/user-attachments/assets/3aa0988d-2054-4960-9db8-e3c62fb7f8ae)
![image](https://github.com/user-attachments/assets/9811ceeb-bb0d-4c7d-a965-38bc989e95db)

Demostración del funcionamiento de los endpoints a través de postman
![Imagen de WhatsApp 2025-06-19 a las 22 59 45_7d5ac168](https://github.com/user-attachments/assets/d652b958-1980-42f1-85d8-3d83d9e86d3c)

[Enlace del video](https://youtu.be/UDbjgP1GyrI)

>**Mobile**
- Versión Inicial
- Estado: Desplegado en apk
![image](https://github.com/user-attachments/assets/38aa8b3a-1d0a-4bc6-9b7d-71d6ffb3f390)

[Enlace del video](https://youtu.be/Tnb-feMw1N8)

>**IoT Embedded**
- Versión Inicial
- Estado: Simulado en Wokwi e integrado con broker MQTT

![Imagen de WhatsApp 2025-06-18 a las 21 53 50_c4c6f0c1](https://github.com/user-attachments/assets/f3b9f7b5-c4df-4104-903a-b7897d88e73a)
[Enlace de demostración de su funcionamiento](https://youtu.be/mHsDo7mMxjk?si=jYEzVz3hB8E_QJCo)

>**Edge**
- Versión Inicial
- Estado: Pruebas de entorno local

![image](https://github.com/user-attachments/assets/c715a7e0-b8bf-4fc1-8d42-ae2e549313d5)
![Imagen de WhatsApp 2025-06-19 a las 08 47 13_da59ddfe](https://github.com/user-attachments/assets/d1d4f105-9631-4dd1-82cc-a4255e09c334)
![Imagen de WhatsApp 2025-06-19 a las 08 49 45_664c14b8](https://github.com/user-attachments/assets/eae9c537-12bf-4d1e-9665-23f3f560e07b)

Demostración de funcionamiento de edge y su comunicación con el embedded.

![image](https://github.com/user-attachments/assets/87bda626-4f78-4302-a082-356b6325a396)
[Enlace del video](https://youtu.be/mHsDo7mMxjk)


#### 6.2.2.7. Services Documentation Evidence for Sprint Review

Para el Sprint 2, se definieron los siguientes endpoints clave que permiten gestionar usuarios, entregas, servicios, incidentes, rutas seguras, historial y publicaciones dentro del sistema. Cada endpoint cumple una función específica en la arquitectura del backend.

| Endpoint | Detalles |
| - | - | 
| /user-controller| En este endpoint se almacenan la información de los usuarios, tales como username, email, password, role, photo y token | 
| /deliveries | En este endpoint se almacenan las entregas que aun no tienen ligadas un incidente | 
| /services  | En este endpoint se almacenan los servicios realizados por parte de las empresas | 
| /incidents | En este endpoint se almacenan los incidentes registrados manualmente | 
| /sensors	 | 	Este endpoint gestiona la creación, consulta y envío de notificaciones de mantenimiento, nuevas solicitudes y alertas por tiempo de conducción. | 

>Sensors

![image](https://github.com/user-attachments/assets/91290394-3803-49fd-99da-e2f50a973e65)

Al hacer un post se muestra en la página web los sensores que están activados

![image](https://github.com/user-attachments/assets/7909b9a7-90f7-48d3-81c1-d98aec20efcc)

>Incidents

![image](https://github.com/user-attachments/assets/d39b9b08-f3ef-481e-a115-97c23c922255)

Visualización de Incidents en el mobile 

![Imagen de WhatsApp 2025-06-20 a las 18 04 12_de39af0b](https://github.com/user-attachments/assets/ebe1eac1-8a60-4cef-b6af-e62908f5baf4)


>Services

![image](https://github.com/user-attachments/assets/a4296f9c-cb99-47aa-802c-1feb6683278b)

Se muestra los servicios On-Going en la página web

![image](https://github.com/user-attachments/assets/a673b2f7-2695-42e3-a299-006171176a46)

Se muetsra los servicios On-Going en la app mobile

![Imagen de WhatsApp 2025-06-20 a las 18 02 37_6554115d](https://github.com/user-attachments/assets/1abd3326-5818-4282-b652-b5f4e27a5f74)


>Deliveries

![image](https://github.com/user-attachments/assets/6fbaa0b1-9c2a-4a5d-b07a-690c7f6f30a6)

Los servicios monitoreados en tiempo real

![image](https://github.com/user-attachments/assets/0c116d69-0ae2-4e24-bdcf-740b5789c602)

Los servicios a tiempo real visualizados en mobile

![Imagen de WhatsApp 2025-06-20 a las 18 03 01_abdef808](https://github.com/user-attachments/assets/109230bf-d1dd-4054-a871-3b0255c6c201)


Más detalles de los servicios en tiempo real

![image](https://github.com/user-attachments/assets/2a765605-1ee4-4e46-aa97-aaa23c643381)


Más detalle del deliveries vistos en mobile

![Imagen de WhatsApp 2025-06-20 a las 18 03 47_ccd2b56e](https://github.com/user-attachments/assets/f7427e13-3f42-4ca4-a89d-64b01afcde64)


>Auth controller & User controller

![image](https://github.com/user-attachments/assets/4c2e8574-5027-4a7e-8fb3-73cdbfbf6dfd)

Muestra de los empleados de acuerdo al usuario autenticado

![image](https://github.com/user-attachments/assets/9ae48dec-c055-4fc8-a08a-66b70bf44254)



#### 6.2.2.8. Software Deployment Evidence for Sprint Review

>**Despliegue de Landing Page** 

La Landing Page fue desplegada utilizando **GitHub Pages**, lo que permitió alojar el sitio de forma gratuita y accesible mediante una URL pública. Se configuró el repositorio con la rama correspondiente (`main` o `gh-pages`) y se habilitó la opción de GitHub Pages desde la configuración del repositorio para publicar el contenido estático. Esto facilitó compartir el proyecto con usuarios finales y stakeholders sin necesidad de servidores externos.

![github](https://github.com/user-attachments/assets/73bd7cc4-21c8-4b74-8825-5187511ba209)
[Enlace de video](https://youtu.be/iZ1wX6IyvGI)

>**Despliegue del Frontend**

Para la aplicación principal desarrollada en Angular, se utilizó **Netlify** como plataforma de despliegue debido a su integración continua y facilidad de configuración.

El proceso consistió en:

**Compilación del proyecto Angular**  
Se ejecutó el comando `ng build` desde la raíz del proyecto, generando los archivos estáticos dentro del directorio `dist/`.

**Configuración del archivo `netlify.toml`**  
Se creó el archivo de configuración `netlify.toml` con el objetivo de gestionar correctamente las rutas internas de Angular. Esto garantiza que las solicitudes de navegación directa a rutas definidas por Angular sean correctamente redirigidas.

**Carga del contenido en Netlify**  
Se seleccionó el subdirectorio correspondiente dentro de `dist/` (específicamente el que representa el nombre del proyecto) como carpeta de despliegue en Netlify.  
Al finalizar el proceso, se obtuvo el registro exitoso del despliegue.

![Imagen de WhatsApp 2025-06-20 a las 17 25 55_64fe3bb9](https://github.com/user-attachments/assets/0bd7cdc5-cf6d-459a-8fbc-b6a5c4c09c24)


De esta manera, el avance del **Sprint 2** quedó funcional y disponible públicamente para su evaluación.

![image](https://github.com/user-attachments/assets/a1e99f7f-b64f-43fc-9b08-a09f93a62f4d)

>**Despliegue del Backend**

**Configuración del repositorio**
   - Se aseguró que el repositorio de backend estuviera limpio y contuviera todos los archivos necesarios para el build.
   - Se definieron variables de entorno desde Railway para la conexión a servicios externos como la base de datos y MQTT.

**Integración con Azure**
   - Se accedió a **Portal Azure** y se creó un nuevo proyecto.
   - Se conectó el proyecto directamente al repositorio en GitHub, seleccionando la rama principal para el despliegue.
   - Azure detectó automáticamente el stack del proyecto e inició el proceso de construcción (**build**).

![image](https://github.com/user-attachments/assets/d97cd947-f44f-4dc6-a285-1579a49b85ac)

**Despliegue automático**
   - Una vez completado el build, Azure desplegó el backend y proporcionó una URL pública accesible.
   - Se habilitó el monitoreo en tiempo real para verificar el estado del servicio.
   - En caso de errores o necesidad de debugging, Railway ofrece visualización de logs directamente desde el panel.

![image](https://github.com/user-attachments/assets/6c857f5a-dfec-4720-8997-26c3be44dfa4)

Aquí se hace presente el video demostrando el funcionamiento del despliegue del backend haciendo uso de POSTMAN.

[Enlace del video](https://youtu.be/UDbjgP1GyrI)

>**Despliegue del Mobile**

Para el despliegue de la aplicación móvil, se generó el archivo APK utilizando Flutter. Esto se logró mediante el siguiente comando:

```bash
flutter build apk --release
```
Posteriormente, se realizó la carga del APK en una plataforma de distribución para facilitar las pruebas internas. **Firebase App Distribution**

Finalmente, se verificó su correcto funcionamiento en distintos dispositivos Android con el fin de asegurar la **estabilidad**, **compatibilidad** y **usabilidad** del APK generado.

Este despliegue permitió a los usuarios evaluar las funcionalidades implementadas durante el Sprint, facilitando la **retroalimentación temprana** para futuras iteraciones y asegurando una **experiencia fluida** antes de su publicación oficial.

![Imagen de WhatsApp 2025-06-19 a las 22 38 36_ee83ce24](https://github.com/user-attachments/assets/e102840b-4ae3-47d2-bdc6-74f68dc8febc)

![Imagen de WhatsApp 2025-06-19 a las 22 38 54_9e29d9ee](https://github.com/user-attachments/assets/25d3c782-9102-47a0-ab15-4aeb012f2281)

![Imagen de WhatsApp 2025-06-19 a las 22 40 12_6e97f421](https://github.com/user-attachments/assets/0d4b2b4f-aa55-43c9-b206-b451c01e2538)

Link de landing page: https://chemtrack-grupo4.github.io/Landing-Page/

Link de web application: https://chemtrack-app.netlify.app/services

Link del mobile application: https://drive.google.com/file/d/1Zb7HNpkLBJKW9ON0I5ydz33bGrYA59-D/view?usp=drive_link

Link de backend: https://chemtrack-b4dybhf0g7asevgk.canadacentral-01.azurewebsites.net/swagger-ui/index.html#/

Link de IoT: https://wokwi.com/projects/434116969269344257


#### 6.2.1.9. Team Collaboration Insights during Sprint

>**Pulse**

**Frontend**

![image](https://github.com/user-attachments/assets/39d31df0-be02-4f36-ab3e-7dbabce2ea2e)

**Backend**

![image](https://github.com/user-attachments/assets/5a92a8e8-8461-4c02-958c-e1759071afb9)


**Mobile**

![image](https://github.com/user-attachments/assets/aadec403-6240-41b9-94b3-0be255777759)


>**Network**

**Frontend**

![image](https://github.com/user-attachments/assets/81f0c621-67a9-4a43-9a99-d68c658aea6e)

**Backend**

![image](https://github.com/user-attachments/assets/02fb1b6c-b316-404b-9b58-68c0b7cb3ff1)

**Mobile**

![image](https://github.com/user-attachments/assets/81f0c621-67a9-4a43-9a99-d68c658aea6e)


>**Contributors**

**Frontend**

![image](https://github.com/user-attachments/assets/06d7cf2c-585b-4801-ac55-a7509aa09928)

**Backend**

![image](https://github.com/user-attachments/assets/30b9cfdd-d2b0-4fb3-9c34-b22eae6ee4e7)

**Mobile**

![image](https://github.com/user-attachments/assets/c335ebe4-27c9-47d2-b7e6-e36ab04ad0f3)


### 6.2.3. Sprint 3
#### 6.2.3.1. Sprint Planning 3


| Sprint #                         | 3                                                                                                                                                                           |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**   |                                                                                                                                                                             |
| Date                             | 2025 - 07 - 06                                                                                                                                                     |
| Time                             | 06:00 AM                                                                                                                                                                     |
| Location                         | Virtual via Discord                                                                                                                                                          |
| Prepared By                      | Barrial Marin, Sharon Antuanet Ivet                                                                                                                                          |
| Attendees (to planning meeting)  | Camila Amaro, Sharon Barrial, Andrea García, Fabrizzio Laguerre, Josue Bustamante, Niurka Huarcaya, Josue Hidalgo                                                            |
| Sprint 3 - Review Summary        | Durante el Sprint 2, el equipo completó con éxito todas las tareas planificadas. Las tareas  implementadas incluyen todas las tareas core del sistema.     |
| Sprint 3 - Retrospective Summary | **Aspectos positivos** <br> - El equipo logró completar la mayoría de tareas conforme a los tiempos estimados, manteniendo una buena organización del trabajo.<br> - La distribución de tareas entre plataformas (Web, Mobile, IoT, Edge y Backend) permitió avanzar en paralelo y cumplir con funcionalidades clave del sistema.<br>**Áreas de mejora**<br> - La integración entre frontend, mobile y backend evidenció algunos retrasos por falta de endpoints definidos previamente.<br>**Acciones a implementar**<br> - Definir endpoints con mayor anticipación en el backlog técnico antes de asignar tareas dependientes.<br> - Establecer una checklist de documentación por módulo (mockup, API, lógica de validación) para agilizar el entendimiento del equipo.                                                                                                                                            |
| **Sprint Goal & User Stories**   |                                                                                                                                                                              |
| Sprint 3 Goal                    | El objetivo de este Sprint fue implementar funcionalidades complementarias para completar las operaciones claves del sistema relacionadas en la versión web como móvil, backend, edge e IoT.<br>**Logros del sprint** <br> - Monitoreo a tiempo real de mitigación de riesgos. <br> - Implementación del historial de incidentes para usuarios y transportistas. <br> - Publicación y filtrado de solicitudes de transporte desde la web y app móvil.<br> - Control y alertas por exceso de tiempo de conducción integrados en sensores IoT.         |
| Sprint 3 - Velocity              | El equipo puede aceptar 37 Story Points                                                                                                                                      |
| Sprint 3 - Story Points          | La suma de los Story Points de los User Stories que se atenderá es 37 Story Points                                                                 |

#### 6.2.3.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Landing Page <br> Features Leader (L)/Collaborator (C) | Frontend Web - Mobile <br> Features Leader (L)/Collaborator (C)  | Backend <br> Features Leader (L)/Collaborator (C) | IoT <br> Features Leader (L)/Collaborator (C) |
|----|-----|-----|----|----|----|
|Camila Amaro | CamiAm404 | L | C | C | C |
|Sharon Barrial | SharonBarrial | C | C | C | L |
|Andrea García | Armix18 | C | C | C | C |
|Fabrizzio Laguerre | UwUInspector | C | C | C | C |
|Josue Hidalgo | Kabudence | C | L | C | C |
|Niurka Huarcaya| NLH18 | C | C | L | C |

#### 6.2.3.3. Sprint Backlog 3

Mejoras de Frontend (web y mobile) e implementación del Backend, IoT y Edge acorde con las User Stories para la entrega del producto final.

<table>
<tbody>
    <tr>
        <th valign="top">Sprint 3</th>
        <th colspan="7" valign="top"> Sprint: Implementar mejoras de la web, backend, edge e IoT para el prototipo final </th>
    </tr>
    <tr>
        <td colspan="2" valign="top">User Story</td>
        <td colspan="6" valign="top">Work-Item / Task</td>
    </tr>
    <tr>
        <td valign="top">Id</td>
        <td valign="top">Title</td>
        <td valign="top">Id</td>
        <td valign="top">Title</td>
        <td valign="top">Description</td>
        <td valign="top">Estimation (Hours)</td>
        <td valign="top">Assigned To</td><td valign="top"><p dir="auto">Status </p><p dir="auto">(To-do/In Process/To Review /Done)</p></td>
    </tr>
    <tr>    
        <td rowspan="5" valign="top">US03</td>
        <td rowspan="5" valign="top"> Verificación de Seguimiento de transporte a tiempo real</td>
        <td valign="top">T01</td>
        <td valign="top">Configuración del backend</td>
        <td valign="top">Crear endpoints y lógica para generar, almacenar y enviar los datos del sensor GPS</td>
        <td valign="top">4</td>
        <td valign="top">Josue Hidalgo</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T02</td>
    <td valign="top">Integración backend-frontend</td>
    <td valign="top">Consumir la API de sensor de GPS desde para mostrar los datos al usuario.</td>
    <td valign="top">5</td>
    <td valign="top">Fabrizzio Laguerre</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T03</td>
    <td valign="top">Vista de mapa con el seguimiento de transporte</td>
    <td valign="top">Desarrollar la visualización de mapa que refleje en tiempo real el movimiento del transporte.</td>
    <td valign="top">6</td>
    <td valign="top">Niurka Huarcaya</td>
    <td valign="top">In Progress</td>
</tr>
<tr>
    <td valign="top">T04</td>
    <td valign="top">Sensor GPS para el seguimiento del transporte IoT </td>
    <td valign="top">Consumir y mostrar los datos generados por el sensor GPS en el frontend para seguimiento IoT.</td>
    <td valign="top">4</td>
    <td valign="top">Fabrizzio Laguerre </td>
    <td valign="top">In Progress</td>
</tr>
<tr>
    <td valign="top">T05</td>
    <td valign="top">API de gps para el seguimiento a tiempo real del transporte</td>
    <td valign="top">Desplegar una API que permita consultar la ubicación actual del transporte en tiempo real.</td>
    <td valign="top">5</td>
    <td valign="top">Sharon Barrial</td>
    <td valign="top">In Progress</td>
</tr>
    <tr>
        <td rowspan="2" valign="top">US12</td>
        <td rowspan="2" valign="top"> Visualizaciónde transportistas disponibles</td>
        <td valign="top">T11</td>
    <td valign="top">Configuración del backend</td>
    <td valign="top">Crear la lógica necesaria para mostrar rutas activas y alertas en el mapa desde el backend.</td>
    <td valign="top">6</td>
    <td valign="top">Josue Hidalgo  </td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T12</td>
    <td valign="top">Integración backend-frontend</td>
    <td valign="top">Integrar la funcionalidad para mostrar rutas seguras.</td>
    <td valign="top">4</td>
    <td valign="top">Andrea Garcia</td>
    <td valign="top">In progress</td>
</tr>
    <tr>
        <td rowspan="1" valign="top">US10</td>
        <td rowspan="1" valign="top"> Actualización de Estado del Transporte    </td>
        <td valign="top">T13</td>
        <td valign="top">Visualización de actualización del estado</td>
        <td valign="top">Diseñar la vista web donde se mostrarán el estado de actualizado de cada transporte.</td>
        <td valign="top">3</td>
        <td valign="top">Fabrizzio Laguerre </td>
        <td valign="top">Done</td>
</tr>
    <tr>
        <td rowspan="1" valign="top">US08</td>
        <td rowspan="1" valign="top"> Registro de Transportista de Combustibles Peligrosos  </td>
        <td valign="top">T09</td>
        <td valign="top">Implementar un botón que permita modificar el estado de habilitación de transportistas.</td>
        <td valign="top">Diseñar la vista web donde se mostrarán los transportistas disponibles.</td>
        <td valign="top">4</td>
        <td valign="top">Camila Amaro</td>
        <td valign="top">Done</td>
</tr>
<tr>
        <td rowspan="2" valign="top">TS01</td>
        <td rowspan="2" valign="top">Implementación de Monitoreo del Vehículo</td>
        <td valign="top">T03</td>
        <td valign="top">Configuración del backend</td>
        <td valign="top">Crear endpoints para recibir y procesar datos del GPS del vehículo en tiempo real.</td>
        <td valign="top">6</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T04</td>
    <td valign="top">Integración backend-frontend</td>
    <td valign="top">Mostrar al usuario la ubicación del vehículo consumiendo datos GPS desde el backend.</td>
    <td valign="top">4</td>
    <td valign="top">Fabrizzio Laguerre</td>
    <td valign="top">Done</td>
</tr>   
<tr>
        <td rowspan="3" valign="top">US03</td>
        <td rowspan="3" valign="top">Implementación de Monitoreo del Vehículo</td>
        <td valign="top">T06</td>
        <td valign="top">Mapa interactivo de rutas(Mobile)</td>
        <td valign="top">Desarrollar visualización de rutas en dispositivos móviles con datos GPS en tiempo real.</td>
        <td valign="top">5</td>
        <td valign="top">Andrea Garcia</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T07</td>
    <td valign="top">Sensor GPS por rutas(IoT)</td>
    <td valign="top">Integrar sensor GPS IoT que recoja la ubicación según rutas definidas</td>
    <td valign="top">6</td>
    <td valign="top">Camila Amaro</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T08</td>
    <td valign="top">API de rutas y alertas</td>
    <td valign="top">Crear API para enviar rutas y alertas capturadas desde sensores GPS al frontend.</td>
    <td valign="top">6</td>
    <td valign="top">Fabrizzio Laguerre</td>
    <td valign="top">Done</td>
</tr>
<tr>
        <td rowspan="2" valign="top">US12</td>
        <td rowspan="2" valign="top">Visualización de Transportitas disponibles</td>
        <td valign="top">T11</td>
        <td valign="top">Configuración del Backend</td>
        <td valign="top">Configurar lógica y endpoints para consultar transportistas disponibles según posición GPS.</td>
        <td valign="top">6</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T12</td>
    <td valign="top">Integración frontend-backend</td>
    <td valign="top">Mostrar transportistas disponibles en la interfaz usando datos GPS desde el backend.</td>
    <td valign="top">4</td>
    <td valign="top">Fabrizzio Laguerre</td>
    <td valign="top">Done</td>
</tr>
<tr>
        <td rowspan="3" valign="top">US10</td>
        <td rowspan="3" valign="top">Actualización del estado del transporte</td>
        <td valign="top">T14</td>
        <td valign="top">Visualización de actualización del estado</td>
        <td valign="top">Implementar vista para mostrar los cambios en el estado del transporte desde el backend.</td>
        <td valign="top">4</td>
        <td valign="top">Andrea Garcia</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T15</td>
    <td valign="top">Sensor de estado del vehiculo</td>
    <td valign="top">Integrar sensor que detecte y envíe actualizaciones del estado del vehículo.</td>
    <td valign="top">4</td>
    <td valign="top">Fabrizzio Laguerre</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T16</td>
    <td valign="top">API de estados del transporte</td>
    <td valign="top">Desarrollar API para consultar y visualizar el estado actual de cada unidad de transporte.</td>
    <td valign="top">5</td>
    <td valign="top">Sharon Barrial</td>
    <td valign="top">Done</td>
</tr>
<tr>
        <td rowspan="4" valign="top">US11</td>
        <td rowspan="4" valign="top">Publicación de Solicitudes de Transporte de Productos Peligrosos</td>
        <td valign="top">T17</td>
        <td valign="top">Búsqueda de transportistas</td>
        <td valign="top">Implementar lógica para filtrar y buscar transportistas disponibles para productos peligrosos.</td>
        <td valign="top">5</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T18</td>
    <td valign="top">Formulario de solicitud</td>
    <td valign="top">Crear formulario interactivo que registre solicitudes de transporte en el frontend.</td>
    <td valign="top">4</td>
    <td valign="top">Camila Amaro</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T19</td>
    <td valign="top">Validación de condiciones</td>
    <td valign="top">Validar los requisitos y condiciones de seguridad en la solicitud de transporte.</td>
    <td valign="top">6</td>
    <td valign="top">Sharon Barrial</td>
    <td valign="top">Done</td>
</tr>
<tr>
    <td valign="top">T20</td>
    <td valign="top">API de publicación de solicitudes</td>
    <td valign="top">Crear API que registre y publique las solicitudes en tiempo real en el sistema.</td>
    <td valign="top">5</td>
    <td valign="top">Fabrizzio Laguerre</td>
    <td valign="top">Done</td>
</tr>
<tr>
        <td rowspan="4" valign="top">US13</td>
        <td rowspan="4" valign="top">Acceso a reporte de incidentes</td>
        <td valign="top">T21</td>
        <td valign="top">Vista de historial e incidentes</td>
        <td valign="top">Diseñar vista que muestre historial de viajes e incidentes</td>
        <td valign="top">5</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
</tr>
    <tr>
        <td valign="top">T22</td>
        <td valign="top">Historial del transportista</td>
        <td valign="top">Mostrar información histórica sobre rutas, incidentes y desempeño del conductor.</td>
        <td valign="top">4</td>
        <td valign="top">Josue Hidalgo</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">T23</td>
        <td valign="top">Sincronización de logs</td>
        <td valign="top">Integrar la lógica para sincronizar registros del sistema con los eventos GPS..</td>
        <td valign="top">5</td>
        <td valign="top">Andrea Garcia</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">T24</td>
        <td valign="top">API del historial</td>
        <td valign="top">Crear API que permita consultar datos históricos y eventos del transportista.</td>
        <td valign="top">4</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
            <td rowspan="4" valign="top">US14</td>
            <td rowspan="4" valign="top">Control de tiempos de conducción de transporte</td>
            <td valign="top">T25</td>
            <td valign="top">Dashboard de tiempos</td>
            <td valign="top">Mostrar tiempos de conducción acumulados por viaje en un panel de control visual.</td>
            <td valign="top">5</td>
            <td valign="top">Sharon Barrial</td>
            <td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">T26</td>
        <td valign="top">Alertas de conducción</td>
        <td valign="top">Generar alertas si el conductor excede límites de tiempo establecidos.</td>
        <td valign="top">4</td>
        <td valign="top">Fabrizzio Laguerre</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">T27</td>
        <td valign="top">Sensor de tiempo de conducción</td>
        <td valign="top">Registrar la duración de los trayectos usando sensores GPS.</td>
        <td valign="top">5</td>
        <td valign="top">Josue Hidalgo</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">T28</td>
        <td valign="top">Control y lógica de alertas</td>
        <td valign="top">Desarrollar lógica para determinar cuándo emitir alertas de conducción excesiva.</td>
        <td valign="top">6</td>
        <td valign="top">Camila Amaro</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
            <td rowspan="2" valign="top">US15</td>
            <td rowspan="2" valign="top">Notificación de tiempo de conducción de transporte en exceso</td>
            <td valign="top">T31</td>
            <td valign="top">Configuración del backend de notificaciones</td>
            <td valign="top">Desarrollar backend que detecte exceso de tiempo y envíe alertas automáticas.</td>
            <td valign="top">6</td>
            <td valign="top">Fabrizio Laguerre</td>
            <td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">T32</td>
        <td valign="top">Integracion backend frontend</td>
        <td valign="top">Mostrar notificaciones al usuario en la aplicación cuando haya conducción en exceso.</td>
        <td valign="top">4</td>
        <td valign="top">Niurka Huarcaya</td>
        <td valign="top">Done</td>
    </tr>
    <tr>
            <td rowspan="1" valign="top">US16</td>
            <td rowspan="1" valign="top">Landing Page responsive</td>
            <td valign="top">T33</td>
            <td valign="top">Mejora del diseño responsive en dispositivos reales</td>
            <td valign="top">Probar y ajustar el diseño web para garantizar correcta visualización en múltiples dispositivos.</td>
            <td valign="top">2</td>
            <td valign="top">Sharon Barrial</td>
            <td valign="top">Done</td>
    </tr>
</tbody>
</table>

Se hizo uso de la herramienta Trello para gestionar las tareas de manera ágil y colaborativa tanto para este sprint como losque vienen en las próximas iteracciones. Como resultado se obtuvo 33 tasks para el presente sprint.

![image](https://github.com/user-attachments/assets/02a33094-d734-4709-804b-2441ea9695d1)

[Enlace del Trello](https://trello.com/invite/b/681fc71a5692939678facc66/ATTIc15614080cece153cca3c2bae0cd3505CFC7F6B0/chemtrack)

#### 6.2.3.4. Development Evidence for Sprint Review

Se presentan los commits realizados en el repositorio de GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.

- Repositorio Landing Page: https://github.com/Chemtrack-Grupo4/Landing-Page 

<br>

- Repositorio Frontend: https://github.com/Chemtrack-Grupo4/chemtrack-webapp

<br>

- Repositorio Backend: https://github.com/Chemtrack-Grupo4/chemtrack-backend
  
<br>

- Repositorio Mobile: https://github.com/Chemtrack-Grupo4/chemtrack-mobileapp
  
<br>

- Repositorio IoT: https://github.com/Chemtrack-Grupo4/chemtrack-embedded
  
<br>

- Repositorio Edge: https://github.com/Chemtrack-Grupo4/chemtrack-edge
  
<br>

<table  align="left" border="1" width="100%">
    <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Commited on (Date)</th>
    </tr>
    <tr>
        <td>Landing Page</td>
        <td>develop</td>
        <td>c833922</td>
        <td>docs: update documentation</td>
        <td>-</td>
        <td>06/07/25</td>
    </tr>
    <tr>
    <td rowspan=5>Web app</td>
    <td>feature/alerts</td>
    <td>eaf23bc</td>
    <td>feat(alerts): add real-time alert system</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/dashboard-visuals</td>
    <td>f0c1239</td>
    <td>feat(dashboard): enhance UI with charts and graphs</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/language-support</td>
    <td>c3a789d</td>
    <td>feat(i18n): add multi-language support</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/login-oauth</td>
    <td>ab19f88</td>
    <td>feat(auth): integrate OAuth login (Google, GitHub)</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/theme-switch</td>
    <td>d47cfa2</td>
    <td>feat(ui): implement light/dark theme toggle</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>

<tr>
    <td rowspan=5>Mobile</td>
    <td>feature/alerts-ui</td>
    <td>9dcab01</td>
    <td>feat(alerts): create alerts modal for notifications</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/dashboard-viz</td>
    <td>fd23b76</td>
    <td>feat(dashboard): display sensor data in charts</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/i18n-support</td>
    <td>a1cc229</td>
    <td>feat(i18n): implement multilingual support</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/social-login</td>
    <td>4fe9b3c</td>
    <td>feat(auth): enable social media authentication</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/theme-toggle</td>
    <td>c0d88a1</td>
    <td>feat(ui): switch between dark/light themes</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>

<tr>
    <td rowspan=5>Backend</td>
    <td>feature/alerts-api</td>
    <td>5e1c788</td>
    <td>feat(alerts): implement real-time alert endpoint</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/dashboard-data</td>
    <td>b2d9231</td>
    <td>feat(dashboard): expose analytics data via API</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/i18n-config</td>
    <td>ac7d23b</td>
    <td>feat(i18n): serve translated content via API</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/oauth-login</td>
    <td>d913fad</td>
    <td>feat(auth): support OAuth token handling</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/user-preferences</td>
    <td>33fc812</td>
    <td>feat(user): add theme and language preferences</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>

<tr>
    <td rowspan=5>IoT</td>
    <td>feature/alert-led</td>
    <td>e1caa12</td>
    <td>feat(hardware): trigger LED on alert events</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/sensor-stats</td>
    <td>b30afcc</td>
    <td>feat(sensors): send statistical summaries</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/lang-commands</td>
    <td>9ae77b4</td>
    <td>feat(i18n): support multilingual voice commands</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/auth-module</td>
    <td>4c3f8c9</td>
    <td>feat(auth): device authentication with token</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/display-mode</td>
    <td>a9b0233</td>
    <td>feat(ui): toggle LCD theme based on time</td>
    <td>-</td>
    <td>06/07/25</td>
</tr>

<tr>
    <td rowspan=3>Edge</td>
    <td>feature/alert-processing</td>
    <td>bdc1342</td>
    <td>feat(edge): handle critical alerts locally</td>
    <td>Added logic to detect thresholds and trigger buzzer without backend.</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/local-dashboard</td>
    <td>d41c99e</td>
    <td>feat(ui): serve local dashboard on port 8080</td>
    <td>Lightweight web server to display local sensor data.</td>
    <td>06/07/25</td>
</tr>
<tr>
    <td>feature/offline-mode</td>
    <td>fa9231b</td>
    <td>feat(edge): queue data during network outages</td>
    <td>Buffers MQTT messages and sends when connection is restored.</td>
    <td>06/07/25</td>
</tr>


</table>

#### 6.2.3.5. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-1.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-2.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-3.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-4.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-5.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-6.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-7.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-8.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-9.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-10.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-11.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-12.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2959347 | Acceptance-test-13.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | 2d887b9 | Acceptance-test-14.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-15.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b99 | Acceptance-test-16.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | bfc7b98 | Acceptance-test-17.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | cxy7b63 | Acceptance-test-18.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | ccc7b45 | Acceptance-test-19.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | e3m7b62 | Acceptance-test-20.feature  | - | 06/07/2025 |
| chemtrack-testing | test/UserStories | jgx7333 | Acceptance-test-21.feature  | - | 06/07/2025 |


Link de repositorio: https://github.com/Chemtrack-Grupo4/chemtrack-testing

#### 6.2.3.6. Execution Evidence for Sprint Review

En el Sprint 3 se alcanzó a desarrollar la última versión de la landing page,  Frontend del Web Application, Mobile, Backend e IoT de la aplicación. A continuación se muestra lo realizado:

>**Landing page**

- Versión Final
- Estado: En producción activa
- Se accede a la página web - Frontend, desde la opción *Aplicación* cta.

<a href="https://chemtrack-grupo4.github.io/Landing-Page/"><img src="https://i.ibb.co/zVDsx58N/Captura-de-pantalla-2025-05-14-003027.png" alt="Landing page" border="0"></a>

Demostración del contenido de Landing Page y su conexión con la página web desde el botón *Call-To-Action*.
![image](https://github.com/user-attachments/assets/9e48c805-dd5f-45f9-a23c-fd81e63e2de6)

[Enlace de video](https://youtu.be/iZ1wX6IyvGI)

<br>

>**Frontend**

- Versión Final
- Estado: En producción activa

![image](https://github.com/user-attachments/assets/c81b1bf8-9ce5-450e-bdb9-995c629f16f8)
![Imagen de WhatsApp 2025-06-06 a las 21 01 36_aca33b7f](https://github.com/user-attachments/assets/cd16edf9-ba5b-48a0-bdd9-cdfc1fab861b)
![image](https://github.com/user-attachments/assets/4ce06d6c-c59c-4360-91d6-56066d9a9c23)
![image](https://github.com/user-attachments/assets/ba75656d-0b2b-4138-907f-8fa107e8c399)
![image](https://github.com/user-attachments/assets/f9631fb8-8240-4173-a67c-2a3e5bd76886)

<br>

>**Backend**

- Versión Inicial
- Estado: En producción activa

Endpoints
![image](https://github.com/user-attachments/assets/3aa0988d-2054-4960-9db8-e3c62fb7f8ae)
![image](https://github.com/user-attachments/assets/9811ceeb-bb0d-4c7d-a965-38bc989e95db)

Demostración del funcionamiento de los endpoints a través de postman
![Imagen de WhatsApp 2025-06-19 a las 22 59 45_7d5ac168](https://github.com/user-attachments/assets/d652b958-1980-42f1-85d8-3d83d9e86d3c)

[Enlace del video](https://youtu.be/UDbjgP1GyrI)

<br>

>**Mobile**
- Versión Final
- Estado: Desplegado en apk
![image](https://github.com/user-attachments/assets/38aa8b3a-1d0a-4bc6-9b7d-71d6ffb3f390)

[Enlace del video](https://youtu.be/Tnb-feMw1N8)

<br>

>**IoT Embedded**
- Versión Final
- Estado: Simulado en Wokwi e integrado con broker MQTT

![Imagen de WhatsApp 2025-06-18 a las 21 53 50_c4c6f0c1](https://github.com/user-attachments/assets/f3b9f7b5-c4df-4104-903a-b7897d88e73a)
[Enlace de demostración de su funcionamiento](https://youtu.be/mHsDo7mMxjk?si=jYEzVz3hB8E_QJCo)

>**Edge**
- Versión Final
- Estado: Pruebas de entorno local

Se trabajó bajo el paradigma de Edge Computing, diseñando su arquitectura y validando su lógica a través de pruebas locales.

Estas pruebas permitieron verificar:

- La correcta suscripción y publicación de mensajes MQTT.

- La recepción y procesamiento de eventos generados por dispositivos simulados.

- La integración con servicios REST para el reenvío de información.

- El comportamiento general del componente ante posibles eventos en tiempo real.

El enfoque se centró en simular el comportamiento de un nodo Edge sin necesidad de realizar un despliegue completo, cumpliendo con los objetivos funcionales del proyecto y las indicaciones académicas.

![image](https://github.com/user-attachments/assets/c715a7e0-b8bf-4fc1-8d42-ae2e549313d5)
![Imagen de WhatsApp 2025-06-19 a las 08 47 13_da59ddfe](https://github.com/user-attachments/assets/d1d4f105-9631-4dd1-82cc-a4255e09c334)
![Imagen de WhatsApp 2025-06-19 a las 08 49 45_664c14b8](https://github.com/user-attachments/assets/eae9c537-12bf-4d1e-9665-23f3f560e07b)

Demostración de funcionamiento de edge y su comunicación con el embedded.

![image](https://github.com/user-attachments/assets/87bda626-4f78-4302-a082-356b6325a396)
[Enlace del video](https://youtu.be/mHsDo7mMxjk)

<br>

> **Demo de la comunicación y flujo de todos los artefactos requeridos y desarrollados a lo largo de este proyecto**

Esta demo muestra como todos los artefactos de nuestro prototipo final (embedded, edge, backend, frontend y mobile) se comunican mandando y recibiendo los datos de forma correcta.

![image](https://github.com/user-attachments/assets/808fe024-a4ef-4702-b84c-5d03abda5031)

[Enlace de video](https://youtu.be/8AKGtBELu74)

<br>

> **Demo de la comunicación del prototipo físico embendded para la recepción de sus datos en edge y backend**

Esta demo muestra como nuestro prototipo físico se comunica con el edge, a través del broker Active MQ y junto con el uso del protocolo MQTT para almacenarse en el backend.

![image](https://github.com/user-attachments/assets/c285f9d7-04c7-4723-b804-ae1ad8e5af22)

[Enlace de video](https://youtu.be/vl2Iv7xnhAs)


#### 6.2.3.7. Services Documentation Evidence for Sprint Review

Para el Sprint 3, se verificaron que los siguientes endpoints clave permitan gestionar usuarios, entregas, servicios, incidentes, rutas seguras, historial y publicaciones dentro del sistema. Cada endpoint cumple una función específica en la arquitectura del backend.

| Endpoint | Detalles |
| - | - | 
| /user-controller| En este endpoint se almacenan la información de los usuarios, tales como username, email, password, role, photo y token | 
| /deliveries | En este endpoint se almacenan las entregas que aun no tienen ligadas un incidente | 
| /services  | En este endpoint se almacenan los servicios realizados por parte de las empresas | 
| /incidents | En este endpoint se almacenan los incidentes registrados manualmente | 
| /sensors	 | 	Este endpoint gestiona la creación, consulta y envío de notificaciones de mantenimiento, nuevas solicitudes y alertas por tiempo de conducción. | 

>Sensors

![image](https://github.com/user-attachments/assets/91290394-3803-49fd-99da-e2f50a973e65)

Al hacer un post se muestra en la página web los sensores que están activados

![image](https://github.com/user-attachments/assets/7909b9a7-90f7-48d3-81c1-d98aec20efcc)

>Incidents

![image](https://github.com/user-attachments/assets/d39b9b08-f3ef-481e-a115-97c23c922255)

Visualización de Incidents en el mobile 

![Imagen de WhatsApp 2025-06-20 a las 18 04 12_de39af0b](https://github.com/user-attachments/assets/ebe1eac1-8a60-4cef-b6af-e62908f5baf4)


>Services

![image](https://github.com/user-attachments/assets/a4296f9c-cb99-47aa-802c-1feb6683278b)

Se muestra los servicios On-Going en la página web

![image](https://github.com/user-attachments/assets/a673b2f7-2695-42e3-a299-006171176a46)

Se muetsra los servicios On-Going en la app mobile

![Imagen de WhatsApp 2025-06-20 a las 18 02 37_6554115d](https://github.com/user-attachments/assets/1abd3326-5818-4282-b652-b5f4e27a5f74)


>Deliveries

![image](https://github.com/user-attachments/assets/6fbaa0b1-9c2a-4a5d-b07a-690c7f6f30a6)

Los servicios monitoreados en tiempo real

![image](https://github.com/user-attachments/assets/0c116d69-0ae2-4e24-bdcf-740b5789c602)

Los servicios a tiempo real visualizados en mobile

![Imagen de WhatsApp 2025-06-20 a las 18 03 01_abdef808](https://github.com/user-attachments/assets/109230bf-d1dd-4054-a871-3b0255c6c201)


Más detalles de los servicios en tiempo real

![image](https://github.com/user-attachments/assets/2a765605-1ee4-4e46-aa97-aaa23c643381)


Más detalle del deliveries vistos en mobile

![Imagen de WhatsApp 2025-06-20 a las 18 03 47_ccd2b56e](https://github.com/user-attachments/assets/f7427e13-3f42-4ca4-a89d-64b01afcde64)


>Auth controller & User controller

![image](https://github.com/user-attachments/assets/4c2e8574-5027-4a7e-8fb3-73cdbfbf6dfd)

Muestra de los empleados de acuerdo al usuario autenticado

![image](https://github.com/user-attachments/assets/9ae48dec-c055-4fc8-a08a-66b70bf44254)

#### 6.2.3.8. Software Deployment Evidence for Sprint Review

>**Despliegue de Landing Page** 

La Landing Page fue desplegada utilizando **GitHub Pages**, lo que permitió alojar el sitio de forma gratuita y accesible mediante una URL pública. Se configuró el repositorio con la rama correspondiente (`main` o `gh-pages`) y se habilitó la opción de GitHub Pages desde la configuración del repositorio para publicar el contenido estático. Esto facilitó compartir el proyecto con usuarios finales y stakeholders sin necesidad de servidores externos.

![github](https://github.com/user-attachments/assets/73bd7cc4-21c8-4b74-8825-5187511ba209)
[Enlace de video](https://youtu.be/iZ1wX6IyvGI)

>**Despliegue del Frontend**

Para la aplicación principal desarrollada en Angular, se utilizó **Netlify** como plataforma de despliegue debido a su integración continua y facilidad de configuración.

El proceso consistió en:

**Compilación del proyecto Angular**  
Se ejecutó el comando `ng build` desde la raíz del proyecto, generando los archivos estáticos dentro del directorio `dist/`.

**Configuración del archivo `netlify.toml`**  
Se creó el archivo de configuración `netlify.toml` con el objetivo de gestionar correctamente las rutas internas de Angular. Esto garantiza que las solicitudes de navegación directa a rutas definidas por Angular sean correctamente redirigidas.

**Carga del contenido en Netlify**  
Se seleccionó el subdirectorio correspondiente dentro de `dist/` (específicamente el que representa el nombre del proyecto) como carpeta de despliegue en Netlify.  
Al finalizar el proceso, se obtuvo el registro exitoso del despliegue.

![Imagen de WhatsApp 2025-06-20 a las 17 25 55_64fe3bb9](https://github.com/user-attachments/assets/0bd7cdc5-cf6d-459a-8fbc-b6a5c4c09c24)


De esta manera, el avance del **Sprint 3** quedó funcional y disponible públicamente para su evaluación.

![image](https://github.com/user-attachments/assets/a1e99f7f-b64f-43fc-9b08-a09f93a62f4d)

>**Despliegue del Backend**

**Configuración del repositorio**
   - Se aseguró que el repositorio de backend estuviera limpio y contuviera todos los archivos necesarios para el build.
   - Se definieron variables de entorno desde Railway para la conexión a servicios externos como la base de datos y MQTT.
  
![image](https://github.com/user-attachments/assets/fd7eda0a-4a91-4d17-9423-233721ffeaf9)

**Integración con Railway**
   - Se accedió a **Railway** y se creó un nuevo proyecto.
   - Se conectó el proyecto directamente al repositorio en GitHub, seleccionando la rama principal para el despliegue.
   - Azure detectó automáticamente el stack del proyecto e inició el proceso de construcción (**build**).

![image](https://github.com/user-attachments/assets/71854586-de95-47f1-95d6-3d7bbb7d692c)

**Despliegue automático**
   - Una vez completado el build, Azure desplegó el backend y proporcionó una URL pública accesible.
   - Se habilitó el monitoreo en tiempo real para verificar el estado del servicio.
   - En caso de errores o necesidad de debugging, Railway ofrece visualización de logs directamente desde el panel.

![image](https://github.com/user-attachments/assets/c785684f-f244-4fda-ac0d-f2789e486c8e)

Aquí se hace presente el video demostrando el funcionamiento del despliegue del backend haciendo uso de POSTMAN.

![image](https://github.com/user-attachments/assets/fc05e8af-9983-4ac9-a668-b7a00e4ddb01)


[Enlace del video](https://youtu.be/UDbjgP1GyrI)


>**Despliegue del Mobile**

Para el despliegue de la aplicación móvil, se generó el archivo APK utilizando Flutter. Esto se logró mediante el siguiente comando:

```bash
flutter build apk --release
```

![Imagen de WhatsApp 2025-06-19 a las 22 38 36_ee83ce24](https://github.com/user-attachments/assets/e102840b-4ae3-47d2-bdc6-74f68dc8febc)

![Imagen de WhatsApp 2025-06-19 a las 22 38 54_9e29d9ee](https://github.com/user-attachments/assets/25d3c782-9102-47a0-ab15-4aeb012f2281)

![Imagen de WhatsApp 2025-06-19 a las 22 40 12_6e97f421](https://github.com/user-attachments/assets/0d4b2b4f-aa55-43c9-b206-b451c01e2538)

Posteriormente, se realizó la carga del APK en una plataforma de distribución para facilitar las pruebas internas. **Firebase App Distribution**

![WhatsApp Image 2025-07-06 at 04 33 19_01cd0acc](https://github.com/user-attachments/assets/716deca3-3264-4db3-965f-8f606c24314c)

Finalmente, se verificó su correcto funcionamiento en distintos dispositivos Android con el fin de asegurar la **estabilidad**, **compatibilidad** y **usabilidad** del APK generado.

![WhatsApp Image 2025-07-06 at 04 33 19_454dfcb3](https://github.com/user-attachments/assets/f2dea5fc-af47-4135-a6a9-17a253dd12d4)

Este despliegue permitió a los usuarios evaluar las funcionalidades implementadas durante el Sprint, facilitando la **retroalimentación temprana** para futuras iteraciones y asegurando una **experiencia fluida** antes de su publicación oficial.

![WhatsApp Image 2025-07-06 at 04 33 19_a39014b7](https://github.com/user-attachments/assets/64ca8414-a14c-4bd6-8075-920b4d8c6801)

![WhatsApp Image 2025-07-06 at 04 35 40_f41ef473](https://github.com/user-attachments/assets/8144f604-38ad-43b0-8a74-a7658a6d78f9)

Es así como se muestra el despligue de cada uno de los artefactos que lo requiere.

Link de landing page: https://chemtrack-grupo4.github.io/Landing-Page/

Link de web application: https://chemtrack-app.netlify.app/services

Link del mobile application: https://appdistribution.firebase.google.com/accept/c8ccff066da71ba3db942648

Link de backend: https://chemtrack-backend-production.up.railway.app/api/safeflow/v1/records

Link de IoT: https://wokwi.com/projects/434116969269344257


#### 6.2.3.9. Team Collaboration Insights During Sprint

>**Pulse**

**Frontend**

![image](https://github.com/user-attachments/assets/71fd2db4-855d-4b21-9e5d-951a915ad01a)

**Backend**

![image](https://github.com/user-attachments/assets/71fd2db4-855d-4b21-9e5d-951a915ad01a)

**Mobile**

![image](https://github.com/user-attachments/assets/b05cce36-20fc-49ab-849a-b029ca136f14)

>**Network**

**Frontend**

![image](https://github.com/user-attachments/assets/4cd541d8-64da-45f6-ab6d-d8bf84d24721)

**Backend**

![image](https://github.com/user-attachments/assets/8f896d13-a0dd-44cf-9d87-02b47cdf26d8)

**Mobile**

![image](https://github.com/user-attachments/assets/b4c6b016-25f8-4fcc-8629-1048329480f1)


>**Contributors**

**Frontend**

![image](https://github.com/user-attachments/assets/cbc4b40b-6454-4aa2-8e89-bac5ca5ff19f)

**Backend**

![image](https://github.com/user-attachments/assets/61874ad0-5ba3-43ed-b0d0-5aec0cd745d6)

**Mobile**

![image](https://github.com/user-attachments/assets/fba34660-9cbd-48ed-888c-052a1f16fa3c)

## 6.3. Validation Interviews
### 6.3.1. Diseño de Entrevistas
A continuación, se diseñaron entrevistas dirigidas a los dos segmentos objetivos definidos para el proyecto. Las preguntas fueron elaboradas con el objetivo de identificar fortalezas y oportunidades de mejora en la plataforma teniendo en cuenta aspectos como experiencia de uso, percepción del diseño y utilidad de la información. Cabe mencionar que las preguntas de introducción no están incluidas en esta lista; sin embargo, se realizarán al inicio de cada entrevista.

**Segmento objetivo: Transportistas**

El objetivo de las preguntas del segmento objetivo de los transportistas es recopilar información valiosa desde su experiencia directa cuando interactúan con la plataforma ChemTrack. A través de sus respuestas, buscamos evaluar la usabilidad, claridad, rapidez de navegación y efectividad de las funcionalidades móviles y web para el monitoreo de servicios y el registro de incidentes.

**Alcances de la demostración:**

- Landing Page
- Principales tareas en la app movil
- Principales secciones de la app web

**Preguntas prinicipales**

- ¿Consideras que el landing page ofrece toda la información necesaria para entender el propósito y funcionalidades ofrecidas por la aplicación para obtener información de sensores y registrar incidentes?

- ¿Resulta agradable a la vista la manera en la que la información está presentada?

- ¿Qué dispositivo utilizaste para acceder al Landing Page? ¿La página presenta algún tipo de inconveniente de diseño que impida navegar de manera fluida?

- Con respecto a la aplicación móvil, ¿consideras que el proceso para agregar un nuevo servicio e incidente es intuitivo?

- ¿La información de los incidentes y servicios que se visualiza es suficiente? ¿Qué otros datos te gustaría visualizar?

- ¿Qué opinas acerca de la distribución de secciones en la aplicación móvil? ¿Agregarías más secciones? ¿Cuáles?

- ¿Cómo describirías nuestra aplicación móvil en pocas palabras?

- De todas las características evidenciadas en la aplicación móvil para agregar y registrar incidentes, ¿cuál crees que debería mejorarse? ¿Por qué?

- ¿Qué nuevas funcionalidades relacionadas al monitoreo de sensores o al registro de incidentes consideras útiles en el contexto del transporte de combustibles peligrosos?

- ¿Consideras que el diseño de la aplicación móvil es adecuado?

- ¿La información de monitoreo de sensores es clara y útil para la toma de decisiones? ¿Qué detalles adicionales te gustaría ver?

- ¿La navegación para acceder a diferentes secciones (sensores, incidentes, reportes) te resultó fácil y rápida?

- ¿Consideras que la aplicación web responde de manera adecuada y rápida a tus acciones (ej. carga de datos, actualización de información)?

- ¿Sientes que la aplicación ayuda a prevenir o manejar mejor los incidentes relacionados con el transporte? ¿De qué manera?

**Segmento objetivo: Empresas de transporte de productos peligrosos**

Las preguntas dirigidas a las empresas de transporte de productos peligrosos tienen como finalidad entender el valor estratégico que aporta la plataforma ChemTrack a la gestión de operaciones, prevención de riesgos y toma de decisiones. A través de su visión administrativa y gerencial, buscamos validar si la información ofrecida por el sistema es suficiente, si la plataforma contribuye al control efectivo de incidentes y procesos, y qué funcionalidades adicionales podrían potenciar su uso como herramienta de monitoreo y prevención de riesgos.

**Alcances de la demostración:**

- Landing Page
- Principales tareas en la app movil
- Principales secciones de la app web

**Preguntas prinicipales**

- ¿Consideras atractiva la manera en la que el producto ChemTrack está promocionado en la Landing Page?

- ¿Consideras que el landing page ofrece toda la información necesaria para tener un entendimiento adecuado del funcionamiento, propósito y funcionalidades ofrecidas?

- ¿Resulta agradable a la vista la manera en la que la información está presentada?

- ¿Qué dispositivo utilizaste para acceder al Landing Page? ¿La página presenta algún tipo de inconveniente de diseño que impida navegar de manera fluida?

- Del 1 al 10, ¿cómo calificarías el diseño de la Landing Page?

- Con respecto a la aplicación móvil, ¿consideras que es complicado encontrar un servicio realizado?

- ¿Los detalles de los servicios y de los incidentes son adecuados en las secciones? ¿Qué otros apartados te gustaría visualizar?

- ¿Qué características específicas deseas que agreguemos a la aplicación móvil?

- De todas las características evidenciadas en la aplicación móvil, ¿cuál crees que debería mejorarse? ¿Por qué?

- ¿Consideras que el diseño es adecuado?

- ¿La interfaz web te parece intuitiva y rápida de usar? ¿Qué mejorarías?
  
- ¿Te parece útil la visualización de empleados dentro de la plataforma? ¿La información mostrada es suficiente para tus necesidades?
  
- ¿La aplicación te permite controlar y monitorear fácilmente los procesos que gestionas? ¿Qué funcionalidades te gustaría que se añadieran para mejorar el control?
  
- ¿Qué tan fácil te resulta buscar la información que requieres dentro de la plataforma?

### 6.3.1. Registro de Entrevistas

**Segmento objetivo: Empresas de transporte de productos peligrosos**

***Primera Entrevista:***

Nombres y apellidos: Astrid Boronda

Edad: 20

Inicio: 0:00

Fin: 7:37

Duración: 7:37

Link: https://youtu.be/DdtaxQZaJT0

![Imagen de WhatsApp 2025-07-06 a las 04 31 04_a191dfc4](https://github.com/user-attachments/assets/cc4485d2-ae16-4164-93a8-2e1765bd6de4)

Resumen:

- Astrid trabaja en una empresa de transporte. Ella nos comentó acerca del diseño de la landing page, resaltando que el diseño le parece correcto, pero podría mejorar en el tamaño de la barra de navegación. En cuanto a la información, menciona que ofrece la información de los servicios que ofrece Chemtrack junto a testimonios, lo cual incremeta la confianza frente a los usuarios. Sobre la aplicación móvil, se requieren mejoras en el diseño, especificamente los colores que se presentan. La navegación es intuitiva tanto en la aplicación móvil como en la web, pero faltan más detalles o datos relacionados a los servicios, incidentes y empleados.

***Segunda Entrevista:***

Nombres y apellidos: Nataly Rodriguez

Edad: 26

Inicio: 7:37

Fin: 13:41

Duración: 06:04

Link: https://youtu.be/DyXvV2IVVvA

![Imagen de WhatsApp 2025-07-06 a las 04 30 46_01447af4](https://github.com/user-attachments/assets/abee3d30-75d3-494d-bd5d-5ab9237947bd)

Resumen:

- Se entrevistó a Nataly de 26 años, trabajadora en una empresa de transporte. Según sus respuestas se puede percibir una respuesta mayormente positiva sobre Chemtrack. La Landing Page es vista como clara, profesional y confiable, aunque se sugiere complementar con un video explicativo y mejorar algunos elementos para dispositivos móviles. En cuanto a la aplicación móvil, se destaca su facilidad de uso, pero se recomienda implementar filtros y buscadores para localizar servicios e incidentes más eficientemente, así como ampliar la información mostrada. El diseño general es considerado adecuado y moderno. Respecto a la interfaz web, se valora su intuición y rapidez, aunque se sugiere un sistema de búsqueda más avanzado y un historial de acciones de los empleados. Finalmente, se propone agregar reportes automáticos y control de mantenimiento preventivo para mejorar la gestión integral.

**Segmento objetivo: Transportistas**

***Primera Entrevista:***

Nombre: Ariana Rimache

Edad: 21

Inicio: 13:41

Fin: 18:29

Duración: 5:48

Link: https://youtu.be/wAN-fKC7AGQ

![Imagen de WhatsApp 2025-07-06 a las 04 45 14_575ffb12](https://github.com/user-attachments/assets/46cbcc9a-d028-4b1e-b282-ffe357372b76)

Resumen:

- Se entrevistó a Ariana, quien ha tenido una experiencia positiva con ChemTrack. Consideró que la Landing Page es clara, bien presentada y fácil de navegar, aunque sugirió mejorar la visualización en móviles. Destacó que la app móvil es intuitiva y funcional, aunque recomendó incluir filtros en el historial de incidentes y nuevas secciones como alertas en tiempo real o protocolos de seguridad. Propuso funcionalidades como notificaciones automáticas, registro de incidentes por sensores y mapa en tiempo real. La información de sensores fue calificada como clara, y la versión web como rápida y estable. En conjunto, señaló que ChemTrack ayuda a prevenir y gestionar incidentes de forma eficaz.

***Segunda Entrevista:***

Nombre: Karina Ramirez

Edad: 36

Inicio: 18:30

Fin: 23:59

Duración: 5:29

Link: https://youtu.be/N6JERwsmU-o

![Imagen de WhatsApp 2025-07-06 a las 04 55 46_fc463411](https://github.com/user-attachments/assets/68080a56-1cc5-4b55-be52-3972a984505d)

Resumen:

- Hemos entrevistado a Lisanne, quien mencionó que actualmente solo cuentan con un sistema de GPS para rastrear los vehículos y proporcionan un seguro de vida a los transportistas, pero no implementan medidas adicionales específicas para protegerlos. La capacitación que se ofrece es básica, enfocándose en evitar que la carga esté expuesta a fuentes de calor o movimientos bruscos, y se prefiere contratar conductores con experiencia. Además del GPS y los teléfonos entregados por la empresa, no utilizan tecnologías adicionales para garantizar la seguridad de las cargas.

### 6.3.1.1 Análisis de Entrevistas de Validación
Durante el proceso de validación del sistema, se realizaron entrevistas a cuatro personas con experiencia en el sector transporte. El objetivo fue conocer su percepción sobre el diseño, funcionalidad y utilidad de la plataforma web, aplicación móvil y otros componentes relacionados con el sistema.

1. Landing Page
- La mayoría de entrevistados coincidió en que la página principal presenta un diseño profesional, claro y genera confianza en el usuario. Sin embargo, se identificaron oportunidades de mejora, tales como el ajuste del tamaño de la barra de navegación, una mejor adaptación para dispositivos móviles y la inclusión de elementos audiovisuales explicativos.

2. Aplicación Móvil
- Se valoró positivamente la facilidad de uso y la navegación intuitiva de la aplicación. No obstante, se sugirió realizar mejoras en la presentación visual, como el uso de una paleta de colores más adecuada. Asimismo, se recomendó implementar funcionalidades adicionales como filtros, buscadores, visualización más detallada del historial de incidentes y secciones para alertas o notificaciones automáticas.

3. Plataforma Web
- La interfaz web fue calificada como rápida, estable e intuitiva. Las recomendaciones se centraron en mejorar el sistema de búsqueda, incluir un historial de acciones de los empleados y desarrollar funcionalidades orientadas a la generación de reportes automáticos y control de mantenimiento preventivo.

4. Contexto de Seguridad y Tecnología en Empresas
- Una de las entrevistadas compartió la experiencia de su empresa, que actualmente solo utiliza herramientas básicas como GPS y teléfonos para el seguimiento de vehículos, sin la implementación de tecnologías complementarias que garanticen mayor seguridad. Esta observación permite evidenciar la necesidad real de soluciones más completas como las que ofrece el sistema desarrollado.

Conclusión y Métrica Final
- En general, los participantes manifestaron una percepción positiva sobre el sistema, destacando su usabilidad, claridad y potencial para optimizar procesos de monitoreo y prevención de incidentes en el sector transporte. Sin embargo, todos coincidieron en aspectos específicos que podrían ser mejorados, tanto en términos de diseño visual como en funcionalidades adicionales.

- Métrica final: El 75% de los entrevistados calificó el sistema como funcional, intuitivo y útil, pero también identificó al menos una área de mejora concreta relacionada al diseño o a la información disponible. Esta métrica sugiere un alto nivel de aceptación del producto con un margen claro para optimización, lo cual constituye una base sólida para futuras iteraciones.



### 6.3.2. Evaluaciones según heurísticas

#### <div align="center">UX Heuristics & Principles Evaluation</div>

##### <div align="center">Usability – Inclusive Design – Information Architecture</div>

<b> Carrera: </b> Ingeniería de Software  
<b> Curso: </b> Desarrollo de Soluciones IoT  
<b> Sección: </b> 2939 

<b> <em> SITE O APP A EVALUAR: </em> </b> <br>
Chemtrack  

<b> <em> TAREAS A EVALUAR: </em> </b> <br>
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
- Web Application
   - Registro de un usuario nuevo
   - Inicio de sesión de usuario existente
   - Añadir nuevo servicio
   - Añadir nuevo delivery
   - Añadir nuevo incidente
   - Visualización de empleados
   - Visualización de detalles de deliveries
   - Visualización de monitoreo de sensores

- Mobile Application
   - Añadir nuevo servicio
   - Añadir nuevo incidente
   - Visualización de detalles de deliveries
   - Aceptar o rechazar deliveries
   - Búsqueda de servicios, deliveries e incidentes

No están incluidas en esta versión de la evaluación las siguientes tareas:

- Registro de usuario e inicio de sesión en aplicación móvil
- Gestión de notificaciones
- Opciones de ayuda y soporte

<b> <em> ESCALA DE SEVERIDAD: </em> </b> <br>
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

<table align="center" border="1" width="100%" style="text-align:center;">
    <tr>
        <th>
            <b>Nivel</b>
        </th>
        <th>
            Descripción
        </th>
    </tr>
    <tr>
        <td>
            <b>1</b>
        </td>
        <td align="left">
            Problema superficial: Puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a menos que exista disponibilidad de tiempo.
        </td>
    </tr>
    <tr>
        <td>
            <b>2</b>
        </td>
        <td align="left">
            Problema menor: Ocurre más frecuentemente o es un poco más difícil de superar para el usuario. Debería asignarse una prioridad baja para resolverlo en una futura versión.
        </td>
    </tr>
    <tr>
        <td>
            <b>3</b>
        </td>
        <td align="left">
            Problema mayor: Ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que sea corregido y debe asignársele una prioridad alta.
        </td>
    </tr>
    <tr>
        <td>
            <b>4</b>
        </td>
        <td align="left">
            Problema muy grave: Un error crítico que impide al usuario continuar utilizando la herramienta. Es imperativo que se corrija antes del lanzamiento.
        </td>
    </tr>
</table>

<b> <em> TABLA DE RESUMEN: </em> </b> <br>
La siguiente tabla resume los resultados de la evaluación:

- Web Application

<table align="center" border="1" width="100%" style="text-align:center;">
    <tr>
        <th>#</th>
        <th>Problema</th>
        <th>Escala de severidad</th>
        <th>Heurística/Principio violada(o)</th>
    </tr>
    <tr>
        <td>1</td>
        <td align="left">Mensajes de error poco claros</td>
        <td>3</td>
        <td align="left">Usabilidad - Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores</td>
    </tr>
    <tr>
        <td>2</td>
        <td align="left">Falta de opción para mostrar la contraseña</td>
        <td>2</td>
        <td align="left">Usabilidad - Flexibilidad y eficiencia de uso</td>
    </tr>
    <tr>
        <td>3</td>
        <td align="left">Falta de opciones para categorizar el incidente</td>
        <td>2</td>
        <td align="left">Arquitectura de la Información: Is it usable?</td>
    </tr>
    <tr>
        <td>4</td>
        <td align="left">No hay opción para editar la información del empleado</td>
        <td>2</td>
        <td align="left">Usabilidad - Control y libertad del usuario</td>
    </tr>
    <tr>
        <td>5</td>
        <td align="left">Falta de indicadores de estado de entrega</td>
        <td>3</td>
        <td align="left">Usabilidad - Visibilidad del estado del sistema</td>
    </tr>
    <tr>
        <td>6</td>
        <td align="left">No se muestran las imágenes de los empleados en el listado</td>
        <td>2</td>
        <td align="left">Arquitectura de la Información: Is it understandable?</td>
    </tr>
</table>

- Mobile Application

<table align="center" border="1" width="100%" style="text-align:center;">
    <tr>
        <th>#</th>
        <th>Problema</th>
        <th>Escala de severidad</th>
        <th>Heurística/Principio violada(o)</th>
    </tr>
    <tr>
        <td>1</td>
        <td align="left">No hay confirmación tras registrar un servicio</td>
        <td>3</td>
        <td align="left">Usabilidad - Visibilidad del estado del sistema</td>
    </tr>
    <tr>
        <td>2</td>
        <td align="left">No se ofrece lista de tipos de incidente predefinidos</td>
        <td>2</td>
        <td align="left">Usabilidad - Flexibilidad y eficiencia de uso</td>
    </tr>
    <tr>
        <td>3</td>
        <td align="left">No hay distinción visual entre servicios activos y completados</td>
        <td>3</td>
        <td align="left">Arquitectura de la Información: Is it organized?</td>
    </tr>
    <tr>
        <td>4</td>
        <td align="left">No hay mensaje de confirmación tras aceptar</td>
        <td>3</td>
        <td align="left">Usabilidad - Visibilidad del estado del sistema</td>
    </tr>
    <tr>
        <td>5</td>
        <td align="left">No se puede deshacer la acción</td>
        <td>3</td>
        <td align="left">Usabilidad - Control y libertad del usuario</td>
    </tr>
    <tr>
        <td>6</td>
        <td align="left">El campo de búsqueda no diferencia entre tipos de contenido</td>
        <td>3</td>
        <td align="left">Arquitectura de la Información: Is it findable?</td>
    </tr>
</table>

<b> <em> DESCRIPCIÓN DEL PROBLEMA: </em> </b> <br>

**- Web Application**

**PROBLEMA #1:** Mensajes de error poco claros  
<b>Severidad:</b> 3  
<b>Heurística violada:</b> Usabilidad - Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores  
<b>Problema:</b>  
Los mensajes de error al ingresar credenciales incorrectas son genéricos y no indican cuál fue el problema específico.  
<b>Recomendación:</b>  
Proporcionar mensajes de error específicos, como "Usuario no encontrado" o "Contraseña incorrecta", para ayudar al usuario a identificar y corregir el error. <br>

<img src="https://i.ibb.co/DDNWkHB4/Captura-de-pantalla-2025-06-09-005016.png" alt="web-problem1" border="0"><br>

**PROBLEMA #2:** Falta de opción para mostrar la contraseña<br>
<b>Severidad:</b> 2  
<b>Heurística violada:</b> Usabilidad - Flexibilidad y eficiencia de uso  
<b>Problema:</b>  
No se ofrece una opción para mostrar la contraseña mientras se escribe, lo que puede llevar a errores al ingresar la contraseña <br>
<b>Recomendación:</b>  
Incluir un ícono de ojo para permitir al usuario ver la contraseña mientras la escribe. <br>

<img src="https://i.ibb.co/S7WmzFGH/Captura-de-pantalla-2025-06-09-005325.png" alt="web-problem2" border="0"><br>

**PROBLEMA #3:**  Falta de opciones para categorizar el incidente  
<b>Severidad:</b> 2<br>
<b>Heurística violada:</b> Arquitectura de la Información: Is it usable?<br>
<b>Problema:</b>  
No se ofrecen opciones para categorizar el incidente, lo que puede dificultar su clasificación y seguimiento.  
<b>Recomendación:</b>  
Incluir un campo desplegable o un conjunto de botones para categorizar el incidente. <br>

<img src="https://i.ibb.co/DDXBfTCJ/Captura-de-pantalla-2025-06-09-005627.png" alt="web-problem3" border="0"><br>

**PROBLEMA #4:** No hay opción para editar la información del empleado  
<b>Severidad:</b> 2  
<b>Heurística violada:</b> Usabilidad - Control y libertad del usuario  
<b>Problema:</b>  
Una vez que la información del empleado ha sido añadida, no se ofrece una opción para editarla. 
<b>Recomendación:</b>  
Permitir la edición de la información del empleado desde la interfaz de usuario. <br>

<img src="https://media.discordapp.net/attachments/1364445917452697683/1381341024118378506/image.png?ex=6855aa14&is=68545894&hm=60762ed73edb340afc554907d9bbe50c5d55aacef4ead0f9c40ca87ab3435c11&=&format=webp&quality=lossless&width=1236&height=823" alt="web-problem4" border="0"><br>

**PROBLEMA #5:** Falta de indicadores de estado de entrega<br>
<b>Severidad:</b> 3  
<b>Heurística violada:</b> Usabilidad - Visibilidad del estado del sistema  
<b>Problema:</b>  
No se proporcionan indicadores claros del estado de cada entrega (por ejemplo, "En camino", "Entregado"). <br>
<b>Recomendación:</b>  
Incluir indicadores visuales del estado de cada entrega en la pantalla principal. <br>

<img src="https://media.discordapp.net/attachments/1364445917452697683/1381340703304716418/image.png?ex=6855a9c7&is=68545847&hm=583c8c650bb070c8173569b8a60d16bfe171d556f5ef435897c0be244133bc24&=&format=webp&quality=lossless&width=1238&height=823" alt="web-problem5" border="0"><br>

**PROBLEMA #6:** No se muestran las imágenes de los empleados en el listado  
<b>Severidad:</b> 2 <br>
<b>Heurística violada:</b> Arquitectura de la Información: Is it understandable?<br>
<b>Problema:</b>  
La sección de empleados muestra solo nombres y datos básicos sin incluir la imagen del empleado. Esto dificulta la identificación visual rápida, especialmente en equipos grandes, y reduce la conexión humana que ayuda a reconocer personas en la organización.  
<b>Recomendación:</b>  
Incorporar imágenes o avatares de los empleados junto a sus nombres. Si por razones de privacidad no se puede mostrar la foto real, usar avatares personalizados o íconos que ayuden a la diferenciación visual. <br>

<img src="https://media.discordapp.net/attachments/1364445917452697683/1381341024118378506/image.png?ex=6855aa14&is=68545894&hm=60762ed73edb340afc554907d9bbe50c5d55aacef4ead0f9c40ca87ab3435c11&=&format=webp&quality=lossless&width=1236&height=823" alt="web-problem6" border="0"><br>

**- Mobile Application**

**PROBLEMA #1:** No hay confirmación tras registrar un servicio  
<b>Severidad:</b> 3  
<b>Heurística violada:</b> Usabilidad - Visibilidad del estado del sistema  
<b>Problema:</b>  
No se muestra un mensaje de éxito o alerta visual clara luego de añadir el servicio.<br>
<b>Recomendación:</b>  
Mostrar un snackbar o modal de confirmación (“Servicio registrado exitosamente”). <br>

<img src="https://i.ibb.co/0RV8Fy9X/Captura-de-pantalla-2025-06-19-185601.png" alt="mob-problem1" border="0"><br>

**PROBLEMA #2:** No se ofrece lista de tipos de incidente predefinidos<br>
<b>Severidad:</b> 2  
<b>Heurística violada:</b> Usabilidad - Flexibilidad y eficiencia de uso  
<b>Problema:</b>  
Se debe escribir manualmente el tipo de incidente, sin sugerencias ni autocompletado.
<b>Recomendación:</b>  
Incluir desplegable con tipos frecuentes (fuga, explosión, temperatura, etc.). <br>

<img src="https://i.ibb.co/cPdj06G/Captura-de-pantalla-2025-06-19-185638.png" alt="mob-problem2" border="0"><br>

**PROBLEMA #3:**  No hay distinción visual entre servicios activos y completados  
<b>Severidad:</b> 3<br>
<b>Heurística violada:</b> Arquitectura de la Información: Is it organized?<br>
<b>Problema:</b>  
Todas las entregas aparecen visualmente iguales, lo cual dificulta el reconocimiento de los estados de las entregas.<br>
<b>Recomendación:</b>  
Usar colores, etiquetas o secciones para separarlas por estado. <br>

<img src="https://i.ibb.co/8nj3mdWD/Captura-de-pantalla-2025-06-19-205349.png" alt="mob-problem3" border="0"><br>

**PROBLEMA #4:** No hay mensaje de confirmación tras aceptar  
<b>Severidad:</b> 3 <br>
<b>Heurística violada:</b> Usabilidad - Visibilidad del estado del sistema  
<b>Problema:</b>  
El sistema no informa si la acción de aceptar una entrega fue exitosa ni qué cambia después.
<b>Recomendación:</b>  
Mostrar mensaje de éxito (“Entrega asignada”) y actualizar la lista de entregas en tiempo real. <br>

<img src="https://i.ibb.co/CpppQtN8/Captura-de-pantalla-2025-06-19-205429.png" alt="mob-problem4" border="0"><br>

**PROBLEMA #5:** No se puede deshacer la acción<br>
<b>Severidad:</b> 3 <br>
<b>Heurística violada:</b> Usabilidad - Control y libertad del usuario <br>
<b>Problema:</b>  
Una vez que se acepta o rechaza, no hay opción de revertir, tampoco hay un cuadro de diálogo para confirmar la eliminación de una entrega.<br>
<b>Recomendación:</b>  
Agregar botón de “deshacer” o confirmación previa. <br>

<img src="https://i.ibb.co/23QyfRzk/Captura-de-pantalla-2025-06-19-205611.png" alt="mob-problem5" border="0"><br>

**PROBLEMA #6:** El campo de búsqueda no diferencia entre tipos de contenido <br>
<b>Severidad:</b> 3 <br>
<b>Heurística violada:</b> Arquitectura de la Información: Is it usable?<br>
<b>Problema:</b>  
Al buscar no está claro si se está filtrando por nombre, tipo, fecha o ubicación, lo cual complica la búsqueda de algún elemento<br>
<b>Recomendación:</b>  
Añadir filtros o placeholders específicos (ej. “Buscar por nombre o tipo…”).<br>

<img src="https://i.ibb.co/5xXkSYbf/Captura-de-pantalla-2025-06-19-205745.png" alt="mob-problem6" border="0"><br>

## 6.4. Video About-the-Product

![image](https://github.com/user-attachments/assets/0ecd0257-3f03-425e-9722-d6b0c539c7dd)

[Enlace del video](https://youtu.be/pxbxr8Wg00w)

# Conclusiones
## Conclusiones y Recomendaciones

En las presentes entregas, se llevaron a cabo actividades orientadas a la captura de requisitos y la definición de la solución tecnológica. Se estableció el dominio del negocio, identificando la problemática a resolver, los segmentos objetivo y los requisitos clave, así como la elaboración de user stories. Además, se diseñó la versión inicial de la arquitectura del sistema, utilizando metodologías de Domain Driven Design como EventStorming y Bounded Context Canvas. Estos avances sentaron las bases sólidas para el desarrollo de la arquitectura de la solución propuesta.

Como equipo llegamos a las siguientes conclusiones:

En la primera fase del proyecto permitió comprender a profundidad el dominio del negocio y delimitar claramente la problemática relacionada con la seguridad en el transporte de materiales peligrosos. El realizar todas las secciones previstas en este sistema se brindó una visión compartida del problema y sus posibles soluciones, además de  un avance clave que facilitará futuras iteraciones de diseño, implementación y validación de ChemTrack. La planificación y ejecución del Sprint 1 permitió establecer una base sólida para el desarrollo del proyecto, facilitando la identificación temprana de los elementos faltantes y el enfoque necesario para avanzar de forma estructurada. El desarrollo del Sprint Backlog fue clave para priorizar las tareas más relevantes, lo que permitió entregar una primera versión funcional del prototipo, centrada en los pilares del sistema.

Durante el srpint 2, se logró desplegar la versión final del frontend (web app y landing page), así como la primera versión funcional de los módulos Mobile, IoT y Edge, permitiendo validar integralmente los principales componentes del sistema ChemTrack. Se completaron tareas clave como el despliegue de servicios web en entornos reales, la generación de artefactos móviles (APK), la implementación del canal de comunicación mediante MQTT entre dispositivos IoT y el backend, y la configuración del entorno de edge computing sobre AWS. Estas entregas representan una base operativa robusta sobre la cual se continuará construyendo en sprints futuros.

En el sprint 3 se logró consolidar la versión final e integrada de las plataformas Mobile, IoT y Edge, asegurando una comunicación fluida y estable entre todos los componentes del sistema. La validación con usuarios reales permitió confirmar que la solución cumple con los requerimientos funcionales y de experiencia definidos al inicio del proyecto. Se completó exitosamente el prototipo físico del dispositivo IoT, el cual demostró su funcionalidad tanto en la recolección como en la transmisión de datos en tiempo real. La interoperabilidad entre artefactos (móvil ↔ IoT ↔ Edge) fue validada, confirmando que los flujos de datos y la arquitectura de comunicación diseñada son robustos y escalables. Se realizó el cierre del proyecto con todos los entregables principales completados, incluyendo documentación técnica, prototipos funcionales y resultados de validación.

Por otro lado recomendaríamos que en base en los aprendizajes obtenidos a lo largo del desarrollo del proyecto ChemTrack, se proponen las siguientes recomendaciones para optimizar futuras fases del sistema y mejorar la gestión de proyectos similares: 

- Es fundamental establecer reuniones periódicas entre todos los actores del proyecto para asegurar la alineación de objetivos, evitar ambigüedades y garantizar una toma de decisiones coherente desde el inicio hasta el cierre.

- Se recomienda documentar de forma sistemática cada sprint, incluyendo avances, decisiones clave, problemas encontrados y soluciones implementadas. Esto facilitará la trazabilidad del proceso y agilizará futuras iteraciones o fases de mantenimiento.

- El desempeño del equipo durante el proyecto demostró que la colaboración efectiva, la distribución equilibrada de tareas y el cumplimiento de plazos son factores críticos de éxito. Se sugiere continuar reforzando prácticas de trabajo en equipo y herramientas de gestión colaborativa.

- Incluir pruebas frecuentes con usuarios reales en cada entrega incrementa la posibilidad de detectar y corregir errores o aspectos de usabilidad antes de etapas finales. Esta validación temprana mejora la calidad del producto y su adecuación a las necesidades del usuario.

- Considerando la naturaleza distribuida y multitecnológica del sistema (web, móvil, IoT, edge), es recomendable adoptar prácticas DevOps para automatizar procesos de integración, pruebas y despliegue continuo, lo que garantiza entregas más seguras y eficientes.

- La validación de la interoperabilidad entre los componentes es un paso clave; se sugiere mantener y evolucionar la arquitectura modular y escalable que fue planteada, especialmente en lo relacionado a microservicios, comunicación MQTT y procesamiento en el borde (edge computing).

- Incorporar herramientas de monitoreo en tiempo real y sistemas de alerta para evaluar el desempeño de los distintos módulos (mobile, IoT y edge) permitirá identificar cuellos de botella y anticipar problemas en entornos de producción.

- Con el proyecto finalizado, se recomienda diseñar una hoja de ruta que contemple mantenimiento, soporte técnico, actualización de tecnologías clave, y posibles mejoras futuras, especialmente si se planea escalar el sistema a nuevos contextos o usuarios.

Más allá de los resultados técnicos, es esencial registrar y compartir los desafíos superados, decisiones clave, y buenas prácticas adquiridas, como parte del conocimiento colectivo del equipo. Esto enriquecerá futuros desarrollos y contribuirá a una cultura de mejora continua.


## Video About-the-Team

En el presente video hablamos de nuestras experiencias en el equipo cumpliendo con las competencias del presente student outcome y presentando las actas de participación de los integrantes.

![Imagen de WhatsApp 2025-06-20 a las 23 36 44_9c3d8588](https://github.com/user-attachments/assets/e2da59f9-e5ff-4689-a3e4-f27233aec618)

[Enlace del video](https://youtu.be/HpFXHfODu2s)


# Bibliografía

Aguilar-Velázquez, J. A., & Salazar-González, M. (2018). Evaluación del riesgo en el transporte terrestre de sustancias peligrosas mediante sistemas de información geográfica. Revista Internacional de Contaminación Ambiental, 34(1), 131-141.

García, C. H., & Martínez, J. D. (2022). Aplicación de sensores IoT para detección temprana de fugas en unidades móviles de transporte de gas. Revista Electrónica de Ciencia y Tecnología, 19(1), 47-55.

López-Atamoros, L. G., Fernández-Villagómez, G., Cruz-Gómez, M. J., & Durán-de-Bazúa, C. (2010). Integración de una Base Nacional de Datos de Accidentes durante el Transporte de Gas LP (BNDAT@ GLP) 1998-2009: Sustento para un estudio de evaluación de riesgo. Tecnología, Ciencia, Educación, 25(2), 99-112.

Rivas-Tovar, L. A., & Vázquez-González, R. (2017). Desarrollo de un sistema de monitoreo para transporte de materiales peligrosos utilizando sensores y redes inalámbricas. Revista Iberoamericana de Automática e Informática Industrial RIAI, 14(3), 315-324.

Soto, J. A. S., González, D. L. E., Sánchez, J. F. I., Reyes, J. A., & Layva, J. M. E. (2023). DISEÑO DE DISPOSITIVO PARA PREVENIR ACCIDENTES CAUSADOS POR FUGAS DE GAS. Revista IPSUMTEC, 6(4), 11-14.


# Anexos

**Anexo A.** Event Storming desarrollado en la plataforma MIRO.

![eventStorming](https://github.com/user-attachments/assets/fe7db010-856e-4eee-8ef3-90a84ecb3327)

*[Enlace del MIRO para mayor visualización del Event Storming](https://miro.com/welcomeonboard/ZDUyWkh5OTlpSVF4RGdTNG9tdkI0N0FnS1F5VUtRczM0dXJkS2dSZHRDeW1yWm54RW02c3EybHBKYzdIaGkxRjZUb2lwNHB2a0RKelJzRmJNUDd3NEoyNVE3Wk1Uc2U5MUFySzEyZFNBZ0pSa011QkVnQy93aVprVXUyVGFsQ2pNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=980476835383)*

**Anexo B.** Diagrama de Clases de Chemtrack.

![image](https://github.com/user-attachments/assets/0ba27eb9-5cc4-468f-b3a3-f3ab755b4e94)


**Anexo C.** Diagrama de Base de Datos de Chemtrack.

![image](https://github.com/user-attachments/assets/8891c6d6-734c-46f2-9289-fd25f42f66af)


**Videos de exposición**

[Video de exposición TB1](https://youtu.be/n4_SKmnvCeU)

[Video de exposición TP1](https://youtu.be/Y9wkGYbHHYE)

[Video de exposición TB2](https://youtu.be/Yd74MizvXWY)

[Video de exposición TF1](https://youtu.be/F0Hp7YIlBoA)




