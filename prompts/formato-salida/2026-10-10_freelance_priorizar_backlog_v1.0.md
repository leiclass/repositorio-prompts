# Clasificación y priorización de backlog diario de desarrollo web

- **Patrón:** Output Automater / Formato de salida
- **Ámbito:** freelance / desarrollo web
- **Versión:** 1.0 · **Creada:** 2026-10-10
- **Etiquetas:** #freelance #formato-salida #estructurado

## Situación laboral

Organización y priorización de backlog diario de tareas

## Objetivo

Ordenar solicitudes dispersas en una matriz de priorización limpia y categorizada.

## Contexto

Trabajo como desarrollador freelance y recibo múltiples mensajes, correos y peticiones sin jerarquía.

## Prompt

```text
Actúa como Gestor de Proyectos de Software. Procesa el listado adjunto y clasifica las tareas devolviendo la respuesta estrictamente con esta estructura:
## 🚨 1. URGENTES E IMPORTANTES (Resolver Hoy)
- {cliente} - {tarea}: {justificacion_impacto}
## 📅 2. IMPORTANTES NO URGENTES (Programar esta semana)
- {cliente} - {tarea}: {estimacion_tiempo}
## 💬 3. REQUIERE MÁS INFORMACIÓN DEL CLIENTE
- {cliente} - {pregunta_o_dato_faltante}
```

## Variables

{listado_solicitudes_sucio}

## Métricas

≤ 1 iteración, lectura y priorización en < 60 segundos.

## Resultado esperado

Una matriz de priorización clara y categorizada que permite saber exactamente qué programar hoy, qué agendar para la semana y a qué clientes pedir más detalles antes de empezar.

## Changelog

- **v1.0** (2026-10-10) — versión inicial, Hands-on 4 del Módulo 2.
