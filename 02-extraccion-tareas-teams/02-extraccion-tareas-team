# Extracción automática de tareas desde transcripciones de Teams

## Objetivo
Automatizar la identificación de acuerdos y tareas a partir de una transcripción de reunión.

## Problema de negocio
Después de una reunión, las tareas suelen quedar en texto libre y se pierden responsables, fechas límite o evidencias. Esta solución estructura automáticamente los compromisos.

## Entrada
Transcripción de una reunión de Teams.

## Salida esperada
JSON con:
- participantes
- tareas
- responsable
- correo del responsable
- fecha límite
- evidencia textual

## Herramientas usadas
- Microsoft Teams
- Power Automate
- Copilot Studio / LLM
- Planner
- JSON Schema

## Ejemplo de salida

```json
{
  "participantes": [
    {
      "nombre": "Ana"
    }
  ],
  "tareas": [
    {
      "titulo": "Enviar reporte semanal",
      "responsable": "Ana",
      "correoResponsable": "ana@empresa.com",
      "fechaLimite": "2026-06-10",
      "evidencia": "Ana comentó que enviará el reporte el miércoles"
    }
  ]
}
