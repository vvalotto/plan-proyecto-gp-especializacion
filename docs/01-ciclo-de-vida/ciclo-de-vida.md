# 🔄 Ciclo de Vida del Proyecto

## Enfoque seleccionado

> **[COMPLETAR: Predictivo / Adaptativo / Híbrido]**

## Justificación de la elección

> [COMPLETAR: explicar por qué este enfoque es el más adecuado considerando estabilidad de los requisitos, complejidad, tamaño y experiencia del equipo, tolerancia al cambio, posibilidad de entregas incrementales, restricciones del entorno, etc.]

## Árbol de decisión

```mermaid
flowchart TD
    A{{"¿Los requisitos\nson estables?"}}
    B{{"¿El equipo tiene\nexperiencia en ágil?"}}
    C{{"¿El entorno admite\nentregas incrementales?"}}

    A -- Sí --> P["✅ Predictivo\n(Cascada)"]
    A -- No --> B
    B -- Sí --> D["✅ Adaptativo\n(Scrum / Kanban)"]
    B -- No --> C
    C -- Sí --> H["✅ Híbrido"]
    C -- No --> P

    style P fill:#BDD7EE,stroke:#2E75B6
    style D fill:#C8E6C9,stroke:#2E7D32
    style H fill:#FFF9C4,stroke:#F9A825
```

> **Decisión del equipo:** [COMPLETAR: indicar qué rama aplica al proyecto y por qué]

## Fases del proyecto

```mermaid
flowchart LR
    F1["📌 Fase 1\n[COMPLETAR]"]
    F2["📌 Fase 2\n[COMPLETAR]"]
    F3["📌 Fase 3\n[COMPLETAR]"]
    F4["📌 Fase 4\n[COMPLETAR]"]

    F1 --> F2 --> F3 --> F4
```

| Fase | Nombre | Objetivo | Criterio de salida |
|------|--------|----------|-------------------|
| 1 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| 2 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| 3 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| 4 | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |

## Adaptación del enfoque (tailoring)

> [COMPLETAR: qué prácticas de otros enfoques se incorporan y por qué (por ejemplo, revisiones iterativas dentro de un marco predictivo).]

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
