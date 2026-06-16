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
El **EcoMercado UGR** es una iniciativa de la Universidad de Granada y la Red Agroecológica de Granada, celebrada mensualmente los jueves en los Paseíllos Universitarios del Campus de Fuentenueva (9:30–14:00 h). Está dentro  del proyecto **Granada Tierra Viva** (Impronta Granada) y reúne a productores locales de proximidad agroecológica. Más allá de un mercado, es un espacio de aprendizaje, intercambio y conexión entre sostenibilidad, territorio y comunidad universitaria.

El **problema central** es que el EcoMercado carece de una página web propia. La información se encuentra en distinta páginas que no están diseñadas específicamente para ese propósito, sino para otros lo que hace que ofrece una experiencia mala a aquellas personas que si quieran visitar el EcoMercado.
 
### 2a. Análisis del referente: Mercat de Pages — Xarxa de Consum Solidari (xarxaconsum.org)
**Justificación de la elección:** Hemos escogido esta página porque creo que es la que nos va a permitir comparar mejor con el Ecomercado UGR. He descartado Nuestras Huertas porque su propuesta está maś destinada a la venta online de productos, y quizás se aleja más de nuestra página y no aporta nada importante a nuestro mercado.

Voy a realizar el análisis intentando ser lo más técnico posible, aplicando las **heurísticas de Nielsen** y el marco de **diseño centrado en usuario** como referencia objetiva.
 
#### ¿Quién es el usuario y qué necesita?

El perfil principal es un consumidor adulto (30-55 años) al que le interesa la ecológia, este accederá para encontrar información relevante, saber cuando es el mercado, donde está situado, que productos se ofrecerán....
Seguramente esta consulta la haga desde un móvil, consultandolo un dia antes o incluso en el mismo día par aasegurarse de la hora por ejemplo. Las tareas críticas serán:
    - Encontrar el mercado más cercano
    - Conocer el horario
    - Saber que productos se va a encontrar
Nuestra web no está pensada para nada de eso, lo que implica un grave problema
 
#### Puntos fuertes
La sección "Mercados de campesinos" está accesible desde el menú principal de forma directa, cumpliendo **H3 de Nielsen** (*control y libertad del usuario*) y minimizando la profundidad de navegación para la tarea principal,ya que solo es necesario un clic.
 
#### Problemas de usabilidad y UX detectados
 
**1. Disonancia de contexto en la página principal (severidad: alta)**
La pantalla de inicio muestra un carrusel con fotografías de cooperación internacional y su texto correspondiente, esto puede hacer pensar al usuario que llega a la página que no está en el sitio correcto, puede desorientarlo. Aplicando el concepto de **modelo mental** de Norman (2013), el visitante espera el patrón "mercado ecológico" (productos frescos, fecha próxima, mapa) y encuentra el patrón "ONG de cooperación internacional". Este problema obliga al usuario a tener que invertir tiempo y esfuerzo en encontrar la seccion de "mercado de campesions" para poder encontrar lo que busca, lo que aumenta la probabilidad de abandono en los primeros segundos.

**2. Sobrecarga de acciones sin jerarquía (severidad: alta)**
En la sección de mercados, cada localización presenta 4 botones simultáneos en 3 colores distintos: "Localización" (verde), "Grupo de Telegram" (azul), "Haz un pedido" (azul) y "Grupo de WhatsApp" (verde). Esto viola **H8** (*diseño estético y minimalista*): se expone al usuario a todas las opciones posibles sin priorizar la tareas más común, sobrecargando la página y aumentando el tiempo de decisión.

**3. Layout no adaptado a móvil (severidad: crítica)**
En la sección de "Mercados de campesinos" las columnas se comprimen sin reflow adecuado y los 4 botones de cada mercado se apilan en vertical, ocupando casi toda la pantalla y obligando al usuario a hacer un scroll extenso para llegar al mercado siguiente. Este es el fallo más crítico dado que el contexto de uso más frecuente se produce desde el teléfono.
 
#### Valoración global del referente
| Criterio | Valoración | Justificación |
|---|---|---|
| Tarea principal resuelta en ≤2 clics | ✓ |A pesar de que la págna principal desoriente,con un clic se llega al sitio deseado |
| Jerarquía visual clara de acciones | ✗ | Demasiadas interaciones por mercado sin orden prioridad |
| Adaptación móvil | ✗ | Layout de columnas se rompe en pantalla pequeña obligando a hacer scroll |
| Info de próxima edición visible | ✓ | En cada mercado pone la ubicación y el horario |
| Reconocimiento visual de productores | ✓ | Foto + nombre + categoría |
 
La web cumple como canal institucional de la ONG pero falla como herramienta orientada al usuario asistente. La arquitectura refleja la estructura organizativa interna, no el modelo mental del visitante que quiere saber cuándo y dónde ir a comprar.
  
### 2b. Insights y Propuesta de Valor para EcoMercado UGR
#### Insights extraídos del análisis

**Insight 1** — Tenemos que aprovechar la parte educativa y de comunidad, porque va a ser nuestro gran diferencial. En la web que estamos usando de referencia solo viene una lista sosa de los productores, pero no se cuenta su historia, de dónde vienen o cómo trabajan. Como el EcoMercado va a ser de la UGR, el contexto universitario es nuestro punto fuerte. En nuestra futura web tenemos que meter todo este contenido para educar al usuario; esto es lo que de verdad nos va a diferenciar del resto y lo que justifica que creemos una página propia.

**Insight 2** — Diseñar pensando primero en el ordenador sería el peor error técnico. La web de referencia está hecha para pantallas grandes y en el móvil se ve fatal. Como nuestro público va a ser mayoritariamente universitario y van a entrar a la web desde el teléfono mientras están en el campus, hacer un diseño mobile-first (pensado primero para el móvil) no es un extra que molaría tener, es algo obligatorio desde el primer día.

**Insight 3 — Menos canales, más claridad.** El referente ofrece 4 canales de contacto por mercado sin jerarquía. La propuesta para el EcoMercado debe priorizar: un CTA de mapa y un CTA de calendario, y nada más en el primer nivel de interacción.
 
#### Personas
**Lucía, 22 años, estudiante de Biología (Campus Fuentenueva)**
Pasa por los Paseíllos a diario pero no siempre sabe cuándo hay mercado. Le interesan los productos locales pero la falta de información clara hace que se entere por casualidad. Dispositivo principal: móvil. Frustración actual: *"He llegado cuando ya estaban recogiendo"*.
 
**Andrés, 47 años, profesor titular de la ETSIIT**
Consume productos ecológicos regularmente y valora conocer el origen de lo que come. Reserva el jueves del mercado pero tiene agenda ajustada. Frustración actual: *"No sé qué productores van a ir hasta que llego"*.
 
Ambas personas comparten la misma tarea inicial (¿hay mercado y cuándo?) pero divergen en profundidad de uso: Lucía necesita consulta rápida; Andrés necesita explorar los productos que encontrará.

---
#### Propuesta de diseño: EcoMercado UGR
 
**Justificación del formato:** dado el perfil de usuario (universitario, móvil como dispositivo principal, consulta en movilidad), se propone una web accesible sin necesidad de descargar nada. Este enfoque aplica el principio de **diseño orientado al contexto de uso**.
 
**Principios aplicados y justificación:**
- **Mobile-first**: la pantalla principal responde "¿hay mercado este jueves?" sin scroll. La tarjeta hero muestra fecha, horario y ubicación en el primer viewport, con dos botones de acción claros: "Ver mapa" (outlined) y "+ Calendario" (filled verde). La tarea de mayor frecuencia ocupa el nivel 0 de la interfaz.
- **Progressive disclosure**: la home muestra solo lo esencial. Las categorías de productores (Huerta, Quesos, Miel) permiten anticipar qué hay sin entrar en detalle; el usuario que quiere profundizar navega a la pantalla de Productores, donde cada uno tiene foto, categoría etiquetada y descripción breve. Resuelve directamente la sobrecarga de información detectada en el referente.
- **H4 Nielsen — Consistencia y estándares**: bottom navigation bar fija con 4 secciones (Inicio, Productores, Calendario, Aprende), consistente en todas las pantallas con la pestaña activa destacada en verde. 
- **H1 Nielsen — Visibilidad del estado**: la etiqueta "PRÓXIMA EDICIÓN" en verde y la fecha en grande resuelven de un vistazo la frustración más frecuente identificada en las personas: no saber si hay mercado ese día. El calendario marca el jueves 26 en verde para reforzar esa misma información desde otra pantalla.
- **Accesibilidad desde el diseño**: fondo oscuro con texto blanco y acento verde ), combinación que garantiza contraste ≥ 4.5:1 (WCAG AA, criterio 1.4.3). Los botones tienen tamaño suficiente para cumplir el área táctil mínima de 44×44px (criterio 2.5.5). Las etiquetas de categoría (Verduras, Lácteos, Apicultura, Panadería) añaden contexto textual a cada productor, cumpliendo el criterio 1.1.1.
- **Arquitectura de información**:
```
EcoMercado UGR (PWA)
├── Inicio
│   ├── Tarjeta hero: próxima edición (fecha, hora, lugar, mapa, +calendario)
│   ├── Productores del mes por categoría (Huerta, Quesos, Miel)
│   └── Contenido destacado: receta del mes
├── Productores
│   ├── Listado del mes con avatar, nombre, categoría y descripción breve
│   │   (Huerta La Vega, Quesos Sierra Nevada, Miel del Poniente, Pan Artesano Granada)
│   └── Ficha individual (historia, técnicas, productos, contacto)
├── Calendario
│   ├── Vista mensual con ediciones destacadas en verde
│   └── Tarjetas de próximas ediciones con fecha y ubicación
├── Aprende
│   ├── Recetas de temporada
│   ├── ¿Qué es la agroecología?
│   ├── Charlas y talleres
│   └── Newsletter: suscripción a novedades del mercado
└── Sobre el proyecto
    └── Red Agroecológica / Granada Tierra Viva / Impronta UGR
```
El labelling sigue el principio de economía de lenguaje: "Productores" en lugar de "Nuestros productores agroecológicos participantes"; "Aprende" en lugar de "Contenido educativo y divulgativo". Las etiquetas cortas son más escaneables en móvil y reducen la carga cognitiva en la barra de navegación.

---
#### Mockup — Pantallas (mobile, 390px)
Enlace a figma: https://fence-pop-58809035.figma.site

 <img width="568" height="1124" alt="image" src="https://github.com/user-attachments/assets/c02eb154-fcda-4ef1-ac7c-2985aace6547" />
 <img width="568" height="1124" alt="image" src="https://github.com/user-attachments/assets/c4b412f8-8918-40d6-a7d8-359ddb22eae3" />
<img width="568" height="1124" alt="image" src="https://github.com/user-attachments/assets/e96b0d62-8af9-42f1-972a-506ac7f7a60d" />
<img width="568" height="1124" alt="image" src="https://github.com/user-attachments/assets/0f924f59-1032-4deb-88bb-197d192727b4" />

El diseño resultante consta de cuatro pantallas que cubren el flujo completo de uso de la aplicación.
- La pantalla de Inicio resuelve en el primer viewport la tarea más frecuente del usuario: saber si hay mercado y cuándo. La tarjeta hero muestra fecha, horario y ubicación con dos CTAs diferenciados ("Ver mapa" para navegación física y "+ Calendario" para planificación). Bajo el hero, las categorías de productores (Huerta, Quesos, Miel) permiten anticipar el contenido del mercado antes de ir, aumentando la motivación de asistencia. La sección "Aprende" cierra la pantalla con una receta de temporada, creando un punto de contacto continuo entre ediciones.
- La pantalla de Productores lista los participantes del mes con avatar, nombre, etiqueta de categoría (Verduras, Lácteos, Apicultura, Panadería) y una línea de descripción. Esta estructura aplica H6 de Nielsen (reconocimiento antes que recuerdo): el usuario identifica visualmente si hay un productor de su interés sin necesidad de leer texto en detalle, resolviendo directamente la frustración de Andrés ("no sé qué productores van a ir hasta que llego").
- La pantalla de Calendario presenta una vista mensual con el jueves 26 destacado en verde, reforzando visualmente el estado del sistema (H1 Nielsen). Las tarjetas de próximas ediciones bajo el calendario ofrecen la misma información en formato lista para usuarios que prefieren ese patrón de lectura.
- La pantalla de Aprende agrupa el contenido educativo en tres tarjetas (Recetas de temporada, ¿Qué es la agroecología?, Charlas y talleres) más un bloque de newsletter. Esta sección transforma el EcoMercado de evento puntual en comunidad digital activa, diferenciándolo del referente analizado que no ofrece ningún contenido de valor entre ediciones.
---
#### Comparativa propuesta vs. referente
| Dimensión | Mercado de campesinos (referente) | EcoMercado UGR (propuesta) |
|---|---|---|
| Tarea principal resuelta en ≤2 clics | ✗ | ✓ |
| Mobile-first | ✗ | ✓ |
| Info de próxima edición visible | ✓ | ✓ |
| Jerarquía clara de acciones | ✗ | ✓ (2 CTAs max por pantalla) |
| Info detallada de productores | Básica | Sí + historia |
| Componente educativo/comunidad | No | Sí |
| Accesibilidad WCAG AA por diseño | No evaluada | Sí, desde el sistema de colores |
| Presencia digital propia | No (embebida en ONG) | Sí |

### 2c. Reflexión y autoevaluación
#### Lo que he aplicado en prácticas y tiene relación con este caso
Mirando el trabajo que hice durante el curso, hay varias cosas que se podrían aplicar directamente a este caso de estudio.
Lo más evidente es todo lo de investigación con respecto al usuario de P1: el User Research Plan, las personas y la Usability Review. De hecho, el análisis que he hecho del referente (Xarxa Consum) sigue exactamente la misma lógica que la Usability Review de Goiko: identificar problemas, asignarles severidad y justificarlos con heurísticas de Nielsen. La diferencia es que en el EcoMercado el usuario tiene un perfil muy concreto (estudiante universitario que pasa por el campus) y eso habría condicionado mucho las personas desde el principio.

La arquitectura de información de P2 también es directamente transferible: el sitemap y el labelling que propongo para el EcoMercado siguen exactamente el mismo proceso que hice para Goiko. La diferencia principal es que aquí el eje central es el calendario y los eventos, no un catálogo de productos, lo que cambia bastante cómo se organiza la información.

El prototipado de P3, el proceso de moodboard → design system → wireframes → prototipo en Figma lo he recorrido completo en las prácticas, y el resultado del EcoMercado que presento aquí lo demuestra, ya que me ha permitido hacerlo bastante a mi gusto con figma make y con los requisitos que he querido y he considerado oportunos. Eso sí, en Goiko el contenido lo generaba una sola marca, y en el EcoMercado cada productor aportaría su propia información, pero eso no está implementado

- Por último, las técnicas de evaluación de P5 (SUS, A/B testing, eye tracking, WAVE) serían directamente aplicables para validar el diseño propuesto con usuarios reales antes de lanzarlo.

#### Lo que me ha faltado y hubiera mejorado este caso
Hay tres cosas concretas que, viéndolo ahora, me habría gustado aplicar aquí..
La primera es el card sorting. El sitemap que propongo lo he construido de arriba a abajo, igual que hice en P2: yo decido las categorías y las organizo según mi criterio. Pero no sé si un estudiante de la UGR que nunca ha ido al EcoMercado organizaría la información de la misma manera. Quizás "Aprende" no le dice nada como etiqueta, o quizás esperaría encontrar las recetas dentro de "Productores". Un card sorting con cinco usuarios habría resuelto esa duda antes de diseñar nada.
La segunda es la etnografía en contexto real. En el ejercicio de clase observé comportamientos en un entorno digital, pero aquí lo valioso hubiera sido ir al propio mercado y observar cómo se comporta la gente con el móvil mientras está allí: ¿consultan información de algún productor? ¿llegan con algo abierto en el teléfono? ¿comparten en Instagram? Esas respuestas habrían convertido algunas de las decisiones de diseño que ahora son hipótesis en decisiones basadas en evidencia real.
La tercera es el diseño de contenido. En las prácticas diseñé interfaces, pero el texto que va dentro de esas interfaces lo tratamos como algo secundario. En el EcoMercado, donde hay una dimensión educativa y comunitaria importante, la voz, el tono y la longitud de los textos creo que son tan importantes como el diseño visual. Es algo que en un proyecto real requeriría criterios explícitos desde el principio.

#### Conclusión
Este ejercicio me ha servido para ver con perspectiva todo lo que he aprendido durante el curso. Los problemas que he detectado en la página que tome como referente, la disonancia de contexto en la página principal, la falta de adaptación a móvil, etc, son exactamente el tipo de problemas que el proceso UX del curso nos ha enseñado a indentificar y resolver. La diferencia entre señalar que "la web es mala" y argumentar que "viola H1 de Nielsen porque no informa al usuario del estado más relevante para su decisión de asistencia" es, la diferencia entre una opinión y un análisis.

