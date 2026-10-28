# ⏱️ Gestión del Tiempo

> Consolida el trabajo de [`02-edt-estimacion/`](../02-edt-estimacion/) y lo lleva a una **línea base de cronograma**.

## Cronograma consolidado

```mermaid
gantt
    title Línea base - Nombre del Proyecto
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section Fase 1
    Paquete 1.1             :a1, 2027-03-01, 5d
    Paquete 1.2             :a2, after a1, 7d
    Hito 1                  :milestone, m1, after a2, 0d

    section Fase 2
    Paquete 2.1             :b1, after m1, 10d
    Reserva de contingencia :crit, b2, after b1, 4d
    Hito final              :milestone, m2, after b2, 0d
```

## Hitos

| Hito | Descripción | Fecha línea base | Criterio |
|------|-------------|:----------------:|----------|
| M1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| M2 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |

## Ruta crítica y holguras

> [COMPLETAR: ruta crítica del proyecto y tareas con menor holgura. Referenciar `red-de-tareas.md`.]

## Optimización del cronograma

> [COMPLETAR: si fue necesario comprimir (paralelizar, reasignar recursos), qué se hizo y qué riesgo se agregó.]

## Control del cronograma

| Indicador | Cómo se calcula | Umbral | Acción |
|-----------|-----------------|:------:|--------|
| Desvío de hitos | Fecha real − fecha línea base | > [X] días | [COMPLETAR] |
| % de avance | Paquetes completos / total | [COMPLETAR] | [COMPLETAR] |

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
