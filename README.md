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

El **EcoMercado UGR** es una iniciativa de la Universidad de Granada y la Red Agroecológica de Granada, celebrada mensualmente (el cuarto jueves de cada mes) en los Paseíllos del Campus de Fuentenueva. Se enmarca en el proyecto europeo **SOILCRATES** (Living Lab Granada Tierra Viva) y reúne a pequeños productores locales con principios agroecológicos. No es solo un punto de venta: es un **espacio de aprendizaje e intercambio** con especial vinculación a la comunidad universitaria, lo que tiene implicaciones directas en el diseño de su presencia digital.

---

### 2a. Análisis de referentes

#### Referente 1: Mercat de Pages — Xarxa de Consum Solidari

**Perfil de usuario hipotético:** consumidor adulto (30-55 años), conciencia ecológica, usuario ocasional de plataformas web, busca información práctica sobre cuándo y dónde se celebra el mercado.

**Puntos fuertes:**

La sección "Mercados de Campesinos" está accesible desde el menú principal en un solo clic, cumpliendo la heurística H3 de Nielsen (*control y libertad del usuario*) y reduciendo la carga cognitiva de localización. La web ofrece información bilingüe con iconos de bandera, respondiendo bien al principio de **internacionalización**.

**Puntos débiles:**

El principal problema es la **disonancia de contexto**: la sección de mercados forma parte de una web institucional de una ONG de comercio justo. El usuario que llega buscando fecha, lugar y productores encuentra una arquitectura diseñada para presentar la organización, no para facilitar la asistencia al mercado. Aplicando el **modelo mental** del usuario (Norman, 2013), el visitante espera un patrón de "página de evento" (fecha destacada, mapa, lista de productores, fotos) que esta web no satisface.

La **densidad de texto** sin imágenes de producto genera una experiencia informativa pero poco motivadora para asistir. Tampoco hay **adaptación responsiva optimizada** para móvil, crítico dado que el usuario suele consultar información el mismo día del mercado desde el teléfono.

**Valoración:** funcionalmente correcta para comunicación institucional, con importantes carencias como herramienta de captación de asistentes. La estructura de navegación no está orientada a las tareas principales del usuario visitante.

---

#### Referente 2: Nuestras Huertas (nuestrashuertas.com)

**Perfil de usuario hipotético:** consumidor urbano (25-45 años), alta frecuencia de uso de e-commerce, interesado en productos ecológicos de proximidad.

**Puntos fuertes:**

La **propuesta de valor es clara y visible** desde el primer scroll: productos ecológicos, de temporada, de agricultores locales. La integración de **e-commerce con contexto de mercado físico** es una fortaleza diferenciadora: el usuario puede comprar online y también localizar mercados, satisfaciendo distintos momentos del journey del consumidor ecológico.

**Puntos débiles:**

Incurre en **sobrecarga de información** en algunas secciones: demasiadas opciones visibles simultáneamente sin jerarquía visual clara, dificultando el escaneo rápido (viola H8 de Nielsen: *diseño estético y minimalista*). La **adaptación a móvil**, aunque presente, no está optimizada para el contexto de consulta rápida en desplazamiento.

---

### 2b. Insights y Propuesta de Valor para EcoMercado UGR

#### Insights extraídos del análisis

**Insight 1 — El usuario llega con objetivos muy concretos:** los asistentes habituales del EcoMercado (estudiantes, personal universitario, vecinos del entorno) buscan información específica: ¿hay mercado este mes? ¿qué productores van? ¿a qué hora? La plataforma debe responder a esas tareas en el menor número de pasos posible.

**Insight 2 — La comunidad universitaria es la ventaja diferencial:** a diferencia de otros mercados ecológicos urbanos, el EcoMercado UGR tiene acceso a una comunidad joven, tecnológicamente activa y con valores de sostenibilidad, lo que abre la posibilidad de diseñar una experiencia más participativa.

**Insight 3 — La ausencia de presencia digital específica es el problema central:** el EcoMercado carece de web o app propia. La información se distribuye fragmentada entre páginas institucionales (Impronta Granada, Medialab UGR, Canal UGR), generando fricción en el journey del usuario.

**Insight 4 — El componente educativo y social necesita espacio digital:** la dimensión de living lab (charlas, origen de los alimentos, productores con historia) no se comunica digitalmente de forma efectiva en ninguno de los canales actuales.

---

#### Personas para el EcoMercado UGR

**Lucía, 22 años, estudiante de Biología.** Vive cerca del campus de Fuentenueva. Le interesan los productos locales pero no siempre recuerda cuándo es el mercado ni qué productores asisten. Usa el smartphone como principal canal de información. Necesita: recordatorio de fecha, lista de productores del mes, horario, cómo llegar.

**Andrés, 45 años, profesor asociado de la ETSII.** Consume productos ecológicos habitualmente y le gusta conocer el origen de lo que come. Reserva los jueves del mercado en su agenda pero tiene poco tiempo entre semana. Necesita: información detallada de productores, contenido sobre prácticas agroecológicas, posibilidad de anticipar qué encontrará antes de ir.

---

#### Propuesta de diseño: Web App EcoMercado UGR (Mobile-first)

**Público objetivo principal:** estudiantes y personal de la UGR (18-45 años), alta penetración de smartphone, valores de sostenibilidad, patrón de uso principalmente móvil.

**Propuesta de valor:** una plataforma que convierte el EcoMercado UGR en una experiencia continua, no solo un evento mensual.

**Arquitectura de información propuesta:**

```
EcoMercado UGR
├── Inicio          → Próxima edición + CTA asistir
├── El Mercado      → Fechas, mapa Campus Fuentenueva, categorías de producto
├── Productores     → Listado del mes + ficha individual (historia, productos)
├── Calendario      → Ediciones anteriores y próximas
├── Aprende         → Recetas de temporada, agroecología, charlas
└── Sobre el proyecto → Red Agroecológica / Granada Tierra Viva / SOILCRATES
```

**Principios de diseño aplicados:**

- **Mobile-first:** dado el perfil de usuario, el diseño se concibe para móvil. Fecha, horario y ubicación deben ser visibles sin scroll en la pantalla principal.
- **Progressive disclosure:** la pantalla principal muestra solo lo esencial (cuándo, dónde, qué hay). El usuario que quiera profundizar navega a secciones específicas, reduciendo la sobrecarga cognitiva detectada en los referentes.
- **Affordance y feedback visual:** botones de acción principal en verde (coherente con los valores de ecología), con contraste que cumple WCAG AA (ratio ≥ 4.5:1).
- **Consistencia y estándares:** bottom navigation bar con 4-5 secciones (no menú hamburguesa oculto) para reducir la curva de aprendizaje en usuarios nuevos.

---

#### Boceto de wireframe — Pantalla principal (mobile)

```
┌──────────────────────────────┐
│  🌿 EcoMercado UGR           │
│                              │
│  ┌──────────────────────┐    │
│  │  PRÓXIMA EDICIÓN     │    │
│  │  Jueves 26 junio     │    │
│  │  9:30 – 14:00 h      │    │
│  │  Paseíllos Fuentenueva│   │
│  │  [Ver en mapa] [+Cal] │    │
│  └──────────────────────┘    │
│                              │
│  PRODUCTORES DEL MES (15)    │
│  ┌──────┐ ┌──────┐ ┌──────┐ │
│  │  🥬  │ │  🧀  │ │  🍯  │ │
│  │Huertas│ │Quesos│ │ Miel │ │
│  └──────┘ └──────┘ └──────┘ │
│  [Ver todos los productores →]│
│                              │
│  ¿QUÉ HAY ESTA SEMANA?       │
│  Verduras temporada · Pan    │
│  artesano · Cosmética eco…   │
│                              │
│  ┌──────────────────────┐    │
│  │  📚 APRENDE          │    │
│  │  Receta: Gazpacho    │    │
│  │  con tomate de la Vega│   │
│  └──────────────────────┘    │
│                              │
│ [Inicio][Productores][Cal][+] │
└──────────────────────────────┘
```

La **tarjeta hero** muestra los datos esenciales de la próxima edición con dos CTAs claros (mapa y calendario), resolviendo directamente la tarea más frecuente del usuario. La sección de productores del mes permite anticipar qué encontrará antes de asistir, aumentando la motivación. La sección "Aprende" convierte la plataforma en un punto de contacto continuo, no solo informativo. La **bottom nav** sigue el patrón estándar de apps móviles para minimizar la curva de aprendizaje.

---

**Propuesta de valor vs. referentes:**

| Dimensión | Mercat Pages | Nuestras Huertas | EcoMercado UGR (propuesta) |
|---|---|---|---|
| Orientación al usuario asistente | Baja | Media | Alta |
| Mobile-first | No | Parcial | Sí |
| Info detallada de productores | Básica | Media | Sí + historia |
| Componente educativo | No | No | Sí (recetas, charlas) |
| Integración calendario | No | No | Sí (Google/Apple Cal) |
| Accesibilidad WCAG AA | No evaluada | No evaluada | Diseñada desde el inicio |

---

### 2c. Reflexión y autoevaluación

#### Lo que he aplicado en prácticas y su relación con este caso

Las prácticas del curso han cubierto la mayoría de fases que este caso requeriría:

- **Investigación de usuario (P1):** desk research, análisis competitivo, personas y usability review son directamente transferibles. Para el EcoMercado añadiría observación etnográfica en el propio mercado (comportamientos reales de asistentes) y entrevistas con productores como stakeholders clave.
- **Arquitectura de información (P2):** sitemap y labelling directamente aplicables. La diferencia aquí sería la mayor importancia del **calendario y los eventos** frente al e-commerce.
- **Prototipado (P3):** el flujo en Figma demostró que puedo trasladar wireframes a prototipos navegables con coherencia visual. El reto adicional aquí sería diseñar fichas de productor con contenido generado por múltiples actores.
- **Evaluación (P5):** SUS, A/B testing, Eye Tracking y WAVE/Lighthouse son directamente aplicables. La auditoría de accesibilidad es especialmente relevante para un proyecto universitario con público diverso.

#### Lo que me ha faltado y habría sido valioso aplicar

**Card sorting para la IA:** en las prácticas el sitemap fue más top-down. Para el EcoMercado habría sido valioso validar con usuarios reales que las categorías propuestas corresponden a sus modelos mentales.

**Investigación etnográfica en contexto de uso:** observar cómo usan el móvil los asistentes durante el mercado (¿buscan info de un productor? ¿comparten en redes?) habría informado decisiones de diseño que ahora son hipótesis.

**Test de accesibilidad con usuarios reales:** WAVE y Lighthouse detectan fallos técnicos, pero un test con usuarios con discapacidad visual o motriz aportaría información cualitativa imposible de captar automáticamente.

**Diseño de contenido (Content Design):** la voz, el tono y la longitud de los textos tienen mucho peso en un proyecto con dimensión educativa y comunitaria como el EcoMercado, y es un aspecto poco trabajado en las prácticas.

#### Conclusión

Este caso me ha permitido verificar que el proceso UX aprendido durante el curso es transferible a contextos muy distintos del caso de práctica. El EcoMercado UGR plantea retos específicos —audiencia universitaria, propuesta que combina mercado físico con comunidad digital, múltiples stakeholders— que habrían enriquecido aún más el proceso de investigación y diseño. La principal conclusión es que no hay atajos: el rigor metodológico en la fase de investigación es lo que determina la calidad de las decisiones de diseño posteriores.

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
