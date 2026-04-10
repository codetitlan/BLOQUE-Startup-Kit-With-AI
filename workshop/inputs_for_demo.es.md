# Inputs para demo: taller de pitch deck con agentes de IA

Este archivo contiene bloques listos para copiar y pegar durante la demostración en vivo.

## 1. Notas iniciales de la startup

Pegar este bloque al inicio, cuando quieras mostrar cómo un agente convierte notas desordenadas en una narrativa más clara.

```text
Startup: RutaFlow

Estamos construyendo software para pequeñas empresas urbanas de logística en América Latina.

Hoy muchas de estas empresas coordinan sus operaciones diarias con WhatsApp, llamadas telefónicas, grupos de chat y hojas de cálculo. Eso vuelve muy difícil saber qué conductor va en qué ruta, qué entregas van tarde y dónde hubo incidencias.

Nuestro producto busca resolver ese problema con una herramienta simple para asignar rutas, ver estatus en tiempo real y registrar incidencias de entrega.

Creemos que esto importa ahora porque muchos operadores pequeños ya quieren digitalizarse, pero las herramientas enterprise son demasiado caras, complejas o están pensadas para empresas mucho más grandes.

Todavía estamos validando el modelo exacto, pero pensamos cobrar una suscripción mensual basada en la cantidad de vehículos activos.

Hasta ahora tenemos 18 clientes piloto, 6 de ellos activos semanalmente, y los fundadores han hecho 40 entrevistas con operadores del sector.

Todavía no sabemos bien cuál será la retención real ni si la disposición a pagar será tan alta como pensamos.

Competencia:
- operadores que siguen usando WhatsApp + Excel
- software de logística enterprise
- herramientas internas hechas por los propios operadores

Lo que queremos:
- entender si esta historia tiene sentido para un pitch deck temprano
- identificar qué partes están fuertes y cuáles todavía son débiles
```

## 2. Prompt sugerido para limpieza de contexto

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
[PEGA AQUÍ LAS NOTAS INICIALES DE LA STARTUP]
```

## 3. Resumen limpio de contexto

Usar este bloque si quieres avanzar rápido sin depender del resultado del primer prompt.

```text
RutaFlow es una startup de software para pequeñas empresas urbanas de logística en América Latina.

Su cliente inicial son operadores logísticos pequeños que hoy coordinan despacho y seguimiento de entregas con WhatsApp, llamadas telefónicas y hojas de cálculo.

El problema es que ese sistema manual vuelve caótica la operación diaria: dificulta asignar rutas, seguir entregas en tiempo real y registrar incidencias.

La propuesta de RutaFlow es una herramienta simple para asignación de rutas, monitoreo de estatus y registro de incidencias, diseñada específicamente para operadores pequeños.

La razón de oportunidad es que estos operadores ya sienten presión por digitalizarse, pero las soluciones enterprise suelen ser demasiado costosas o complejas para su contexto.

El modelo de negocio todavía es una hipótesis: suscripción SaaS mensual basada en el número de vehículos activos.

La evidencia actual incluye 18 clientes piloto, 6 activos semanalmente y 40 entrevistas realizadas por el equipo fundador.

Los riesgos o vacíos principales son:
- retención todavía no probada
- disposición a pagar todavía no validada
- falta de claridad sobre velocidad de adopción en operaciones pequeñas
```

## 4. Prompt sugerido para narrativa

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
[PEGA AQUÍ EL RESUMEN LIMPIO]
```

## 5. Narrativa recomendada para continuar la demo

Usar este bloque si quieres saltar directamente a la generación del outline.

```text
Narrativa recomendada:

RutaFlow ayuda a pequeños operadores logísticos a salir del caos operativo diario reemplazando coordinación manual en WhatsApp, llamadas y Excel por una herramienta simple diseñada para su realidad.

Esta narrativa funciona bien para una startup en incubación porque:
- parte de un dolor claro y observable
- conecta con evidencia temprana real
- no depende de promesas exageradas
- deja espacio para hablar honestamente de lo que todavía falta probar

Riesgo principal de esta narrativa:
- si la evidencia de frecuencia e impacto del problema no se vuelve más fuerte, puede sonar más como una mejora operativa que como una oportunidad grande
```

## 6. Prompt sugerido para outline del deck

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
[PEGA AQUÍ EL RESUMEN LIMPIO O LA NARRATIVA RECOMENDADA]
```

## 7. Outline de ejemplo para continuar la demo

Usar este bloque si quieres mostrar la crítica sin depender del resultado en vivo.

```text
1. Portada
- RutaFlow
- Software simple para operaciones logísticas pequeñas
- Ayudamos a operadores pequeños a salir del caos de WhatsApp + llamadas + Excel

2. Problema
- La coordinación diaria de rutas y entregas sigue siendo manual
- Los equipos alternan entre múltiples canales sin una fuente única de verdad
- Eso genera retrasos, errores y poca visibilidad operativa

3. Cliente / contexto de mercado
- El cliente inicial son pequeñas empresas urbanas de logística en América Latina
- Este segmento ya necesita digitalizarse, pero no puede adoptar software enterprise complejo
- El problema es frecuente y operativo, no solo administrativo

4. Solución
- RutaFlow centraliza asignación de rutas, estatus e incidencias
- Está diseñada para operadores pequeños, no para grandes redes logísticas
- Busca reducir complejidad sin exigir procesos enterprise

5. Producto
- Vista simple de rutas y operadores
- Seguimiento de entregas e incidencias
- Herramienta ligera para uso diario por equipos operativos

6. Modelo de negocio
- Suscripción SaaS mensual
- Precio basado en vehículos activos
- Hipótesis todavía por validar en disposición a pagar

7. Tracción / validación
- 18 clientes piloto
- 6 activos semanalmente
- 40 entrevistas con operadores
- Retención y conversión todavía no probadas

8. Competencia / alternativas
- WhatsApp + Excel + llamadas
- Software enterprise de logística
- Herramientas internas o procesos manuales

9. Go-to-market
- Empezar con operadores pequeños en entornos urbanos
- Venta directa y onboarding cercano
- Aprender primero en un nicho operacional claro

10. Equipo
- Equipo con experiencia en producto, tecnología e implementación
- Capacidad para construir software y trabajar cerca del cliente

11. Roadmap / hitos
- Mejorar uso recurrente en pilotos
- Validar disposición a pagar
- Definir el wedge más fuerte de adopción

12. Ask
- Feedback, conexiones con operadores logísticos y apoyo para validar GTM
- Eventualmente capital para acelerar validación y producto
```

## 8. Prompt sugerido para crítica de inversionista

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
[PEGA AQUÍ EL OUTLINE]
```

## 9. Crítica de ejemplo para continuar la demo

```text
Las 3 diapositivas más débiles son:

1. Modelo de negocio
- El pricing está planteado como hipótesis, pero no hay evidencia de disposición a pagar
- Falta claridad sobre quién decide la compra y qué tan sensible es ese cliente al precio

2. Go-to-market
- La estrategia todavía es demasiado general
- “Venta directa y onboarding cercano” no explica cómo conseguirán los primeros clientes de forma repetible

3. Equipo
- La credibilidad del equipo está formulada de forma abstracta
- Falta conectar experiencia previa con el problema específico que están resolviendo

Evidencia faltante más importante:
- frecuencia real del dolor
- impacto económico del problema
- señales de retención
- validación de disposición a pagar
- claridad sobre un canal inicial repetible

Top 5 objeciones:
- esto puede ser una mejora incremental y no una empresa grande
- los operadores pequeños podrían no pagar suficiente
- el problema es real, pero tal vez no lo bastante urgente
- la adopción operativa puede ser más lenta de lo esperado
- la competencia del status quo puede ser más fuerte de lo que parece
```

## 10. Prompt sugerido para reescribir diapositivas débiles

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
[PEGA AQUÍ EL RESUMEN LIMPIO]

Diapositivas débiles y crítica:
[PEGA AQUÍ LAS 3 DIAPOSITIVAS DÉBILES + CRÍTICA]
```

## 11. Versión rápida si se complica la demo

Pegar este bloque para resolver todo en una sola ejecución.

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
[PEGA AQUÍ LAS NOTAS INICIALES DE LA STARTUP]
```

## 12. Frases útiles para narrar la demo

Puedes usar estas frases mientras haces copy/paste en vivo:

- “Primero le damos contexto a la IA antes de pedirle una salida.”
- “No le estamos pidiendo un deck completo de golpe; estamos dividiendo el problema.”
- “Aquí lo importante es detectar qué parte está respaldada por evidencia y qué parte sigue siendo hipótesis.”
- “Ahora vamos a cambiar el rol del agente: de estratega a inversionista escéptico.”
- “Si el deck suena bien pero no resiste preguntas, todavía no está listo.”
- “La IA acelera la escritura; el fundador sigue siendo responsable del criterio.”
