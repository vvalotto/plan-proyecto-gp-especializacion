# 👥 Matriz RACI

> **R** = Responsable (ejecuta) · **A** = Aprobador (único por paquete) · **C** = Consultado · **I** = Informado
> Los roles provienen de [`organizacion.md`](../01-ciclo-de-vida/organizacion.md) y los paquetes de [`edt.md`](../02-edt-estimacion/edt.md).

## Matriz

| ID (EDT) | Paquete de trabajo | [Rol 1] | [Rol 2] | [Rol 3] | [Rol 4] | [Rol 5] |
|----------|--------------------|:-------:|:-------:|:-------:|:-------:|:-------:|
| 1.1 | [COMPLETAR] | A | R | I | I | I |
| 1.2 | [COMPLETAR] | A | R | C | I | I |
| 2.1 | [COMPLETAR] | A | C | R | I | I |
| 2.2 | [COMPLETAR] | A | I | R | R | C |
| 3.1 | [COMPLETAR] | A | C | R | R | I |

> ⚠️ **Verificación obligatoria:** cada fila debe tener exactamente **1 A** y al menos **1 R**.

## Análisis de carga de responsabilidades

```mermaid
xychart-beta
    title "Cantidad de paquetes por rol (R + A)"
    x-axis ["Rol 1", "Rol 2", "Rol 3", "Rol 4", "Rol 5"]
    y-axis "Nº de paquetes" 0 --> 10
    bar [4, 5, 6, 3, 2]
```

> [COMPLETAR: analizar roles sobrecargados o con pocas responsabilidades y cómo se equilibra.]

## Asignación y dedicación

| Integrante | Rol | Dedicación (%) | Período | Observaciones |
|-----------|-----|:--------------:|---------|---------------|
| [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |
| [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] |

## Ajustes al cronograma

> [COMPLETAR: si la carga o la dedicación obligan a cambiar duraciones o secuencia, indicar qué se modificó en `cronograma.md` y por qué.]

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
