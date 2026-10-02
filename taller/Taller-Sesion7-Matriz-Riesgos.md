# Taller: matriz inicial de riesgos de sistemas

**Auditoría de Sistemas (ET0114) · Sesión 7 · Matriz de análisis de riesgos**  
**Docente:** Juan Duque  
**Fecha de entrega:** viernes 9 de octubre de 2026

## Objetivo

Vas a continuar el caso del primer taller. Después de elegir los marcos de referencia y la evidencia inicial, ahora identificarás los riesgos del sistema u organización elegidos y propondrás controles verificables.

El propósito no es encontrar todos los riesgos posibles. Es construir una primera matriz clara, coherente y defendible.

## Punto de partida

Trabaja con el mismo equipo y el mismo caso del primer taller. Si necesitas cambiar de caso, explica la razón en una nota breve al inicio del documento.

Recupera del primer taller:

- La organización o sistema elegido.
- El contexto y la preocupación principal.
- Los marcos de referencia seleccionados.
- La evidencia que propusiste solicitar.

## Instrucciones

1. **Actualiza el contexto del caso** en máximo cinco líneas. Identifica el sistema o proceso que analizarás en esta entrega. No escribas “todo el sistema” ni “la seguridad de la empresa”.

2. **Identifica al menos cinco activos o procesos concretos.** Un activo puede ser información, una aplicación, infraestructura o un proceso importante. Ejemplos: historias clínicas, base de datos de clientes, proceso de bajas de usuarios, plataforma de calificaciones.

3. **Construye una matriz con mínimo cinco riesgos.** Cada fila debe incluir:

   - Activo o proceso afectado.
   - Amenaza.
   - Vulnerabilidad.
   - Riesgo redactado como una situación posible y su consecuencia.
   - Probabilidad, de 1 a 5.
   - Impacto, de 1 a 5.
   - Nivel de riesgo, calculado como `probabilidad × impacto`.
   - Control actual o evidencia de que no existe.
   - Control propuesto.
   - Justificación breve de la prioridad.

4. **Diferencia los conceptos.** La amenaza no es la vulnerabilidad. Por ejemplo, un excolaborador que intenta ingresar es una amenaza. Una cuenta que sigue activa después del retiro es una vulnerabilidad.

5. **Propón controles concretos y verificables.** Evita controles como “mejorar la seguridad”. Es mejor proponer “desactivar automáticamente las cuentas cuando termina el contrato y revisar cada mes las cuentas activas sin contrato vigente”.

6. **Declara los supuestos.** Si no tienes acceso a información real de la organización, puedes trabajar con supuestos razonables. Indícalos claramente y no presentes suposiciones como hechos comprobados.

## Escala sugerida

| Valor | Probabilidad | Impacto |
|---|---|---|
| 1 | Raro | Consecuencia menor y fácil de corregir |
| 2 | Poco probable | Afecta una operación limitada |
| 3 | Posible | Afecta un proceso relevante o varios usuarios |
| 4 | Probable | Interrumpe un servicio importante o expone información sensible |
| 5 | Muy probable | Puede afectar gravemente la operación, datos críticos o cumplimiento |

Usa el resultado de `probabilidad × impacto` para ordenar los riesgos. Justifica los valores con el contexto de tu caso; no basta con asignar números.

## Formato de entrega

- Documento en **Markdown (`.md`)**, máximo cinco páginas equivalentes.
- Debe subirse al mismo repositorio usado para el primer taller.
- Incluye al inicio los nombres completos de cada integrante.
- Incluye el contexto actualizado, los supuestos y la matriz de riesgos.
- La matriz puede construirse como tabla Markdown. Si queda muy ancha, puedes usar una tabla por riesgo.
- Comparte el enlace al repositorio en el canal definido en clase.

## Criterios de evaluación

| Criterio | Qué se evalúa |
|---|---|
| Continuidad del caso | El análisis usa el caso del primer taller y conserva coherencia con los marcos elegidos |
| Identificación de activos y riesgos | Los activos, procesos y riesgos son concretos y relevantes para la organización |
| Diferenciación conceptual | Amenaza, vulnerabilidad, riesgo y control están correctamente diferenciados |
| Priorización | Probabilidad e impacto tienen una justificación coherente con el caso |
| Controles y evidencia | Los controles propuestos son verificables y se relacionan con la vulnerabilidad identificada |
| Claridad y trazabilidad | La matriz se entiende, declara supuestos y permite seguir el razonamiento de cada fila |

## Antes de entregar

- ¿Cada riesgo se relaciona con un activo o proceso específico?
- ¿La amenaza y la vulnerabilidad son diferentes?
- ¿El riesgo explica qué podría pasar y cuál sería su consecuencia?
- ¿El control propuesto reduce una vulnerabilidad concreta?
- ¿Los valores de probabilidad e impacto tienen una justificación?

Consulta la [guía para construir la matriz](Guia-Sesion7-Matriz-Riesgos.md) antes de empezar.
