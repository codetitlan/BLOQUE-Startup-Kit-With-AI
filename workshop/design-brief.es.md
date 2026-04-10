# Design Brief: deck HTML para taller de pitch deck con agentes de IA

## Objetivo
Este documento define la dirección visual para convertir el taller en una presentación HTML. El objetivo no es solo que “se vea bien”, sino que sea:

- fácil de presentar en vivo
- legible a distancia
- simple de convertir en una landing o slide deck web
- consistente con un tono profesional, actual y sobrio

La prioridad visual debe ser:

1. claridad
2. jerarquía
3. ritmo
4. consistencia

## Contexto de uso
- audiencia: emprendedores en incubación con perfiles mixtos
- formato: taller de 1 hora
- medio principal: página HTML tipo slide deck
- posible uso secundario: exportación o adaptación a PDF / presentaciones

## Tono visual
- moderno, limpio y profesional
- tecnológico sin verse “demasiado startup cliché”
- didáctico, claro y confiable
- más cercano a un workshop premium que a un pitch comercial

## Principios de diseño
- una idea principal por slide
- poco texto visible; el detalle vive en speaker notes o en el discurso
- contraste alto
- composiciones amplias, con mucho espacio en blanco
- usar visuales funcionales, no decorativos
- si un elemento no mejora comprensión, no debe estar

## Sistema visual recomendado

### Paleta
- fondo principal: azul carbón muy oscuro o gris casi negro
- fondo alterno: blanco cálido o gris muy claro para slides de respiro
- color primario: azul eléctrico moderado
- color secundario: verde menta o aqua para acentos
- color de alerta: ámbar suave para riesgos, vacíos o errores
- texto principal oscuro sobre fondos claros y blanco roto sobre fondos oscuros

### Tipografía
- títulos: sans serif moderna y limpia
- cuerpo: sans serif de alta legibilidad
- pesos recomendados:
  - 700 para títulos
  - 500 o 600 para subtítulos
  - 400 o 500 para bullets

### Estilo de iconografía
- iconos lineales simples
- trazos consistentes
- sin ilustraciones complejas
- evitar íconos demasiado caricaturescos

### Estilo de formas
- tarjetas con esquinas suaves
- líneas divisorias sutiles
- bloques con relleno ligero
- usar glow o sombras solo muy leves

## Layout base para HTML

### Contenedor
- ancho máximo de contenido: amplio, estilo `1200px–1400px`
- altura pensada para `100vh`
- padding generoso en escritorio
- grid principal de 12 columnas o layout flexible equivalente

### Zonas comunes
- encabezado superior opcional para título de sección
- área principal con mensaje dominante
- área secundaria para bullets o visuales
- pie mínimo solo si aporta navegación o progreso

### Comportamiento responsivo
- en escritorio: layouts de 2 columnas cuando haya visual + texto
- en tablet: apilar conservando jerarquía
- en móvil: mantenerlo legible, aunque el foco principal es presentar en desktop o proyector

## Componentes base
- slide title
- slide kicker opcional
- lista corta de bullets
- tarjeta de insight
- tarjeta de ejemplo
- diagrama de flujo
- bloque de advertencia
- bloque de pregunta
- bloque de call to action

## Animación recomendada
- transiciones suaves, de baja distracción
- fade y translate leve
- evitar parallax agresivo
- evitar animaciones por cada bullet si dificultan el ritmo del presentador

## Reglas de consistencia
- máximo una visual dominante por slide
- máximo 4–6 bullets visibles por slide
- no mezclar demasiados estilos de layout
- los íconos deben compartir misma familia visual
- usar el color de acento con intención, no como decoración

## Dirección slide por slide

### Slide 1 — Título
**Objetivo visual**
Presentar el tema con autoridad y claridad.

**Layout**
- composición centrada o split 60/40
- título grande dominante
- subtítulo breve debajo
- detalle pequeño para “taller de 1 hora”

**Visual**
- fondo oscuro con gradiente sutil
- patrón abstracto ligero tipo red, nodos o flujos

**Icono**
- chispa, nodo conectado, o cerebro/diagrama minimalista

**Notas HTML**
- ideal como hero section de apertura
- puede usar animación de entrada suave en título y subtítulo

---

### Slide 2 — Hoy se llevan
**Objetivo visual**
Mostrar valor práctico desde el inicio.

**Layout**
- grid de 2x2 o 4 tarjetas horizontales
- cada tarjeta con una frase corta

**Visual**
- tarjetas limpias con ícono y etiqueta

**Iconos**
- flujo, documento, lupa/crítica, prompt/chat

**Chart / elemento**
- no necesita chart

**Notas HTML**
- usar tarjetas consistentes reutilizables
- buen momento para establecer el componente base de “beneficio”

---

### Slide 3 — La IA no reemplaza el criterio del fundador
**Objetivo visual**
Fijar una postura clara y madura sobre IA.

**Layout**
- composición dual:
  - lado izquierdo: “fundador”
  - lado derecho: “IA”
- al centro, relación o intersección

**Visual**
- diagrama de responsabilidades compartidas

**Iconos**
- persona/fundador
- chip o agente
- check o flechas de colaboración

**Chart / elemento**
- mini diagrama tipo Venn o flujo bilateral

**Notas HTML**
- una comparación visual funciona mejor que una lista larga

---

### Slide 4 — Un deck temprano debe responder
**Objetivo visual**
Convertir preguntas clave en estructura mental simple.

**Layout**
- lista de preguntas en columna
- o 6 bloques distribuidos en grid

**Visual**
- cada pregunta dentro de una tarjeta simple

**Iconos**
- problema, usuario, reloj, gráfico, equipo, objetivo

**Chart / elemento**
- no chart; sí grid de preguntas

**Notas HTML**
- mantener mucho aire entre preguntas
- esta slide debe sentirse didáctica, no densa

---

### Slide 5 — Estructura recomendada
**Objetivo visual**
Mostrar el mapa del deck.

**Layout**
- timeline vertical u horizontal de 12 pasos
- alternativa: 3 bloques de 4 slides

**Visual**
- progresión visual clara, no solo lista numerada

**Iconos**
- uno pequeño por bloque o por etapa

**Chart / elemento**
- timeline o roadmap del deck

**Notas HTML**
- si 12 elementos se ven apretados, agrupar por fases:
  - historia
  - prueba
  - ejecución

---

### Slide 6 — 4 roles útiles
**Objetivo visual**
Mostrar que el trabajo con IA se divide por roles.

**Layout**
- 4 tarjetas horizontales o cuadrícula 2x2

**Visual**
- una tarjeta por rol
- nombre corto + una línea de descripción

**Iconos**
- analista: lupa
- estratega: brújula
- inversionista escéptico: escudo o signo de pregunta
- editor: lápiz o pluma

**Chart / elemento**
- no chart

**Notas HTML**
- reutilizar patrón de tarjetas del slide 2 pero con tono más funcional

---

### Slide 7 — Sin contexto, el deck sale genérico
**Objetivo visual**
Mostrar que los inputs definen la calidad del output.

**Layout**
- izquierda: inputs mínimos
- derecha: resultado esperado

**Visual**
- diagrama input → output

**Iconos**
- formulario / input
- caja de procesamiento
- documento / slide output

**Chart / elemento**
- flujo simple con flecha fuerte

**Notas HTML**
- este slide conviene mucho para HTML porque puede animar el paso de inputs a output

---

### Slide 8 — Flujo recomendado
**Objetivo visual**
Hacer visible el proceso paso a paso.

**Layout**
- pipeline horizontal de 7 pasos
- alternativa: escalera ascendente

**Visual**
- cada paso con número, etiqueta y estado visual

**Iconos**
- contexto, búsqueda, narrativa, deck, crítica, edición, documento final

**Chart / elemento**
- flow diagram principal

**Notas HTML**
- una barra de progreso o conexión entre nodos funciona muy bien
- esta slide define el lenguaje visual del proceso

---

### Slide 9 — Demo
**Objetivo visual**
Preparar a la audiencia para observar el método.

**Layout**
- lista corta a la izquierda
- mockup o frame de demo a la derecha

**Visual**
- wireframe de ventana de chat + outline de deck

**Iconos**
- monitor, chat, checklist

**Chart / elemento**
- no chart; usar mockup de interfaz

**Notas HTML**
- ideal para insertar una captura ficticia o un bloque estilizado que simule el demo

---

### Slide 10 — Caso: RutaFlow
**Objetivo visual**
Presentar el caso de ejemplo de forma concreta y memorable.

**Layout**
- tarjeta principal de startup
- columnas pequeñas para problema / solución / evidencia / riesgo

**Visual**
- mini ficha de startup

**Iconos**
- camión o ruta
- mensaje/chat
- mapa o pin
- alerta para riesgo

**Chart / elemento**
- pequeño bloque de métricas para pilotos y entrevistas

**Notas HTML**
- usar una tarjeta destacada con jerarquía fuerte
- el riesgo debe verse como algo abierto, no como defecto oculto

---

### Slide 11 — No acepten el primer borrador
**Objetivo visual**
Activar pensamiento crítico.

**Layout**
- checklist de revisión
- o panel de “preguntas de control”

**Visual**
- lista con checks / alerts

**Iconos**
- lupa
- alerta
- check parcial

**Chart / elemento**
- no chart

**Notas HTML**
- conviene que esta slide se sienta como una herramienta de revisión

---

### Slide 12 — Fallas comunes
**Objetivo visual**
Hacer visibles los errores típicos.

**Layout**
- 6 tarjetas o lista de errores en dos columnas

**Visual**
- cada error con ícono y etiqueta breve
- opcional: color ámbar suave para marcar riesgo

**Iconos**
- advertencia, nube vacía, megáfono, gráfico inflado, mapa global, CV

**Chart / elemento**
- no chart

**Notas HTML**
- esta slide puede usar estilo de “anti-patterns”
- útil para contraste con slides más limpias

---

### Slide 13 — Afirmación / Evidencia / Implicación
**Objetivo visual**
Introducir la regla operativa más importante.

**Layout**
- tres bloques grandes en secuencia
- o stack vertical con conectores

**Visual**
- diagrama simple de tres etapas

**Iconos**
- megáfono o statement
- lupa / prueba
- flecha / impacto

**Chart / elemento**
- diagrama de secuencia de 3 nodos

**Notas HTML**
- esta slide debe ser visualmente muy limpia
- puede funcionar con tipografía grande y casi sin texto extra

---

### Slide 14 — Ejemplo
**Objetivo visual**
Aterrizar la regla anterior con un caso concreto.

**Layout**
- tres tarjetas alineadas:
  - afirmación
  - evidencia
  - implicación

**Visual**
- ejemplo aplicado al caso RutaFlow

**Iconos**
- reutilizar los mismos del slide 13

**Chart / elemento**
- no chart, pero sí mantener la secuencia visual

**Notas HTML**
- conviene conservar continuidad visual con el slide 13

---

### Slide 15 — Actividad
**Objetivo visual**
Dar instrucciones claras para el ejercicio.

**Layout**
- columna izquierda: pasos
- columna derecha: tiempo y entregable

**Visual**
- bloque de actividad tipo workshop card

**Iconos**
- cronómetro
- teclado o chat
- documento

**Chart / elemento**
- mini temporizador o badge “12–13 min”

**Notas HTML**
- esta slide debe sentirse accionable y simple
- usar jerarquía para que el tiempo sea muy visible

---

### Slide 16 — Debrief
**Objetivo visual**
Guiar la discusión final.

**Layout**
- 4 preguntas en grid o lista amplia

**Visual**
- tarjetas de reflexión o bloques de preguntas

**Iconos**
- burbuja de diálogo
- lupa
- alerta
- evidencia / documento

**Chart / elemento**
- no chart

**Notas HTML**
- esta slide debe verse abierta, conversacional y menos rígida

---

### Slide 17 — Después del taller
**Objetivo visual**
Cerrar con una llamada a la acción y una frase memorable.

**Layout**
- arriba: lista corta de próximos pasos
- abajo: bloque de cierre con frase final

**Visual**
- cierre limpio, con mucho espacio
- idealmente volver al fondo oscuro del inicio para cerrar el arco visual

**Iconos**
- check, cliente, gráfico, mensaje crítico

**Chart / elemento**
- no chart

**Notas HTML**
- la frase final debe verse como statement de cierre
- puede ocupar gran parte del espacio inferior

## Componentes HTML sugeridos

### 1. `HeroSlide`
Para apertura y cierre.

### 2. `CardGrid`
Para beneficios, roles, preguntas o errores.

### 3. `ProcessFlow`
Para el flujo recomendado.

### 4. `ComparisonSplit`
Para fundador vs IA o inputs vs outputs.

### 5. `ExampleTriptych`
Para afirmación / evidencia / implicación.

### 6. `WorkshopTask`
Para actividad con tiempo y entregable.

## Guía de gráficos y elementos visuales
- usar charts solo cuando representen proceso o estructura
- evitar charts cuantitativos falsos o decorativos
- los diagramas deben ser simples y geométricos
- si se usan capturas o mockups, deben verse limpios y consistentes con la UI HTML

## Recomendaciones para implementación HTML
- usar variables de diseño para color, spacing, radius y tipografía
- construir componentes reutilizables para slides repetibles
- preparar modo oscuro como base
- considerar navegación por teclado
- considerar vista presenter más adelante, pero no bloquear este primer paso por eso

## Qué evitar
- exceso de texto por slide
- fondos con demasiado ruido
- iconografía mezclada
- demasiados colores de acento
- animaciones que ralenticen la presentación
- cajas y bordes por todos lados sin jerarquía

## Resultado esperado
Al convertir este brief en HTML, el deck debe sentirse:

- actual
- premium
- claro
- profesional
- útil para enseñar, no solo para impresionar
