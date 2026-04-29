<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="LogoUPC">
</p>

# <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
## <p align="center">Ingeniería de Software</p>
<p align="center">Periodo: 202610</p>
<p align="center">1ASI0732 | Diseño de Experimentos de Ingeniería de Software</p>
<p align="center">NRC: 17821</p>
<p align="center">Docente: Lennin Percy Cenas Vasquez</p>

---

<br>

## <p align="center">Informe del Trabajo Final</p>

<p align="center">Startup: ClaudeFlow</p>
<p align="center">Producto: FoodFlow</p>

---

<p align="center">Integrantes:</p>
<p align="center"><code>U202310308</code> - Borja Molina, Gabriel Sebastián</p>
<p align="center"><code>U202310003</code> - Lang Nassi, Werner Khalil</p>
<p align="center"><code>U202311334</code> - Rodriguez Rodriguez, Luis Piero</p>
<p align="center"><code>U202123373</code> - Román Pajuelo, Luis Gustavo</p>
<p align="center"><code>U202311532</code> - Suárez Romero, Santiago Manuel</p>
  
<br>

<p align="center"><i>Ciclo 202610</i></p>

<br>

<div style="page-break-after: always;"></div>

---

## Registro de versiones del informe
| Versión | Fecha | Autores | Descripción de la modificación |
| :--- | :--- | :--- | :--- |
| 1.0 (AV1) | 30/04/26 | - Borja Molina, Gabriel Sebastián<br>- Lang Nassi, Werner Khalil<br>- Rodriguez Rodriguez, Luis Piero<br>- Román Pajuelo, Luis Gustavo<br>- Suárez Romero, Santiago Manuel | **Capítulos I, II, III, IV y V** |

---

## Project Report Collaboration Insights

Para el desarrollo de este informe se utilizó GitHub como plataforma de colaboración y control de versiones. A continuación, se presentan algunos insights sobre la colaboración del equipo durante la elaboración del informe:

---

# Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [1.2.1.1. What](#1211-what)
      - [1.2.1.2. When](#1212-when)
      - [1.2.1.3. Where](#1213-where)
      - [1.2.1.4. Who](#1214-who)
      - [1.2.1.5. Why](#1215-why)
      - [1.2.1.6. How](#1216-how)
      - [1.2.1.7. How much](#1217-how-much)
        - [1.2.1.7.1 Estadísticas que sustentan la problemática](#12171-estadísticas-que-sustentan-la-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statement](#1221-lean-ux-problem-statement)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmento Objetivo](#13-segmento-objetivo)
- [Capítulo II: Requirements \& Analysis](#capítulo-ii-requirements--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y Tácticas Competitivas de FoodFlow](#212-estrategias-y-tácticas-competitivas-de-foodflow)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Map](#234-empathy-map)
    - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4 Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
  - [3.3 Product Backlog](#33-product-backlog)
  - [3.4 Impact Map](#34-impact-map)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
  - [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2 Software Architecture Container Diagrams.](#462-software-architecture-container-diagrams)
    - [4.6.3 Software Architecture Components Diagrams.](#463-software-architecture-components-diagrams)
  - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
    - [4.7.2 Class Dictionary](#472-class-dictionary)
  - [4.8 Database Design](#48-database-design)
    - [4.10.1 Relational Database Diagram](#4101-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Product Implementation \& Deployment.](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs.](#521-sprint-backlogs)
    - [### 5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
    - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.6. RESTful API documentation](#526-restful-api-documentation)
    - [5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)
  - [5.3. Video About-the-Product](#53-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET: ABET – EAC - Student Outcome 5 Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos. En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|

---

# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

ClaudeFlow es una startup liderada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), dedicada al desarrollo de soluciones digitales para la gestión financiera de restaurantes. Con el propósito de brindar a los dueños de negocios gastronómicos una herramienta accesible, intuitiva y especializada, se ha desarrollado el proyecto FoodFlow, una aplicación web orientada al monitoreo de la salud financiera del restaurante, la visualización de ingresos y gastos, el análisis de rentabilidad por plato, la gestión de inventario, el control de órdenes y la generación de reportes estratégicos. En ClaudeFlow, consideramos que una adecuada gestión financiera es fundamental para la sostenibilidad, rentabilidad y crecimiento de los restaurantes, especialmente en negocios pequeños y medianos que suelen operar con procesos manuales, hojas de cálculo o información dispersa. Por ello, FoodFlow busca convertirse en una solución tecnológica que permita transformar los datos operativos del restaurante en información clara y útil para la toma de decisiones.

**Misión:** Facilitar la gestión financiera de los restaurantes mediante una plataforma web intuitiva, accesible y especializada, que permita monitorear métricas económicas clave, analizar ingresos, gastos, inventario y ventas por plato, y optimizar la toma de decisiones estratégicas de los propietarios para mejorar la rentabilidad y reducir pérdidas operativas.

**Visión:** Convertirse en una startup referente en Latinoamérica en el desarrollo de soluciones de inteligencia financiera para restaurantes, impulsando la digitalización de pequeños y medianos negocios gastronómicos a través de herramientas tecnológicas que simplifiquen el control económico, fortalezcan la toma de decisiones basada en datos y contribuyan a la sostenibilidad financiera del sector.

### 1.1.2 Perfiles de integrantes del equipo

| Foto | Nombre | Codigo | Carrera | Acerca de | Habilidades |
| :--- | :--- | :--- | :--- | :--- | :--- |
| ![GabrielBorja.jpg](assets/GabrielBorja.jpg) | Borja Molina, Gabriel Sebastián | U202310308 | Ingeniería de Software | | |
| ![WernerLang.jpg](assets/WernerLang.jpg) | Lang Nassi, Werner Khalil | U202310003 | Ingeniería de Software | Estudiante de la Universidad Peruana de Ciencias Aplicadas (UPC), cursando en 7.º ciclo. Soy un estudiante que le gusta investigar cosas nuevas. | Investigador, Innovador, Analista, Cooperativo. |
| ![LuisRodriguez.jpg](assets/LuisRodriguez.png) | Rodriguez Rodriguez, Luis Piero | U202311334 | Ingeniería de Software | Estudiante de la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente en 7mo ciclo, con interés en el rubro de desarrollo y análisis de datos. | |
| ![GustavoRoman.jpg](assets/GustavoRoman.jpg) | Román Pajuelo, Luis Gustavo | U202123373 | Ingeniería de Software | Estudiante de la Universidad Peruana de Ciencias Aplicadas (UPC), cursando en 7.º ciclo. Me considero un estudiante con ganas de seguir aprendiendo constantemente | Responsable, Cooperativo, Proactivo, Perseverante. |
| ![SantiagoSuarez.jpg](assets/SantiagoSuarez.jpg) | Suárez Romero, Santiago Manuel | U202311532 | Ingeniería de Software | | |

## 1.2 Solution Profile

FoodFlow es una aplicación web diseñada para transformar la manera en que los restaurantes gestionan y analizan su información financiera y operativa. A través de una plataforma intuitiva, accesible y especializada, permite a los dueños de restaurantes visualizar ingresos, gastos, reportes, inventario, órdenes y rendimiento de platos de forma clara y centralizada. Con el objetivo de facilitar la toma de decisiones estratégicas y mejorar la rentabilidad del negocio, FoodFlow conecta la información diaria del restaurante con herramientas visuales que permiten comprender mejor su desempeño económico en un entorno digital moderno.

### 1.2.1 Antecedentes y problemática

### 1.2.1. Antecedentes y Problemática

Con el fin de comprender con mayor claridad las necesidades de los usuarios de FoodFlow, resulta esencial examinar los antecedentes y la problemática mediante la técnica de las 5W’s & 2H’s. Según Alvarez (2020), citado por Lean Construction México, esta herramienta permite definir, estructurar y orientar un plan de acción o una estrategia detallada. Por ello, la información presentada a continuación ha sido organizada aplicando dicha metodología, con el propósito de analizar la situación actual de los dueños de restaurantes frente a la gestión financiera y operativa de sus negocios.

Las dos preguntas “H” de la técnica 5W+2H corresponden a “¿Cómo?” y “¿Cuánto?”. La pregunta “¿Cómo?” se enfoca en la manera en que se desarrollan las acciones o procesos, lo cual resulta clave para comprender y explicar una situación específica. En el contexto de FoodFlow, esta pregunta permitirá analizar cómo los dueños de restaurantes podrán adoptar la plataforma como una herramienta de apoyo para centralizar la información de su negocio, revisar ingresos y gastos, gestionar inventario, controlar órdenes, visualizar reportes y tomar decisiones estratégicas a partir de datos organizados. Esto incluye una experiencia web intuitiva, dashboards visuales, navegación clara entre módulos y funcionalidades orientadas a simplificar el monitoreo financiero diario del restaurante.

Por otro lado, la pregunta “¿Cuánto?” se centra en cuantificar la magnitud del problema y dimensionar su impacto. En este caso, los datos recopilados permitirán comprender con mayor profundidad las dificultades que enfrentan los restaurantes pequeños y medianos al gestionar sus finanzas mediante registros manuales, hojas de cálculo o sistemas poco integrados. Esto implica considerar la frecuencia con la que los dueños revisan sus ingresos y gastos, la cantidad de información dispersa entre órdenes, inventario y reportes, el tiempo invertido en consolidar datos de forma manual, el nivel de desconocimiento sobre la rentabilidad de los platos y el impacto positivo que puede generar centralizar la gestión financiera y operativa en una sola aplicación web como FoodFlow.

#### 1.2.1.1. What

##### ¿Cuál es el problema?

FoodFlow nace como respuesta a una problemática recurrente dentro del sector gastronómico: la dificultad que enfrentan los dueños de restaurantes para monitorear, interpretar y controlar adecuadamente la información financiera y operativa de sus negocios. Aunque la industria de restaurantes ha mostrado señales de crecimiento en el Perú, este avance no siempre se encuentra acompañado de una gestión interna eficiente. Según el Instituto Nacional de Estadística e Informática, la actividad de restaurantes aumentó 5.32 % en marzo de 2024 y acumuló un crecimiento de 3.03 % entre enero y marzo del mismo año, en comparación con el periodo similar de 2023 (INEI, 2024a). Asimismo, en noviembre de 2024, el sector creció 4.48 %, acumulando un incremento de 3.37 % entre enero y noviembre frente al año anterior (INEI, 2025).

Sin embargo, este crecimiento contrasta con una realidad crítica: muchos negocios gastronómicos no logran sostenerse debido a una gestión deficiente. Según lo señalado por Fernando Oré, coordinador culinario de la Universidad Le Cordon Bleu, aproximadamente el 70 % de los negocios relacionados con la venta de comida en el Perú cierran o se traspasan cada año a causa de una mala gestión (Guzmán, 2019). Esta situación evidencia que no basta con ofrecer buenos productos o contar con demanda; también es necesario disponer de herramientas que permitan controlar costos, inventario, ventas, márgenes y flujo de caja de manera constante.

Tradicionalmente, muchos restaurantes pequeños y medianos gestionan sus finanzas mediante cuadernos, hojas de cálculo, registros manuales o sistemas POS que se enfocan principalmente en ventas y facturación. Si bien estas herramientas pueden cubrir necesidades básicas, presentan limitaciones importantes al momento de obtener una visión integral del negocio. Entre las principales dificultades se encuentran la falta de reportes claros, la baja visibilidad sobre la rentabilidad por plato, la ausencia de control centralizado del inventario y la toma de decisiones basada en intuición más que en datos.

En este contexto, FoodFlow se presenta como una solución digital especializada que busca centralizar la información financiera y operativa del restaurante en una plataforma web intuitiva. A través de dashboards, reportes, gestión de inventario, control de órdenes y análisis de platos, el sistema permite que los dueños de restaurantes comprendan mejor el estado de su negocio y tomen decisiones más informadas.

##### ¿Cuál es la relación con la persona en cuestión?

Para los dueños de restaurantes, FoodFlow representa una herramienta de apoyo en la gestión diaria del negocio, ya que permite visualizar información clave sobre ingresos, gastos, órdenes, inventario y rendimiento de platos desde un entorno digital centralizado. La relación con el usuario se basa en la necesidad de reducir la incertidumbre financiera, mejorar el control operativo y facilitar la toma de decisiones estratégicas sin depender únicamente de registros manuales o conocimientos contables avanzados.

#### 1.2.1.2. When

##### ¿Cuándo sucede el problema?

El problema ocurre principalmente cuando el dueño del restaurante necesita tomar decisiones económicas u operativas y no cuenta con información clara, actualizada o integrada. Esto puede suceder en distintos momentos de la gestión diaria, semanal o mensual del negocio, especialmente cuando se requiere evaluar ventas, controlar gastos, revisar stock, identificar platos más rentables o analizar si el restaurante está generando ganancias reales.

Específicamente, esta problemática se presenta cuando:

* El dueño necesita conocer sus ingresos y pérdidas, pero la información se encuentra dispersa en hojas de cálculo, cuadernos o sistemas independientes.
* Se deben tomar decisiones sobre precios, compras o promociones sin contar con reportes financieros claros.
* El restaurante experimenta quiebres de stock o sobrecompra de insumos por falta de control de inventario.
* Se desconoce qué platos generan mayor rentabilidad o cuáles tienen menor desempeño.
* Se requiere revisar el flujo de caja, pero no existen métricas visuales que faciliten su interpretación.
* El propietario depende de terceros para comprender la situación financiera del negocio.

Estas situaciones dificultan una gestión oportuna y aumentan el riesgo de pérdidas acumuladas, decisiones poco sustentadas y menor sostenibilidad financiera.

##### ¿Cuándo utiliza el cliente el servicio?

El cliente utiliza FoodFlow cuando necesita consultar, registrar o analizar información relevante para la gestión de su restaurante. Esto puede ocurrir al iniciar la jornada, al cierre del día, durante la revisión semanal de resultados o al preparar decisiones relacionadas con compras, menú, precios y control financiero.

Asimismo, el dueño del restaurante puede usar la plataforma cuando desea visualizar reportes diarios, semanales o mensuales; revisar el estado del inventario; analizar las órdenes registradas; consultar el rendimiento de sus platos; o verificar la situación general del negocio desde el dashboard principal. De esta forma, FoodFlow se convierte en una herramienta de consulta y control continuo para la administración del restaurante.

#### 1.2.1.3. Where

##### ¿Dónde está el cliente cuando usa el producto?

FoodFlow está diseñado como una aplicación web, por lo que el usuario puede acceder a la plataforma desde un dispositivo con conexión a internet, principalmente desde una computadora o laptop. El dueño del restaurante puede utilizar el sistema desde el mismo local, una oficina administrativa, su hogar o cualquier espacio donde necesite revisar la información de su negocio.

Esta accesibilidad permite que la gestión financiera y operativa no dependa únicamente de la presencia física en el restaurante, sino que pueda realizarse desde un entorno digital que centraliza los datos más importantes del negocio.

##### ¿Dónde surge el problema?

La problemática surge principalmente dentro de los restaurantes pequeños y medianos, especialmente en aquellos donde la información financiera, las ventas, las compras y el inventario se gestionan de manera manual o poco integrada. También aparece en contextos donde el dueño no cuenta con un sistema especializado para interpretar sus datos y debe apoyarse en herramientas genéricas que no responden completamente a las necesidades del sector gastronómico.

El problema se evidencia en la administración diaria del negocio: en la caja, en la cocina, en el control de insumos, en la planificación de compras, en la revisión de ventas y en la evaluación de resultados. Cada una de estas áreas genera información valiosa, pero si no se encuentra organizada y conectada, pierde utilidad para la toma de decisiones.

#### 1.2.1.4. Who

##### ¿Quiénes están involucrados?

Los principales involucrados son los dueños de restaurantes, quienes necesitan información clara para controlar la salud financiera y operativa de su negocio. También se encuentran involucrados los administradores, encargados de caja, responsables de inventario y personal que registra órdenes o actualiza información relacionada con productos y platos.

Aunque FoodFlow está orientado principalmente al propietario del restaurante, su impacto se relaciona con todo el funcionamiento interno del negocio, ya que la información registrada sobre ventas, órdenes, inventario y platos permite construir una visión más completa del desempeño del restaurante.

##### ¿A quiénes les sucede el problema?

El problema afecta principalmente a dueños de restaurantes pequeños y medianos que no cuentan con herramientas especializadas para monitorear sus finanzas y operaciones. Este segmento suele enfrentar limitaciones de tiempo, presupuesto y conocimiento técnico, lo que dificulta la adopción de soluciones empresariales complejas o de alto costo.

Asimismo, afecta a restaurantes que dependen de registros manuales, hojas de cálculo o sistemas POS con reportes limitados. En estos casos, el propietario puede conocer cuánto vendió durante el día, pero no necesariamente comprende si sus platos son rentables, si sus gastos están controlados o si el inventario está siendo gestionado de forma eficiente.

##### ¿Quién lo utilizará?

FoodFlow será utilizado principalmente por dueños de restaurantes que buscan una herramienta sencilla, visual y especializada para gestionar su información financiera y operativa. También podrá ser empleado por administradores o responsables internos que apoyen en el registro y seguimiento de datos relacionados con órdenes, inventario, menú, reportes y perfil del negocio.

El usuario objetivo no necesariamente posee conocimientos contables avanzados, por lo que la plataforma prioriza una experiencia clara, accesible y orientada a la toma de decisiones. De esta manera, FoodFlow se adapta a propietarios que necesitan comprender rápidamente el estado de su restaurante sin recurrir a procesos complejos o herramientas demasiado técnicas.

#### 1.2.1.5. Why

##### ¿Cuál es la causa del problema?

La causa principal del problema es la falta de una gestión financiera y operativa integrada en los restaurantes pequeños y medianos. Muchos negocios del sector gastronómico se enfocan en la producción, atención al cliente y ventas diarias, pero dejan en segundo plano el análisis de costos, márgenes, inventario y rentabilidad. Esto provoca que las decisiones se tomen de manera reactiva, sin una visión clara del impacto económico que generan.

Una segunda causa es la dependencia de herramientas manuales o genéricas. El uso de cuadernos, hojas de cálculo o reportes básicos de POS puede ser útil en etapas iniciales, pero se vuelve insuficiente cuando el negocio necesita analizar tendencias, comparar periodos, identificar categorías de gasto o evaluar el rendimiento de cada plato. Según NetSuite, la gestión financiera en restaurantes implica presupuestar, controlar costos, gestionar flujo de caja, definir precios, negociar con proveedores y monitorear operaciones en un entorno de márgenes reducidos (NetSuite, 2025). Por ello, la falta de sistemas adecuados limita la capacidad del propietario para sostener la rentabilidad.

Otra causa importante se relaciona con el inventario. En restaurantes, una mala gestión de insumos puede generar sobrecompras, desperdicio, quiebres de stock, pérdidas por vencimiento o decisiones de compra poco eficientes. Sage señala que los altos costos de alimentos suelen originarse por sobreordenamiento, desperdicio, robos, control inconsistente de porciones o precios de menú inadecuados (Sage, 2025). En consecuencia, cuando el inventario no se controla de manera constante, se afecta directamente la rentabilidad del negocio.

Finalmente, la falta de visibilidad financiera provoca que muchos propietarios no identifiquen a tiempo los problemas. Pueden existir ventas constantes, pero también gastos ocultos, baja rentabilidad por plato o pérdidas acumuladas. Esta falta de claridad incrementa el riesgo de sostenibilidad y dificulta que el restaurante crezca de manera ordenada.

#### 1.2.1.6. How

##### ¿En qué condiciones los clientes utilizan nuestro producto?

Los clientes utilizan FoodFlow en condiciones relacionadas con la gestión diaria y estratégica del restaurante. Principalmente, acceden a la plataforma cuando necesitan revisar indicadores financieros, consultar reportes, registrar productos, visualizar órdenes, gestionar platos o analizar información del negocio desde un dashboard centralizado.

Estas condiciones suelen presentarse durante la operación del restaurante, al cierre de caja, en la planificación de compras, en la revisión de resultados semanales o al evaluar cambios en el menú. En todos estos casos, FoodFlow permite organizar la información y transformarla en datos visuales que facilitan la comprensión del estado financiero y operativo del negocio.

##### ¿Cómo nos conocieron los clientes?

Los clientes pueden conocer FoodFlow mediante canales digitales como redes sociales, landing page, recomendaciones, presentaciones académicas o campañas orientadas a restaurantes pequeños y medianos. Al tratarse de una solución web enfocada en la gestión financiera gastronómica, la comunicación del producto se centra en mostrar su utilidad para reducir pérdidas, controlar mejor el inventario, comprender ingresos y gastos, y tomar decisiones basadas en información clara.

##### ¿Cómo prefieren los dueños de restaurantes acceder a nuestro contenido?

Los dueños de restaurantes prefieren acceder a la información de manera rápida, visual y sencilla. Por ello, FoodFlow organiza los datos mediante dashboards, gráficos, tablas y reportes que permiten interpretar el estado del negocio sin revisar grandes volúmenes de información de forma manual.

La plataforma responde a la necesidad de contar con una experiencia intuitiva, donde el usuario pueda consultar métricas clave, alternar entre periodos de tiempo, revisar platos, órdenes e inventario, y obtener una visión general de la salud financiera del restaurante. Esta forma de acceso resulta especialmente valiosa para propietarios que necesitan información práctica y accionable.

##### ¿Qué llevó a la persona a llegar a esta situación?

El dueño de restaurante llega a esta situación debido a una combinación de factores operativos, financieros y tecnológicos. En muchos casos, el crecimiento del negocio se produce de manera rápida o informal, sin que exista una estructura adecuada para controlar costos, inventario y rentabilidad. Al inicio, los registros manuales pueden parecer suficientes, pero conforme aumentan las órdenes, los productos, los gastos y la complejidad del menú, la información se vuelve más difícil de administrar.

Además, muchos propietarios se enfocan principalmente en vender, atender clientes y mantener la calidad del servicio, dejando el análisis financiero como una actividad secundaria. Esta dinámica puede generar una falsa sensación de estabilidad, ya que vender más no siempre significa ganar más. Sin reportes claros, el dueño puede no identificar a tiempo pérdidas por insumos, platos poco rentables, compras mal planificadas o gastos que reducen el margen de utilidad.

Todo esto conduce a una gestión basada en intuición, donde las decisiones se toman a partir de la experiencia diaria, pero no necesariamente con respaldo de datos. FoodFlow busca atender esta necesidad mediante una plataforma que centraliza la información y facilita su análisis.

#### 1.2.1.7. How much

##### 1.2.1.7.1 Estadísticas que sustentan la problemática

Según el Instituto Nacional de Estadística e Informática, la actividad de restaurantes creció 5.32 % en marzo de 2024 y acumuló un incremento de 3.03 % entre enero y marzo del mismo año, en comparación con el periodo similar de 2023 (INEI, 2024a). Este crecimiento evidencia que el sector gastronómico mantiene dinamismo y continúa siendo relevante dentro de la economía peruana.

Asimismo, el INEI reportó que en noviembre de 2024 la actividad de restaurantes aumentó 4.48 %, mientras que entre enero y noviembre de ese año el sector acumuló un crecimiento de 3.37 % frente al mismo periodo de 2023 (INEI, 2025). Esto demuestra que existe una demanda activa en el mercado gastronómico, pero también una mayor necesidad de que los restaurantes gestionen sus operaciones con herramientas más eficientes.

A pesar de este crecimiento, la sostenibilidad de los negocios gastronómicos sigue siendo un desafío. Según Fernando Oré, aproximadamente el 70 % de los negocios relacionados con la venta de comida en el Perú cierran o se traspasan cada año debido a una mala gestión (Guzmán, 2019). Este dato refuerza la importancia de contar con soluciones que ayuden a los propietarios a controlar sus finanzas, operaciones e inventario de manera más organizada.

En cuanto a la gestión interna, NetSuite señala que la administración financiera en restaurantes involucra presupuestos, control de costos, manejo de flujo de caja, fijación de precios, negociación con proveedores y monitoreo de operaciones, todo dentro de una industria competitiva y de márgenes reducidos (NetSuite, 2025). Por su parte, Sage indica que los altos costos de alimentos pueden originarse por sobrecompra, desperdicio, robos, control inconsistente de porciones o precios de menú inadecuados, lo que evidencia la importancia de un inventario bien gestionado (Sage, 2025).

Estas estadísticas y referencias permiten concluir que FoodFlow responde a una problemática real: los restaurantes necesitan herramientas digitales que les permitan centralizar información, controlar sus recursos, analizar resultados y tomar decisiones basadas en datos para mejorar su rentabilidad y sostenibilidad.


### 1.2.2. Lean UX Process

En esta sección se presenta el proceso Lean UX aplicado al desarrollo de FoodFlow, con el objetivo de comprender el problema desde la perspectiva del usuario, identificar las principales necesidades del segmento objetivo y establecer hipótesis que orienten la validación de la propuesta de valor. Este proceso incluye la formulación del Lean UX Problem Statement, la definición de supuestos de negocio, usuario y solución, así como la construcción de hipótesis que permiten evaluar la viabilidad, utilidad y adopción de la plataforma.

FoodFlow se plantea como una solución digital enfocada en dueños de restaurantes pequeños y medianos que requieren mayor visibilidad sobre sus ingresos, gastos, inventario, órdenes y rendimiento de platos. A partir de este enfoque, el proceso Lean UX permite alinear las funcionalidades del producto con los problemas reales del usuario, evitando desarrollar una herramienta genérica y priorizando una experiencia simple, visual y orientada a la toma de decisiones.

#### 1.2.2.1. Lean UX Problem Statement

FoodFlow busca ofrecer un entorno digital de gestión financiera y operativa que centralice la información más relevante de un restaurante en una sola plataforma web. A través de este entorno, los dueños de restaurantes pueden visualizar ingresos y pérdidas, revisar reportes financieros, gestionar inventario, controlar órdenes y analizar el desempeño de sus platos, con el propósito de tomar decisiones más informadas y reducir la dependencia de registros manuales o herramientas dispersas.

Hemos observado un factor crítico que afecta el desempeño de muchos restaurantes pequeños y medianos: la falta de visibilidad clara, integrada y oportuna sobre la situación financiera del negocio. Actualmente, varios propietarios gestionan sus operaciones mediante cuadernos, hojas de cálculo, sistemas POS básicos o reportes aislados, lo que dificulta comprender la rentabilidad real, identificar pérdidas, controlar insumos y evaluar el comportamiento de las ventas. Esta fragmentación limita la capacidad del dueño para actuar de manera preventiva y tomar decisiones estratégicas basadas en datos.

El desafío principal consiste en diseñar una plataforma accesible, intuitiva y especializada que permita a los dueños de restaurantes monitorear sus finanzas y operaciones sin requerir conocimientos contables avanzados. FoodFlow debe ofrecer una experiencia clara, visual y práctica, capaz de transformar la información diaria del restaurante en indicadores útiles para mejorar la rentabilidad, optimizar recursos y fortalecer la sostenibilidad del negocio.

¿Cómo podemos diseñar una plataforma web de gestión financiera para restaurantes que centralice ingresos, gastos, inventario, órdenes, reportes y rendimiento de platos, permitiendo que los dueños tomen decisiones estratégicas de manera sencilla, accesible y basada en datos?

#### 1.2.2.2. Lean UX Assumptions

##### Features

* Dashboard financiero con visualización de ingresos, pérdidas y variaciones.
* Reportes financieros diarios, semanales y mensuales.
* Gestión de inventario con visualización de productos, stock, costo unitario y unidad de medida.
* Registro y administración de platos del menú.
* Gestión de órdenes con cálculo de totales y registro de información relevante.
* Visualización de platos más vendidos o con mayor rendimiento.
* Análisis de categorías de gastos mediante gráficos y reportes.
* Gestión de perfil de usuario y datos de cuenta.
* Autenticación mediante registro e inicio de sesión.
* Visualización y gestión de planes de suscripción.

##### Business Outcomes

**Generación de ingresos recurrentes:**  
FoodFlow busca operar bajo un modelo SaaS basado en planes de suscripción, permitiendo generar ingresos mensuales o periódicos a partir del uso de la plataforma por parte de restaurantes pequeños y medianos. Este modelo permite sostener la evolución del producto, mejorar la calidad del servicio y mantener una propuesta accesible para negocios que no pueden asumir los costos de soluciones empresariales complejas.

**Diferenciación en el mercado gastronómico:**  
A diferencia de herramientas contables genéricas o sistemas POS enfocados principalmente en facturación, FoodFlow se posiciona como una solución especializada en la gestión financiera y operativa de restaurantes. Su propuesta de valor se centra en ofrecer dashboards visuales, reportes financieros, control de inventario y análisis de platos en un entorno diseñado específicamente para las necesidades del sector gastronómico.

**Optimización de la toma de decisiones:**  
Uno de los principales resultados esperados es que los dueños de restaurantes puedan dejar de tomar decisiones únicamente por intuición y comiencen a apoyarse en información estructurada. Al centralizar datos de ingresos, gastos, órdenes, inventario y menú, FoodFlow permite que el usuario identifique tendencias, evalúe el rendimiento del negocio y actúe de forma más estratégica.

**Reducción de pérdidas operativas:**  
FoodFlow busca contribuir a la reducción de pérdidas asociadas a una mala gestión de inventario, desconocimiento de gastos, falta de seguimiento de órdenes o ausencia de reportes claros. Al ofrecer una visión más completa del negocio, la plataforma permite identificar áreas críticas y mejorar el control sobre los recursos del restaurante.

**Adopción en restaurantes pequeños y medianos:**  
El producto está orientado a un segmento que requiere soluciones accesibles, sencillas y de rápida implementación. Por ello, FoodFlow busca ser adoptado por restaurantes independientes, cafeterías, pastelerías y negocios gastronómicos que necesitan profesionalizar su gestión sin depender de herramientas demasiado complejas.

##### User Benefits

* Acceso a una visión centralizada de la situación financiera del restaurante desde un dashboard visual.
* Mayor claridad sobre ingresos, gastos, pérdidas y variaciones del negocio.
* Control más organizado del inventario, productos, stock y costos unitarios.
* Identificación de platos con mejor desempeño para apoyar decisiones sobre el menú.
* Registro y seguimiento de órdenes para mantener un control operativo más ordenado.
* Análisis de reportes financieros por distintos periodos de tiempo.
* Reducción del uso de registros manuales, hojas de cálculo dispersas o procesos poco integrados.
* Ahorro de tiempo en la revisión de información financiera y operativa.
* Apoyo en la toma de decisiones estratégicas relacionadas con precios, compras, platos e inventario.
* Experiencia web intuitiva, pensada para usuarios sin conocimientos contables avanzados.

##### Business Assumptions

1. Creemos que los dueños de restaurantes pequeños y medianos están dispuestos a pagar una suscripción si la plataforma les ayuda a comprender mejor sus finanzas, reducir pérdidas y mejorar la rentabilidad del negocio.
2. Creemos que los restaurantes independientes necesitan una solución más especializada que una hoja de cálculo o un sistema POS básico.
3. Creemos que el segmento inicial con mayor potencial está conformado por restaurantes pequeños, cafeterías, pastelerías y negocios gastronómicos que aún gestionan parte de su información de forma manual.
4. Creemos que la competencia principal estará conformada por sistemas POS, software contables genéricos y plataformas de gestión empresarial con mayor complejidad o costo.
5. Creemos que la adopción del producto dependerá de que el usuario perciba rápidamente valor en la visualización de reportes, control de inventario y monitoreo de indicadores financieros.
6. Creemos que la retención dependerá de la frecuencia con la que el dueño utilice el dashboard para revisar la salud financiera de su restaurante.

##### User Assumptions

1. Creemos que los dueños de restaurantes necesitan reportes claros de ingresos y pérdidas para tener un control real sobre el estado económico del negocio.
2. Creemos que los usuarios requieren identificar los platos más vendidos o con mejor desempeño para tomar decisiones sobre precios, menú y compras.
3. Creemos que los dueños valoran una plataforma visual e intuitiva porque no todos cuentan con conocimientos contables avanzados.
4. Creemos que los usuarios prefieren consultar gráficos, tarjetas de resumen y paneles consolidados antes que revisar tablas extensas o archivos dispersos.
5. Creemos que los dueños necesitan revisar información en distintos periodos de tiempo, como reportes diarios, semanales y mensuales.
6. Creemos que los usuarios buscan reducir errores derivados del registro manual y mejorar la organización de sus operaciones.

##### Solution Assumptions

1. Creemos que un dashboard con indicadores de ingresos, gastos y pérdidas permitirá al dueño comprender rápidamente la salud financiera de su restaurante.
2. Creemos que la visualización de reportes diarios, semanales y mensuales facilitará el análisis de tendencias y la toma de decisiones estratégicas.
3. Creemos que un módulo de inventario permitirá mejorar el control de productos, stock, costos y unidades de medida.
4. Creemos que la gestión de órdenes permitirá mantener un registro más organizado de las ventas realizadas.
5. Creemos que el análisis de platos ayudará al dueño a identificar patrones de consumo y oportunidades de mejora en el menú.
6. Creemos que una interfaz clara, accesible y de baja curva de aprendizaje aumentará la adopción de la plataforma.
7. Creemos que la integración de módulos financieros y operativos en una sola aplicación reducirá la dependencia de herramientas externas o procesos manuales.

##### ¿Quién es el usuario?

El usuario principal de FoodFlow es el dueño de un restaurante pequeño o mediano que necesita controlar mejor la situación financiera y operativa de su negocio. También pueden utilizar la plataforma administradores o encargados que participen en el registro de órdenes, revisión de inventario, actualización del menú o consulta de reportes. Estos usuarios buscan una herramienta sencilla, visual y especializada que les permita organizar la información del restaurante sin depender exclusivamente de hojas de cálculo, cuadernos o sistemas poco integrados.

##### ¿Dónde encaja nuestro producto, en su trabajo o en su vida?

FoodFlow se integra directamente en la gestión diaria del restaurante. El producto acompaña al usuario en momentos clave como la revisión de ingresos, el control de gastos, la actualización de inventario, el registro de órdenes, la evaluación del menú y el análisis de reportes financieros. Su función principal es convertirse en un punto central de consulta y control, permitiendo que el dueño tenga una visión clara del desempeño del negocio y pueda tomar decisiones con mayor seguridad.

##### ¿Qué problemas tiene nuestro producto y cómo se pueden resolver?

Los principales riesgos del producto están relacionados con la resistencia al cambio, la percepción de complejidad y la costumbre de seguir utilizando métodos tradicionales como Excel, cuadernos o reportes aislados. Estos problemas pueden resolverse mediante una interfaz intuitiva, una navegación sencilla entre módulos, visualizaciones claras, mensajes de validación comprensibles y una experiencia enfocada en mostrar valor desde el primer uso. De esta manera, FoodFlow debe reducir la fricción inicial y demostrar que centralizar la información permite ahorrar tiempo y mejorar la gestión del restaurante.

##### ¿Cuándo y cómo es usado nuestro producto?

FoodFlow se utiliza de forma recurrente durante la operación y administración del restaurante. El usuario puede acceder a la plataforma al inicio de la jornada para revisar el estado general del negocio, durante el día para registrar o consultar información operativa, y al cierre para analizar ingresos, gastos, órdenes e inventario. También puede emplearse en revisiones semanales o mensuales para evaluar tendencias, comparar resultados y tomar decisiones relacionadas con compras, precios, menú o planificación financiera.

##### ¿Qué características son importantes?

Las características más importantes de FoodFlow son el dashboard financiero, los reportes por periodo, la gestión de inventario, la administración del menú, el registro de órdenes, el análisis de platos, la visualización de gastos por categoría, la autenticación segura, la gestión de perfil y la visualización de planes de suscripción. Estas funcionalidades permiten que el usuario tenga una experiencia integral de control financiero y operativo sin abandonar la simplicidad necesaria para restaurantes pequeños y medianos.

##### ¿Cómo debe verse nuestro producto y cómo debe comportarse?

FoodFlow debe tener un diseño moderno, profesional, claro y visualmente ordenado. La plataforma debe priorizar la lectura rápida de indicadores, el uso de gráficos comprensibles, la navegación simple entre secciones y una distribución de información que no sobrecargue al usuario. Su comportamiento debe ser fluido, confiable y consistente, permitiendo registrar, consultar y analizar información sin procesos innecesarios. La experiencia debe transmitir control, claridad y confianza, de modo que el usuario perciba la plataforma como una herramienta práctica para gestionar mejor su restaurante.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Business Hypotheses

Creemos que, al ofrecer FoodFlow como una plataforma SaaS por suscripción para dueños de restaurantes pequeños y medianos, obtendremos ingresos recurrentes y sostenibles para la startup. Sabremos que hemos tenido éxito cuando al menos el 60 % de los usuarios de prueba se conviertan en clientes de pago después de 30 días.

Creemos que, al centralizar la gestión financiera y operativa en un solo dashboard, para dueños de restaurantes que actualmente trabajan con herramientas dispersas, obtendremos una mayor percepción de valor y uso frecuente de la plataforma. Sabremos que hemos tenido éxito cuando al menos el 70 % de los usuarios ingresen al dashboard tres o más veces por semana.

Creemos que, al posicionar FoodFlow como una solución especializada para restaurantes y no como un software contable genérico, obtendremos una mayor diferenciación frente a POS básicos y herramientas financieras tradicionales. Sabremos que hemos tenido éxito cuando los usuarios identifiquen la especialización gastronómica como una de las principales razones para adoptar la plataforma.

##### User Hypotheses

Creemos que, al mostrar reportes claros de ingresos, gastos y pérdidas, para dueños de restaurantes que necesitan comprender el estado económico de su negocio, obtendremos decisiones más rápidas y mejor sustentadas. Sabremos que hemos tenido éxito cuando el 80 % de los usuarios consulte reportes financieros semanales sin depender de herramientas externas.

Creemos que, al visualizar los platos más vendidos o con mejor desempeño, para dueños que buscan optimizar su menú, obtendremos una mejor capacidad para ajustar precios, priorizar productos y planificar compras. Sabremos que hemos tenido éxito cuando al menos el 50 % de los usuarios realice ajustes en su menú o decisiones relacionadas con platos durante los primeros dos meses de uso.

Creemos que, al incorporar una gestión de inventario clara y actualizada, para restaurantes que presentan quiebres de stock o compras poco planificadas, obtendremos una reducción de pérdidas operativas y una mejor organización de insumos. Sabremos que hemos tenido éxito cuando los usuarios reporten una disminución de al menos 30 % en pedidos no atendidos por falta de productos o insumos.

##### Solution Hypotheses

Creemos que, al consolidar reportes financieros diarios, semanales y mensuales mediante gráficos fáciles de interpretar, para dueños que necesitan analizar tendencias sin revisar grandes volúmenes de datos, obtendremos mayor claridad en el control del negocio. Sabremos que hemos tenido éxito cuando el 70 % de los usuarios valore positivamente la usabilidad de los gráficos en encuestas de satisfacción.

Creemos que, al integrar módulos de dashboard, inventario, menú, órdenes y reportes dentro de una sola aplicación web, para usuarios que actualmente trabajan con información dispersa, obtendremos una experiencia de gestión más ordenada y eficiente. Sabremos que hemos tenido éxito cuando los usuarios indiquen que la plataforma reduce el tiempo dedicado a revisar información del restaurante.

Creemos que, al diseñar una interfaz intuitiva y de baja curva de aprendizaje, para dueños de restaurantes sin conocimientos contables avanzados, obtendremos mayor adopción y menor abandono inicial. Sabremos que hemos tenido éxito cuando la mayoría de usuarios pueda completar tareas básicas como consultar reportes, revisar inventario y visualizar órdenes sin asistencia externa.

Creemos que, al incluir análisis de ventas y rendimiento de platos, para usuarios que necesitan identificar patrones de consumo, obtendremos una mejor comprensión del comportamiento del menú. Sabremos que hemos tenido éxito cuando al menos el 40 % de los usuarios consulte esta información semanalmente durante los primeros tres meses.

<div style="page-break-after: always;"></div>

#### 1.2.2.4. Lean UX Canvas

<img alt="canvas" src="https://github.com/Fundamentos-de-Arquitectura/final-project-report/blob/master/assets/canvas.png?raw=true" />

## 1.3. Segmento Objetivo

Con el objetivo de orientar adecuadamente el desarrollo de FoodFlow y asegurar que la plataforma responda a necesidades reales del mercado gastronómico, se ha definido un único segmento objetivo principal. Este segmento concentra a los usuarios que enfrentan directamente los principales problemas de gestión financiera, control operativo y toma de decisiones dentro de restaurantes pequeños y medianos.

**Segmento objetivo: Dueños de restaurantes**

Este segmento está conformado por propietarios de restaurantes pequeños y medianos que necesitan mejorar el control financiero y operativo de sus negocios. Estos usuarios son responsables de tomar decisiones relacionadas con ingresos, gastos, precios, inventario, platos, compras y rentabilidad; sin embargo, en muchos casos no cuentan con herramientas digitales especializadas que les permitan visualizar esta información de manera clara, centralizada y oportuna.

Los dueños de restaurantes suelen apoyarse en hojas de cálculo, cuadernos, reportes manuales o sistemas POS básicos para registrar parte de sus operaciones. Aunque estas herramientas pueden ser útiles para tareas específicas, no siempre permiten obtener una visión completa del estado financiero del negocio. Por ello, FoodFlow se enfoca en este segmento, ofreciendo una plataforma web que permite monitorear indicadores clave, organizar información operativa y facilitar la toma de decisiones basada en datos.

**Aspectos demográficos:**

* Sexo: Masculino y femenino
* Rango de edad: A partir de los 25 años de edad
* Ocupación: Dueños, propietarios o administradores principales de restaurantes, cafeterías, pastelerías y negocios gastronómicos independientes
* Nivel socioeconómico: clases B y C, principalmente emprendedores y pequeños empresarios con capacidad de inversión en herramientas digitales accesibles
* Nivel de conocimiento tecnológico: básico a intermedio, con disposición a utilizar plataformas web simples e intuitivas

**Aspectos geográficos:**

* Nacionalidad: Principalmente peruana, con proyección hacia el mercado latinoamericano
* Zona geográfica: Urbana
* Ubicación del negocio: Restaurantes ubicados en distritos con actividad comercial, zonas gastronómicas, áreas residenciales con oferta de comida y espacios de alta rotación de clientes

**Aspectos psicográficos:**

* Intereses: Crecimiento del negocio, control financiero, reducción de pérdidas, mejora de rentabilidad, organización del inventario y optimización del menú
* Estilo de vida: Emprendedores gastronómicos con alta carga operativa diaria, acostumbrados a tomar decisiones rápidas y resolver problemas de gestión en tiempo real
* Actitudes: Valoran la practicidad, la claridad visual, el ahorro de tiempo y las herramientas que simplifican procesos administrativos sin exigir conocimientos contables avanzados
* Necesidades: Requieren información confiable sobre ingresos, gastos, órdenes, inventario y rendimiento de platos para tomar decisiones estratégicas con mayor seguridad
* Comportamiento digital: Utilizan herramientas como Excel, sistemas POS, aplicaciones de mensajería, redes sociales y plataformas web para administrar o promocionar su negocio

Este segmento resulta estratégico para FoodFlow porque los dueños de restaurantes son quienes experimentan directamente las consecuencias de una gestión financiera poco organizada. La falta de visibilidad sobre ingresos, gastos, inventario y rentabilidad puede generar decisiones basadas en intuición, compras mal planificadas, desconocimiento de platos poco rentables y pérdidas acumuladas. En ese sentido, FoodFlow busca brindarles una solución accesible, visual y especializada que centralice la información más importante del restaurante en una sola plataforma.

Las estadísticas del sector respaldan la relevancia de este segmento. Según el Instituto Nacional de Estadística e Informática, la actividad de restaurantes en el Perú presentó un crecimiento de 5.32 % en marzo de 2024 y acumuló un incremento de 3.03 % entre enero y marzo del mismo año, en comparación con el periodo similar de 2023 (INEI, 2024). Asimismo, en noviembre de 2024, el sector restaurantes aumentó 4.48 %, acumulando un crecimiento de 3.37 % entre enero y noviembre frente al año anterior (INEI, 2025). Estos datos evidencian que el rubro gastronómico mantiene dinamismo, pero también exige una gestión más eficiente para sostener su crecimiento.

A pesar de este panorama favorable, la sostenibilidad de los negocios gastronómicos continúa siendo un reto. Según Fernando Oré, aproximadamente el 70 % de los negocios relacionados con la venta de comida en el Perú cierran o se traspasan cada año debido a una mala gestión (Guzmán, 2019). Esta situación refuerza la necesidad de soluciones como FoodFlow, orientadas a brindar mayor control financiero, reducir errores operativos y apoyar a los dueños de restaurantes en la toma de decisiones estratégicas para la continuidad de sus negocios.

---

# Capítulo II: Requirements & Analysis

## 2.1 Competidores

En el sector de las soluciones digitales para la gestión financiera, contable y operativa de negocios, existen diversas plataformas que ofrecen herramientas orientadas al control de ingresos, gastos, facturación, reportes e inventario. Sin embargo, no todas se encuentran diseñadas específicamente para las necesidades de restaurantes pequeños y medianos. Por ello, el análisis competitivo de FoodFlow se enfoca en identificar cómo se posiciona frente a herramientas consolidadas como Wave, Xero y Restaurant365, considerando su propuesta de valor, mercado objetivo, nivel de especialización, accesibilidad y funcionalidades principales.

**Wave:**  
Wave es una plataforma de contabilidad en la nube orientada principalmente a pequeños negocios, freelancers y microempresas. Su propuesta se basa en ofrecer herramientas simples para gestionar facturación, pagos, ingresos, gastos y reportes financieros desde un entorno digital accesible. Su principal fortaleza radica en la facilidad de uso y en su enfoque para usuarios que buscan llevar una contabilidad básica sin asumir altos costos iniciales. No obstante, al tratarse de una solución financiera generalista, no está enfocada específicamente en restaurantes ni contempla de forma especializada funcionalidades como análisis de rentabilidad por plato, gestión de menú, control operativo de órdenes o monitoreo de inventario gastronómico. En ese sentido, FoodFlow se diferencia al ofrecer una experiencia más contextualizada para dueños de restaurantes que necesitan comprender el desempeño económico de su negocio desde una perspectiva financiera y operativa.

**Xero:**  
Xero es un software de contabilidad en la nube dirigido a pequeñas y medianas empresas que requieren una solución financiera más robusta. Ofrece funcionalidades como conciliación bancaria, facturación, gestión de gastos, reportes contables, integración con bancos, colaboración con contadores y conexión con múltiples aplicaciones externas. Su fortaleza principal se encuentra en la amplitud de su ecosistema y en su capacidad para adaptarse a empresas con necesidades contables más avanzadas. Sin embargo, esta misma robustez puede representar una curva de aprendizaje mayor para dueños de restaurantes que no poseen conocimientos contables o que buscan una herramienta más directa para revisar ingresos, gastos, inventario y rendimiento de platos. Frente a ello, FoodFlow se posiciona como una alternativa más simple, visual y especializada, enfocada en facilitar la toma de decisiones dentro del contexto gastronómico.

**Restaurant365 (R365):**  
Restaurant365 es una plataforma integral de gestión para restaurantes que combina contabilidad, inventario, operaciones, programación de personal, costos laborales y análisis de datos. Su principal fortaleza es la especialización completa en el sector restaurantero, ya que permite administrar distintas áreas del negocio desde una misma solución. Sin embargo, su alcance está orientado principalmente a restaurantes medianos, grandes cadenas, franquicias o grupos gastronómicos con necesidades operativas más complejas y mayor capacidad de inversión. Esto puede convertirla en una herramienta costosa o sobredimensionada para restaurantes pequeños e independientes. En comparación, FoodFlow se enfoca en brindar una alternativa más ligera, accesible y fácil de implementar, dirigida a negocios gastronómicos que necesitan mejorar su control financiero sin adoptar una plataforma empresarial compleja.

A partir de este análisis, se observa que FoodFlow se ubica en un punto intermedio estratégico. Por un lado, ofrece mayor especialización gastronómica que plataformas contables generales como Wave o Xero; por otro, mantiene una propuesta más accesible y sencilla que soluciones integrales como Restaurant365. Su ventaja competitiva se centra en combinar dashboards financieros, reportes visuales, gestión de inventario, control de órdenes y análisis de platos dentro de una aplicación web pensada para dueños de restaurantes pequeños y medianos. De esta manera, FoodFlow busca diferenciarse no por ofrecer una solución contable compleja, sino por transformar la información diaria del restaurante en datos claros y útiles para la toma de decisiones.
<br>

### 2.1.1. Análisis competitivo.
<table>
  <tr>
    <th colspan="22">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="1">¿Por qué llevar a cabo el análisis?</td>
    <td colspan="17">Este análisis se lleva a cabo con la finalidad de poder conocer la competencia y cómo FoodFlow se diferencia ante esta.</td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td><img src="https://github.com/user-attachments/assets/ea9f01cd-e244-4de2-9f8d-8e95d1b32267" />
<br>FoodFlow</td>
    <td><img alt="image" src="https://github.com/user-attachments/assets/796ca84b-b894-47ea-a4ba-f3c20d30ce96" />
<br>Wave</td>
    <td><img src="https://github.com/user-attachments/assets/2f1d8e77-95c6-4e4c-a426-d3a9fd975be2" />
<br>Xero</td>
    <td><img src="https://github.com/user-attachments/assets/aac638c1-842e-451c-8ae1-634fd98f7601" />
<br>R365</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>FoodFlow es una aplicación web que ofrece gestión financiera especializada para restaurantes. Integra dashboards con reportes visuales y análisis de rentabilidad por plato, con un enfoque en simplicidad y accesibilidad para dueños de restaurantes</td>
    <td>Wave es una plataforma gratuita de contabilidad en la nube que ofrece facturación, gestión de ingresos/gastos, reportes financieros básicos y nómina opcional, enfocada en pequeños negocios y freelancers.</td>
    <td>Xero es un software de contabilidad en la nube para pequeñas y medianas empresas. Ofrece conciliación bancaria automática, facturación, pagos, inventario, proyectos y reportes colaborativos en tiempo real.</td>
    <td>Restaurant365 (R365) es una solución integral para la industria restaurantera, que combina contabilidad, inventario, nómina, recursos humanos y analítica avanzada en una sola plataforma.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td>FoodFlow ofrece simplicidad y accesibilidad: dashboards visuales, análisis de platos y reportes de inventario. Su propuesta de valor se centra en la inteligencia financiera especializada para restaurantes, sin ser un software contable complejo</td>
    <td>Ofrece un software gratuito e intuitivo que permite a pequeños negocios manejar sus finanzas sin conocimientos contables avanzados. Su valor clave es accesibilidad y simplicidad.</td>
    <td>Proporciona un ecosistema financiero robusto con integraciones a más de 1,000 apps, escalabilidad y colaboración en tiempo real, ideal para pymes con crecimiento acelerado.</td>
    <td>Proporciona a restaurantes un control total de operaciones: inventario, contabilidad, nómina y gestión operativa, con datos en tiempo real y optimización de costos alimentarios.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado Objetivo</td>
    <td>Dueños de restaurantes pequeños y medianos, especialmente negocios independientes que requieren control financiero accesible, sin conocimientos contables avanzados</td>
    <td>Pequeños negocios, freelancers y microempresas que buscan soluciones de contabilidad simples y sin costo inicial.</td>
    <td>Pequeñas y medianas empresas que requieren contabilidad avanzada, integraciones y colaboración con contadores.</td>
    <td>Restaurantes medianos, grandes cadenas y franquicias con múltiples locales y necesidades avanzadas de gestión operativa y financiera.</td>
  </tr>
  <tr>
    <td>Estrategias de Marketing</td>
    <td>Publicidad digital, landing page optimizada y redes sociales.</td>
    <td>Enfoque en marketing digital, testimonios de pequeños negocios y atracción mediante la gratuidad de la plataforma.</td>
    <td>Marketing basado en partners contables, agencias financieras y presencia activa en mercados internacionales mediante integraciones y alianzas.</td>
    <td>Posicionamiento como solución “todo en uno” para restaurantes, campañas directas al sector HORECA y alianzas con POS y bancos.</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos y Servicios</td>
    <td>Dashboard financiero visual, análisis de ventas por plato, gestión de menú, gestión de inventario y reportes.</td>
    <td>Software de contabilidad gratuito, facturación, reportes financieros, payroll (opcional y pago).</td>
    <td>Software de contabilidad integral: facturación, inventario, conciliación bancaria, proyectos, análisis financiero, pagos integrados.</td>
    <td>Plataforma integral de gestión de restaurantes: contabilidad, inventario, compras, nómina, recursos humanos, reportes avanzados.</td>
  </tr>
  <tr>
    <td>Precios y Costos</td>
    <td>Modelo de suscripción mensual accesible para pequeños y medianos restaurantes</td>
    <td>Gratuito (se cobra por servicios extra como nómina o pagos electrónicos).</td>
    <td>Planes desde ~20 USD/mes hasta planes superiores según necesidades. Modelo SaaS con escalabilidad.</td>
    <td>Planes de suscripción elevados, orientados a cadenas y grupos de restaurantes. No es accesible para negocios muy pequeños.</td>
  </tr>
  <tr>
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td>Plataforma web.</td>
    <td>Plataforma web y aplicación móvil. Integración directa con bancos y servicios de pago.</td>
    <td>Plataforma web y aplicación móvil para Android/iOS. Marketplace con más de 1,000 integraciones.</td>
    <td>Plataforma web y aplicación móvil. Integración con POS, bancos y proveedores específicos de la industria restaurantera.</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Especialización en finanzas para restaurantes con usabilidad sencilla, dashboards visuales y accesibilidad</td>
    <td>Plataforma gratuita, fácil de usar, ideal para pequeños negocios. Acceso sencillo a facturación y reportes básicos.</td>
    <td>Contabilidad robusta, integraciones masivas, colaboración en tiempo real y escalabilidad internacional.</td>
    <td>Especialización total en el sector restaurantero, integración de todas las áreas de negocio en una sola plataforma.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Poca experiencia en el mercado y menor reconocimiento frente a grandes competidores</td>
    <td>Limitado para negocios medianos o grandes. Pocas integraciones y soporte al cliente limitado.</td>
    <td>Más costoso que Wave, requiere curva de aprendizaje y no está especializado en restaurantes.</td>
    <td>Alto costo de implementación, complejo de usar para pequeños negocios o restaurantes independientes.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Crecer en latino-américa como alternativa accesible, integrando inteligencia financiera en un nicho poco explotado</td>
    <td>Ampliar integraciones, mejorar soporte y penetrar mercados emergentes donde la contabilidad digital aún es baja.</td>
    <td>Crecer en LATAM y mercados emergentes, integrar más fintech y potenciar su ecosistema de pagos tras la adquisición de Melio.</td>
    <td>Expansión global en restaurantes, integración con IA para forecasting y optimización avanzada de operaciones.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Alta competencia con software contables y POS que agregan módulos financieros</td>
    <td>Competencia de software más robusto como Xero o QuickBooks. Posibles problemas regulatorios en servicios financieros.</td>
    <td>Alta competencia con QuickBooks, Wave y nuevas fintech contables. Amenaza de disrupción por IA y open banking.</td>
    <td>Competencia de otras plataformas de gestión de restaurantes y de software financiero más barato y accesible.</td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

## 2.1.2. Estrategias y Tácticas Competitivas de FoodFlow

| **Competidor**                                      | **Estrategia de FoodFlow**                                                                                                                                                          | **Tácticas concretas**                                                                                                                                                                                                                                                                                                             |
|-----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Wave** (software gratuito para pequeños negocios) | **Diferenciación en especialización**: Wave es gratis, pero genérico. FoodFlow debe posicionarse como solución **hecha para restaurantes**, con herramientas que Wave no ofrece.    | - Campañas de marketing destacando funciones exclusivas para restaurantes (ej. “control de rentabilidad por plato” o “gestión de inventario inteligente”).<br>- Generar alianzas con asociaciones de restaurantes locales para aumentar confianza.                                                                                 |
| **Xero** (software contable robusto y global)       | **Enfoque en simplicidad y curva de aprendizaje baja**: competir con facilidad de uso frente a la complejidad y costo de Xero.                                                      | - Ofrecer **onboarding guiado** con tutoriales sencillos para dueños de restaurantes sin experiencia contable.<br>- Precio competitivo enfocado en pequeños y medianos restaurantes de LATAM.<br>- Integrar funciones de reportes financieros con ejemplos prácticos del sector gastronómico (ej. “costos por plato más vendido”). |
| **R365** (plataforma integral, cara y compleja)     | **Accesibilidad en costos + cercanía con negocios independientes**: mientras R365 apunta a grandes cadenas, FoodFlow se posiciona como la **alternativa ligera, ágil y asequible**. | - Estrategia de precios escalonados (plan para pequeños restaurantes, plan avanzado para medianas cadenas).<br>- Marketing enfocado en **“empoderar a restaurantes independientes”**.<br>- Incorporar progresivamente módulos opcionales para crecer sin perder simplicidad.                                                       |


### Estrategia Global de FoodFlow
1. **Posicionamiento claro**: “La plataforma de gestión financiera hecha a medida para restaurantes independientes y medianos”.
2. **Go-to-Market en LATAM**: aprovechar la baja digitalización financiera de restaurantes en la región para ganar mercado más rápido que competidores globales.
3. **Simplicidad como bandera**: mientras otros ofrecen robustez y complejidad, FoodFlow se mantiene ágil y fácil de usar.
4. **Construcción de comunidad**: generar una red de dueños de restaurantes que compartan experiencias y testimonios.

<div style="page-break-after: always;"></div>

## 2.2 Entrevistas
En esta sección, se presentan los resultados de las entrevistas realizadas a dueños de restaurantes para comprender sus necesidades, desafíos y expectativas en relación con la gestión financiera y operativa de sus negocios. Se incluyen citas textuales y análisis de las respuestas obtenidas.

### 2.2.1. Diseño de entrevistas

A continuación, se presentan las preguntas para las entrevistas del segmento objetivo.  
Con el fin de optimizar el tiempo y facilitar la recopilación de datos, se hará uso de Google Forms para recolectar información adicional.

#### Preguntas para el segmento "Dueños de restaurantes"

- ¿Cuántos años lleva operando su restaurante y qué tipo de comida ofrecen?
- ¿Cuál diría que es su principal reto operativo día a día?
- ¿Cómo lleva actualmente el control de sus finanzas? (Excel, cuaderno, sistema POS, contador, etc.)
- ¿Con qué frecuencia revisa los números de su negocio y qué tan fácil le resulta obtener esa información?
- ¿Tiene claridad sobre cuáles son sus platos más rentables?
- ¿Exporta información a Excel o comparte reportes financieros con alguien más?
- ¿Qué información le gustaría tener para tomar mejores decisiones sobre precios, menú o compras?
- ¿Ha tenido que quitar o cambiar platos del menú? ¿En base a qué criterios?
- ¿Cómo controla su inventario y con qué frecuencia se queda sin ingredientes importantes?
- ¿Le sería útil tener un panel donde pueda ver de un vistazo sus ganancias, pérdidas y tendencias?
- ¿Valoraría tener gráficos que muestren sus platos más y menos vendidos para hacer ajustes en su menú?
- ¿Con qué frecuencia le gustaría revisar esta información? (diaria, semanal, mensual)
- ¿Prefiere ver la información en gráficos o en tablas con números?
- ¿Estaría dispuesto a usar una aplicación web que le ayude a monitorear las finanzas de su restaurante?
- ¿Qué tan cómodo se siente usando tecnología para su negocio?
- ¿Cuánto estaría dispuesto a pagar mensualmente por una herramienta que le ayude a gestionar mejor las finanzas?
- ¿Preferiría algo muy intuitivo o no le importaría dedicar tiempo a aprender?
- ¿Si tuviera acceso a mejor información financiera, qué cambios haría en su restaurante?
- ¿Qué dudas o preocupaciones tendría antes de usar una herramienta como FoodFlow?

### 2.2.2. Registro de entrevistas.

En esta sección se aborda la información recolectada de cada entrevista incluyendo un resumen de las respuestas de los entrevistados.

#### Segmento Objetivo: Dueños de restaurantes.

- _Entrevista 1_


| Nombre               | Clara                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------|
| Apellido             | Canahualpa                                                                                                                      |
| Edad                 | 49                                                                                                                              |
| Distrito             | La Molina                                                                                                                       |
| Evidencia            | <img src="https://github.com/user-attachments/assets/e8053896-d2d0-4f92-9c76-e892319ca6bf" /> |
| Url                  | https://acortar.link/Vu9w5X |
| Inicio de entrevista | 00:00:01                                                                                                                        |
| Fin de entrevista    | 00:11:19                                                                                                                        |

- Distrito de residencia:
- Estado civil:
- Ocupación: Dueño de restaurante
- Dispositivo de preferencia: Laptop
- Canales de interacción digital: Facebook, LinkedIn

### Resumen de entrevista:

La entrevistada es Clara Canahualpa, encargada de la producción de postres en la pastelería–cafetería Horneando Amores, ubicada en La Molina, Lima. El negocio lleva alrededor de diez años en funcionamiento y su principal reto diario es lograr mayores ventas. Actualmente, el 80% de la oferta corresponde a productos dulces y el 20% a salados.
Para la gestión financiera, utilizan el sistema ODO, aunque Clara no revisa personalmente los números; esta labor la realizan dos de sus hijas. Una se encarga de la contabilidad, control de inventario y materiales, mientras que la otra gestiona al personal, siendo este último un punto crítico debido a la alta rotación en el área de salados.
En cuanto a la oferta de productos, los más rentables y demandados son el queque de arándano, tres leches (de algarrobina y coco), carrot cake, queques de plátano, crocante de chocolate y pie de limón. Clara recibe reportes diarios en Excel sobre el stock y la producción necesaria, lo que le permite planificar la elaboración de postres.
Sobre el control de inventarios, la información se obtiene principalmente del sistema ODO y de registros manuales en una pizarra. El sistema genera alertas de productos bajos en stock, siempre que la información sea cargada de forma adecuada.
Clara considera muy útil contar con paneles gráficos interactivos que muestren ventas, ganancias, pérdidas y platos más vendidos, y afirma que los consultaría cada tres o cuatro días. Respecto al costo de la plataforma, sabe que es anual y solía rondar los $1,500, aunque ahora es menor; sin embargo, este aspecto también lo maneja su hija.
En cuanto a los planes futuros, se encuentran en un proceso de relanzamiento con nuevos postres, manteniendo su estilo artesanal. Uno de los objetivos principales es fortalecer la presencia en redes sociales, para lo cual han contactado a una persona encargada de marketing digital.
En síntesis, Clara se enfoca principalmente en la producción y el control básico de personal, mientras delega las finanzas y el inventario a sus hijas. El negocio busca innovar con nuevos postres y crecer a través de una mejor estrategia de marketing digital.

- _Entrevista 2_

| Nombre               | Liliana                                                                                                                               |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Apellido             | Barrera                                                                                                                               |
| Edad                 | 52 años                                                                                                                               |
| Distrito             | Los Olivos                                                                                                                            |
| Evidencia            | <img src="https://github.com/user-attachments/assets/dbee5e0a-a6ad-4b38-960d-82c18a16e80e" /> |
| Url                  | https://goo.su/bD7IT                                                                                                                  |
| Inicio de entrevista | 00:11:28                                                                                                                              |    
| Fin de entrevista    | 00:17:40                                                                                                                              |

- Distrito de residencia: Los Olivos
- Estado civil: Casada
- Ocupación: Dueño de restaurante
- Dispositivo de preferencia: Smartphone
- Canales de interacción digital: Instagram, X

### Resumen de entrevista:

La entrevistada es Liliana Barrera, dueña de un restaurante de comida criolla con 3 años de operación,
donde su principal reto diario es mantener la frescura de los ingredientes y la calidad del servicio.
Actualmente, gestiona sus finanzas en Excel con apoyo de un contador y revisa sus números semanalmente,
identificando que platos como el ceviche y el lomo saltado son los más rentables. Aunque controla el inventario manualmente,
suele quedarse sin insumos un par de veces al mes, por lo que valora la posibilidad de tener un control de inventario y contar con un panel
visual que muestre ganancias, pérdidas, tendencias y rentabilidad por plato en gráficos fáciles de interpretar. Está dispuesta a usar una aplicación web intuitiva,
pagar alrededor de S/100 mensuales por ella y aprovechar la información financiera para ajustar precios y menú; sin embargo, expresa preocupación por la facilidad de uso y
la seguridad de los datos.

- _Entrevista 3_

| Nombre               | Gonzalo                                                                                                                             |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Apellido             | Elio                                                                                                                                |
| Edad                 | 58 años                                                                                                                             |
| Distrito             | San Isidro                                                                                                                          |
| Evidencia            | <img alt="werner" src="https://github.com/user-attachments/assets/8391123a-2d53-45e7-bf9b-407177041d5f" /> |
| Url                  | https://goo.su/bD7IT                                                                                                                |
| Inicio de entrevista | 00:17:44                                                                                                                            |
| Fin de entrevista    | 00:28:10                                                                                                                            |

- Distrito de residencia: San Isidro
- Estado civil: Conviviente
- Ocupación: Dueño de restaurante
- Dispositivo de preferencia: Laptop
- Canales de interacción digital: Facebook, LinkedIn

### Resumen de entrevista:

Gonzalo Elio es dueño de un restaurante donde principalmente ofrece cafe y postres, con 1 año y media de experiencia en el rubro.
Su mayor desafío es gestionar el inventario y las finanzas de manera eficiente. Actualmente, utiliza un sistema rudimentario
para llevar el control financiero y revisa los números mensualmente, aunque le gustaría hacerlo con mayor frecuencia.
Identifica que sus productos más rentables son los cafés y postres. Aunque no tiene un sistema formal para controlar el inventario,
suele quedarse sin ingredientes esenciales una vez al mes. Valora la idea de tener un control de inventario y
un panel visual que le permita monitorear ganancias, pérdidas y tendencias de manera sencilla.
Está dispuesto a usar una aplicación web, pagar alrededor de S/300 mensuales y aprovechar la información
financiera para optimizar precios y menú.
Sin embargo, expresa preocupación por la seguridad de los datos y la facilidad de uso de la herramienta.


### 2.2.3. Análisis de entrevistas
El análisis de las tres entrevistas revela que, a pesar de las diferencias en tamaño, experiencia y tipo de negocio, todos los entrevistados comparten retos similares relacionados con la gestión de inventarios y la necesidad de contar con información financiera clara y accesible. Clara Canahualpa, con un negocio de mayor trayectoria, utiliza un sistema más estructurado pero depende de sus hijas para la revisión de finanzas e inventario, lo que la aleja de la toma directa de decisiones. Gonzalo Elio, con menor tiempo en el rubro, enfrenta dificultades en el control de insumos y finanzas, usando métodos rudimentarios que limitan la eficiencia de su gestión. Liliana Barrera, en cambio, trabaja con Excel y apoyo de un contador, lo que le permite tener mayor control, aunque aún enfrenta problemas de quiebres de stock.

En los tres casos se evidencia la necesidad de una herramienta digital que facilite el control financiero y de inventario, especialmente mediante paneles gráficos y un sistema de gestión de inventario que ayuden a evitar pérdidas y mejorar la planificación. También coinciden en que contar con información clara les permitiría ajustar precios, introducir nuevos productos y tomar mejores decisiones estratégicas. Las diferencias surgen en la disposición de inversión, pues mientras Gonzalo está dispuesto a pagar un monto relativamente alto por una solución web, Liliana considera un pago más reducido y Clara ya invierte en un sistema, aunque no se involucra directamente en los costos. Finalmente, tanto Gonzalo como Liliana expresan preocupación por la seguridad de los datos y la facilidad de uso, lo que refuerza la importancia de diseñar soluciones intuitivas y confiables.

#### Estadísticas de entrevistas

Además de las entrevistas personales, a cada entrevistado se le compartió un enlace al formulario realizado con el objetivo de conocer su personalidad a detalle. A continuación se demuestran las estadísticas a las respuestas obtenidas

<img alt="1" src="https://github.com/user-attachments/assets/cdf933b2-255f-4d91-bead-7c73eef19096" />

<img alt="2" src="https://github.com/user-attachments/assets/ee63e3bb-a6f3-4c20-952e-cbad7bf24b30" />

<img src="https://github.com/user-attachments/assets/9a934f16-4dcd-4e0a-922d-2b85195c8411" />

<img src="https://github.com/user-attachments/assets/86d192a7-8323-4db8-a30a-d3efabe9ed30" />

<img src="https://github.com/user-attachments/assets/00251e3d-119c-417e-8967-c8ee26380fc5" />

<img src="https://github.com/user-attachments/assets/4b207734-acaf-48c1-bf13-b3d13bc85615" />

<img src="https://github.com/user-attachments/assets/e94e21e4-b784-408c-bc7c-336ebb833502" />

Enlace al formulario: https://forms.fillout.com/t/xcdy5bB5ZKus

## 2.3 Needfinding

En esta sección se presenta el análisis detallado de la información recolectada durante las entrevistas realizadas a los distintos perfiles involucrados en la gestión financiera de restaurantes. El objetivo principal del proceso de Needfinding ha sido identificar necesidades reales, motivaciones, frustraciones y patrones de comportamiento de los usuarios para guiar el diseño de una solución centrada en ellos.<br>
Los artefactos incluidos User Persona, User Task Matrix, User Journey Maps, Empathy Mapping y As-Is Scenario Mapping, permiten visualizar, sintetizar y comprender de manera estructurada la experiencia actual de los usuarios, sus tareas clave, emociones, puntos de dolor y oportunidades de mejora. Este análisis constituye la base para el diseño de soluciones alineadas con sus contextos y objetivos reales.

<div style="page-break-after: always;"></div>

### 2.3.1 User Personas

<img alt="up" src="https://github.com/user-attachments/assets/429040b1-6c9f-48b6-b20e-78ef7922135a" />

<div style="page-break-after: always;"></div>

### 2.3.2 User Task Matrix

En esta sección, se presenta la matriz de tareas de los usuarios, que muestra las actividades realizadas por los dueños junto con su frecuencia e importancia. Esta matriz ayuda a identificar las tareas clave y
su relevancia para cada tipo de usuario.

Para ello, usamos el user persona creado en la sección anterior tomando a Sofía Ríos, segmento: Dueños de restaurantes

| Actividades                                  | Sofía Ríos (Dueña de restaurante) - Frecuencia / Importancia |
|----------------------------------------------|--------------------------------------------------------------|
| Revisar caja diaria manualmente              | Siempre / Alta                                               |
| Hacer cálculos de ganancias en papel/Excel   | Siempre / Alta                                               | 
| Contar efectivo y arqueo de caja             | Con Frecuencia / Alta                                        | 
| Calcular costos de platos manualmente        | Con Frecuencia / Alta                                        | 
| Anotar productos faltantes en papel          | Con Frecuencia / Media                                       | 
| Calcular necesidades de compra mentalmente   | Siempre / Alta                                               | 
| Contar inventario físicamente                | Siempre / Alta                                               | 
| Identificar platos populares por observación | Siempre / Alta                                               |
| Organizar facturas y comprobantes físicos    | Con Frecuencia / Media                                       |

Sofía representa a una dueña de restaurante experimentada enfocada en la optimización operativa y el
mejoramiento de la eficiencia del negocio. Su enfoque está en actividades estratégicas como el manejo financiero
y la gestión de inventario, que realiza con alta frecuencia e importancia.

<div style="page-break-after: always;"></div>

### 2.3.3 User Journey Mapping

***Segmento objetivo: Dueños de restaurantes***
<p align="center">
  <img src="assets/User_Journey_Mapping.png" alt="UJM" width="1000">
</p>

### 2.3.4 Empathy Map
Esta sección presenta el Empathy Map desarrollado para el User Persona. El proceso de elaboración incluyó la reflexión colaborativa del equipo en torno a la experiencia, necesidades, pensamientos, emociones y percepciones de cada usuario. Este mapa permite profundizar en la comprensión de sus contextos y motivaciones, respondiendo preguntas clave sobre lo que ven, escuchan, piensan, sienten, dicen y hacen. A partir de este análisis, se identificaron sus Pains y Gains, los cuales servirán como base para el diseño de una propuesta de valor relevante. <br>

#### Segmento Objetivo: Dueños de restaurantes. <br>

<img alt="image" src="https://github.com/user-attachments/assets/77ab6fd0-017d-4cae-a71d-3fe5ef1c2174" />

<div style="page-break-after: always;"></div>

### 2.3.5 As-is Scenario Mapping

<img alt="image" src="https://github.com/user-attachments/assets/4b90976d-fe02-4fd8-b28b-9b58e7b1f2d9" />

### 2.4 Ubiquitous Language

| Término | Definición |
| :--- | :--- |
| **Dueño de restaurante** | Propietario o administrador principal de un negocio gastronómico pequeño o mediano, y usuario principal de la plataforma. |
| **Dashboard financiero** | Panel visual centralizado que muestra un resumen rápido de ingresos, pérdidas, porcentajes de variación y el estado general del negocio. |
| **Inventario** | Registro digital de productos e ingredientes que permite controlar el stock actual, costo unitario y unidad de medida. |
| **Menú** | Catálogo digital gestionable de los platos ofrecidos por el restaurante, que detalla nombre, descripción, precio e ingredientes. |
| **Órdenes** | Registro operativo de los pedidos de los clientes, que asocia los platos solicitados a una mesa específica y calcula automáticamente el precio total. |
| **Rentabilidad por plato** | Indicador que clasifica y muestra los platos más populares y vendidos para ayudar en la toma de decisiones sobre precios y compras. |
| **Reporte financiero** | Consolidado visual de datos económicos que permite analizar ingresos y gastos filtrados por períodos (diario, semanal, mensual). |
| **Quiebre de stock** | Situación operativa en la que el restaurante se queda sin ingredientes importantes, generando pedidos no atendidos. |
| **Categoría de gasto** | Clasificación específica de los egresos del restaurante, utilizada en los reportes para identificar áreas de optimización de costos. |
| **Plan de suscripción** | Modelo de servicio SaaS que determina el nivel de acceso (ej. Básico, Premium) a las funcionalidades de la plataforma mediante un pago recurrente. |

<hr>

# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping

Este es el escenario futuro (To-Be) que describe cómo los usuarios interactuarán con el sistema propuesto para satisfacer
sus necesidades y alcanzar sus objetivos. El escenario To-Be se basa en la comprensión de los problemas actuales y las
oportunidades de mejora identificadas en el escenario As-Is. El objetivo es proporcionar una visión clara de cómo el
sistema debe funcionar para mejorar la experiencia del usuario y cumplir con los requisitos del negocio.

Esta es la descripción del escenario futuro (To-Be) para el dueño de un restaurante, después de implementar la solución
tecnológica. Esta solución está diseñada para mejorar las operaciones del restaurante, aumentar la eficiencia, las
ventas y finanzas del negocio.

<img alt="f" src="https://github.com/user-attachments/assets/080a297f-8905-4287-abb7-18aa668b8978" />

<div style="page-break-after: always;"></div>

## 3.2 User Stories

Para la planeación y desarrollo del proyecto, se han definido las siguientes épicas y user stories que describen las funcionalidades clave del sistema desde la perspectiva del usuario final, en este caso, el dueño de un restaurante.

### Epics

| ID     | Título          | Descripción                                                                                                                                                                                                                            |
|:-------|:----------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **E1** | Dashboard       | Permite a los dueños de restaurantes visualizar un resumen de los ingresos y pérdidas, así como identificar los platos más populares y la situación financiera general del negocio.                                                    |
| **E2** | Inventory       | Permite a los dueños de restaurantes gestionar y controlar el inventario de productos, incluyendo la visualización del stock actual y la adición de nuevos productos con validación de campos.                                         |
| **E3** | Menu Management | Permite a los dueños de restaurantes gestionar el menú, incluyendo la adición de nuevos platos, la búsqueda de platos existentes y la visualización de la información completa del menú.                                               |
| **E4** | Orders          | Permite a los dueños de restaurantes gestionar las órdenes de los clientes, desde la visualización de órdenes existentes hasta el registro, confirmación, edición, eliminación y cálculo de los órdenes.                               |
| **E5** | Reports         | Permite a los dueños de restaurantes generar y visualizar reportes financieros, incluyendo ingresos y gastos diarios, con la capacidad de navegar entre diferentes períodos de tiempo y analizar el desglose de gastos por categorías. |
| **E6** | Profiles        | Permite a los dueños de restaurantes gestionar su perfil de usuario, incluyendo la actualización de información personal y la configuración de preferencias.                                                                           |
| **E7** | Authentication  | Permite la autenticación y gestión de acceso de los usuarios del sistema, incluyendo el registro, inicio de sesión y control de roles y permisos.                                                                                      |

### User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|-------------------------|---------------------------|
| US01 | Visualizar ingresos y pérdidas | Como dueño de restaurante, deseo ver en el dashboard un resumen de mis ingresos y pérdidas para conocer rápidamente la situación financiera de mi negocio. | **Scenario 1:** <br> Given que estoy en la pantalla principal del dashboard <br> When ingreso al sistema <br> Then puedo visualizar el monto total de ingresos y pérdidas, junto con el porcentaje de variación (+ o -). | EP01 |
| US02 | Identificar platos más populares | Como dueño de restaurante, deseo ver un listado de mis platos más vendidos para saber cuáles son los más rentables y tomar decisiones sobre el menú. | **Scenario 1:** <br> Given que accedo al dashboard <br> When consulto la sección “Top 5 Dishes” <br> Then puedo ver un ranking de los platos más populares acompañado de barras comparativas de ventas. | EP01 |
| US03 | Visualizar inventario actual | Como dueño de restaurante, deseo ver una tabla con el stock, costo unitario y unidad de medida de cada producto para controlar el inventario de manera clara y rápida. | **Scenario 1:** <br> Given que estoy en la sección “Inventory Management” <br> When ingreso al sistema <br> Then visualizo una tabla con los productos, su stock actual, costo unitario y unidad de medida. | EP02 |
| US04 | Agregar un nuevo producto al inventario | Como dueño de restaurante, deseo registrar un nuevo producto con su nombre, stock, costo unitario y unidad de medida para mantener actualizado mi inventario. | **Scenario 1:** <br> Given que estoy en la sección “Add New Product” <br> When ingreso el nombre del producto, stock, costo y unidad de medida, y presiono “Add Product” <br> Then el nuevo producto se añade a la tabla del inventario con sus datos correctos. | EP02 |
| US05 | Validar campos al agregar producto | Como dueño de restaurante, deseo que el sistema valide los campos obligatorios al agregar un producto para evitar errores en el registro del inventario. | **Scenario 1:** <br> Given que quiero registrar un producto <br> When dejo un campo vacío o ingreso un valor inválido, por ejemplo, letras en “Unit Cost” <br> Then el sistema muestra un mensaje de error y no permite guardar el producto hasta que la información sea correcta. | EP02 |
| US06 | Agregar Nuevo Plato | Como dueño de restaurante, deseo agregar nuevos platos al menú para mantener mi oferta actualizada y atractiva para los clientes. | **Scenario 1: Agregar plato exitosamente** <br> Given que estoy en la página de gestión de menú <br> When completo el formulario con nombre del plato, descripción y precio válidos, y hago clic en "Add Dish" <br> Then el nuevo plato se agrega a la lista de platos existentes, aparece un mensaje de confirmación y los campos del formulario se limpian automáticamente. <br><br> **Scenario 2: Validación de campos obligatorios** <br> Given que estoy en la página de gestión de menú <br> When intento agregar un plato sin completar todos los campos requeridos y hago clic en "Add Dish" <br> Then el sistema muestra mensajes de error indicando los campos faltantes y el plato no se agrega a la lista. <br><br> **Scenario 3: Validación de precio** <br> Given que estoy completando el formulario de nuevo plato <br> When ingreso un precio inválido, negativo, texto o vacío, e intento guardar el plato <br> Then el sistema muestra un mensaje de error sobre el formato del precio y no permite guardar el plato hasta corregir el valor. | EP03 |
| US07 | Buscar Platos Existentes | Como dueño de restaurante, deseo buscar platos específicos en mi menú para encontrar rápidamente la información que necesito. | **Scenario 1: Búsqueda exitosa** <br> Given que tengo platos en mi lista de menú <br> When escribo el nombre de un plato en el campo de búsqueda <br> Then el sistema filtra y muestra solo los platos que coinciden con mi búsqueda, y los resultados se actualizan en tiempo real mientras escribo. <br><br> **Scenario 2: Búsqueda sin resultados** <br> Given que estoy en la página de gestión de menú <br> When busco un plato que no existe en mi menú <br> Then el sistema muestra un mensaje indicando que no se encontraron resultados y la tabla permanece vacía. <br><br> **Scenario 3: Limpiar búsqueda** <br> Given que he realizado una búsqueda previa <br> When borro el contenido del campo de búsqueda <br> Then se muestran nuevamente todos los platos del menú. | EP03 |
| US08 | Visualizar Información Completa del Menú | Como dueño de restaurante, deseo visualizar toda la información de mis platos, nombre, descripción, precio e ingredientes, en una tabla organizada para tener control total sobre mi menú. | **Scenario 1: Visualización completa** <br> Given que tengo platos registrados en mi sistema <br> When accedo a la página de gestión de menú <br> Then veo una tabla con todos mis platos, y cada fila muestra nombre, descripción, precio, ingredientes y acciones disponibles, con la información claramente organizada y fácil de leer. <br><br> **Scenario 2: Manejo de lista vacía** <br> Given que no tengo platos registrados <br> When accedo a la página de gestión de menú <br> Then veo un mensaje indicando que no hay platos disponibles, y el formulario para agregar nuevos platos está visible y accesible. | EP03 |
| US09 | Visualizar órdenes existentes | Como dueño de restaurante, deseo ver en una tabla las órdenes realizadas con su mesa, platos, precio total y fecha para llevar un control claro y rápido de los órdenes. | **Scenario 1:** <br> Given que estoy en la sección "Orders" <br> When ingreso al sistema <br> Then puedo ver una tabla con las órdenes registradas mostrando mesa, platos, precio total y fecha. <br><br> **Scenario 2:** <br> Given que existen múltiples órdenes en diferentes fechas <br> When consulto la tabla <br> Then estas deben aparecer en orden cronológico por defecto. <br><br> **Scenario 3:** <br> Given que visualizo las órdenes <br> When reviso cada fila <br> Then puedo identificar a qué mesa corresponde y qué platos se pidieron. | EP04 |
| US10 | Calcular el total por plato | Como dueño de restaurante, deseo que el sistema calcule automáticamente el precio total de cada plato para evitar errores de facturación manual. | **Scenario 1:** <br> Given que agrego un plato con su precio unitario <br> When especifico la cantidad <br> Then el sistema debe calcular y mostrar el precio total en la columna correspondiente. | EP04 |
| US11 | Visualización de Reportes Financieros Diarios | Como dueño de restaurante, deseo ver mis ingresos y gastos diarios en un dashboard centralizado para tomar decisiones informadas sobre el rendimiento financiero de mi negocio. | **Scenario 1: Visualización de ingresos diarios** <br> Given que estoy en la sección de Reportes <br> When selecciono la pestaña "Daily" <br> Then debo ver el total de ingresos del día y debo ver el porcentaje de cambio respecto al día anterior. <br><br> **Scenario 2: Visualización de gastos diarios** <br> Given que estoy en la sección de Reportes diarios <br> When reviso la sección de gastos <br> Then debo ver el total de gastos del día y debo ver el porcentaje de cambio respecto al día anterior. | EP05 |
| US12 | Navegación entre Períodos de Tiempo | Como dueño de restaurante, deseo poder alternar entre reportes diarios, semanales y mensuales para analizar tendencias en diferentes períodos de tiempo. | **Scenario 1: Cambio a vista semanal** <br> Given que estoy visualizando reportes diarios <br> When hago clic en la pestaña "Weekly" <br> Then debo ver los datos financieros agregados de la semana actual y la pestaña "Weekly" debe aparecer como activa. <br><br> **Scenario 2: Cambio a vista mensual** <br> Given que estoy en cualquier vista de reportes <br> When selecciono la pestaña "Monthly" <br> Then debo ver los datos financieros del mes en curso y todos los gráficos deben actualizarse para mostrar datos mensuales. | EP05 |
| US13 | Análisis de Categorías de Gastos | Como dueño de restaurante, deseo visualizar el desglose de mis gastos por categorías para identificar áreas donde puedo optimizar costos. | **Scenario 1: Visualización de gastos por categoría** <br> Given que estoy en la sección de reportes <br> When reviso la sección de gastos <br> Then debo ver las categorías con sus respectivos montos y cada categoría debe tener una representación visual. <br><br> **Scenario 2: Comparación entre categorías** <br> Given que tengo gastos en múltiples categorías <br> When visualizo el desglose de gastos <br> Then debo poder comparar fácilmente qué categoría representa mayor gasto y los datos deben estar claramente etiquetados. | EP05 |
| US14 | Visualizar Planes de Suscripción | Como dueño de restaurante, deseo ver los diferentes planes de suscripción disponibles para conocer las opciones y beneficios antes de decidirme. | **Scenario 1: Visualización de planes disponibles** <br> Given que accedo a la sección “Subscriptions” <br> When ingreso al sistema <br> Then puedo visualizar una lista de planes con su nombre, precio y beneficios correspondientes. <br><br> **Scenario 2: Manejo de error al cargar planes** <br> Given que ocurre un error al cargar los planes desde el servidor <br> When accedo a la sección “Subscriptions” <br> Then el sistema muestra un mensaje informando que no se pudieron cargar los planes e invita a reintentar la operación. | EP06 |
| US15 | Suscribirse al Plan Premium | Como dueño de restaurante, deseo poder suscribirme al plan premium para acceder a funcionalidades avanzadas que mejoren la gestión de mi negocio. | **Scenario 1: Suscripción exitosa al plan premium** <br> Given que estoy en la sección “Subscriptions” y tengo un método de pago válido <br> When selecciono el plan “Premium” y confirmo el pago <br> Then el sistema activa mi suscripción premium, actualiza mi estado de cuenta y muestra un mensaje de confirmación exitoso. <br><br> **Scenario 2: Error en el pago** <br> Given que intento suscribirme al plan premium <br> When se produce un error en el proceso de pago, por ejemplo, tarjeta rechazada <br> Then el sistema muestra un mensaje de error indicando que la transacción no se pudo completar y mantiene mi suscripción en el estado anterior. <br><br> **Scenario 3: Visualizar beneficios activos** <br> Given que tengo una suscripción premium activa <br> When regreso al dashboard o a la sección “Subscriptions” <br> Then debo ver claramente que mi plan actual es “Premium” y los beneficios asociados están habilitados. | EP06 |
| US16 | Cancelar Suscripción | Como dueño de restaurante, deseo poder cancelar mi suscripción de pago para dejar de usar el plan premium cuando ya no lo considere necesario. | **Scenario 1: Cancelación de suscripción activa** <br> Given que tengo una suscripción premium activa <br> When hago clic en “Cancel Subscription” y confirmo la acción en el cuadro de diálogo <br> Then el sistema cancela la suscripción, actualiza mi estado y muestra un mensaje de confirmación de cancelación exitosa. <br><br> **Scenario 2: Mantener acceso hasta fin de período** <br> Given que he cancelado mi suscripción premium <br> When reviso la información de mi cuenta <br> Then puedo ver que mi suscripción está marcada como “Cancelada” pero con acceso al plan premium hasta la fecha de finalización del período de facturación actual. <br><br> **Scenario 3: Evitar cancelaciones accidentales** <br> Given que hago clic en “Cancel Subscription” <br> When cierro el cuadro de confirmación sin aceptar o selecciono “Cancelar” en el diálogo <br> Then la suscripción permanece activa sin cambios. | EP06 |
| US17 | Visualizar Perfil de Usuario | Como dueño de restaurante, deseo ver mi información personal y detalles de cuenta en la sección “Profile” para poder revisar mis datos registrados. | **Scenario 1: Visualización de datos personales** <br> Given que estoy autenticado en el sistema <br> When accedo a la sección “Profile” <br> Then puedo ver mi información actual, nombre, correo, imagen de perfil y plan de suscripción, de forma organizada. <br><br> **Scenario 2: Datos no disponibles** <br> Given que intento acceder a la sección “Profile” <br> When ocurre un error de conexión o los datos no pueden cargarse <br> Then el sistema muestra un mensaje informando que no fue posible obtener la información del perfil y ofrece un botón para reintentar. | EP06 |
| US18 | Actualizar Datos del Perfil | Como dueño de restaurante, deseo actualizar mi información personal, nombre, correo y contraseña, para mantener mi cuenta al día. | **Scenario 1: Actualización exitosa** <br> Given que estoy en la sección “Profile” <br> When edito mis datos, nombre y correo, y hago clic en “Guardar cambios” <br> Then el sistema guarda la información actualizada y muestra un mensaje de confirmación. <br><br> **Scenario 2: Validación de campos** <br> Given que intento actualizar mis datos <br> When dejo campos obligatorios vacíos o ingreso un formato de correo inválido <br> Then el sistema muestra mensajes de error indicando qué campos deben corregirse. <br><br> **Scenario 3: Cambio de contraseña** <br> Given que estoy en la sección de perfil <br> When ingreso una nueva contraseña y confirmación válida <br> Then el sistema actualiza mi contraseña correctamente y muestra un mensaje de éxito. | EP06 |
| US19 | Iniciar Sesión | Como dueño de restaurante, deseo iniciar sesión en el sistema con mi correo y contraseña para acceder de forma segura a mis datos y funcionalidades. | **Scenario 1: Inicio de sesión exitoso** <br> Given que tengo una cuenta registrada <br> When ingreso mi correo y contraseña válidos y hago clic en “Login” <br> Then el sistema me autentica correctamente y me redirige al dashboard principal. <br><br> **Scenario 2: Credenciales inválidas** <br> Given que intento iniciar sesión <br> When ingreso un correo o contraseña incorrectos <br> Then el sistema muestra un mensaje de error indicando que las credenciales son inválidas. <br><br> **Scenario 3: Campos vacíos** <br> Given que intento iniciar sesión sin llenar ambos campos <br> When hago clic en “Login” <br> Then el sistema muestra un mensaje de advertencia solicitando completar todos los campos requeridos. | EP07 |
| US20 | Crear Cuenta Nueva | Como dueño de restaurante, deseo crear una cuenta ingresando mis datos básicos, nombre, correo y contraseña, para comenzar a usar el sistema. | **Scenario 1: Registro exitoso** <br> Given que estoy en la página de registro <br> When completo el formulario con datos válidos y hago clic en “Sign Up” <br> Then el sistema crea mi cuenta, muestra un mensaje de confirmación y me redirige a la pantalla de inicio de sesión. <br><br> **Scenario 2: Validación de campos obligatorios** <br> Given que intento registrarme <br> When dejo un campo vacío o ingreso un correo inválido <br> Then el sistema muestra un mensaje de error indicando los campos que deben corregirse. <br><br> **Scenario 3: Correo duplicado** <br> Given que intento crear una cuenta con un correo ya registrado <br> When hago clic en “Sign Up” <br> Then el sistema muestra un mensaje indicando que el correo ya está en uso y no permite continuar. | EP07 |

<div style="page-break-after: always;"></div>

## 3.3 Product Backlog

| Orden | User Story Id | Título                                        | Descripción                                                                                                                                                                                | Story Points |
|:------|:--------------|:----------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------|
| 1     | US01          | Visualizar ingresos y pérdidas                | Como dueño de restaurante quiero ver en el dashboard un resumen de mis ingresos y pérdidas para conocer rápidamente la situación financiera de mi negocio.                                 | 8            |
| 2     | US11          | Visualización de Reportes Financieros Diarios | Como dueño de restaurante, quiero ver mis ingresos y gastos diarios en un dashboard centralizado para tomar decisiones informadas sobre el rendimiento financiero de mi negocio.           | 8            |
| 3     | US12          | Navegación entre Períodos de Tiempo           | Como dueño de restaurante, quiero poder alternar entre reportes diarios, semanales y mensuales para analizar tendencias en diferentes períodos de tiempo.                                  | 8            |
| 4     | US13          | Análisis de Categorías de Gastos              | Como dueño de restaurante, quiero visualizar el desglose de mis gastos por categorías para identificar áreas donde puedo optimizar costos.                                                 | 8            |
| 5     | US02          | Identificar platos más populares              | Como dueño de restaurante quiero ver un listado de mis platos más vendidos para saber cuáles son los más rentables y tomar decisiones sobre el menú.                                       | 5            |
| 6     | US03          | Visualizar inventario actual                  | Como dueño de restaurante quiero ver una tabla con el stock, costo unitario y unidad de medida de cada producto para controlar el inventario de manera clara y rápida.                     | 5            |
| 7     | US06          | Agregar Nuevo Plato                           | Como dueño de restaurante, quiero agregar nuevos platos al menú para mantener mi oferta actualizada y atractiva para los clientes.                                                         | 5            |
| 8     | US08          | Visualizar Información Completa del Menú      | Como dueño de restaurante, quiero visualizar toda la información de mis platos (nombre, descripción, precio, ingredientes) en una tabla organizada para tener control total sobre mi menú. | 5            |
| 9     | US09          | Visualizar órdenes existentes                 | Como dueño de restaurante quiero ver en una tabla las órdenes realizadas con su mesa, platos, precio total y fecha para llevar un control claro y rápido de los órdenes.                   | 5            |
| 10    | US14          | Visualizar Planes de Suscripción              | Como dueño de restaurante, quiero ver los diferentes planes de suscripción disponibles (gratuito, estándar y premium) para conocer las opciones y beneficios antes de decidirme.           | 5            |
| 11    | US15          | Suscribirse al Plan Premium                   | Como dueño de restaurante, quiero poder suscribirme al plan premium para acceder a funcionalidades avanzadas que mejoren la gestión de mi negocio.                                         | 5            |
| 12    | US18          | Actualizar Datos del Perfil                   | Como dueño de restaurante, quiero actualizar mi información personal (nombre, correo, contraseña) para mantener mi cuenta al día.                                                          | 5            |
| 13    | US19          | Iniciar Sesión                                | Como dueño de restaurante, quiero iniciar sesión en el sistema con mi correo y contraseña para acceder de forma segura a mis datos y funcionalidades.                                      | 5            |
| 14    | US20          | Crear Cuenta Nueva                            | Como dueño de restaurante, quiero crear una cuenta ingresando mis datos básicos (nombre, correo, contraseña) para comenzar a usar el sistema.                                              | 5            |
| 15    | US04          | Agregar un nuevo producto al inventario       | Como dueño de restaurante quiero registrar un nuevo producto con su nombre, stock, costo unitario y unidad de medida para mantener actualizado mi inventario.                              | 3            |
| 16    | US10          | Calcular el total por plato                   | Como dueño de restaurante quiero que el sistema calcule automáticamente el precio total de cada plato para evitar errores de facturación manual.                                           | 3            |
| 17    | US16          | Cancelar Suscripción                          | Como dueño de restaurante, quiero poder cancelar mi suscripción de pago para dejar de usar el plan premium cuando ya no lo considere necesario.                                            | 3            |
| 18    | US17          | Visualizar Perfil de Usuario                  | Como dueño de restaurante, quiero ver mi información personal y detalles de cuenta en la sección “Profile” para poder revisar mis datos registrados.                                       | 3            |
| 19    | US05          | Validar campos al agregar producto            | Como dueño de restaurante quiero que el sistema valide los campos obligatorios al agregar un producto para evitar errores en el registro del inventario.                                   | 2            |
| 20    | US07          | Buscar Platos Existentes                      | Como dueño de restaurante, quiero buscar platos específicos en mi menú para encontrar rápidamente la información que necesito actualizar.                                                  | 2            |

## 3.4 Impact Map

<img alt="impac" src="https://github.com/user-attachments/assets/df7fd0d7-95bb-451e-80ac-245f69cad627" />

<div style="page-break-after: always;"></div>

---

# Capítulo IV: Product Design

## 4.1 Style Guidelines

FoodFlow busca transformar la manera en que los dueños de restaurantes gestionan, interpretan y utilizan la información financiera y operativa de sus negocios. Para ello, funciona como una aplicación web especializada que centraliza métricas clave, reportes, inventario, órdenes y análisis de platos dentro de una experiencia visual clara, accesible y orientada a la toma de decisiones. Además de facilitar el control diario del restaurante, FoodFlow permite que los propietarios identifiquen oportunidades de mejora, reduzcan errores administrativos y comprendan con mayor precisión la salud financiera de su negocio.

Esta sección presenta una Guía de Estilo integral y estructurada, diseñada para unificar los elementos visuales, de interacción y composición que conforman la plataforma FoodFlow. El propósito es establecer una identidad de producto coherente con su misión: simplificar la gestión financiera de restaurantes mediante una herramienta digital intuitiva, organizada y confiable. Al definir recursos clave como tipografía, paleta de colores, espaciado, componentes visuales y tono comunicacional, la plataforma garantiza consistencia en cada pantalla. Esto no solo mejora la navegación y facilita la lectura de información financiera, sino que también refuerza la percepción de FoodFlow como una solución moderna, profesional y accesible para negocios gastronómicos.

### 4.1.1. General Style Guidelines

El diseño de FoodFlow se sustenta en una Guía de Estilo integral y estructurada, cuyo objetivo es proyectar una identidad visual coherente con los valores del producto: claridad financiera, simplicidad operativa, accesibilidad y confianza. Esta sección define los principales lineamientos visuales de la plataforma, abordando aspectos como Branding, Logotipo, Paleta de Colores, Tipografía, Iconografía, Espaciado y Lenguaje aplicado.

La implementación actual del frontend se basa en Material UI (MUI), utilizando componentes reutilizables, tokens visuales del tema y una estructura responsiva que permite mantener consistencia entre pantallas. Esta decisión favorece una interfaz ordenada, modular y adaptable, especialmente adecuada para una aplicación que presenta información financiera, operativa y analítica mediante dashboards, cards, tablas y gráficos.

Todas las decisiones de diseño se basan en el principio de claridad funcional. FoodFlow prioriza que el usuario pueda comprender rápidamente el estado de su restaurante, identificar métricas relevantes y ejecutar acciones sin fricción. Por ello, cada elemento visual cumple una función específica: jerarquizar información, facilitar la lectura, reducir la carga cognitiva y guiar al usuario hacia las secciones más importantes del sistema.

#### Branding y Logotipo

El Branding de FoodFlow busca transmitir profesionalismo, control y confianza, valores fundamentales para una plataforma enfocada en la gestión financiera de restaurantes. La identidad de marca se expresa principalmente a través del nombre “FoodFlow”, el cual comunica la idea de flujo organizado de información dentro del negocio gastronómico: ingresos, gastos, órdenes, inventario, platos y reportes.

<p align="center">
  <img src="assets/LogoFoodFlow.png" alt="UJM">
</p>

El logotipo y la identidad textual de FoodFlow deben mantener una presencia clara y reconocible dentro de la interfaz, especialmente en la landing page, la barra superior y los espacios de navegación principal. Su uso debe ser consistente, evitando variaciones visuales que puedan debilitar la identidad del producto. En la aplicación web, el branding se complementa con el uso de componentes MUI, tarjetas de métricas, navegación lateral y una estructura visual limpia que refuerza la percepción de una herramienta seria, moderna y confiable.

#### Paleta de Colores (Colors)

La paleta de colores de FoodFlow se basa en un enfoque semántico, donde cada color cumple una función específica dentro de la experiencia de usuario. Esta decisión resulta especialmente importante en una plataforma financiera, ya que los colores permiten comunicar estados, variaciones, alertas y resultados de manera rápida y visual.

<p align="center">
  <img src="assets/ColoresFoodflow.png" alt="UJM">
</p>

**Paleta semántica principal:**

* **Success - Verde principal (`#4caf50`)**: utilizado para representar resultados positivos, métricas favorables, ingresos, crecimiento o estados correctos dentro del sistema.
* **Success Light (`#e8f5e9`)**: utilizado como fondo suave para reforzar información positiva sin saturar visualmente la interfaz.
* **Error - Rojo principal (`#f44336`)**: utilizado para representar pérdidas, errores, alertas críticas o estados que requieren atención del usuario.
* **Error Light (`#ffebee`)**: utilizado como fondo de apoyo para mensajes de error o indicadores negativos.
* **Info - Azul principal (`#2196f3`)**: utilizado para información general, métricas neutras, acciones principales y elementos de navegación.
* **Info Light (`#e3f2fd`)**: utilizado como fondo informativo para destacar contenido relevante sin generar alarma.
* **Warning - Naranja principal (`#ff9800`)**: utilizado para advertencias, estados intermedios, alertas de inventario o información que requiere revisión.
* **Warning Light (`#fff3e0`)**: utilizado como fondo de apoyo para advertencias o indicadores preventivos.

**Colores para gráficas y visualizaciones:**

* Azul: `#2196f3`
* Verde: `#4caf50`
* Naranja: `#ff9800`
* Rojo: `#f44336`
* Morado: `#9c27b0`
* Cian: `#00bcd4`
* Violeta: `#8884d8`

Estos colores se emplean en gráficos, series comparativas, indicadores financieros y cards de métricas. Su uso permite diferenciar categorías, visualizar tendencias y facilitar la lectura de datos sin depender únicamente de texto o tablas extensas.

#### Tipografía (Typography)

La selección tipográfica de FoodFlow prioriza la legibilidad, la jerarquía visual y la claridad en la lectura de datos. Debido a que la plataforma presenta información financiera y operativa, es fundamental que los usuarios puedan identificar rápidamente títulos, cifras, descripciones, etiquetas y acciones.

<p align="center">
  <img src="assets/TipografiaFoodflow.png" alt="UJM">
</p>

El stack tipográfico global utilizado en la aplicación es el siguiente (tanto versión light, regular y bold):

* `Lucida Grande`
* `Segoe UI`
* `Roboto`
* `Helvetica Neue`

Esta combinación permite una visualización estable en distintos sistemas operativos y navegadores, manteniendo una apariencia moderna y familiar para el usuario.

**Variantes tipográficas utilizadas en la aplicación:**

* `h4`: utilizado para títulos principales de páginas o secciones relevantes.
* `h5`: utilizado para encabezados secundarios o bloques destacados.
* `h6`: utilizado para títulos de cards, módulos o subsecciones.
* `body1`: utilizado para textos principales y descripciones.
* `body2`: utilizado para textos secundarios o información complementaria.
* `caption`: utilizado para etiquetas pequeñas, detalles o información contextual.
* `subtitle2`: utilizado para subtítulos, encabezados menores o textos de apoyo.
* `button`: utilizado para acciones dentro de botones y elementos interactivos.

El énfasis visual se aplica principalmente mediante `fontWeight: 'bold'`, especialmente en títulos, cifras financieras y encabezados de métricas. Esta decisión permite que los datos más importantes destaquen dentro de dashboards y reportes, facilitando una lectura rápida del estado del negocio.

#### Iconografía (Iconography)

La iconografía de FoodFlow debe ser simple, clara y funcional. Su propósito principal es apoyar la navegación, facilitar la identificación de módulos y reforzar visualmente las acciones disponibles dentro de la plataforma.

El estilo recomendado para los íconos es limpio y consistente con Material UI, manteniendo proporciones equilibradas y una lectura inmediata. Los íconos deben representar acciones o secciones clave del sistema, tales como dashboard, menú, inventario, órdenes, reportes financieros, configuración, perfil y autenticación.

**Propósito de la iconografía:**

* Facilitar la identificación rápida de módulos dentro del menú lateral.
* Reforzar visualmente acciones como agregar, editar, eliminar, buscar o guardar.
* Acompañar métricas financieras mediante señales visuales de estado.
* Reducir la carga cognitiva del usuario al navegar por la plataforma.
* Mantener coherencia entre la landing page y la aplicación web.

La iconografía no debe utilizarse como elemento decorativo aislado, sino como apoyo funcional para mejorar la comprensión de la interfaz.

#### Espaciado (Spacing)

El sistema de espaciado de FoodFlow se basa en las propiedades `sx` de Material UI, utilizando valores numéricos que se ajustan al tema visual de la aplicación. Esta estructura permite mantener una distribución consistente entre componentes, secciones, cards, tablas y contenedores.

**Ejemplos de espaciado utilizados:**

* `p: 3`: padding interno para contenedores principales o tarjetas.
* `mb: 3`: margen inferior para separar secciones.
* `mt: 8`: margen superior para generar distancia estructural.
* `spacing={2}`: separación entre elementos dentro de layouts flexibles o grids.

La estructura principal de la aplicación está compuesta por un `AppBar` fijo y un `Drawer` lateral con ancho de `240px`, lo que permite mantener una navegación persistente y clara. El contenido principal utiliza padding consistente para evitar saturación visual y asegurar que los datos se presenten con suficiente espacio de lectura.

El espaciado cumple una función esencial dentro de FoodFlow, ya que permite organizar grandes volúmenes de información sin que la interfaz se perciba sobrecargada. En dashboards, reportes y tablas, la separación entre elementos facilita la comparación de métricas, la lectura de cifras y la identificación de acciones disponibles.

#### Responsive Design

FoodFlow utiliza los breakpoints por defecto de Material UI para adaptar la interfaz a distintos tamaños de pantalla. Esta decisión permite que la plataforma conserve una estructura ordenada tanto en vistas compactas como en pantallas de escritorio.

| Media Query | Dispositivo |
|------------|-------------|
| 0px (`xs`) | Web compacto |
| 600px (`sm`) | Web regular |
| 900px (`md`) | Web amplio |
| 1200px (`lg`) | Web escritorio |

Con estas convenciones se definen los momentos en los que el layout debe ajustarse significativamente. Por ejemplo, el `Drawer` puede comportarse de manera distinta según el tamaño de pantalla, mientras que las secciones organizadas en filas pueden transformarse en columnas para preservar la legibilidad en espacios reducidos.

Este enfoque responsivo permite que FoodFlow mantenga una experiencia consistente, priorizando siempre la claridad de la información y la facilidad de navegación.

#### Tono de Comunicación y Lenguaje Aplicado

El tono de comunicación de FoodFlow debe ser claro, profesional y orientado a la acción. Al tratarse de una plataforma de gestión financiera para restaurantes, el lenguaje debe transmitir confianza, precisión y facilidad de uso, evitando tecnicismos innecesarios que puedan dificultar la comprensión de usuarios sin formación contable avanzada.

La comunicación debe enfocarse en guiar al usuario de manera directa, explicando cada acción o resultado de forma sencilla. Los mensajes del sistema, botones, etiquetas y descripciones deben utilizar términos familiares para el dueño de restaurante, como ingresos, gastos, inventario, órdenes, platos, reportes y configuración.

**Características del tono de FoodFlow:**

* **Claro:** los mensajes deben ser directos y fáciles de entender.
* **Profesional:** la plataforma debe transmitir seriedad y confianza en la gestión del negocio.
* **Accesible:** el lenguaje debe evitar complejidad innecesaria y adaptarse a usuarios con distintos niveles de experiencia digital.
* **Orientado a decisiones:** la información debe ayudar al usuario a interpretar resultados y actuar.
* **Consistente:** las etiquetas, botones y mensajes deben mantener una misma lógica en toda la aplicación.

En cuanto al lenguaje aplicado, FoodFlow prioriza la comprensión inmediata. Por ello, las etiquetas del sistema son breves y funcionales, como `Dashboard`, `Menu / Dishes`, `Inventory`, `Orders`, `Finance` y `Settings`. Estas denominaciones permiten que el usuario identifique rápidamente cada sección y comprenda su propósito dentro de la plataforma.

Este enfoque comunicativo permite que FoodFlow no solo sea una herramienta funcional, sino también una experiencia confiable y fácil de adoptar para dueños de restaurantes que buscan mejorar el control financiero y operativo de sus negocios.

### 4.1.2 Web Style Guidelines

En esta sección se explicamos e ilustramos las decisiones sobre los estándares visuales y de
interacción para responsive web interfaces.

Respecto a responsive definimos breakpoints segun el sistema por defecto de MUI, usando los tamaños del tema (no hay overrides) y las etiquetas `xs`, `sm`, `md`, `lg` en los componentes.

|Media Query|Dispositivo|
|-|-|
| 0px (xs) | Web compacto |
| 600px (sm) | Web regular |
| 900px (md) | Web amplio |
| 1200px (lg) | Web escritorio |

con estas convenciones nos hemos guiado para saber en que momentos debemos realizar cambios significativos en layout (por ejemplo, Drawer permanente vs temporal, y stacks en columna vs fila).

## 4.2 Information Architecture

La arquitectura de información es fundamental para definir la manera en que se organizan los diferentes componentes de FoodFlow, permitiendo que los dueños de restaurantes puedan interactuar con la plataforma de forma clara, intuitiva y eficiente. Al tratarse de una aplicación orientada a la gestión financiera y operativa, resulta indispensable estructurar adecuadamente módulos como Dashboard, Menu / Dishes, Inventory, Orders, Finance y Settings, de modo que el usuario pueda encontrar rápidamente la información que necesita para monitorear el estado de su negocio.

Una correcta organización de la información permite reducir la carga cognitiva del usuario, mejorar la navegación entre secciones y facilitar la interpretación de datos clave como ingresos, gastos, órdenes, inventario y rendimiento de platos. Por ello, FoodFlow prioriza una arquitectura visual ordenada y funcional, orientada a retener la atención del usuario, simplificar la consulta de métricas y fomentar el uso constante de la aplicación como herramienta de apoyo para la toma de decisiones.

### 4.2.1 Organization Systems

### 4.2.2 Labeling Systems

### 4.2.3 SEO Tags and Meta Tags

### 4.2.4 Searching Systems

### 4.2.5 Navigation Systems

## 4.3 Landing Page UI Design

La propuesta de diseño para la interfaz de usuario (UI) de la Landing Page de FoodFlow representa la materialización visual de su arquitectura de información y de su enfoque centrado en el usuario. Desde el primer contacto, la interfaz está diseñada para comunicar una identidad profesional, clara y confiable, alineada con el propósito principal de la plataforma: ayudar a los restaurantes a gestionar mejor sus finanzas, optimizar sus operaciones y tomar decisiones basadas en datos.

La estructura de la Landing Page se organiza en secciones clave como Inicio, Funciones, Beneficios, Sobre nosotros, Cómo funciona, Planes, Términos y Condiciones, Política de Privacidad, Ayuda, Preguntas frecuentes y Contacto. Esta distribución permite una navegación ordenada e intuitiva, guiando al visitante desde la presentación general del producto hasta la comprensión de sus funcionalidades, beneficios, modelo de suscripción y canales de soporte.

A nivel visual, FoodFlow emplea una jerarquía clara, componentes modernos, tipografías legibles y una paleta de colores adecuada. Estos elementos permiten transmitir confianza, accesibilidad y eficiencia, reforzando la propuesta de valor del producto. Además, la Landing Page está disponible en español e inglés, lo que amplía su alcance comunicacional y facilita que distintos usuarios puedan comprender la plataforma desde su idioma de preferencia.

### 4.3.1 Landing Page Wireframe

La primera sección de la landing page presenta una descripción breve y directa sobre el propósito de FoodFlow. En la parte superior se ubica un encabezado fijo que acompaña al usuario durante todo el recorrido de la página, facilitando el acceso a las secciones principales. Asimismo, se incluyen dos botones de acción que permiten redirigir al visitante de manera más rápida hacia opciones relevantes, junto con el logotipo de la aplicación y una animación ligera que refuerza la identidad visual del producto.

<p align="center">
  <img src="assets/WireframeFoodFlow1.png" alt="Wireframe de la sección inicial de FoodFlow">
</p>

La siguiente sección presenta los principales problemas que enfrentan actualmente los restaurantes. Cada problema se organiza en tarjetas visuales acompañadas de íconos representativos, lo que permite comunicar de forma clara las dificultades asociadas al control de ingresos, gastos, inventario y toma de decisiones.

<p align="center">
  <img src="assets/WireframeFoodFlow2.png" alt="Wireframe de la sección de problemas actuales">
</p>

Posteriormente, la landing page introduce a FoodFlow como una solución frente a los problemas previamente identificados. Esta sección destaca la propuesta de valor de la aplicación, acompañada por el logotipo del producto y una animación sutil que ayuda a reforzar la presentación visual de la plataforma.

<p align="center">
  <img src="assets/WireframeFoodFlow3.png" alt="Wireframe de la presentación de FoodFlow como solución">
</p>

A continuación, se presentan las principales funciones de FoodFlow, explicando cómo cada una contribuye a resolver las necesidades actuales de los restaurantes. Esta sección permite que el visitante comprenda de manera general el alcance de la plataforma y su utilidad dentro de la gestión diaria del negocio.

<p align="center">
  <img src="assets/WireframeFoodFlow4.png" alt="Wireframe de la sección de funciones de FoodFlow">
</p>

Luego, se profundiza en el propósito de cada función, detallando qué problema específico ayuda a resolver dentro del restaurante. Esta sección busca mostrar con mayor claridad el valor práctico de la plataforma, relacionando sus funcionalidades con beneficios concretos para el usuario.

<p align="center">
  <img src="assets/WireframeFoodFlow5.png" alt="Wireframe de la explicación de funciones y beneficios">
</p>

La siguiente sección resume el proceso de inicio en tres pasos simples, con el objetivo de demostrar que FoodFlow puede ser utilizado de manera rápida y sencilla. Esta estructura facilita que el visitante comprenda cómo comenzar a usar la aplicación sin enfrentarse a procesos complejos.

<p align="center">
  <img src="assets/WireframeFoodFlow6.png" alt="Wireframe de la sección de pasos para iniciar">
</p>

Posteriormente, se realiza una comparación entre FoodFlow y otros métodos tradicionales que suelen emplear los restaurantes para organizar su información, como hojas de cálculo, registros manuales o herramientas no especializadas. Esta sección permite evidenciar las ventajas de utilizar una plataforma centralizada frente a alternativas dispersas o poco eficientes.

<p align="center">
  <img src="assets/WireframeFoodFlow7.png" alt="Wireframe de la sección comparativa de FoodFlow">
</p>

Luego, se presenta la sección “Sobre nosotros”, donde se explica el origen de FoodFlow y la motivación detrás de su creación. Esta parte permite comunicar la identidad del equipo, la problemática que impulsó el desarrollo de la solución y el compromiso de la startup con la mejora de la gestión financiera en restaurantes.

<p align="center">
  <img src="assets/WireframeFoodFlow8.png" alt="Wireframe de la sección sobre nosotros">
</p>

A continuación, se muestran los planes de suscripción que ofrece FoodFlow. Esta sección permite que el visitante compare las opciones disponibles, revise sus beneficios y evalúe cuál se adapta mejor a las necesidades de su restaurante.

<p align="center">
  <img src="assets/WireframeFoodFlow9.png" alt="Wireframe de la sección de planes de FoodFlow">
</p>

La última sección principal corresponde al formulario de contacto. En este espacio, el visitante puede comunicarse con el equipo de FoodFlow ante cualquier consulta, duda o solicitud de información adicional, facilitando un canal directo de interacción con la plataforma.

<p align="center">
  <img src="assets/WireframeFoodFlow10.png" alt="Wireframe de la sección de contacto">
</p>

Finalmente, al completar el recorrido de la página, el usuario llega al pie de página. En esta sección se incluyen enlaces a redes sociales, accesos rápidos para volver a distintas partes de la landing page, y enlaces relacionados con aspectos legales, ayuda, términos y condiciones, política de privacidad y soporte al usuario.

<p align="center">
  <img src="assets/WireframeFoodFlow11.png" alt="Wireframe del pie de página de FoodFlow">
</p>

### 4.3.2 Landing Page Mock-up

Los mockups de la landing page de FoodFlow presentan una representación más cercana a la interfaz final del sitio, incorporando los elementos visuales definidos en la guía de estilo, como la paleta de colores, la tipografía, los componentes gráficos y la jerarquía visual. Esta versión permite validar cómo la estructura planteada en los wireframes se transforma en una experiencia más clara, profesional y atractiva para el usuario, manteniendo el enfoque de comunicar la propuesta de valor de FoodFlow como una solución financiera para restaurantes.

La primera sección del mockup corresponde al hero principal de la landing page. En esta vista se presenta de forma directa la propuesta de valor de FoodFlow: ayudar a los restaurantes a controlar sus finanzas con mayor claridad. La composición utiliza un encabezado superior con navegación hacia las secciones principales, selector de idioma en español e inglés, botón de acción “Comenzar ahora” y el logotipo del producto. Además, se incorpora una ilustración visual relacionada con reportes y métricas financieras, reforzando el enfoque de la plataforma como una solución moderna para centralizar ingresos, gastos, inventario, órdenes y reportes.

<p align="center">
  <img src="assets/MockupFoodFlow1.png" alt="Mockup de la sección inicial de FoodFlow">
</p>

La segunda sección del mockup expone los principales problemas que enfrentan los restaurantes al gestionar su información financiera y operativa de forma dispersa. Mediante tarjetas visuales con íconos representativos, se presentan situaciones como el uso de cuadernos, hojas de cálculo desconectadas, POS enfocados solo en ventas, inventario manejado por memoria, reportes tardíos y decisiones tomadas por intuición. Esta sección busca generar identificación con el usuario, mostrando que vender todos los días no necesariamente significa ganar dinero de manera sostenible.

<p align="center">
  <img src="assets/MockupFoodFlow2.png" alt="Mockup de la sección de problemas actuales de los restaurantes">
</p>

La tercera sección introduce a FoodFlow como la solución centralizada frente a los problemas previamente descritos. El diseño combina un mensaje claro con una composición visual circular alrededor del logotipo, donde se destacan módulos clave como ingresos, inventario, órdenes, menú y reportes. Esta representación refuerza la idea de que FoodFlow funciona como un único punto de control para comprender el estado del negocio, permitiendo que el dueño del restaurante acceda a información financiera y operativa de forma organizada, visual y accionable.

<p align="center">
  <img src="assets/MockupFoodFlow3.png" alt="Mockup de la sección de FoodFlow como solución centralizada">
</p>

La cuarta sección presenta las principales funcionalidades de FoodFlow mediante una interfaz de fondo oscuro y tarjetas modulares. Esta decisión visual permite generar contraste y destacar los módulos más importantes de la plataforma, como finanzas centralizadas, reportes claros, inventario, control de órdenes, platos estrella, gestión de menú, perfil y suscripciones. Cada tarjeta resume una funcionalidad concreta y comunica cómo la aplicación responde a las preguntas que un dueño de restaurante se realiza durante la gestión diaria de su negocio.

<p align="center">
  <img src="assets/MockupFoodFlow4.png" alt="Mockup de la sección de funcionalidades de FoodFlow">
</p>

La quinta sección profundiza en los beneficios que FoodFlow ofrece al usuario, organizándolos en una cuadrícula numerada de fácil lectura. Cada tarjeta presenta un beneficio específico, como claridad de ingresos y gastos, mejor control de inventario, reducción de desperdicio, órdenes ordenadas, decisiones más rápidas, reemplazo de hojas de cálculo frágiles, ahorro de tiempo administrativo, análisis de rentabilidad por plato y uso sin necesidad de conocimientos contables. Esta estructura permite comunicar el valor práctico de la plataforma de manera ordenada y visualmente atractiva.

<p align="center">
  <img src="assets/MockupFoodFlow5.png" alt="Mockup de la sección de beneficios de FoodFlow">
</p>

La sexta sección resume el proceso de adopción de FoodFlow en tres pasos simples: registrar el restaurante, centralizar la información y decidir con datos. El diseño utiliza tarjetas amplias conectadas visualmente, lo que facilita comprender el flujo inicial de uso de la plataforma. Esta sección transmite que FoodFlow no requiere instalaciones complejas ni procesos extensos, sino que está pensado para que el dueño del restaurante pueda empezar a organizar su negocio de forma rápida, clara y progresiva.

<p align="center">
  <img src="assets/MockupFoodFlow6.png" alt="Mockup de la sección de pasos para comenzar con FoodFlow">
</p>

La séptima sección muestra una comparación entre FoodFlow, un software contable tradicional y un POS convencional. Mediante una tabla clara y estructurada, se evalúan características como enfoque gastronómico, inventario por insumo, rentabilidad por plato, lenguaje sin jerga contable y precio accesible. Esta sección cumple una función estratégica dentro de la landing page, ya que evidencia cómo FoodFlow se diferencia de herramientas genéricas al estar diseñado específicamente para restaurantes y no para auditores o procesos contables complejos.

<p align="center">
  <img src="assets/MockupFoodFlow7.png" alt="Mockup de la sección comparativa de FoodFlow">
</p>

La octava sección corresponde a “Sobre nosotros”, donde se presenta la relación entre ClaudeFlow y FoodFlow. El contenido explica que ClaudeFlow es la startup impulsora del producto y que FoodFlow nace como una solución orientada a ordenar la gestión financiera gastronómica. Visualmente, se utiliza una composición de dos columnas: a la izquierda se desarrolla el contexto del proyecto y a la derecha se refuerza la conexión entre startup y producto mediante tarjetas informativas. Esta sección aporta credibilidad, identidad y propósito a la propuesta.

<p align="center">
  <img src="assets/MockupFoodFlow8.png" alt="Mockup de la sección sobre ClaudeFlow y FoodFlow">
</p>

La novena sección presenta los planes de suscripción de FoodFlow mediante tres tarjetas comparativas: Free, Standard y Premium. Cada plan muestra su precio mensual, descripción y beneficios incluidos, permitiendo que el usuario evalúe cuál se adapta mejor a las necesidades de su restaurante. El plan Standard se destaca visualmente como recomendado, utilizando un fondo oscuro y un llamado de atención diferenciado. Esta jerarquía ayuda a guiar la decisión del visitante sin perder claridad en la comparación de opciones.

<p align="center">
  <img src="assets/MockupFoodFlow9.png" alt="Mockup de la sección de planes de suscripción de FoodFlow">
</p>

La décima sección corresponde al bloque de contacto y llamada a la acción final. El diseño utiliza un contenedor amplio con fondo degradado en tonos naranjas, reforzando la identidad visual del producto y generando un cierre llamativo antes del footer. En esta sección se invita al usuario a comenzar a gestionar su restaurante con datos y no con intuición. Además, se incluye un formulario con campos para nombre, correo, teléfono y mensaje, facilitando que el visitante pueda comunicarse directamente con el equipo de FoodFlow.

<p align="center">
  <img src="assets/MockupFoodFlow10.png" alt="Mockup de la sección de contacto de FoodFlow">
</p>

Finalmente, la última sección muestra el footer de la landing page. Este bloque organiza la información complementaria en columnas, incluyendo la identidad de FoodFlow, enlaces del producto, secciones legales, recursos de ayuda y accesos a redes sociales. También se mantiene el selector de idioma en español e inglés, reforzando la disponibilidad bilingüe de la plataforma. El diseño oscuro del pie de página genera un cierre visual sólido y permite concentrar accesos importantes sin sobrecargar el resto de la página.

<p align="center">
  <img src="assets/MockupFoodFlow11.png" alt="Mockup del footer de FoodFlow">
</p>

## 4.4 Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes

### 4.4.2 Web Applications Wireflow Diagrams

### 4.4.3 Web Applications Mock-ups

### 4.4.4 Web Applications User Flow Diagrams

## 4.5 Web Applications Prototyping

## 4.6 Domain-Driven Software Architecture

#### Strategic-Level Domain-Driven Design

En esta sección se introduce el proceso de Domain-Driven Design a nivel estratégico aplicado a FoodFlow. Este enfoque permitió conceptualizar el sistema a partir de la lógica propia del negocio gastronómico, considerando procesos como la gestión financiera, el control de inventario, la administración del menú, el registro de órdenes, los reportes y las suscripciones. A partir de ello, se buscó modelar una arquitectura coherente, alineada con las necesidades reales de los dueños de restaurantes y con los límites funcionales del producto.

Para este propósito, se identificaron los principales subconjuntos del sistema con responsabilidades claras y delimitadas, conocidos como Bounded Contexts. Estos contextos permiten separar adecuadamente las áreas del dominio, evitando mezclar reglas de negocio distintas dentro de un mismo módulo. Asimismo, se emplearon herramientas como EventStorming, para visualizar el flujo de eventos relevantes del negocio, y Bounded Context Canvas, para definir formalmente cada contexto, sus responsabilidades y relaciones. De esta manera, FoodFlow cuenta con una base arquitectónica más ordenada y sólida para representar su dominio de gestión financiera y operativa para restaurantes.

#### Event Storming


#### Candidate Context Discovery


#### Domain Message Flows Modelling


#### Bounded Context Canvases



### 4.6.1 Software Architecture Context Diagram

El sistema tiene como actor principal al **dueño del restaurante**, quien accede desde una interfaz web.

<img alt="contexto" src="https://github.com/user-attachments/assets/67481017-f88b-4c69-b8d5-e9dac63b09fe" />

### 4.6.2 Software Architecture Container Diagrams.

### 4.6.3 Software Architecture Components Diagrams.

## 4.7 Software Object-Oriented Design

### 4.7.1 Class Diagrams

<img alt="Untitled diagram-2025-10-09-034906" src="https://github.com/user-attachments/assets/7cd76b45-2db5-4829-947f-626c5e9c8989" />

<img alt="1" src="https://github.com/user-attachments/assets/215ac1e6-a2cf-402c-860a-5bc39099118a" />

<img alt="2" src="https://github.com/user-attachments/assets/7de7aabb-a9af-430c-8132-bd98b56e7e32" />

<img alt="3" src="https://github.com/user-attachments/assets/375c8a3e-7681-464c-b13c-a81289038fe0" />

<img alt="4" src="https://github.com/user-attachments/assets/7b090aca-b29f-4046-b750-085e7ca219ab" />

<img alt="5" src="https://github.com/user-attachments/assets/050f0fe3-540b-4dd1-ac65-31cc6efa786f" />

<div style="page-break-after: always;"></div>

### 4.7.2 Class Dictionary

#### Suscripción

| Clase                      | Tipo             | Descripción                                               | Propósito                                                                                                                                      |
|----------------------------|------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| **SubscriptionController** | Controlador      | Maneja las peticiones HTTP relacionadas con suscripciones | Expone endpoints REST para que los usuarios puedan ver planes, suscribirse, consultar su suscripción y cancelarla                              |
| **SubscriptionService**    | Servicio         | Contiene la lógica de negocio de las suscripciones        | Orquesta el proceso completo: valida datos, procesa pagos, activa suscripciones y gestiona renovaciones                                        |
| **Subscription**           | Entidad          | Representa una suscripción activa de un usuario           | Almacena información de la suscripción individual: qué usuario, qué plan eligió, cuándo inicia/termina, estado del pago                        |
| **SubscriptionPlan**       | Entidad/Catálogo | Representa los planes de suscripción disponibles          | Define los diferentes planes que se ofrecen (Básico, Premium, Enterprise) con sus precios, características y límites                           |
| **SubscriptionRepository** | Repositorio      | Acceso a datos de suscripciones de usuarios               | Maneja operaciones CRUD de las **suscripciones activas/históricas de usuarios**. Cada vez que un usuario se suscribe, se crea un registro aquí |
| **PlanRepository**         | Repositorio      | Acceso a datos de planes disponibles                      | Maneja operaciones CRUD de los **planes que ofreces como negocio** (catálogo de productos). Son los planes base que no cambian por usuario     |
| **SubscriptionStatus**     | Enum             | Estados posibles de una suscripción                       | Rastrea el flujo: desde que el usuario selecciona un plan, valida pago, procesa, hasta que queda activa o falla                                |
| **BillingPeriod**          | Enum             | Períodos de facturación                                   | Define si el plan se cobra mensual, trimestral o anualmente                                                                                    |
| **PaymentClient**          | Cliente          | Interfaz para procesar pagos                              | Se comunica con una pasarela de pago externa (Stripe, PayPal, etc.) para procesar transacciones                                                |
| **PaymentData**            | DTO              | Datos de pago del usuario                                 | Encapsula información sensible: tarjeta, titular, fecha de expiración, CVV                                                                     |
| **PaymentResult**          | DTO              | Resultado del procesamiento de pago                       | Contiene si el pago fue exitoso, ID de transacción y mensajes de error si aplica                                                               |
---

#### Inventario

| Clase                   | Tipo        | Descripción                                      | Propósito                                                                                            |
|-------------------------|-------------|--------------------------------------------------|------------------------------------------------------------------------------------------------------|
| **InventoryController** | Controlador | Maneja peticiones HTTP de inventario             | Expone endpoints para registrar productos, actualizar stock y consultar inventario                   |
| **InventoryService**    | Servicio    | Lógica de negocio del inventario                 | Gestiona operaciones de productos: crear, actualizar stock, descontar ingredientes usados en órdenes |
| **Product**             | Entidad     | Representa un producto/ingrediente en inventario | Almacena información del producto: nombre, categoría, precio de compra, stock actual, proveedor      |
| **ProductStatus**       | Enum        | Estados del producto                             | Indica el estado del producto en el sistema: pendiente, registrado, stock disponible, bajo o agotado |
| **ProductRepository**   | Repositorio | Acceso a datos de productos                      | Maneja operaciones CRUD de productos en inventario                                                   |

---

#### Menú

| Clase              | Tipo        | Descripción                     | Propósito                                                                       |
|--------------------|-------------|---------------------------------|---------------------------------------------------------------------------------|
| **MenuController** | Controlador | Maneja peticiones HTTP del menú | Expone endpoints para crear platos y consultar el menú                          |
| **MenuService**    | Servicio    | Lógica de negocio del menú      | Gestiona la creación y consulta de platos disponibles para venta                |
| **Dish**           | Entidad     | Representa un plato del menú    | Almacena información del plato: nombre, descripción, precio de venta, categoría |
| **DishStatus**     | Enum        | Estados del plato               | Indica si el plato está en proceso de creación o ya está registrado en el menú  |
| **DishRepository** | Repositorio | Acceso a datos de platos        | Maneja operaciones CRUD de platos del menú                                      |

---

#### Órdenes

| Clase                | Tipo                   | Descripción                              | Propósito                                                                                       |
|----------------------|------------------------|------------------------------------------|-------------------------------------------------------------------------------------------------|
| **OrderController**  | Controlador            | Maneja peticiones HTTP de órdenes        | Expone endpoints para cargar órdenes, consultarlas y filtrar por rango de fechas                |
| **OrderService**     | Servicio               | Lógica de negocio de órdenes             | Procesa órdenes de venta, calcula totales, actualiza inventario y coordina con otros servicios  |
| **Order**            | Entidad                | Representa una orden de venta            | Almacena información de la orden: número, items vendidos, total, fecha, estado de procesamiento |
| **OrderItem**        | Entidad                | Representa un ítem dentro de una orden   | Detalle de cada plato vendido: qué plato, cantidad, precio unitario, subtotal                   |
| **OrderStatus**      | Enum                   | Estados de la orden                      | Rastrea el procesamiento: cargada, procesando, actualizando stock, registrada, completada       |
| **OrderRepository**  | Repositorio            | Acceso a datos de órdenes                | Maneja operaciones CRUD de órdenes, con filtros por fecha y estado                              |
| **MessagingService** | Servicio de mensajería | Publica eventos entre microservicios     | Comunica eventos importantes: orden procesada, actualización de stock, suscripción activada     |
| **StockUpdateEvent** | Evento                 | Evento de actualización de inventario    | Mensaje que se envía cuando una orden requiere descontar stock                                  |
| **InventoryClient**  | Cliente                | Interfaz para comunicarse con Inventario | Permite al servicio de órdenes consultar y actualizar el inventario de otros microservicios     |

<div style="page-break-after: always;"></div>

## 4.8 Database Design

### 4.8.1 Relational Database Diagram

La base de datos **Postgres** mantiene las entidades descritas en los capítulos anteriores:

![WhatsApp Image 2025-11-30 at 9 21 40 PM](https://github.com/user-attachments/assets/59d10088-aa49-4da6-a5b4-be8bac062fe1)

<div style="page-break-after: always;"></div>

#### Entidades del Sistema

#### 1. USER (Usuario)
Almacena la información de los usuarios del sistema.

| Campo      | Tipo        | Descripción                                       |
|------------|-------------|---------------------------------------------------|
| id         | string (PK) | Identificador único del usuario                   |
| email      | string (UK) | Correo electrónico único del usuario              |
| name       | string      | Nombre completo del usuario                       |
| role       | string      | Rol del usuario en el sistema (admin, user, etc.) |
| created_at | datetime    | Fecha de creación del registro                    |
| updated_at | datetime    | Fecha de última actualización                     |

**Propósito**: Gestionar los usuarios que interactúan con el sistema y pueden adquirir suscripciones.

---

#### 2. SUBSCRIPTION (Suscripción)
Registra las suscripciones activas e históricas de los usuarios.

| Campo          | Tipo        | Descripción                                                  |
|----------------|-------------|--------------------------------------------------------------|
| id             | string (PK) | Identificador único de la suscripción                        |
| user_id        | string (FK) | Referencia al usuario suscrito                               |
| plan_id        | string (FK) | Referencia al plan seleccionado                              |
| status         | string      | Estado de la suscripción (ACTIVO, EXPIRADO, CANCELADO, etc.) |
| start_date     | datetime    | Fecha de inicio de la suscripción                            |
| end_date       | datetime    | Fecha de finalización de la suscripción                      |
| auto_renew     | boolean     | Indica si la suscripción se renueva automáticamente          |
| payment_method | string      | Método de pago utilizado                                     |
| transaction_id | string      | ID de la transacción de pago                                 |
| created_at     | datetime    | Fecha de creación del registro                               |
| updated_at     | datetime    | Fecha de última actualización                                |

**Propósito**: Controlar el acceso de los usuarios a las funcionalidades del sistema según su plan activo.

---

#### 3. SUBSCRIPTION_PLAN (Plan de Suscripción)
Define los diferentes planes de suscripción disponibles.

| Campo          | Tipo        | Descripción                                         |
|----------------|-------------|-----------------------------------------------------|
| id             | string (PK) | Identificador único del plan                        |
| name           | string      | Nombre del plan (Básico, Premium, Enterprise, etc.) |
| description    | string      | Descripción detallada del plan                      |
| price          | decimal     | Precio del plan                                     |
| billing_period | string      | Periodo de facturación (MENSUAL, TRIMESTRAL, ANUAL) |
| features       | string      | Lista de características incluidas (JSON o texto)   |
| max_users      | int         | Número máximo de usuarios permitidos                |
| max_orders     | int         | Número máximo de órdenes permitidas                 |
| created_at     | datetime    | Fecha de creación del registro                      |
| updated_at     | datetime    | Fecha de última actualización                       |

**Propósito**: Definir las opciones de suscripción disponibles con sus características y limitaciones.

---

#### 4. PAYMENT_TRANSACTION (Transacción de Pago)
Registra todas las transacciones de pago relacionadas con suscripciones.

| Campo           | Tipo        | Descripción                                            |
|-----------------|-------------|--------------------------------------------------------|
| id              | string (PK) | Identificador único de la transacción                  |
| subscription_id | string (FK) | Referencia a la suscripción asociada                   |
| amount          | decimal     | Monto de la transacción                                |
| currency        | string      | Moneda utilizada (USD, PEN, etc.)                      |
| status          | string      | Estado de la transacción (EXITOSO, FALLIDO, PENDIENTE) |
| transaction_id  | string      | ID único de la transacción del proveedor de pagos      |
| payment_method  | string      | Método de pago usado (tarjeta, PayPal, etc.)           |
| processed_at    | datetime    | Fecha y hora en que se procesó el pago                 |
| created_at      | datetime    | Fecha de creación del registro                         |

**Propósito**: Mantener un historial completo de todas las transacciones de pago para auditoría y seguimiento.

---

#### 5. PRODUCT (Producto)
Almacena información de los productos del inventario.

| Campo          | Tipo        | Descripción                                           |
|----------------|-------------|-------------------------------------------------------|
| id             | string (PK) | Identificador único del producto                      |
| name           | string      | Nombre del producto                                   |
| category       | string      | Categoría del producto                                |
| purchase_price | decimal     | Precio de compra del producto                         |
| current_stock  | int         | Stock actual disponible                               |
| unit           | string      | Unidad de medida (kg, unidad, litro, etc.)            |
| purchase_date  | datetime    | Fecha de compra del producto                          |
| supplier       | string      | Proveedor del producto                                |
| status         | string      | Estado del producto (DISPONIBLE, STOCK_BAJO, AGOTADO) |
| created_at     | datetime    | Fecha de creación del registro                        |
| updated_at     | datetime    | Fecha de última actualización                         |

**Propósito**: Gestionar el inventario de productos y materia prima del negocio.

---

#### 6. DISH (Platillo)
Contiene los platillos disponibles en el menú.

| Campo       | Tipo        | Descripción                                               |
|-------------|-------------|-----------------------------------------------------------|
| id          | string (PK) | Identificador único del platillo                          |
| name        | string      | Nombre del platillo                                       |
| description | string      | Descripción del platillo                                  |
| price       | decimal     | Precio de venta del platillo                              |
| category    | string      | Categoría del platillo (entrada, principal, postre, etc.) |
| status      | string      | Estado del platillo (DISPONIBLE, NO_DISPONIBLE)           |
| created_at  | datetime    | Fecha de creación del registro                            |
| updated_at  | datetime    | Fecha de última actualización                             |

**Propósito**: Administrar el menú de platillos ofrecidos a los clientes.

---

#### 7. ORDER (Orden)
Registra las órdenes realizadas por los clientes.

| Campo        | Tipo        | Descripción                                          |
|--------------|-------------|------------------------------------------------------|
| id           | string (PK) | Identificador único de la orden                      |
| order_number | string (UK) | Número único de orden para identificación            |
| total_amount | decimal     | Monto total de la orden                              |
| status       | string      | Estado de la orden (CARGADA, PROCESANDO, COMPLETADA) |
| order_date   | datetime    | Fecha y hora en que se realizó la orden              |
| processed_at | datetime    | Fecha y hora en que se procesó la orden              |
| created_at   | datetime    | Fecha de creación del registro                       |
| updated_at   | datetime    | Fecha de última actualización                        |

**Propósito**: Gestionar las órdenes de los clientes y su procesamiento.

---

#### 8. ORDER_ITEM (Item de Orden)
Detalla los platillos incluidos en cada orden.

| Campo      | Tipo        | Descripción                           |
|------------|-------------|---------------------------------------|
| id         | string (PK) | Identificador único del item          |
| order_id   | string (FK) | Referencia a la orden principal       |
| dish_id    | string (FK) | Referencia al platillo ordenado       |
| dish_name  | string      | Nombre del platillo (desnormalizado)  |
| quantity   | int         | Cantidad de platillos ordenados       |
| unit_price | decimal     | Precio unitario del platillo          |
| subtotal   | decimal     | Subtotal del item (cantidad × precio) |
| created_at | datetime    | Fecha de creación del registro        |

**Propósito**: Detallar el contenido específico de cada orden.

---

#### 9. INCOME_DETAIL (Detalle de Ingresos)
Desglosa la información detallada de ingresos en un reporte.

| Campo               | Tipo        | Descripción                            |
|---------------------|-------------|----------------------------------------|
| id                  | string (PK) | Identificador único del detalle        |
| report_id           | string (FK) | Referencia al reporte principal        |
| total_sales         | decimal     | Total de ventas en el periodo          |
| order_count         | int         | Cantidad de órdenes procesadas         |
| average_order_value | decimal     | Valor promedio por orden               |
| sales_by_dish       | string      | Ventas desglosadas por platillo (JSON) |
| sales_by_day        | string      | Ventas desglosadas por día (JSON)      |
| created_at          | datetime    | Fecha de creación del registro         |

**Propósito**: Proporcionar análisis detallado de los ingresos generados.

---

#### 10. LOSS_DETAIL (Detalle de Pérdidas)
Desglosa la información detallada de pérdidas en un reporte.

| Campo                 | Tipo        | Descripción                              |
|-----------------------|-------------|------------------------------------------|
| id                    | string (PK) | Identificador único del detalle          |
| report_id             | string (FK) | Referencia al reporte principal          |
| total_purchases       | decimal     | Total de compras en el periodo           |
| purchase_count        | int         | Cantidad de compras realizadas           |
| purchases_by_category | string      | Compras desglosadas por categoría (JSON) |
| purchases_by_day      | string      | Compras desglosadas por día (JSON)       |
| created_at            | datetime    | Fecha de creación del registro           |

**Propósito**: Proporcionar análisis detallado de las pérdidas o gastos incurridos.

---

#### Relaciones entre Entidades

| Relación                           | Cardinalidad | Descripción                                                                                              |
|------------------------------------|--------------|----------------------------------------------------------------------------------------------------------|
| USER → SUBSCRIPTION                | 1:N          | Un usuario puede tener múltiples suscripciones (historial de suscripciones actuales y pasadas)           |
| SUBSCRIPTION → SUBSCRIPTION_PLAN   | N:1          | Cada suscripción pertenece a un plan específico; un plan puede ser usado por múltiples suscripciones     |
| SUBSCRIPTION → PAYMENT_TRANSACTION | 1:N          | Una suscripción puede generar múltiples transacciones (pagos iniciales, renovaciones, intentos fallidos) |
| ORDER → ORDER_ITEM                 | 1:N          | Una orden contiene múltiples items; cada item pertenece a una única orden                                |
| DISH → ORDER_ITEM                  | 1:N          | Un platillo puede estar en múltiples items de orden; cada item referencia un único platillo              |

---

# Capítulo V: Product Implementation

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.

| Tipo de Herramienta  | Herramienta Utilizada                         | Propósito                              |
|----------------------|-----------------------------------------------|----------------------------------------|
| IDE                  | Visual Studio Code / WebStorm / IntelliJ Idea | Desarrollo frontend y backend          |
| Control de versiones | Git + GitHub                                  | Versionamiento y trabajo colaborativo  |
| Testing              | Gherkin                                       | Acceptance Tests                       |
| API Client           | Postman / Swagger                             | Validación de endpoints                |
| Base de Datos        | Postgres                                      | Almacenamiento persistente             |
| Documentación        | Swagger (OpenAPI)                             | Generación automática de documentación |
| Gestión de proyecto  | Trello                                        | Control ágil de tareas y User Stories  |

**Configuraciones adicionales:**  
El entorno de desarrollo utiliza variables `.env`, dependencias gestionadas con `npm`, y scripts configurados para automatizar pruebas y despliegues.

---

### 5.1.2. Source Code Management.

El control de versiones se gestiona con **GitHub** bajo la metodología **GitFlow Workflow**, que define ramas estables y de desarrollo:

- `develop`: rama principal de desarrollo.
- `feature/*`: ramas por funcionalidad.

**Convenciones:**
- Semantic Versioning (`v1.0.0`, `v1.1.0`, etc.)
- Conventional Commits (`feat:`, `fix:`, `docs:`)

**Repositorio donde se realizó el código:**

<br>

**Repositorio del proyecto actual:**

---

### 5.1.3. Source Code Style Guide & Conventions.

Guías de estilo aplicadas:

- TypeScript Style Guide.
- Gherkin Conventions for Readable Specifications.
- Clases en camelCase
- Uso de inglés en todo el código.

---

### 5.1.4. Software Deployment Configuration.

El despliegue de la landing page se realiza en Vercel

El despliegue del frontend se realiza en netlify

El despliegue del backend se realiza en **FreeSQL** para la base de datos.

**Pasos del pipeline:**
1. Build del proyecto (`npm run build`)
2. Ejecución de pruebas (`npm run test`)
3. Despliegue automatizado en entorno cloud
4. Validación mediante Postman y Swagger

<div style="page-break-after: always;"></div>

**Deployment Diagram (C4):**

<div style="page-break-after: always;"></div>

## 5.2. Product Implementation & Deployment.

### 5.2.1. Sprint Backlogs.

### 5.2.2. Implemented Landing Page Evidence

Se completó el desarrollo de la Landing Page de FoodFlow como el primer espacio de presentación del producto ante potenciales usuarios. Esta página funciona como una entrada informativa y comercial a la plataforma, permitiendo que los visitantes comprendan rápidamente qué problema resuelve FoodFlow, cómo ayuda a los restaurantes y cuáles son sus principales beneficios.

La landing page está organizada en una secuencia clara de secciones que guían al usuario durante todo el recorrido: Inicio, Funciones, Beneficios, Sobre nosotros, Cómo funciona, Planes, Contacto, Términos y Condiciones, Política de Privacidad, Ayuda y Preguntas frecuentes. Además, incorpora navegación superior, llamados a la acción, formulario de contacto, selector de idioma en español e inglés y un pie de página con accesos relevantes para reforzar la usabilidad y la confianza del visitante.

A nivel visual y funcional, la implementación respeta la identidad definida para FoodFlow, utilizando una composición moderna, jerarquía tipográfica clara, tarjetas informativas, contraste adecuado, componentes visuales consistentes y una estructura adaptable a distintos tamaños de pantalla. De esta manera, la Landing Page no solo comunica la propuesta de valor de la aplicación, sino que también facilita que los dueños de restaurantes identifiquen a FoodFlow como una solución accesible para organizar sus finanzas, centralizar información operativa y tomar decisiones basadas en datos.

Link de la Landing Page: [https://claudeflow-org.github.io/FoodFlow-LandingPage/](https://claudeflow-org.github.io/FoodFlow-LandingPage/)

### 5.2.3. Implemented Frontend-Web Application Evidence

### 5.2.4. Acuerdo de Servicio - SaaS

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

### 5.2.6. RESTful API documentation

### 5.2.7. Team Collaboration Insights

## 5.3. Video About-the-Product

# Conclusiones

## Conclusiones y recomendaciones

---

# Bibliografía

- Alvarez, A. (2020, 4 de agosto). *5W2H: qué significa, para qué sirve, cómo aplicarla y algunos ejemplos*. Lean Construction México. [https://www.leanconstructionmexico.com.mx/post/5w2h-qué-significa-para-qué-sirve-cómo-aplicarla-y-algunos-ejemplos](https://www.leanconstructionmexico.com.mx/post/5w2h-qu%C3%A9-significa-para-qu%C3%A9-sirve-c%C3%B3mo-aplicarla-y-algunos-ejemplos)

- Guzmán, C. (2019, 28 de junio). *Negocios de comida: el 70% cierra al primer año por mala gestión*. PQS. [https://pqs.pe/actualidad/economia/negocios-de-comida-el-70-cierra-al-primer-ano-por-mala-gestion/](https://pqs.pe/actualidad/economia/negocios-de-comida-el-70-cierra-al-primer-ano-por-mala-gestion/)

- Instituto Nacional de Estadística e Informática. (2024a). *Actividad de restaurantes aumentó 5,32% en marzo 2024*. INEI. [https://m.inei.gob.pe/prensa/noticias/actividad-de-restaurantes-aumento-532-en-marzo-2024-15163/](https://m.inei.gob.pe/prensa/noticias/actividad-de-restaurantes-aumento-532-en-marzo-2024-15163/)

- Instituto Nacional de Estadística e Informática. (2025, 20 de enero). *Actividad restaurantes aumentó 4,48% en noviembre 2024*. Plataforma del Estado Peruano. [https://www.gob.pe/institucion/inei/noticias/1094253-actividad-restaurantes-aumento-4-48-en-noviembre-2024](https://www.gob.pe/institucion/inei/noticias/1094253-actividad-restaurantes-aumento-4-48-en-noviembre-2024)

- NetSuite. (2025, 9 de enero). *The ultimate guide to restaurant finance management*. Oracle NetSuite. [https://www.netsuite.com/portal/resource/articles/financial-management/restaurant-financial-management.shtml](https://www.netsuite.com/portal/resource/articles/financial-management/restaurant-financial-management.shtml)

- Sage. (2025, 19 de junio). *Guide to restaurant inventory management and best practices*. Sage Advice. [https://www.sage.com/en-us/blog/restaurant-inventory-management-best-practices/](https://www.sage.com/en-us/blog/restaurant-inventory-management-best-practices/)

---

# Anexos

