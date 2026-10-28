# 🕸️ Red de Tareas y Ruta Crítica

## Diagrama de dependencias

```mermaid
flowchart LR
    INI(["Inicio"]) --> T11["1.1\n[Tarea]\n5d"]
    T11 --> T12["1.2\n[Tarea]\n7d"]
    T11 --> T21["2.1\n[Tarea]\n10d"]
    T12 --> T31["3.1\n[Tarea]\n6d"]
    T21 --> T31
    T31 --> FIN(["Fin"])

    style T11 fill:#FFCDD2,stroke:#C62828
    style T21 fill:#FFCDD2,stroke:#C62828
    style T31 fill:#FFCDD2,stroke:#C62828
```

> Los nodos en rojo representan la **ruta crítica** (reemplazar según el cálculo propio).

## Tabla de precedencias

| ID | Tarea | Duración (d) | Predecesoras | Inicio temprano | Fin temprano | Holgura |
|----|-------|:------------:|--------------|:---------------:|:------------:|:-------:|
| 1.1 | [COMPLETAR] | [COMPLETAR] | — | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| 1.2 | [COMPLETAR] | [COMPLETAR] | 1.1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| 2.1 | [COMPLETAR] | [COMPLETAR] | 1.1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| 3.1 | [COMPLETAR] | [COMPLETAR] | 1.2, 2.1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |

**Ruta crítica:** [COMPLETAR: secuencia de tareas con holgura 0]
**Duración total:** [COMPLETAR] días

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
