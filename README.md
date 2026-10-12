# Repositorio de prompts

Banco personal de prompts reutilizables para tareas de trabajo freelance en desarrollo web.
Nació del Hands-on 4 del Módulo 2 de la carrera **Consultor IA** (clase del 2026-10-10).

## Para qué existe

Dejar de reescribir desde cero los prompts de tareas que se repiten semana a semana
—priorizar el backlog, responder reclamos, presupuestar, reportar mantenimiento— y tener
una versión probada lista para copiar y pegar.

**Alcance:** uso personal, repositorio público. Sin datos de clientes ni credenciales:
todo dato sensible va entre `{llaves}` como variable.

## Índice maestro

| Prompt | Patrón | Situación | Estado |
| --- | --- | --- | --- |
| [Clasificación y priorización de backlog diario de desarrollo web](prompts/formato-salida/2026-10-10_freelance_priorizar_backlog_v1.0.md) | Output Automater / Formato de salida | Organización y priorización de backlog diario de tareas | ✅ Validado |
| [Respuesta diplomática y asertiva ante reclamo por caída o error web](prompts/persona/2026-10-10_freelance_responder_reclamo_v1.0.md) | Persona | Respuesta formal y profesional ante un reclamo o urgencia de un cliente | ✅ Validado |
| [Entrevista guiada para cálculo y actualización de tarifa hora en ARS](prompts/flipped-interaction/2026-10-10_freelance_calcular_tarifa_hora_v1.0.md) | Flipped Interaction | Cálculo dinámico y actualización de tarifa hora (Contexto Argentina) | ✅ Validado |
| [Propuesta comercial y presupuesto formal para desarrollo web](prompts/combinados/2026-10-10_freelance_generar_presupuesto_v1.0.md) | Persona + Output Automater + Restricciones | Elaboración y presentación de presupuesto para un nuevo proyecto web | ✅ Validado |
| [Generación estandarizada de reporte de mantenimiento mensual](prompts/few-shot/2026-10-10_freelance_reporte_mantenimiento_v1.0.md) | Few-shot | Redacción estandarizada de reporte mensual de mantenimiento web | ✅ Validado |

## Estructura

```
prompts/
├── formato-salida/        salida con estructura fija y obligatoria
├── persona/               la IA responde desde un rol profesional
├── flipped-interaction/   la IA pregunta primero, responde después
├── combinados/            varios patrones en un prompt extenso
└── few-shot/              se le da un ejemplo para que lo clone
templates/
└── ficha-prompt.md        plantilla en blanco para sumar prompts nuevos
```

## Convención de nombres

```
AAAA-MM-DD_ámbito_acción_descriptor_vX.Y.md
```

Ejemplo: `2026-10-10_freelance_priorizar_backlog_v1.0.md`

## Cómo se usa

1. Buscá la situación en el índice maestro.
2. Abrí la ficha y copiá el bloque **Prompt**.
3. Reemplazá las `{variables}` por los datos reales.
4. Si tuviste que corregir el prompt para que funcionara, actualizá la ficha y subí la versión.

## Checklist de calidad

Antes de dar un prompt por validado: claridad · completitud · robustez · verificabilidad · eficiencia.

---

Inspirado en el repo del docente Mariano Gobea Alcoba:
<https://github.com/Mgobeaalcoba/prompt-engineering-repo>
