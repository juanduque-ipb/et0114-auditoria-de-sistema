# Taller final: informe de auditoría y plan de acción

**Asignatura:** ET0114 · Auditoría de Sistemas  
**Modalidad:** trabajo en equipo y presentación  
**Entrega:** fecha y canal indicados por el docente  
**Calificación:** 70 % informe escrito con plan de acción y 30 % presentación

## Propósito

Integrar el trabajo realizado durante el semestre en un informe de auditoría. Cada equipo comunicará qué revisó, qué evidencia examinó, qué resultados obtuvo y qué acciones propone para atender los hallazgos sustentados.

La secuencia del trabajo es: **caso y marcos de referencia → matriz de riesgos → plan de auditoría → pruebas y evidencia → informe y plan de acción**.

## Punto de partida

Trabajen con el mismo equipo, organización o sistema, matriz de riesgos y plan de auditoría de los entregables anteriores. Seleccionen el riesgo y los controles que desarrollaron en el plan. Si necesitan ajustar el alcance, el control o los procedimientos, expliquen qué cambió y por qué.

Si realizaron la actividad de ejecución y evidencia de la clase, utilicen su papel de trabajo como base. Si aún no la realizaron, documenten al menos **una prueba de un control** para este taller.

## Información real y simulada

- Usen evidencia real únicamente cuando tengan autorización para consultarla y compartirla. Protejan los datos personales y la información sensible.
- Si no tienen acceso a registros reales, preparen un conjunto pequeño de datos ficticios coherente con el caso. Identifiquen claramente la prueba, los registros y los resultados como **simulados**.
- Una simulación demuestra cómo se aplicaría la prueba; no demuestra el cumplimiento o incumplimiento real de la organización.
- Distingan los hechos comprobados, los supuestos y las propuestas. No presenten evidencia esperada como evidencia obtenida ni inventen políticas, causas o resultados reales.

## Actividades

### 1. Recuperar el riesgo y el plan

Indiquen la organización o caso, el sistema o proceso y el riesgo priorizado. Referencien la fila de la matriz y el plan de auditoría anterior. Expliquen brevemente qué control eligieron y por qué se relaciona con ese riesgo.

### 2. Ejecutar y documentar la prueba

Elaboren o anexen un papel de trabajo que permita entender y repetir la prueba. Incluyan:

- **Objetivo:** qué desean comprobar sobre el control.
- **Criterio y fuente:** condición esperada y documento o referencia que la establece. Si es un criterio ficticio para el ejercicio, indíquenlo.
- **Población y muestra:** elementos y periodo revisados, cantidad examinada y forma de selección. Si la población real es desconocida, declárenlo.
- **Procedimiento:** pasos y comparaciones realizados.
- **Evidencia examinada:** registros y fuentes consultados, señalando si son reales o simulados.
- **Resultado:** casos revisados y excepciones identificadas, si las hay.
- **Limitaciones:** información que faltó y alcance de la conclusión.

Una entrevista puede ayudar a comprender el proceso, pero propongan cómo corroborarla con registros o configuraciones cuando el objetivo sea comprobar la operación del control.

### 3. Evaluar los resultados y redactar hallazgos

Cuando la evidencia muestre una diferencia frente al criterio, redacten el hallazgo con:

1. **Criterio:** qué debía ocurrir y cuál es su fuente.
2. **Condición:** qué observaron, con referencia a la prueba y a la evidencia.
3. **Causa:** por qué ocurrió, solo si tienen soporte; de lo contrario, indíquenla como pendiente de confirmar.
4. **Efecto o riesgo:** consecuencia observada o posible, diferenciando ambas.
5. **Recomendación:** acción concreta que podría atender la condición o su causa.

Si no encuentran excepciones, registren el resultado y sus límites. No fabriquen un hallazgo ni concluyan que todo el sistema está libre de riesgos. Una muestra limitada no permite generalizar automáticamente a toda la población.

### 4. Preparar el informe de auditoría

Entreguen un único documento en Markdown (`.md`) en el repositorio del equipo, con estas secciones:

1. **Identificación:** integrantes, organización o caso y fecha.
2. **Resumen ejecutivo:** riesgo, trabajo realizado, resultado principal y acción propuesta; señalen si el ejercicio es simulado.
3. **Objetivo y alcance:** proceso, sistema, periodo, población, inclusiones y exclusiones.
4. **Criterios y metodología:** fuentes del criterio, procedimientos, muestra y evidencia examinada.
5. **Resultados y hallazgos:** lo observado y sus soportes, o el resultado sin excepciones cuando corresponda.
6. **Conclusión y limitaciones:** qué permite afirmar la evidencia y qué queda pendiente.
7. **Plan de acción:** tabla descrita en la siguiente sección.
8. **Referencias y anexos:** enlaces a la matriz, el plan, los papeles de trabajo y las fuentes usadas.

Se sugiere una extensión de **cuatro a seis páginas equivalentes**, sin contar anexos. Prima la claridad y la trazabilidad sobre la cantidad de texto.

### 5. Diseñar el plan de acción

Para cada hallazgo sustentado, propongan una acción concreta y verificable. El responsable y el plazo pueden ser **propuestos** si no se acordaron con la organización. No presenten una acción como aprobada o implementada si no existe evidencia de ello.

| ID del hallazgo | Acción propuesta | Responsable propuesto | Prioridad y justificación | Plazo propuesto | Evidencia de cierre |
|---|---|---|---|---|---|
| H-01 | ¿Qué se hará para atender el hallazgo? | ¿Qué rol podría ejecutarlo? | ¿Por qué requiere esa prioridad? | ¿Cuándo se propone terminar? | ¿Qué demostraría que se completó y funciona? |

Si no hubo hallazgos, expliquen que no corresponde formular acciones correctivas para esa prueba. Pueden proponer una acción de seguimiento o mejora, identificándola como tal y justificándola.

### Ejemplo ilustrativo

**Caso ficticio:** una política simulada exige desactivar las cuentas al finalizar el día de desvinculación. En una muestra ficticia de cinco cuentas, una se desactivó tres días después.

- **Criterio:** baja de acceso al finalizar el día de desvinculación, según la política ficticia del ejercicio.
- **Condición:** una de las cinco cuentas revisadas se desactivó tres días después.
- **Causa:** pendiente de confirmar.
- **Riesgo:** la cuenta pudo estar disponible para un acceso no autorizado. La prueba no demuestra que alguien la haya usado.
- **Recomendación:** revisar el flujo de notificación y baja, y hacer seguimiento a las cuentas pendientes.

| Hallazgo | Acción propuesta | Responsable propuesto | Prioridad y justificación | Plazo propuesto | Evidencia de cierre |
|---|---|---|---|---|---|
| H-01: baja tardía | Revisar el flujo de desvinculación y establecer seguimiento de cuentas pendientes | Responsable de gestión de accesos | Alta, por la posibilidad de acceso tras la desvinculación | 30 días, sujeto a acuerdo | Procedimiento actualizado y registros de una prueba posterior del control |

El resultado corresponde solamente a la muestra ficticia. No describe a una organización real ni permite extrapolar el incumplimiento a toda la población.

## Presentación

Cada equipo dispondrá de **10 a 15 minutos** como referencia, incluyendo preguntas. Todos los integrantes deben estar preparados para explicar y defender el trabajo. Pueden usar diapositivas o mostrar el documento; se valora el razonamiento por encima del diseño visual.

Distribución sugerida:

| Tiempo | Contenido |
|---|---|
| 1–2 minutos | Caso, riesgo y continuidad con la matriz y el plan |
| 2–3 minutos | Objetivo, alcance, criterio y prueba realizada |
| 3–4 minutos | Evidencia, resultado y hallazgo, si corresponde |
| 2–3 minutos | Plan de acción y evidencia de cierre |
| 2–3 minutos | Conclusión, limitaciones y preguntas |

Si el resultado es simulado, declárenlo al comenzar y al presentar la conclusión. Si no hubo excepciones, expliquen el resultado y sus límites en lugar de inventar un hallazgo.

## Evaluación: 70 % informe y 30 % presentación

La nota final se calcula en escala de **0,0 a 5,0**:

**Nota final = (nota del informe × 0,70) + (nota de la presentación × 0,30).**

El informe incluye el plan de acción. Los siguientes pesos suman **100 puntos de la nota final**:

| Componente | Criterio | Peso |
|---|---|---:|
| Informe | Continuidad con el caso, la matriz y el plan; objetivo y alcance claros | 10 % |
| Informe | Prueba, muestra y evidencia documentadas con trazabilidad | 20 % |
| Informe | Resultados, hallazgos o ausencia de excepciones, conclusión y limitaciones sustentadas | 20 % |
| Informe | Plan de acción concreto, coherente y verificable | 15 % |
| Informe | Claridad, organización, fuentes y distinción entre información real y simulada | 5 % |
| Presentación | Explicación del caso, riesgo, objetivo y prueba | 10 % |
| Presentación | Sustento de resultados, conclusión y plan de acción | 10 % |
| Presentación | Claridad, participación y respuestas a preguntas | 10 % |
| **Total** | | **100 %** |

Un trabajo sólido conecta cada conclusión con la evidencia examinada, reconoce sus límites y propone acciones que responden al resultado. La duración es una guía, no una penalización automática.

## Lista de revisión antes de entregar

- ¿El caso y el riesgo se pueden relacionar con los entregables anteriores?
- ¿El objetivo y el alcance indican qué se revisó y qué quedó fuera?
- ¿El criterio tiene una fuente identificada o se declara ficticio?
- ¿La prueba explica población, muestra, procedimiento, evidencia y resultado?
- ¿Las afirmaciones distinguen hechos, supuestos y simulaciones?
- ¿Cada hallazgo tiene soporte y la causa se presenta como pendiente si no se comprobó?
- ¿Las acciones tienen responsables y plazos propuestos, y una forma de verificar el cierre?
- ¿El informe y los enlaces del repositorio son accesibles?
