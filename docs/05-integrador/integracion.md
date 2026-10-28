# 🔗 Gestión de la Integración

## Ciclo de vida y plan de gestión

> Resumen de [`ciclo-de-vida.md`](../01-ciclo-de-vida/ciclo-de-vida.md) y [`plan-gestion.md`](../04-acta-plan-gestion/plan-gestion.md): [COMPLETAR]

## Ejecución, monitoreo y control

| Reunión / mecanismo | Objetivo | Frecuencia | Participantes | Salida |
|---------------------|----------|:----------:|---------------|--------|
| Seguimiento | [COMPLETAR] | Semanal | [COMPLETAR] | [COMPLETAR] |
| Revisión de hito | [COMPLETAR] | Por hito | [COMPLETAR] | [COMPLETAR] |

## Control integrado de cambios

```mermaid
flowchart TD
    A(["📝 Solicitud de Cambio\nCualquier interesado"]) --> B["Completar\nFormulario de Cambio"]
    B --> C["Director de Proyecto\nRevisa la solicitud"]
    C --> D{{"¿Impacto\nsignificativo?"}}

    D -- "Bajo impacto\n(≤ X días / ≤ $Y)" --> E["Director aprueba\ndirectamente"]
    D -- "Alto impacto\n(> X días / > $Y)" --> F["Comité de Cambios\nevalúa el impacto"]

    F --> G{{"¿Aprobado?"}}
    G -- Sí --> H["✅ Cambio aprobado\nActualizar plan y líneas base"]
    G -- No --> I["❌ Rechazado\nNotificar solicitante"]

    E --> H
    H --> J["Comunicar al\nequipo afectado"]
    J --> L(["📋 Registro de\ncambios actualizado"])
    I --> L
```

### Roles

| Rol | Persona | Responsabilidad |
|-----|---------|----------------|
| Solicitante | Cualquier interesado | Completar el formulario de cambio |
| Evaluador inicial | [COMPLETAR — Director de Proyecto] | Analizar impacto y urgencia |
| Comité de Cambios | [COMPLETAR] | Aprobar cambios de alto impacto |
| Implementador | [COMPLETAR] | Ejecutar el cambio aprobado |

### Criterios de aprobación

| Criterio | Aprobación directa (Director) | Requiere Comité |
|----------|:-----------------------------:|:---------------:|
| Impacto en cronograma | ≤ [X] días | > [X] días |
| Impacto en presupuesto | ≤ $[Y] | > $[Y] |
| Cambio en alcance o línea base | No afecta entregables | Afecta entregables |
| Urgencia | Normal | Crítico |

### Registro de cambios

> Ver plantilla: [`formulario-cambio.md`](../../plantillas/formulario-cambio.md)

| # | Fecha | Descripción del cambio | Solicitante | Estado | Impacto |
|---|-------|------------------------|------------|:------:|---------|
| CC-001 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [Aprobado/Rechazado/En análisis] | [COMPLETAR] |

## Cambios respecto de entregas previas

| Artefacto | Cambio realizado | Motivo | Formulario |
|-----------|------------------|--------|:----------:|
| [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [CC-00X] |

## Cierre del proyecto o de fase

| Actividad de cierre | Responsable | Evidencia |
|--------------------|-------------|-----------|
| Verificar entregables aceptados | [COMPLETAR] | [COMPLETAR] |
| Cierre de adquisiciones | [COMPLETAR] | [COMPLETAR] |
| Archivo de documentación | [COMPLETAR] | [COMPLETAR] |
| Liberación de recursos | [COMPLETAR] | [COMPLETAR] |

### Lecciones aprendidas

| Qué funcionó | Qué no funcionó | Recomendación |
|--------------|-----------------|---------------|
| [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
