# Prompt Pack: flujo de agentes de IA para pitch decks en etapa temprana

Usa estos prompts en secuencia. La persona fundadora debe editar los resultados en cada paso en lugar de aceptarlos sin revisión.

## Prompt 1 — Levantamiento de contexto de la startup

```text
Actúa como analista de narrativa para startups.

Soy fundador(a) de una startup en etapa temprana y estoy preparando un pitch deck.
Primero, lee mis notas y extrae:
1. la idea central de la startup
2. cliente objetivo
3. problema que se está resolviendo
4. alternativas actuales
5. por qué esto importa ahora
6. hipótesis del modelo de negocio
7. tracción o evidencia de validación
8. supuestos o vacíos principales

Después devuelve:
- un resumen conciso de la startup en lenguaje simple
- una lista de afirmaciones respaldadas por evidencia
- una lista de afirmaciones que son solo supuestos
- una lista de información faltante para un pitch deck creíble

Usa lenguaje claro. No inventes hechos. Marca la incertidumbre explícitamente.

Aquí están mis notas:
[PEGA TUS NOTAS]
```

## Prompt 2 — Estrategia narrativa

```text
Actúa como estratega de pitch deck para una startup muy temprana.

Usando el contexto de la startup que aparece abajo, propone 3 narrativas posibles para el pitch.
Para cada narrativa, incluye:
- el mensaje central
- con qué tipo de audiencia resonaría
- el principal riesgo de usar esa narrativa

Después recomienda la narrativa más fuerte para una startup en incubación y explica por qué.

Restricciones:
- mantén todo anclado en la evidencia disponible
- evita lenguaje inflado
- optimiza por claridad y credibilidad

Contexto de la startup:
[PEGA EL RESUMEN LIMPIO]
```

## Prompt 3 — Outline del deck

```text
Actúa como un experto en fundraising para startups.

Crea un outline de pitch deck de 10 a 12 diapositivas para la startup de abajo.

Para cada diapositiva incluye:
- título de la diapositiva
- propósito de la diapositiva
- 3 a 5 bullets con contenido sugerido
- qué evidencia fortalecería esa diapositiva

Usa esta estructura salvo que exista una mejor y la justifiques:
1. Portada
2. Problema
3. Cliente / contexto de mercado
4. Solución
5. Producto
6. Modelo de negocio
7. Tracción / validación
8. Competencia / alternativas
9. Go-to-market
10. Equipo
11. Roadmap / hitos
12. Ask

Reglas:
- no inventes métricas
- señala cuando la evidencia sea débil
- prioriza especificidad sobre lenguaje genérico pulido
- escribe para inversionistas o mentores de etapa temprana

Contexto de la startup:
[PEGA EL RESUMEN LIMPIO]
```

## Prompt 4 — Revisión de inversionista escéptico

```text
Actúa como un inversionista de etapa temprana que revisa este outline.

Para cada diapositiva:
- identifica qué está poco claro, débil, genérico, no sustentado o riesgoso
- enumera la pregunta más difícil que haría un inversionista

Después entrega:
- las 3 diapositivas que más necesitan mejora
- la evidencia faltante más importante
- las 5 objeciones principales a la historia completa de la startup

Sé directo y específico. No suavices la crítica.

Outline del deck:
[PEGA EL OUTLINE]
```

## Prompt 5 — Reescribir las diapositivas débiles

```text
Actúa como editor de pitch decks.

Te voy a dar 3 diapositivas débiles de mi outline junto con la crítica del inversionista.
Reescribe cada diapositiva para que sea:
- más clara
- más específica
- más basada en evidencia
- más adecuada para una startup en etapa de incubación

Para cada diapositiva reescrita, entrega:
- título revisado
- bullets revisados
- una oración explicando qué cambió
- una oración describiendo qué prueba sigue faltando

No fabriques evidencia.

Contexto de la startup:
[PEGA EL RESUMEN LIMPIO]

Diapositivas débiles y crítica:
[PEGA EL MATERIAL]
```

## Prompt 6 — Convertir el outline en copy para diapositivas

```text
Actúa como redactor conciso de diapositivas para startups.

Convierte este outline de pitch deck en una primera versión de copy para diapositivas.

Restricciones:
- cada diapositiva debe ser concisa
- usa lenguaje claro y apto para inversionistas
- evita buzzwords
- no excedas 40 palabras por diapositiva salvo que sea necesario
- si una diapositiva carece de evidencia, escribe una nota entre corchetes

Formato de salida:
- número de diapositiva
- título de la diapositiva
- copy de la diapositiva

Outline:
[PEGA EL OUTLINE REVISADO]
```

## Prompt 7 — Brief de diseño para herramienta de presentaciones

```text
Actúa como redactor de briefs de diseño para presentaciones.

Con base en este pitch deck, crea un brief de diseño para construir las diapositivas en una herramienta de presentaciones.

Incluye:
- tono general
- estilo visual
- densidad recomendada por diapositiva
- dónde conviene usar gráficas o capturas del producto
- dónde un diagrama simple funciona mejor que texto
- 3 errores de diseño que deben evitarse

No rediseñes la narrativa del negocio. Enfócate solo en la calidad de presentación.

Contenido del deck:
[PEGA EL COPY DEL DECK]
```

## Prompt 8 — Revisión final antes de mostrar el deck

```text
Actúa como revisor final antes de que este deck se muestre a mentores o inversionistas.

Revisa el deck y entrega:
1. las principales fortalezas
2. las principales debilidades
3. cualquier diapositiva que suene genérica
4. cualquier afirmación que necesite prueba
5. cualquier sección que parezca fuera de orden
6. una recomendación final:
   - listo para revisión
   - necesita una revisión más
   - no está listo

Mantén la revisión concisa y práctica.

Deck:
[PEGA EL COPY DEL DECK]
```

## Versión rápida para fundadores con poco tiempo

```text
Actúa como agente para crear pitch decks de startups.

Usando mis notas, haz lo siguiente en orden:
1. resume la startup
2. identifica información faltante
3. propone la narrativa más fuerte para el pitch
4. crea un outline de 10 a 12 diapositivas
5. critica el outline como inversionista escéptico
6. reescribe las 3 diapositivas más débiles

Reglas:
- no inventes hechos
- marca los supuestos con claridad
- prioriza claridad sobre pulido
- escribe para una audiencia de incubación en etapa temprana

Mis notas:
[PEGA TUS NOTAS]
```

## Prompt para ejercicio del taller

```text
Actúa como asistente de taller para fundadores de etapa temprana.

Una persona participante tiene notas limitadas sobre su startup y necesita ayuda para crear un primer outline de pitch deck.

Tu trabajo es:
- extraer los hechos más importantes
- identificar piezas faltantes sin desanimar
- crear un outline práctico de 10 diapositivas
- marcar las 3 diapositivas que más necesitan evidencia del fundador

Usa lenguaje simple adecuado para fundadores con experiencias mixtas en negocio.
No inventes información.

Notas de la persona participante:
[PEGA TUS NOTAS]
```
