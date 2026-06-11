# Trabajo Final DIU 2025/26
## Portfolio UX y Propuesta de Diseño — EcoMercado UGR

**Alumno:** Gerardo Pérez Triviño 


https://fence-pop-58809035.figma.site


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
 
El **EcoMercado UGR** es una iniciativa de la Universidad de Granada y la Red Agroecológica de Granada, celebrada mensualmente los jueves en los Paseíllos Universitarios del Campus de Fuentenueva (9:30–14:00 h). Se enmarca en el proyecto **Granada Tierra Viva** (Impronta Granada) y reúne a productores locales de proximidad agroecológica. Más allá de un mercado, es un espacio de aprendizaje, intercambio y conexión entre sostenibilidad, territorio y comunidad universitaria.
 
El **problema central** es que el EcoMercado carece de presencia digital propia. La información se distribuye fragmentada entre páginas institucionales con arquitecturas diseñadas para otros propósitos, generando fricción en el journey de cualquier usuario que quiera informarse antes de asistir.
 
---
 
### 2a. Análisis del referente: Mercat de Pages — Xarxa de Consum Solidari (xarxaconsum.org)
 
**Justificación de la elección:** se selecciona este referente por ser el más comparable al EcoMercado UGR: mercado físico periódico con componente comunitario y valores agroecológicos, sin modelo e-commerce como eje central. Se descarta Nuestras Huertas (nuestrashuertas.com) como referente principal porque su propuesta gira en torno a la venta online de cajas de productos, un modelo diferente que no aporta aprendizajes directamente transferibles al caso de un mercado presencial universitario.
 
El análisis se realiza con criterios de evaluador experto, aplicando las **heurísticas de Nielsen** y el marco de **diseño centrado en usuario** como referencia objetiva.
 
---
 
#### ¿Quién es el usuario y qué necesita?
 
El perfil principal es un consumidor adulto (30-55 años) con conciencia ecológica que accede para encontrar información práctica: cuándo es el mercado, dónde está, qué productos habrá. El contexto de uso más probable es el **móvil en desplazamiento**, consultando el mismo día o el día anterior. Las tareas críticas por frecuencia son: (1) localizar el mercado más cercano, (2) conocer el horario, (3) saber qué productos hay. La web no está estructurada en torno a ninguna de estas tareas, lo que constituye el problema central de usabilidad.
 
---
 
#### Puntos fuertes
 
La sección "Mercados de campesinos" está accesible desde el menú principal de forma directa, cumpliendo **H3 de Nielsen** (*control y libertad del usuario*) y minimizando la profundidad de navegación para la tarea principal: un clic desde cualquier página del sitio. El listado de productores con fotografía, nombre y categoría aplica correctamente **H6** (*reconocimiento antes que recuerdo*): el usuario puede identificar visualmente si hay productos de su interés sin necesidad de leer texto. La web ofrece además selector de idioma español/catalán, respondiendo al principio de internacionalización.
 
---
 
#### Problemas de usabilidad y UX detectados
 
**1. Disonancia de contexto en la home (severidad: alta)**
 
La pantalla de inicio muestra un carrusel con fotografías de cooperación internacional y el texto "Tejiendo alianzas con organizaciones de mujeres de todo el mundo". Un usuario que llega buscando un mercado ecológico no reconoce que ha llegado al sitio correcto. Aplicando el concepto de **modelo mental** de Norman (2013), el visitante espera el patrón "mercado ecológico" (productos frescos, fecha próxima, mapa) y encuentra el patrón "ONG de cooperación internacional". Esta ruptura de expectativa obliga al usuario a invertir esfuerzo cognitivo adicional para reorientarse y aumenta la probabilidad de abandono en los primeros segundos.
 
**2. Sobrecarga de acciones sin jerarquía (severidad: alta)**
 
En la sección de mercados, cada localización presenta 4 botones simultáneos en 3 colores distintos: "Localización" (verde), "Grupo de Telegram" (azul), "Haz un pedido" (azul oscuro) y "Grupo de WhatsApp" (verde). Esto viola **H8** (*diseño estético y minimalista*): se expone al usuario a todas las opciones posibles sin priorizar, cuando la tarea más frecuente requiere un único CTA claro. La multiplicidad de canales sin jerarquía genera **sobrecarga de elección** (Schwartz, 2004), aumentando el tiempo de decisión y la fricción en lugar de reducirlos.
 
**3. Layout no adaptado a móvil (severidad: crítica)**
 
La sección de descripción usa un layout de dos columnas (título a la izquierda, texto a la derecha) que rompe completamente en móvil: las columnas se comprimen sin reflow adecuado y los 4 botones por mercado se apilan en vertical, ocupando casi toda la pantalla y obligando a un scroll extenso para llegar al mercado siguiente. Este es el fallo más crítico dado que el contexto de uso más frecuente se produce desde el teléfono.
 
**4. Ausencia de información de próxima celebración (severidad: alta)**
 
En ningún punto de la web aparece de forma visible la fecha de la próxima edición. El usuario que quiere saber "¿hay mercado este sábado?" no puede resolverlo desde la web: debe acceder al grupo de Telegram o WhatsApp. Esto viola **H1 de Nielsen** (*visibilidad del estado del sistema*): el sistema no informa al usuario del dato más relevante para su decisión de asistencia.
 
---
 
#### Valoración global del referente
 
| Criterio | Valoración | Justificación |
|---|---|---|
| Tarea principal resuelta en ≤2 clics | ✗ | La home no orienta al mercado |
| Jerarquía visual clara de acciones | ✗ | 4 CTAs por mercado sin prioridad |
| Adaptación móvil | ✗ | Layout de columnas rompe en pantalla pequeña |
| Info de próxima edición visible | ✗ | No existe en ninguna pantalla |
| Acceso directo al mercado desde menú | ✓ | 1 clic desde cualquier página |
| Reconocimiento visual de productores | ✓ | Foto + nombre + categoría |
 
La web cumple como canal institucional de la ONG pero falla como herramienta orientada al usuario asistente. La arquitectura refleja la estructura organizativa interna, no el modelo mental del visitante que quiere saber cuándo y dónde ir a comprar.
 
---
 
### 2b. Insights y Propuesta de Valor para EcoMercado UGR
 
#### Insights extraídos del análisis
 
**Insight 1 — La tarea más frecuente del usuario no tiene respuesta directa en el referente.** "¿Hay mercado este jueves y qué voy a encontrar?" no se puede resolver desde la web de Xarxa Consum sin navegar por varios niveles y acudir a canales externos (Telegram, WhatsApp). Esta es la oportunidad de diseño principal: una plataforma que resuelva esa pregunta en el primer viewport.
 
**Insight 2 — El componente educativo y comunitario es un diferencial no explotado.** El referente lista productores pero no aprovecha el potencial narrativo de cada uno (historia, territorio, técnicas) ni ofrece contenido educativo. Para el EcoMercado UGR, con la universidad como contexto, esto es el valor diferencial que justifica una presencia digital propia.
 
**Insight 3 — La ausencia de diseño mobile-first es el fallo técnico más grave.** El referente está diseñado para escritorio y se degrada en móvil. El público universitario del EcoMercado accede mayoritariamente desde el teléfono, lo que hace de mobile-first un requisito, no una mejora.
 
**Insight 4 — Menos canales, más claridad.** El referente ofrece 4 canales de contacto por mercado sin jerarquía. La propuesta para el EcoMercado debe priorizar: un CTA de mapa y un CTA de calendario, y nada más en el primer nivel de interacción.
 
---
 
#### Personas
 
**Lucía, 22 años, estudiante de Biología (Campus Fuentenueva)**
Pasa por los Paseíllos a diario pero no siempre sabe cuándo hay mercado. Le interesan los productos locales pero la falta de información clara hace que se entere por casualidad. Dispositivo principal: smartphone. Frustración actual: *"He llegado cuando ya estaban recogiendo"*.
 
**Andrés, 47 años, profesor titular de la ETSII**
Consume productos ecológicos regularmente y valora conocer el origen de lo que come. Reserva el jueves del mercado pero tiene agenda ajustada. Frustración actual: *"No sé qué productores van a ir hasta que llego"*.
 
Ambas personas comparten la misma tarea inicial (¿hay mercado y cuándo?) pero divergen en profundidad de uso: Lucía necesita consulta rápida; Andrés necesita exploración previa.
 
---
 
#### Propuesta de diseño: PWA EcoMercado UGR
 
**Justificación del formato:** dado el perfil de usuario (universitario, smartphone como dispositivo principal, consulta en movilidad), se propone una **Progressive Web App (PWA)**: accesible sin descarga pero con experiencia nativa (notificaciones push, añadir a pantalla de inicio). Este enfoque aplica el principio de **diseño orientado al contexto de uso**.
 
**Principios aplicados y justificación:**
 
- **Mobile-first:** la pantalla principal responde "¿hay mercado este jueves?" sin scroll. Fecha, horario y ubicación visibles en el primer viewport. La tarea de mayor frecuencia ocupa el nivel 0 de la interfaz.
- **Progressive disclosure** (Johnson, 2010): se muestra primero lo esencial; el usuario que quiere profundizar navega voluntariamente. Resuelve directamente la sobrecarga de información del referente.
- **H4 Nielsen — Consistencia y estándares:** bottom navigation bar fija con 4 secciones. Se descarta el menú hamburguesa porque oculta las opciones y aumenta la carga cognitiva.
- **H1 Nielsen — Visibilidad del estado:** indicador claro de si hay mercado este mes, resolviendo la frustración más frecuente de las personas definidas.
- **Accesibilidad desde el diseño:** contraste ≥ 4.5:1 (WCAG AA, criterio 1.4.3), botones con área táctil mínima 44×44px (criterio 2.5.5), etiquetas accesibles en todos los elementos interactivos (criterio 1.1.1).
**Arquitectura de información:**
 
```
EcoMercado UGR (PWA)
├── Inicio
│   ├── Tarjeta hero: próxima edición (fecha, hora, lugar, mapa, +calendario)
│   ├── Productores del mes por categoría
│   └── Contenido destacado: receta o charla del mes
├── Productores
│   ├── Listado del mes con foto y categorías
│   └── Ficha individual (historia, técnicas, productos, contacto)
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
 
El labelling sigue el principio de economía de lenguaje: "Productores" en lugar de "Nuestros productores agroecológicos participantes"; "Aprende" en lugar de "Contenido educativo y divulgativo". Las etiquetas cortas reducen la carga cognitiva y son más escaneables en móvil.
 
---
 
#### Boceto wireframe — Pantalla principal (mobile, 390px)
 
```
┌────────────────────────────┐
│  🌿 EcoMercado UGR    🔔   │  ← header fijo
├────────────────────────────┤
│  ┌──────────────────────┐  │
│  │ PRÓXIMA EDICIÓN      │  │  ← primer viewport, sin scroll
│  │ Jueves 26 junio      │  │
│  │ 9:30 – 14:00 h       │  │
│  │ Paseíllos Fuentenueva │  │
│  │ [📍 Ver mapa][+🗓 Cal]│  │  ← 2 CTAs, verde primario
│  └──────────────────────┘  │
│                            │
│  PRODUCTORES DEL MES       │
│  ┌────┐ ┌────┐ ┌────┐     │
│  │ 🥬 │ │ 🧀 │ │ 🍯 │     │
│  │Huer│ │Ques│ │Miel│     │
│  └────┘ └────┘ └────┘     │
│  Ver todos →               │
│                            │
│  ┌──────────────────────┐  │
│  │ 📚 APRENDE           │  │
│  │ Gazpacho con tomate  │  │
│  │ de la Vega granadina │  │
│  └──────────────────────┘  │
├────────────────────────────┤
│ [🏠][👩‍🌾][🗓][📖]          │  ← bottom nav fija
└────────────────────────────┘
```
 
La **tarjeta hero** ocupa el primer viewport completo y responde directamente la pregunta más frecuente (Insight 1). Los dos únicos CTAs tienen función clara y diferenciada, solucionando el problema de sobrecarga del referente (Insight 4). La sección de productores por categoría reduce la incertidumbre antes de ir (Insight 2). La sección "Aprende" crea contacto continuo entre ediciones, transformando el EcoMercado de evento puntual en comunidad digital activa.
 
---
 
#### Comparativa propuesta vs. referente
 
| Dimensión | Mercat Pages (referente) | EcoMercado UGR (propuesta) |
|---|---|---|
| Tarea principal resuelta en ≤2 clics | ✗ | ✓ |
| Mobile-first | ✗ | ✓ |
| Info de próxima edición visible | ✗ | ✓ |
| Jerarquía clara de acciones | ✗ | ✓ (2 CTAs max por pantalla) |
| Info detallada de productores | Básica | Sí + historia |
| Componente educativo/comunidad | No | Sí |
| Accesibilidad WCAG AA por diseño | No evaluada | Sí, desde el sistema de colores |
| Presencia digital propia | No (embebida en ONG) | Sí |
 
---
 
### 2c. Reflexión y autoevaluación
 
#### Lo que he aplicado en prácticas con transferencia directa
 
**Investigación de usuario (P1):** el User Research Plan, la creación de personas con escenarios y métricas concretas y la Usability Review son directamente transferibles. En este caso añadiría observación etnográfica en el propio mercado para validar hipótesis de comportamiento, y entrevistas con productores como stakeholders clave.
 
**Arquitectura de información (P2):** sitemap y labelling tienen aplicación directa. La diferencia es que en el EcoMercado el eje estructural es el **calendario y los eventos**, no el catálogo de productos, lo que requiere una IA orientada al tiempo más que al inventario.
 
**Prototipado en Figma (P3):** el proceso moodboard → design system → wireframes → prototipo navegable es completamente transferible. El reto adicional sería diseñar las fichas de productor considerando que el contenido lo generarían múltiples actores con distintos niveles de habilidad digital.
 
**Evaluación con usuarios (P5):** SUS, A/B testing, eye tracking y WAVE/Lighthouse son directamente aplicables. La auditoría de accesibilidad es especialmente relevante en un contexto universitario con público diverso.
 
#### Lo que me ha faltado y habría aportado valor
 
**Card sorting:** el sitemap se construyó de forma top-down en las prácticas. Para el EcoMercado habría sido valioso validar con usuarios reales que las categorías propuestas ("Productores", "Aprende", "Calendario") corresponden a sus modelos mentales, o si agruparían la información de otra manera.
 
**Etnografía en contexto de uso:** observar cómo se comportan los asistentes al mercado con el móvil en mano habría convertido varias hipótesis de diseño en decisiones basadas en evidencia real.
 
**Test de accesibilidad con usuarios reales:** WAVE y Lighthouse detectan fallos técnicos, pero un test con usuarios con discapacidad visual o motriz aportaría información cualitativa imposible de captar automáticamente.
 
**Diseño de contenido (Content Design):** la voz, el tono y la longitud de los textos tienen especial importancia en un proyecto con dimensión educativa y comunitaria. Es un área poco trabajada en las prácticas que en un proyecto real requeriría criterios explícitos de redacción UX.
 
#### Conclusión
 
Este caso ha confirmado que el proceso UX aprendido durante el curso es transferible a contextos muy distintos del proyecto de prácticas. Los problemas identificados en el referente —disonancia de contexto, ausencia de jerarquía visual, falta de diseño mobile-first, invisibilidad de la próxima edición— son exactamente los que el proceso de investigación, ideación y prototipado del curso permite detectar y resolver de forma argumentada. La diferencia entre una propuesta de experto y una opinión personal reside en la capacidad de justificar cada decisión con criterios cuantificables y referencias metodológicas. Eso es lo que este proceso enseña.
 
---
 
## Referencias
 
- Nielsen, J. (1994). *10 Usability Heuristics for User Interface Design*. Nielsen Norman Group.
- Norman, D. (2013). *The Design of Everyday Things* (Revised Edition). Basic Books.
- Rohrer, C. (2014). *When to Use Which User-Experience Research Methods*. Nielsen Norman Group.
- Brooke, J. (1996). *SUS: A 'Quick and Dirty' Usability Scale*. Usability Evaluation In Industry.
- W3C (2018). *Web Content Accessibility Guidelines (WCAG) 2.1*. W3C Recommendation.
- Schwartz, B. (2004). *The Paradox of Choice*. Harper Perennial.
- Cooper, A., Reimann, R., & Cronin, D. (2007). *About Face 3: The Essentials of Interaction Design*. Wiley.
- Johnson, J. (2010). *Designing with the Mind in Mind*. Morgan Kaufmann.
- EcoMercado UGR: [improntagranada.es](https://improntagranada.es/evento/jornada-inaugural-del-ecomercado-ugr/)
- Xarxa de Consum Solidari: [xarxaconsum.org](https://xarxaconsum.org/es/mercados-de-campesinos/)
---
 
*Trabajo elaborado para la asignatura Diseño de Interfaces de Usuario — ETSI Informática y Telecomunicaciones, Universidad de Granada. Curso 2025/26.*
  2025/26.*
