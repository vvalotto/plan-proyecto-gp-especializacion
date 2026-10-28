# 📋 Template — Plan de Proyecto (Especialización)

> **Gestión de Proyectos · Especializaciones en Sistemas Embebidos y en Diseño y Desarrollo de Productos · FIUNER · 2026**
> Basado en los **principios y dominios de desempeño del PMBOK v7**

---

## ¿Qué es este repositorio?

Es una **plantilla de trabajo** para desarrollar, de forma incremental, el **plan del proyecto** de diseño y desarrollo (D&D) de un producto elegido por el equipo (equipos de **5 a 6 integrantes**).

Los artefactos se construyen a lo largo de las 7 semanas del curso:

- **5 tareas grupales** semanales (carpetas `00` a `04`).
- **1 presentación PechaKucha** del plan (carpeta `05`): 20 diapositivas × 20 segundos.

No hay un plan escrito integrado: la presentación sintetiza lo trabajado en las cinco tareas. Los temas de riesgos, calidad, configuración, alcance y cambios se trabajan en las clases y en los cuestionarios de Moodle.

Cada archivo incluye instrucciones, tablas y diagramas en formato [Mermaid](https://mermaid.js.org/) listos para completar.

---

## 🚀 ¿Cómo usar este template?

1. Crear un repositorio propio a partir de este template (botón **Use this template** en GitHub).
2. Completar los datos del equipo en [`docs/00-equipo-y-proyecto/equipo.md`](docs/00-equipo-y-proyecto/equipo.md).
3. Elegir el proyecto y formular la propuesta de valor en [`docs/00-equipo-y-proyecto/proyecto-y-propuesta-de-valor.md`](docs/00-equipo-y-proyecto/proyecto-y-propuesta-de-valor.md).
4. Trabajar cada carpeta en la semana indicada en el cronograma.
5. Llegar a la clase síncrona indicada con la tarea lista para la discusión entre pares.

---

## 📂 Estructura del repositorio

```
plan-proyecto-gp-especializacion/
├── README.md                              ← Este archivo
│
├── docs/
│   ├── 00-equipo-y-proyecto/              ← Tarea 1: equipo, proyecto y propuesta de valor
│   ├── 01-ciclo-de-vida/                  ← Tarea 2: ciclo de vida, estructura del equipo y entregables
│   ├── 02-edt-estimacion/                 ← Tarea 3: EDT y estimaciones
│   ├── 03-raci/                           ← Tarea 4: matriz RACI
│   ├── 04-comunicaciones-metricas/        ← Tarea 5: interesados, comunicaciones y OKR/indicadores
│   └── 05-pechakucha/                     ← Presentación PechaKucha
│
└── plantillas/
    ├── acta-reunion.md                    ← Acta de reunión
    └── checklist-entrega.md               ← Verificación previa a cada entrega
```

---

## 📅 Cronograma de actividades

| # | Tarea | Carpeta | Semana de trabajo | Discusión entre pares (clase síncrona, jueves) |
|---|-------|---------|-------------------|------------------------------------------------|
| 1 | Proyecto y propuesta de valor | `00-equipo-y-proyecto/` | 28 de octubre al 3 de noviembre | Semana 2 |
| 2 | Ciclo de vida, estructura del equipo y entregables | `01-ciclo-de-vida/` | 4 al 10 de noviembre | Semana 3 |
| 3 | EDT y estimaciones | `02-edt-estimacion/` | 11 al 17 de noviembre | Semana 4 |
| 4 | Matriz RACI | `03-raci/` | 18 al 24 de noviembre | Semana 6 (junto con la Tarea 5) |
| 5 | Comunicaciones, métricas e indicadores | `04-comunicaciones-metricas/` | 25 de noviembre al 1 de diciembre | Semana 6 (junto con la Tarea 4) |
| 6 | PechaKucha del plan de proyecto | `05-pechakucha/` | Preparación: 2 al 8 de diciembre | Presentación: semana 7 (9 al 15 de diciembre) |

> La discusión entre pares se hace en la clase síncrona de la semana siguiente a la de trabajo, en salas de 2 o 3 equipos. La clase de la semana 5 se dedica a OKR, por eso las Tareas 4 y 5 se discuten juntas en la semana 6.
> Las **fechas límite de entrega** exactas se publican en el cronograma de Moodle y en el foro de novedades. Este template solo indica la semana de trabajo.

---

## 🎯 Evaluación

| Componente | Peso | Dónde se evidencia |
|-----------|:----:|--------------------|
| Desempeño semanal | 40 % | Cuestionarios, foros y participación en las discusiones (Moodle y clases; no se entrega en este repo) |
| Tareas 1 a 5 | 30 % (6 % cada una) | Carpetas `00` a `04` |
| PechaKucha | 30 % | Carpeta `05` |

La nota mínima para aprobar es **60 %**. Las tareas y la presentación se evalúan con una rúbrica de tres niveles: **I** (insuficiente, 40 %), **A** (adecuado, 70 %) y **S** (sobresaliente, 100 %).

---

## 🧭 Marco de referencia: PMBOK 7

| Tarea | Dominio(s) de desempeño PMBOK 7 | Dónde se trabaja |
|-------|---------------------------------|------------------|
| 1 · Proyecto y propuesta de valor | Interesados · Planificación | `00` |
| 2 · Ciclo de vida, equipo y entregables | Enfoque de desarrollo y ciclo de vida · Equipo · Entrega | `01` |
| 3 · EDT y estimaciones | Planificación · Trabajo del proyecto | `02` |
| 4 · RACI | Equipo · Planificación | `03` |
| 5 · Comunicaciones, métricas e indicadores | Interesados · Medición | `04` |

Los **12 principios** del PMBOK 7 se aplican de forma transversal y se discuten en las clases.

---

## 🧱 Convenciones del template

- Los bloques `[COMPLETAR: ...]` indican dónde el equipo debe ingresar información.
- Los diagramas Mermaid tienen la **estructura** correcta; solo hay que reemplazar los datos de ejemplo.
- Cada carpeta tiene un `README.md` con el objetivo, los archivos y los criterios de evaluación de la entrega.
- Las tareas **se encadenan**: los entregables y la estructura del equipo (Tarea 2) alimentan la EDT (Tarea 3) y la RACI (Tarea 4); los indicadores (Tarea 5) se apoyan en la EDT y el cronograma. Si algo cambia, se actualiza en su carpeta de origen.
- El proyecto lo elige el equipo en la Tarea 1 (de una asignatura anterior, de la práctica profesional o del Trabajo Final Integrador). El producto no se rediseña: se **planifica**.

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
