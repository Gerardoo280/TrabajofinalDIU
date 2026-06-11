# Trabajo Final DIU 2025/26
## Portfolio UX y Propuesta de Diseño — EcoMercado UGR

**Alumno:** Gerardo Pérez Triviño 

---

## Índice
1. [Parte I: Mi Experiencia UX](#parte-i-mi-experiencia-ux)
2. [Parte II: Caso de Estudio — EcoMercado UGR](#parte-ii-caso-de-estudio--ecomercado-ugr)

---

## PARTE I: Mi Experiencia UX

### Introducción

A lo largo de este curso he acumulado experiencia en UX a través de: por un lado, una serie de **ejercicios de clase** propuestos por el profesor sobre técnicas concretas; por otro, el **proyecto de prácticas** (P1–P5) aplicado al rediseño de la app de Goiko desarrollado junto con mi compañero Claudio. A continuación describo las aportaciones más relevantes de cada una, relacionándolas con los conceptos y marcos metodológicos estudiados.

---

### A. Ejercicios de clase

#### A.1 Etnografía

El ejercicio etnográfico fue una experiencia bastante interesante, porque te obliga a observar lo que ocurre alrededor con especial atención. La conclusión más relevante que extraje es que el comportamiento real de las personas frente a una interfaz raramente coincide con el comportamiento que los desarrolladores piensan que van a tener los usuarios que usan su interfaz. Esto implica que para el desarrollo del diseño no basta con preguntar cual es la necesidad del usuario, hay que observarlo.

#### A.2 Moodboard

El ejercicio de moodboard me ayudó a comprender la importancia que tienen las decisiones visuales dentro de un proyecto de diseño. Antes de empezar a crear las pantallas, mi grupo y yo definimos una estética acorde con la temática de la web y con la experiencia que queríamos transmitir al usuario.

En nuestro caso, trabajamos con referencias relacionadas con ciudades marcadas por acontecimientos históricos, lugares abandonados, memoria colectiva y turismo cultural alternativo. Las imágenes oscuras, los tonos apagados y las referencias a distintos lugares con una historia trágica nos sirvieron para definir una  visualización basada en el misterio, la reflexión y el descubrimiento. Además, la selección de colores, el tipo de letra y las fotografías nos permitió establecer la temática de nostalgia que queriamos transmitir

La principal conclusión que obtuve es que el moodboard funciona como una guía visual que ayuda a tomar decisiones más coherentes durante el proceso de diseño. 

#### A.3 Eye Tracking

A pesar de que el ejercicio de eye tracking aplicado sobre una interfaz real nos fallará al hacerlo en clase por usar firefox, en las prácticas lo volví a usar junto con mi compañero y funcionó de forma correcta, lo que fue bastante útil para entender la **jerarquía visual** más alla de la teoría.
Usando GazeMapping sobre capturas estáticas, pudimos comprobar cómo los usuarios distribuyen su atención sobre todo a los elementos más llamativos o en aquellos elementos que les parecen más interesantes de la página.
Los resultados mostraron que las imágenes de gran tamaño, los títulos destacados y los botones fue lo que concentró mayoritariamente la vista de los usuarios. 

#### A.4 Usabilidad con Heurio

El ejercicio práctico consistió en evaluar la experiencia de usuario en la plataforma web de la Universidad de Málaga (uma.es).
A través de la extensión Heurio, realizamos una inspección visual colaborativa sobre la interfaz, agrupando y priorizando los hallazgos en un tablero según su nivel de severidad:

### Neutral (Puntos Fuertes / Facilidades de Uso)
* **Erasmus encontrado en un click:** Excelente arquitectura de información para la sección de movilidad internacional.
* **Fácil encontrar el calendario académico:** Acceso rápido e intuitivo a las fechas clave del curso.
* **Fácil encontrar el defensor universitario:** Localización directa de los canales institucionales de apoyo al estudiante.

### Medium (Severidad Media)
* **No encontramos un asistente:** Ausencia de sistemas automatizados de guía o asistentes virtuales integrados para resolver dudas frecuentes.
* **Demasiada información:** Sobrecarga cognitiva debido a la saturación visual y la densidad de elementos en determinadas pantallas.

### High (Severidad Alta)
* **Falta una ayuda general:** Deficiencia notable por la carencia de un centro de ayuda global o soporte técnico visible desde el flujo principal.

A partir de esta evaluación nos dimos cuenta que realmente la accesibilidad no es un parche que se añade al final de un proyecto sin más, es un criterio de diseño fundamental que debe implementarse desde el primer día.

#### A.5 Accesibilidad

El ejercicio de accesibilidad se aplicó sobre la web del Ayuntamiento de Almería, obteniendo una valoración total de 52/100, lo que indica una accesibilidad no demasiado buena con algunos defectos importantes para tratarse de una institución pública que debería de garantizar su fácil accesibilidad.

Usando WAVE, mi grupo y yo identificamos 5 errores críticos: 1 imagen enlazada sin texto alternativo, 4 enlaces vacíos sin descripción y 2 errores de contraste muy bajo, todos bajo el criterio Perceptible de las WCAG (criterios 1.1.1 y 1.4.3). Con Funkify simulamos distintas discapacidades y comprobé que usuarios con visión borrosa no podían localizar eventos culturales por la alta densidad de elementos y banners dinámicos superpuestos, que usuarios con dislexia tenían dificultades reales con los titulares de noticias por falta de descripción alternativa en imágenes, y que usuarios con enfermedades como el parkinson encontraban los enlaces del menú demasiado pequeños y difíciles de clicar. Además, otro defecto que encontramos fue la imposibilidad de cambiar de idioma por si algún extranjero quisiera consultar y leer esta página..
Como aspectos positivos, la web sí incorpora un widget de accesibilidad propio con opciones de contraste, fuente y máscara de lectura, skip links y estructura semántica con H1/H2, lo que indica intención de cumplimiento pero una ejecución incompleta. La principal conclusión fue que la accesibilidad automática (WAVE) detecta fallos técnicos, pero la simulación con Funkify aporta los problemas para la visión humana de aquellas peersonas con distintas capacidades, esto es algo que un editor automático no puede encontrar.

#### A.6 Portfolio con Figma Make

El ejercicio de portfolio con **Figma Make** fue una introducción al uso de IA para generar un portfolio. La creación de este portfolio permitió que me diera cuenta que un buen prompt es mejor que 10 prompts malos y breves. Figma make puede generar plantillas visuales en minutos, y cuanto más precisos seamos especificando lo que queremos obtener, mejor será el resultado que obtendremos.

---

### B. Prácticas: Proyecto Goiko (P1–P5)

#### B.1 UX User & Desk Research & Analisis
La primera práctica estuvo centrada en comprender el problema antes de empezar a diseñar. Para ello elaboramos un User Research Plan en el que definimos los objetivos de investigación, los perfiles de usuario, los escenarios de uso y las métricas que utilizaríamos posteriormente para evaluar la experiencia. Este documento fue especialmente útil porque nos obligó a pensar desde el principio qué queríamos medir y cómo íbamos a justificar nuestras decisiones.

También realizamos un Competitive Analysis comparando Goiko con Five Guys y The Champions Burger. Este análisis nos permitió identificar qué elementos diferenciaban a cada competidor y qué oportunidades de mejora existían para Goiko. A partir de ahí desarrollamos dos Personas representativas de nuestro público objetivo y sus correspondientes User Journey Maps, lo que nos ayudó a comprender mejor sus motivaciones, necesidades y posibles frustraciones durante el proceso de búsqueda y compra de una hamburguesa.

Finalmente, realizamos una Usability Review de la web actual de Goiko. Gracias a esta evaluación detectamos fortalezas importantes, como la calidad visual de los productos y la facilidad para acceder a la carta, pero también problemas como la ausencia de buscador interno, la falta de filtros en la carta o la inexistencia de un indicador de progreso durante el proceso de pedido. Esto nos dió ideas para mejorar la web de Goiko.

#### B.2 UX Design (P2)

Una vez comprendido el contexto y las necesidades de los usuarios, comenzamos la fase de ideación. Para ello elaboramos un Empathy Map y un Feedback Capture Grid, herramientas que nos permitieron transformar los problemas detectados en oportunidades concretas de diseño.

La principal idea surgida durante esta fase fue la creación de un sistema de hamburguesas personalizadas, permitiendo al usuario elegir ingredientes, guardar combinaciones y reutilizarlas en futuros pedidos. Esta funcionalidad se nos ocurrió ya que es algo que la gente, incluso nosotros, hemos reclamado alguna vez.

El **Scope Canvas** fue útil para evitar el *scope creep* antes de prototipar, es decir, hacer cosas que le dieran demasiada complejidad a nuestra funcionalidad. La elaboración del **Sitemap** y el **labelling** fue mi primera aplicación real de arquitectura de información. Además aprendí que las etiquetas no son neutras, por ejemplo los botones de "Pedir" o de "Realizar un pedido" reducen la carga cognitiva de forma drástica y también nos dimos cuenta que la estructura de navegación por la página debe ser acorde a la mente del usuario, no la organización interna del negocio.

#### B.3 Mi UX-Case Study (diseño) (P3)

En esta fase transformamos las ideas y estructuras definidas anteriormente en una propuesta visual completa. 
La creación del Moodboard superó la simple selección de referencias, nos sirvió para establecer el marco del diseño en el proyecto. Tomando como base la identidad de Goiko (colores oscuros y fotografía premium). Concluimos que mantener esta estética no solo respeta el branding, sino que genera un entorno de familiaridad que reduce la desconfianza del usuario en entornos digitales.

El diseño de la Landing Page se enfocó como el punto crítico del embudo de conversión. En lugar de saturar al usuario, se aplicaron principios de jerarquía visual y reducción de la carga cognitiva, priorizando los accesos rápidos a la personalización de hamburguesas y reserva de mesas. La conclusión clave de esta estructura es que al minimizar los pasos iniciales, se reduce la tasa de abandono potencial

El desarrollo de las Guidelines (patrones de interfaz, navegación y componentes) funcionó como el sistema de diseño del proyecto. La aportación principal de este documento fue garantizar la consistencia cognitiva. Al unificar el comportamiento de los botones y menús, el usuario no tiene que reaprender a usar la aplicación en cada pantalla nueva, lo que mejora la curva de aprendizaje y la usabilidad general.

No planteamos el prototipo interactivo en Figma solo como una entrega técnica de pantallas bonitas, sino como la prueba real para comprobar si el flujo de usuario (user flow) funcionaba en la práctica. Al poder simular todo el recorrido (desde la pantalla de inicio hasta la confirmación del pago) nos encargamos de comprobar que las decisiones previas que tomamos sobre la arquitectura de nestra página eran las más correctas y eficientes. La conclusión clave de este paso es que aplicar un Diseño Centrado en el Usuario nos permitió detectar y resolver los problemas de navegación de forma visual, antes de entrar a la fase de programación, donde cualquier cambio habría sido mucho más complejo y costoso.

#### B.4 Exportación y documentación(P4)
Aquí pasamos el landing page a una aplicación de React.js, pero no pudimos usar el código que genera figma por lo que lo creamos desde cero nostros mismos.
Esto nos permitió seguir aprendiendo el lenguaje de React.js un poco más, ya que mi conocimiento en React.js era mínimo pero mi compañero si tenía más nivel, lo cuál me ayudó a aprender más sobre react y a mi compañero a recordar cosas que ya sabía.

#### B.5 Pruebas de Evaluación(P5)

La última práctica estuvo dedicada a comprobar si las decisiones tomadas durante el diseño realmente mejoraban la experiencia de usuario. Para ello realizamos un estudio comparativo entre nuestra propuesta de Goiko (Caso A) y el proyecto de otro grupo, la cafetería Despiertoo (Caso B).
No la planteamos como un simple trámite de testeo, sino como la oportunidad real de validar mediante datos empíricos si nuestras decisiones de diseño realmente optimizaban la experiencia de usuario frente a otras alternativas del mercado.

Al comparar nuestra propuesta de Goiko (Caso A) con el proyecto Despiertoo (Caso B), los datos demostraron la efectividad de nuestro rediseño. Logramos una tasa media de éxito del 83,34 %, reduciendo además el tiempo y el número de interacciones necesarias. La conclusión teórica más importante aquí es que la reducción de la carga cognitiva y la jerarquía visual que planificamos funcionaron en la práctica: los usuarios localizaron la personalización de hamburguesas de inmediato, demostrando que una interfaz intuitiva elimina la frustración y acelera el flujo de conversión.

También aplicamos el cuestionario SUS (System Usability Scale) para obtener una medida estandarizada de la percepción de usabilidad. Los resultados reflejaron una valoración positiva de la facilidad de uso y de la integración de las funcionalidades principales, lo cual es clave para la retención de clientes en una app real.

Por otra parte, realizamos un estudio de Eye Tracking mediante GazeMapping sobre la web de Despiertoo. Este análisis nos permitió observar qué elementos captaban la atención de los usuarios y cómo la jerarquía visual influía en su comportamiento. Los mapas de calor mostraron que determinadas zonas concentraban gran parte de las miradas mientras que otras áreas relevantes pasaban prácticamente desapercibidas. Esto nos aportó una conclusión clave: si no guías la mirada del usuario de forma intencionada a través del diseño, el usuario se pierde, lo que reforzó nuestra decisión de mantener un diseño limpio y enfocado en Goiko.

Por último, más allá de utilizar las herramientas WAVE y Lighthouse para buscar errores estáticos y obtener una puntuación, estás herramientas nos ayudaron a entender el diseño inclusivo. Detectar problemas reales de contraste y botones vacíos nos hizo comprender que la accesibilidad no es una lista de requisitos secundarios, sino una parte fundamental de la UX. Aprendimos que un error de contraste o la falta de texto y unicamente poner un icono en su lugar no son solo un fallo técnico, sino una barrera real que excluye directamente a usuarios con discapacidades visuales.

---

### Valoración global

La realización de este proyecto me ha permitido recorrer todas las etapas de un proceso de diseño UX completo. A diferencia de otros trabajos centrados únicamente en el diseño visual, en este proyecto hemos pasado por fases de investigación, análisis, ideación, arquitectura de información, prototipado, implementación y evaluación.

Entre los trabajos desarrollados destacan la elaboración del User Research Plan, el Competitive Analysis, las Personas, los Journey Maps, el Empathy Map, el Scope Canvas, el Sitemap, los Wireframes, el Moodboard, la Landing Page, las Guidelines, el prototipo interactivo en Figma y la implementación parcial en React. Ver cómo todos estos entregables estaban conectados entre sí me ayudó a comprender mejor la metodología UX y la importancia de seguir un proceso estructurado.

Si tuviera que destacar un aprendizaje principal, sería entender que las mejores decisiones de diseño no surgen de la intuición, sino de la investigación y de la validación con usuarios reales. Las pruebas que realizamos al final del proyecto demostraron que muchas de las decisiones tomadas durante las primeras fases tenían un gran impacto en la facilidad de uso del producto final, por tatno, un detalle que parece insignificante en la primera etapa se vuelve crucial en las etapas finales.

---

## PARTE II: Caso de Estudio — EcoMercado UGR
 
### Contexto del proyecto
 
El **EcoMercado UGR** es una iniciativa de la Universidad de Granada y la Red Agroecológica de Granada, celebrada mensualmente los jueves en los Paseíllos Universitarios del Campus de Fuentenueva (9:30–14:00 h). Se enmarca en el proyecto **Granada Tierra Viva** (Impronta Granada) y reúne a productores locales de proximidad agroecológica. Más allá de un mercado, es un espacio de aprendizaje, intercambio y conexión entre sostenibilidad, territorio y comunidad universitaria. Esta dimensión social y educativa tiene implicaciones directas en el diseño de su presencia digital: el objetivo no es solo informar de una fecha, sino construir comunidad y continuidad entre ediciones.
 
El **problema central identificado** es que el EcoMercado UGR carece de presencia digital propia. La información se distribuye de forma fragmentada entre páginas institucionales (Impronta Granada, Canal UGR) con arquitecturas diseñadas para otros propósitos, lo que genera fricción en el journey de cualquier usuario que quiera informarse antes de asistir.
 
---
 
### 2a. Análisis de referentes
 
Para este análisis se adopta el rol de evaluador experto, aplicando los criterios del **proceso de diseño centrado en usuario** y las **heurísticas de Nielsen** como marco de referencia objetivo.
 
---
 
#### Referente 1: Mercat de Pages — Xarxa de Consum Solidari (xarxaconsum.org)
 
**¿Quién es el usuario de esta página?**
 
El perfil más probable es un consumidor adulto (30-55 años) con conciencia ecológica y conocimiento previo de la organización, que accede para encontrar información práctica sobre los mercados: cuándo, dónde, qué productores participan. También puede ser un usuario nuevo que llega por búsqueda orgánica ("mercado ecológico Barcelona"). En ambos casos, la tarea principal es informacional, no transaccional.
 
**¿Qué busca/necesita?**
 
Las tareas críticas identificadas son: (1) localizar el mercado más cercano, (2) saber el horario, (3) conocer qué productos hay disponibles. Tareas secundarias: contactar con un productor, suscribirse a novedades.
 
**Puntos fuertes desde el factor humano:**
 
La sección "Mercados de campesinos" está accesible desde el menú principal en un clic directo, lo que aplica correctamente la heurística H3 (*control y libertad del usuario*) y minimiza la profundidad de navegación para la tarea principal. El listado de productores con foto, nombre y categoría responde bien al principio de **reconocimiento antes que recuerdo** (H6 de Nielsen): el usuario puede identificar visualmente si hay productos de su interés sin leer texto. La web ofrece además selector de idioma (español/catalán), respondiendo al criterio de **internacionalización**.
 
**Problemas detectados:**
 
El problema estructural más relevante es la **disonancia de contexto**: la página de mercados vive dentro de una web institucional de una ONG de comercio justo. El usuario que llega buscando información práctica de asistencia encuentra una arquitectura diseñada para comunicar la organización, no para resolver sus tareas. Aplicando el concepto de **modelo mental** de Norman (2013): el visitante espera el patrón "página de evento" (fecha destacada, mapa, lista de productos, CTA de asistencia) y la web no lo satisface, lo que genera desorientación y aumenta el tiempo en tarea.
 
En términos de arquitectura de información, cada mercado (Fort Pienc, Eixample, Guinardó…) está presentado como un bloque de texto con múltiples enlaces (localización, Telegram, WhatsApp, formulario de pedido) sin jerarquía visual clara, lo que viola la heurística H8 (*diseño estético y minimalista*): se muestran cuatro canales de contacto por mercado de forma simultanea cuando el usuario probablemente solo necesita uno.
 
No se detecta adaptación responsiva optimizada para móvil, lo cual es un fallo crítico dado que el usuario que consulta dónde ir un sábado por la mañana lo hace desde el teléfono. Las tablas de mercados y bloques de texto se comprimen sin reflow adecuado, dificultando la lectura en pantallas pequeñas.
 
**Valoración global:** la web cumple su función como canal de comunicación institucional, pero falla como herramienta orientada a la tarea del usuario asistente. La estructura de navegación refleja la organización interna de la ONG, no el modelo mental del visitante.
 
---
 
#### Referente 2: Nuestras Huertas (nuestrashuertas.com)
 
*Nota: esta web bloquea el acceso automatizado. El análisis se basa en el análisis del snippet de búsqueda, metadatos públicos y descripción disponible.*
 
**¿Quién es el usuario de esta página?**
 
Consumidor urbano (25-45 años) con hábito de compra online y valores de consumo responsable, que busca tanto información sobre mercados físicos como la posibilidad de hacer pedidos o suscripciones a cajas de productos.
 
**Puntos fuertes:**
 
La propuesta de valor (productos ecológicos, de temporada, de agricultores locales) está definida y visible desde el primer contacto, lo que aplica el principio de **claridad en el modelo conceptual** del producto: el usuario sabe inmediatamente qué ofrece el servicio y para quién es. La integración de canal online y mercado físico satisface distintos momentos del journey del consumidor ecológico.
 
**Problemas detectados:**
 
Según la información disponible, la plataforma presenta sobrecarga de opciones en algunas secciones, lo que dificulta el escaneo rápido (viola H8). La orientación está más centrada en el canal e-commerce que en facilitar la asistencia a mercados físicos, lo que no se alinea bien con el caso de uso del EcoMercado UGR, donde el componente presencial y comunitario es el núcleo de la propuesta.
 
---
 
### 2b. Insights y Propuesta de Valor para EcoMercado UGR
 
#### Insights extraídos del análisis comparativo
 
**Insight 1 — Ningún referente resuelve bien la tarea del usuario asistente ocasional.** Mercat Pages prioriza la comunicación institucional y Nuestras Huertas prioriza el e-commerce. El usuario que quiere saber simplemente "¿hay mercado este jueves y qué voy a encontrar?" no tiene una respuesta clara en ninguno de los dos. Esto define la oportunidad de diseño principal para el EcoMercado UGR.
 
**Insight 2 — El componente de comunidad y aprendizaje es un diferencial no explotado digitalmente.** Ambos referentes listan productores, pero ninguno aprovecha el potencial narrativo de cada productor (historia, territorio, técnicas) ni el componente educativo (talleres, recetas de temporada, charlas). Para el EcoMercado UGR, que tiene la universidad como contexto, este es el valor diferencial que justifica una presencia digital propia más allá de una simple página de evento.
 
**Insight 3 — La fragmentación de la información es el principal problema de usabilidad del EcoMercado UGR actual.** Sin un punto de entrada único y orientado al usuario, la fricción en el journey es máxima: el usuario debe navegar entre webs institucionales con arquitecturas no diseñadas para sus tareas. Esto se traduce directamente en abandono y menor asistencia.
 
**Insight 4 — El perfil de usuario universitario exige diseño mobile-first.** El público principal (estudiantes, PAS, PDI) accede a la información desde el móvil. Cualquier propuesta que no esté optimizada para este contexto falla en su caso de uso más frecuente.
 
---
 
#### Definición de personas
 
**Persona 1 — Lucía, 22 años, estudiante de Biología (ETSI Caminos, Campus Fuentenueva)**
Pasa por los Paseíllos todos los días pero no siempre sabe cuándo hay mercado. Le interesan los productos locales y le gustaría repetir, pero la falta de información clara hace que se entere por casualidad. Dispositivo principal: iPhone. Necesidades: saber si hay mercado esta semana, horario, qué tipo de productos habrá. Frustración actual: "He llegado cuando ya estaban recogiendo".
 
**Persona 2 — Andrés, 47 años, profesor titular de la ETSII**
Consume productos ecológicos regularmente y valora conocer el origen de lo que come. Reserva el jueves del mercado pero tiene agenda ajustada. Necesita: lista de productores del mes, qué productos traerá cada uno, contenido sobre prácticas agroecológicas. Frustración actual: "No sé qué productores van a ir hasta que llego".
 
Ambas personas comparten la misma tarea inicial (¿hay mercado y cuándo?) pero divergen en profundidad de uso: Lucía es un usuario de consulta rápida; Andrés es un usuario de exploración.
 
---
 
#### Propuesta de diseño: App móvil EcoMercado UGR
 
**Justificación del formato app vs. web:** dado el perfil de usuario (universitario, smartphone como dispositivo principal, consulta en contexto de movilidad), una **Progressive Web App (PWA)** ofrece el mejor equilibrio entre accesibilidad (sin descarga) y experiencia nativa (notificaciones, añadir a pantalla de inicio). Este enfoque aplica el principio de **diseño orientado al contexto de uso** estudiado en clase.
 
**Principios de diseño aplicados y justificación:**
 
- **Mobile-first:** la pantalla principal debe responder la pregunta "¿hay mercado este jueves?" sin hacer scroll, con fecha, horario y ubicación visibles en el primer viewport. Cualquier otro contenido es secundario. Esto deriva directamente del análisis de tareas: la tarea de mayor frecuencia y urgencia debe estar en el nivel 0 de la interfaz.
- **Progressive disclosure (Johnson, 2010):** se muestra primero lo esencial (cuándo, dónde, qué hay), y el usuario que quiere profundizar (historia de un productor, receta de temporada, charlas) navega voluntariamente a secciones específicas. Esto evita la sobrecarga cognitiva detectada en Mercat Pages.
- **Consistencia y estándares (H4 Nielsen):** bottom navigation bar fija con 4 secciones, patrón estándar en apps móviles que reduce la curva de aprendizaje para usuarios nuevos. Se descarta el menú hamburguesa porque oculta las opciones y aumenta la carga cognitiva.
- **Visibilidad del estado del sistema (H1 Nielsen):** indicador claro de si el mercado está activo este mes ("Próxima edición: jueves 26 junio" vs. "No hay mercado este mes"), evitando que el usuario llegue sin que haya mercado, que es la frustración más frecuente identificada en las personas.
- **Accesibilidad desde el diseño:** paleta con contraste ≥ 4.5:1 (WCAG AA, criterio 1.4.3), botones con área táctil mínima de 44×44px (WCAG 2.5.5), etiquetas accesibles en todos los elementos interactivos (criterio 1.1.1). La accesibilidad no se audita al final: se diseña desde el sistema de colores.
**Arquitectura de información:**
 
```
EcoMercado UGR (PWA)
├── Inicio
│   ├── Tarjeta hero: próxima edición (fecha, hora, lugar, mapa, +calendario)
│   ├── Productores del mes (categorías: huerta, quesos, pan, miel, cosmética)
│   └── Contenido destacado: receta o charla del mes
├── Productores
│   ├── Listado del mes con foto, nombre y categorías
│   └── Ficha de productor (historia, técnicas, productos, contacto)
├── Calendario
│   ├── Próximas ediciones
│   └── Archivo de ediciones anteriores
├── Aprende
│   ├── Recetas de temporada
│   ├── ¿Qué es la agroecología?
│   └── Charlas y actividades paralelas
└── Sobre el proyecto
    └── Red Agroecológica / Granada Tierra Viva / Impronta UGR
```
 
El **labelling** sigue el principio de economía de lenguaje: "Productores" en lugar de "Nuestros productores agroecológicos participantes"; "Aprende" en lugar de "Contenido educativo y divulgativo". Las etiquetas cortas reducen la carga cognitiva y son más escaneables.
 
---
 
#### Boceto de wireframe — Pantalla principal (mobile, 390px)
 
```
┌────────────────────────────┐
│  🌿 EcoMercado UGR    🔔   │  ← header fijo, notificaciones
├────────────────────────────┤
│  ┌──────────────────────┐  │
│  │ PRÓXIMA EDICIÓN      │  │  ← tarjeta hero, primer viewport
│  │ Jueves 26 junio      │  │
│  │ 9:30 – 14:00 h       │  │
│  │ Paseíllos Fuentenueva │  │
│  │ [📍 Ver mapa][+🗓 Cal]│  │  ← 2 CTAs, verde primario
│  └──────────────────────┘  │
│                            │
│  PRODUCTORES DEL MES       │
│  ┌────┐ ┌────┐ ┌────┐     │  ← tarjetas de categoría
│  │ 🥬 │ │ 🧀 │ │ 🍯 │     │
│  │Huer│ │Ques│ │Miel│     │
│  └────┘ └────┘ └────┘     │
│  Ver todos →               │
│                            │
│  ┌──────────────────────┐  │
│  │ 📚 RECETA DEL MES    │  │  ← contenido de valor, engagement
│  │ Gazpacho con tomate  │  │
│  │ de la Vega granadina │  │
│  └──────────────────────┘  │
├────────────────────────────┤
│ [🏠][👩‍🌾][🗓][📖]          │  ← bottom nav fija, 4 secciones
└────────────────────────────┘
```
 
**Descripción de decisiones de diseño:**
 
La **tarjeta hero** ocupa el primer viewport completo en mobile (sin scroll) y responde directamente la pregunta más frecuente del usuario. Los dos CTAs (mapa y calendario) tienen función clara y diferenciada: el primero resuelve la navegación física; el segundo, la planificación. Ambos usan el verde como color primario, coherente con los valores del proyecto y con un contraste que cumple WCAG AA.
 
La sección de **productores del mes por categoría** permite anticipar si habrá algo de interés antes de ir, reduciendo la incertidumbre identificada en las personas ("no sé qué voy a encontrar"). Esto actúa como motivador de asistencia, especialmente para usuarios poco habituales.
 
La sección **"Aprende"** convierte la plataforma en un punto de contacto continuo entre ediciones, transformando el EcoMercado de un evento puntual en una comunidad digital activa. Esta es la diferencia clave respecto a los referentes analizados.
 
---
 
#### Comparativa con referentes
 
| Dimensión | Mercat Pages | Nuestras Huertas | EcoMercado UGR (propuesta) |
|---|---|---|---|
| Tarea principal resuelta en ≤2 clics | No | Parcial | Sí |
| Mobile-first | No | Parcial | Sí |
| Info de productores con historia | No | No | Sí |
| Componente educativo/comunidad | No | No | Sí |
| Integración con calendario personal | No | No | Sí |
| Accesibilidad WCAG AA por diseño | No evaluada | No evaluada | Sí |
| Presencia digital propia | No (embebida en ONG) | Sí | Sí |
 
---
 
### 2c. Reflexión y autoevaluación
 
#### Lo que he aplicado en prácticas y tiene transferencia directa a este caso
 
**Investigación de usuario (P1):** el User Research Plan, la creación de personas con escenarios y métricas concretas, y la Usability Review son directamente transferibles. En este caso los aplicaría con una diferencia importante: añadiría **observación etnográfica en el propio mercado** para entender los comportamientos reales de los asistentes (¿consultan el móvil durante el mercado? ¿cómo llegan al EcoMercado?), y realizaría entrevistas con productores como stakeholders clave cuyas necesidades también debe satisfacer la plataforma.
 
**Arquitectura de información (P2):** el sitemap y el labelling tienen aplicación directa. La diferencia es que en el EcoMercado el eje estructural es el **calendario y los eventos**, no el catálogo de productos, lo que requiere una IA orientada al tiempo más que al inventario.
 
**Prototipado en Figma (P3):** el proceso de moodboard → design system → wireframes → prototipo navegable es completamente transferible. El reto adicional aquí sería diseñar las fichas de productor considerando que el contenido lo generarían múltiples actores con distintos niveles de habilidad digital.
 
**Evaluación con usuarios (P5):** SUS, A/B testing, eye tracking y WAVE/Lighthouse son directamente aplicables. La auditoría de accesibilidad es especialmente relevante en un contexto universitario con público diverso que incluye personas con discapacidad.
 
#### Lo que me ha faltado y habría aportado valor en este caso
 
**Card sorting para validar la arquitectura de información:** en las prácticas el sitemap se construyó de forma top-down. Para el EcoMercado habría sido valioso hacer un card sorting con usuarios reales para validar que las secciones propuestas ("Productores", "Aprende", "Calendario") corresponden a los modelos mentales del público, o si los usuarios agruparían la información de otra manera.
 
**Investigación etnográfica en contexto:** observar cómo se comportan los asistentes al mercado con el móvil en mano (¿buscan info de un productor? ¿comparten en Instagram? ¿llegan con la web abierta?) habría convertido varias hipótesis de diseño en decisiones basadas en evidencia.
 
**Test de accesibilidad con usuarios reales:** WAVE y Lighthouse detectan fallos técnicos de forma automatizada, pero un test con usuarios con discapacidad visual o motriz aportaría información cualitativa sobre el impacto real de esos fallos, algo que ninguna herramienta automática puede capturar.
 
**Diseño de contenido (Content Design):** la voz, el tono y la longitud de los textos tienen especial importancia en un proyecto con dimensión educativa y comunitaria como el EcoMercado. Es un área poco trabajada en las prácticas y que en un proyecto real requeriría criterios explícitos de redacción UX.
 
#### Conclusión
 
El ejercicio de analizar el EcoMercado UGR como caso de estudio ha confirmado que el proceso UX aprendido durante el curso es transferible a contextos muy distintos del proyecto de prácticas. Los problemas identificados —fragmentación informativa, ausencia de orientación al usuario asistente, falta de diseño mobile-first— son exactamente los que el proceso de investigación, ideación y prototipado del curso permite detectar y resolver. La diferencia entre una propuesta bien fundamentada y una opinión personal está en la capacidad de argumentar cada decisión con criterios cuantificables y referencias metodológicas sólidas. Eso es precisamente lo que este proceso enseña.
 
---
 
## Referencias
 
- Nielsen, J. (1994). *10 Usability Heuristics for User Interface Design*. Nielsen Norman Group.
- Norman, D. (2013). *The Design of Everyday Things* (Revised Edition). Basic Books.
- Rohrer, C. (2014). *When to Use Which User-Experience Research Methods*. Nielsen Norman Group.
- Brooke, J. (1996). *SUS: A 'Quick and Dirty' Usability Scale*. Usability Evaluation In Industry.
- W3C (2018). *Web Content Accessibility Guidelines (WCAG) 2.1*. W3C Recommendation.
- Cooper, A., Reimann, R., & Cronin, D. (2007). *About Face 3: The Essentials of Interaction Design*. Wiley.
- EcoMercado UGR: [improntagranada.es](https://improntagranada.es/evento/jornada-inaugural-del-ecomercado-ugr/)
- Xarxa de Consum Solidari: [xarxaconsum.org](https://xarxaconsum.org/es/mercados-de-campesinos/)
- Nuestras Huertas: [nuestrashuertas.com](https://www.nuestrashuertas.com/)
---
 
*Trabajo elaborado para la asignatura Diseño de Interfaces de Usuario — ETSI Informática y Telecomunicaciones, Universidad de Granada. Curso 2025/26.*
