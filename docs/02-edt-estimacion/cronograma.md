# 📅 Cronograma del Proyecto

## Diagrama de Gantt

```mermaid
gantt
    title Cronograma - Nombre del Proyecto
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section Fase 1 - Nombre
    Tarea 1.1               :t11, 2027-03-01, 5d
    Tarea 1.2               :t12, after t11, 7d
    Hito - Fin Fase 1       :milestone, m1, after t12, 0d

    section Fase 2 - Nombre
    Tarea 2.1               :t21, after m1, 10d
    Tarea 2.2               :t22, after t21, 5d
    Hito - Fin Fase 2       :milestone, m2, after t22, 0d

    section Gestion
    Planificacion           :g1, 2027-03-01, 5d
    Seguimiento y Control   :g2, after g1, 30d
    Cierre                  :g3, after t22, 3d
```

> Las fechas del ejemplo son ilustrativas: usar las fechas previstas del proyecto, no las del curso.

## Tabla de tareas

| ID | Tarea | Predecesoras | Responsable | Duración (d) | Inicio | Fin | Hito |
|----|-------|-------------|------------|:------------:|--------|-----|:----:|
| 1.1 | [COMPLETAR] | — | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | No |
| 1.2 | [COMPLETAR] | 1.1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | No |
| M1 | 🏁 Fin Fase 1 | 1.2 | — | 0 | [COMPLETAR] | [COMPLETAR] | **Sí** |
| 2.1 | [COMPLETAR] | M1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | No |
| 2.2 | [COMPLETAR] | 2.1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | No |
| M2 | 🏁 Fin Fase 2 | 2.2 | — | 0 | [COMPLETAR] | [COMPLETAR] | **Sí** |

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
