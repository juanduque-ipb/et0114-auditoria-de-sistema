# Guía: cómo construir la matriz inicial de riesgos

Esta guía acompaña el taller de la sesión 7. Úsala para transformar el caso del primer trabajo en una matriz de riesgos de sistemas.

## 1. Conserva el caso del primer taller

No empieces desde cero. Mantén la organización y el sistema que ya analizaste. Tus marcos de referencia siguen siendo útiles porque ayudan a decidir qué prácticas o controles esperas encontrar.

Ejemplo de continuidad:

> En el primer taller, el equipo eligió una tienda en línea y propuso ISO/IEC 27001 para revisar la protección de los datos de clientes. En este taller, el equipo analiza el proceso de administración de cuentas del panel administrativo.

## 2. Elige un activo o proceso concreto

Un análisis útil empieza con un objeto específico.

| Formulación débil | Formulación útil |
|---|---|
| “La seguridad de la tienda” | “Las cuentas administrativas del panel de pedidos” |
| “La plataforma de la universidad” | “El módulo donde se asignan y retiran roles de docentes” |
| “Los datos de la clínica” | “Las historias clínicas consultadas desde urgencias” |

## 3. Separa amenaza, vulnerabilidad y riesgo

| Concepto | Pregunta que ayuda | Ejemplo: plataforma académica |
|---|---|---|
| Activo | ¿Qué necesita protección? | Calificaciones y datos académicos |
| Amenaza | ¿Quién o qué puede afectarlo? | Un docente retirado usa una cuenta que sigue habilitada |
| Vulnerabilidad | ¿Qué debilidad lo permite? | No se revisan los accesos al terminar un contrato |
| Riesgo | ¿Qué podría ocurrir y qué consecuencia tendría? | Consulta o modificación no autorizada de calificaciones |
| Control | ¿Qué reduce la probabilidad o el impacto? | Baja de cuenta ligada al proceso de terminación y revisión mensual de roles |

Una amenaza no es una vulnerabilidad:

- Incorrecto: “El atacante es la vulnerabilidad”.
- Correcto: “El atacante intenta explotar una cuenta activa que no fue retirada”.

## 4. Redacta el riesgo como una situación posible

Una frase vaga no permite analizar ni proponer un control.

| Redacción débil | Redacción útil |
|---|---|
| “Hay riesgo de seguridad” | “Un excolaborador podría consultar o modificar pedidos porque su cuenta administrativa sigue activa después de su retiro” |
| “La base de datos es vulnerable” | “La información de clientes podría quedar expuesta porque el respaldo se almacena sin controles de acceso definidos” |

La redacción útil conecta tres ideas: el evento posible, la vulnerabilidad y la consecuencia.

## 5. Asigna probabilidad e impacto

No hay una cifra universalmente correcta. Justifica los valores con lo que sabes del caso y con los supuestos que declares.

Ejemplo:

- **Probabilidad: 4.** El proceso no tiene una revisión formal de bajas y el equipo sabe que existen cuentas activas de personas retiradas.
- **Impacto: 4.** Una cuenta con rol administrativo puede consultar o modificar información académica sensible.
- **Nivel de riesgo: 16.** `4 × 4`.

## 6. Propón un control que responda a la vulnerabilidad

| Vulnerabilidad | Control insuficiente | Control verificable |
|---|---|---|
| Cuentas activas después del retiro | “Mejorar la seguridad” | “Desactivar la cuenta cuando termina el contrato y revisar mensualmente las cuentas con rol administrativo” |
| No se conocen cambios realizados | “Tener más cuidado” | “Registrar los cambios de calificaciones y revisar semanalmente los cambios ejecutados por roles administrativos” |
| Respaldos accesibles para cualquier usuario | “Proteger los respaldos” | “Limitar el acceso al repositorio de respaldos a un grupo autorizado y revisar sus permisos cada trimestre” |

Un control puede ser preventivo, detectivo o correctivo:

- **Preventivo:** intenta impedir el incidente.
- **Detectivo:** ayuda a encontrar el incidente o una desviación.
- **Correctivo:** ayuda a recuperar el servicio o limitar el daño.

## 7. Modelo de una fila de matriz

| ID | Activo o proceso | Amenaza | Vulnerabilidad | Riesgo | Prob. | Impacto | Nivel | Control actual o evidencia | Control propuesto | Justificación |
|---|---|---|---|---|---:|---:|---:|---|---|---|
| R-01 | Módulo de calificaciones | Uso indebido de una cuenta de un docente retirado | No existe revisión de accesos al terminar contratos | Un docente retirado podría consultar o modificar calificaciones porque conserva su cuenta activa | 4 | 4 | 16 | El equipo no encontró un registro de revisión mensual de roles | Baja de cuenta ligada al proceso de terminación y revisión mensual de roles | La cuenta conserva acceso a datos sensibles y la baja depende de una gestión manual |

## 8. Plantilla para tu documento

```md
# Matriz inicial de riesgos

**Integrantes:**
- Nombre completo
- Nombre completo

## Caso y contexto actualizado

Escribe de tres a cinco líneas.

## Supuestos

- Declara aquí la información que no pudiste verificar directamente.

## Matriz de riesgos

| ID | Activo o proceso | Amenaza | Vulnerabilidad | Riesgo | Prob. | Impacto | Nivel | Control actual o evidencia | Control propuesto | Justificación |
|---|---|---|---|---|---:|---:|---:|---|---|---|
| R-01 |  |  |  |  |  |  |  |  |  |  |
| R-02 |  |  |  |  |  |  |  |  |  |  |
| R-03 |  |  |  |  |  |  |  |  |  |  |
| R-04 |  |  |  |  |  |  |  |  |  |  |
| R-05 |  |  |  |  |  |  |  |  |  |  |
```

## Errores frecuentes

- Copiar riesgos genéricos de internet sin relacionarlos con el caso.
- Llamar “vulnerabilidad” a una amenaza o a una persona.
- Escribir controles genéricos que nadie podría comprobar.
- Asignar valores de probabilidad e impacto sin explicarlos.
- Inventar que una organización tiene una falla real. Si no puedes comprobarlo, formula el caso como supuesto.
