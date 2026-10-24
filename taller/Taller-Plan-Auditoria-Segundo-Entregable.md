# Taller: del riesgo priorizado al plan de auditoría

**Auditoría de Sistemas (ET0114) · Continuación del primer trabajo y de la matriz de riesgos**  
**Docente:** Juan Duque  
**Exposición:** viernes 30 de octubre de 2026, durante la clase  
**Entrega final:** domingo 1 de noviembre de 2026, hasta las **11:59 p. m. (hora de Colombia)**

## Propósito

En el taller anterior construyeron una matriz con activos o procesos, amenazas, vulnerabilidades, riesgos, probabilidad, impacto y controles. Ahora deben usar esa matriz para responder una pregunta nueva: **¿cómo organizarían una auditoría concreta para evaluar uno de los riesgos prioritarios?**

El producto es un **plan de auditoría propuesto**, no un informe de resultados. No se espera que demuestren que la organización cumple o incumple, ni que inventen registros a los que no tienen acceso. Se espera que expliquen qué evaluarían, por qué, con qué criterio y mediante qué evidencia podrían llegar a una conclusión.

## Punto de partida y continuidad

- Trabajen con **el mismo equipo, caso, sistema u organización** del primer trabajo y del taller de matriz de riesgos.
- Recuperen la versión vigente de su matriz. Seleccionen **un riesgo prioritario** para desarrollarlo con profundidad. Pueden incluir un segundo riesgo si comparte proceso y el plan sigue siendo viable; no es obligatorio.
- Conserven el identificador o una referencia inequívoca a la fila de la matriz. No reemplacen la matriz por una lista nueva de riesgos.
- Retomen los marcos de referencia que escogieron en el primer trabajo, pero utilicen solo aquellos pertinentes al riesgo seleccionado. Pueden ajustar la elección si explican la razón.
- Si el caso o la matriz necesita una corrección, indiquen qué cambiaron y por qué. Un cambio de caso completo requiere justificación expresa al comienzo del documento.

Los incidentes públicos de **Equifax, Knight Capital y Colonial Pipeline** se usarán como ejemplos de método en clase. **No sustituyen automáticamente el caso que cada equipo ya viene trabajando.**

## Actividades del taller

### 1. Presentar el caso y justificar la elección del riesgo

En un párrafo breve, recuerden la organización, el sistema o proceso elegido y la preocupación central. Después copien o referencien el riesgo seleccionado de la matriz e indiquen:

- Activo o proceso afectado.
- Amenaza y vulnerabilidad que lo explican.
- Consecuencia posible.
- Probabilidad, impacto y nivel asignados en la matriz, con la justificación ya trabajada.
- Control actual identificado o control propuesto.
- Razón por la que vale la pena dedicarle una auditoría.

**No basta** con escribir «es el riesgo de mayor puntaje». El puntaje orienta la prioridad, pero también deben explicar la importancia del proceso y la posibilidad de revisar el control.

### 2. Redactar el objetivo de auditoría

Escriban **un objetivo principal verificable**. Debe expresar qué desean determinar sobre el control o proceso relacionado con el riesgo. Puede comenzar con «Determinar si…» o «Evaluar si…».

| Redacción insuficiente | Redacción que orienta una auditoría |
|---|---|
| «Auditar la seguridad del sistema» | «Determinar si los cambios del sistema seleccionado fueron aprobados y probados antes de su liberación durante el periodo definido» |
| «Revisar documentos» | «Determinar si las cuentas con acceso privilegiado se revocan conforme al procedimiento vigente cuando termina el vínculo del usuario» |

El primer ejemplo de cada fila es demasiado amplio o describe una actividad. El segundo plantea una condición que podría contrastarse con evidencia. Adapten la formulación a **su propio caso**; no copien el ejemplo como si fuera un hecho de su organización.

### 3. Delimitar el alcance funcional

Expliquen con precisión:

1. **Proceso o función:** qué actividad revisarán (por ejemplo, aprobación de cambios, bajas de usuarios, respaldos o gestión de parches).
2. **Sistema o componente:** qué aplicación, base de datos, servicio o infraestructura queda dentro.
3. **Población:** cuáles serían los elementos revisables (liberaciones, cuentas, respaldos, solicitudes, etc.).
4. **Periodo:** fechas o intervalo propuesto y por qué es razonable.
5. **Áreas o responsables:** quiénes explicarían el proceso o custodiarían la evidencia.
6. **Inclusiones y exclusiones:** qué se revisaría y qué no, con una razón. Declaren si una exclusión limita la conclusión posible.

Eviten alcances como «todos los sistemas y todos los controles». Si el objetivo trata sobre liberaciones de una aplicación, el alcance debe concentrarse en ese proceso y en los componentes necesarios para comprobarlo.

### 4. Establecer criterios de evaluación

Para cada control que revisarán, indiquen la **condición esperada** y su fuente. Puede ser una política o procedimiento de la organización, un requisito aplicable o un marco pertinente. Expliquen por qué aplica al caso.

- «Cumplir ISO/IEC 27001» o «aplicar COBIT» **no es aún un criterio operativo**.
- «Los cambios a producción requieren aprobación y evidencia de pruebas previas, conforme al procedimiento de cambios vigente» **sí expresa una condición que se puede contrastar**, siempre que el procedimiento exista y se confirme su vigencia.
- No atribuyan a un marco plazos, porcentajes o controles específicos que no hayan verificado. Si no conocen la política interna, escriban **«criterio por confirmar mediante solicitud de la política vigente»**.

### 5. Diseñar el programa de trabajo

Para el riesgo principal, propongan **al menos dos procedimientos complementarios**:

1. **Comprender o verificar el diseño del control:** identificar cómo debería funcionar, quién responde por él y qué documento o configuración lo define.
2. **Verificar su operación:** indicar cómo compararían una población o muestra del periodo contra el criterio y cómo registrarían excepciones.

Cada procedimiento debe decir **qué se obtendría, qué se compararía, sobre qué población o muestra, y qué evidencia se conservaría**. La muestra puede ser propuesta; si no conocen el tamaño real de la población, no inventen cantidades.

| Elemento | Pregunta que deben responder |
|---|---|
| Control | ¿Qué acción reduce la vulnerabilidad y quién la realiza? |
| Criterio | ¿Cuál es la condición exigida o esperada? |
| Procedimiento | ¿Qué haría el auditor, paso a paso, para comprobarla? |
| Población o muestra | ¿Qué elementos y periodo revisaría? ¿Cómo escogería la muestra? |
| Evidencia esperada | ¿Qué registros, documentos, configuraciones o trazas solicitaría? |
| Posibles excepciones | ¿Qué resultado indicaría incumplimiento o falta de evidencia? |

Una entrevista puede ayudar a comprender el proceso, pero **no debe ser la única evidencia** de que un control operó. Propongan cómo corroborar lo dicho con registros o configuraciones.

### 6. Organizar la ejecución propuesta

Incluyan un cronograma breve con fases de preparación, solicitud de información, revisión y cierre; responsables dentro del equipo; dependencias de la organización; y recursos necesarios. Señalen qué partes podrían realizar realmente y cuáles quedarían como planificación por falta de acceso.

### 7. Declarar supuestos y limitaciones

Separen claramente:

- **Hecho comprobado:** aparece en una fuente identificada o en documentación del caso.
- **Supuesto:** condición razonable que necesitan para construir el plan, pero que aún no han verificado.
- **Información por solicitar:** evidencia o política que un auditor pediría.
- **Propuesta del equipo:** objetivo, alcance, criterio o procedimiento diseñado por ustedes.

No presenten evidencia esperada como evidencia obtenida. No redacten hallazgos, porcentajes de cumplimiento ni conclusiones sobre la eficacia del control si no ejecutaron la revisión.

## Producto escrito

Entreguen **un documento Markdown (`.md`)** en el mismo repositorio usado en los trabajos anteriores. Incluyan los nombres completos de los integrantes y un enlace o anexo a la matriz de riesgos vigente. La extensión sugerida es de **cinco a siete páginas equivalentes, sin contar la matriz anexa**; prima la claridad sobre el volumen.

Orden recomendado:

1. Identificación del equipo y del caso.
2. Contexto y riesgo seleccionado, con referencia a la matriz.
3. Justificación y objetivo de auditoría.
4. Alcance funcional y exclusiones.
5. Criterios aplicables o por confirmar.
6. Programa de trabajo: controles, procedimientos, población/muestra y evidencia esperada.
7. Responsables, cronograma, supuestos y limitaciones.
8. Fuentes y referencia a la matriz completa.

Pueden usar esta fila de trazabilidad como base y añadir filas según sus procedimientos:

| ID del riesgo | Control a evaluar | Criterio y fuente | Procedimiento | Población o muestra | Evidencia esperada |
|---|---|---|---|---|---|
| R-__ | Qué control reduce el riesgo | Qué condición se comparará y de dónde proviene | Qué hará el auditor | Qué elementos del periodo revisará | Qué solicitará y para qué |

El documento debe estar publicado en el repositorio **a más tardar el domingo 1 de noviembre a las 11:59 p. m. (hora de Colombia)**. Compartan el enlace por el canal indicado en clase. Revisen que el enlace sea accesible y apunte a la versión final.

## Exposición del viernes 30 de octubre

Cada equipo dispondrá de **10 a 15 minutos** para exponer un **borrador sustantivo** del plan. La exposición ocurre **antes** de la entrega final para que puedan incorporar la retroalimentación recibida durante el fin de semana.

Distribución sugerida del tiempo:

| Tiempo aproximado | Contenido |
|---|---|
| 1–2 minutos | Caso y continuidad con los trabajos anteriores |
| 2 minutos | Riesgo elegido y razón de prioridad |
| 2–3 minutos | Objetivo y alcance funcional, incluyendo exclusiones |
| 3–4 minutos | Criterio, controles y procedimientos propuestos |
| 1–2 minutos | Evidencia esperada, supuestos y limitaciones |
| 1–2 minutos | Cierre, preguntas y aspectos que faltan confirmar |

Pueden apoyarse en el documento del repositorio o en una presentación breve. **No se evalúa el diseño visual de las diapositivas por encima del razonamiento de auditoría.** Todos los integrantes deben estar preparados para explicar cómo se conecta el riesgo con el objetivo, el criterio y la evidencia.

Después de exponer, ajusten el archivo final si la discusión identifica un alcance demasiado amplio, un criterio sin fuente o procedimientos que no producen evidencia suficiente. No es necesario simular la ejecución de la auditoría para la exposición.

## Criterios de evaluación

| Criterio | Qué demuestra un trabajo sólido |
|---|---|
| Continuidad y selección del riesgo | Conserva el caso y la matriz; el riesgo elegido está identificado y justificado. |
| Objetivo y alcance | Formula una pregunta verificable y límites funcionales coherentes, viables y explícitos. |
| Criterios | Define condiciones aplicables y fuentes identificables; distingue lo confirmado de lo pendiente. |
| Procedimientos | Permiten que otra persona entienda y repita cómo se obtendría y contrastaría la evidencia. |
| Evidencia y trazabilidad | Cada evidencia prevista responde a un procedimiento y permite evaluar el control relacionado con el riesgo. |
| Viabilidad y transparencia | Incluye responsables, cronograma, supuestos, dependencias y limitaciones sin inventar resultados. |
| Exposición | Explica y defiende las decisiones principales en 10–15 minutos; incorpora la retroalimentación pertinente en la versión final. |
| Claridad del entregable | El documento es ordenado, legible y accesible en el repositorio. |

## Antes de entregar

- ¿El riesgo seleccionado se puede encontrar en la matriz anterior?
- ¿El objetivo se podría responder con evidencia, en lugar de describir solo una actividad?
- ¿El alcance indica proceso, sistema, población, periodo y exclusiones?
- ¿Cada criterio tiene fuente o está marcado como pendiente de confirmar?
- ¿Los procedimientos explican qué comparar y qué excepciones buscar?
- ¿La evidencia esperada es concreta y corresponde al procedimiento?
- ¿Está claro qué es hecho, supuesto, propuesta e información por solicitar?
- ¿La versión final refleja las correcciones surgidas en la exposición del viernes?

Como apoyo, consulten la [guía de referencia del plan de auditoría](../output/pdf/Guia-Referencia-Plan-Auditoria-Taller2.pdf) y el [taller de matriz de riesgos](Taller-Sesion7-Matriz-Riesgos.md).
