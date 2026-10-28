# 📋 Template — Plan de Proyecto Integrador (Especialización)

> **Gestión de Proyectos · Especializaciones en Sistemas Embebidos y en Diseño y Desarrollo de Productos Médicos · FIUNER · 2026**
> Basado en los **principios y dominios de desempeño del PMBOK v7**

---

## ¿Qué es este repositorio?

Es una **plantilla de trabajo** para desarrollar, de forma incremental, el **Plan de Proyecto** del proyecto de diseño y desarrollo (D&D) de un producto elegido en las asignaturas anteriores de la especialización.

Los artefactos se construyen a lo largo de las 7 semanas del curso:

- **5 actividades grupales** (carpetas `01` a `05`), que son el insumo del trabajo final.
- **1 trabajo integrador final** (carpeta `06`), que consolida y profundiza el plan en siete áreas.
- **1 presentación final** del trabajo integrador (carpeta `07`).

Cada archivo incluye instrucciones, tablas y diagramas en formato [Mermaid](https://mermaid.js.org/) listos para completar.

---

## 🚀 ¿Cómo usar este template?

1. Crear un repositorio propio a partir de este template (botón **Use this template** en GitHub).
2. Completar los datos del equipo en [`docs/00-proyecto-y-equipo/equipo.md`](docs/00-proyecto-y-equipo/equipo.md).
3. Describir el proyecto base en [`docs/00-proyecto-y-equipo/proyecto-base.md`](docs/00-proyecto-y-equipo/proyecto-base.md).
4. Trabajar cada carpeta en la semana indicada en el cronograma.

---

## 📂 Estructura del repositorio

```
plan-proyecto-gp-especializacion/
├── README.md                              ← Este archivo
├── plan-proyecto.md                       ← Plan maestro consolidado
│
├── docs/
│   ├── 00-proyecto-y-equipo/              ← Proyecto base y datos del equipo
│   ├── 01-ciclo-de-vida/                  ← Actividad 1 (grupal)
│   ├── 02-edt-estimacion/                 ← Actividad 2 (grupal)
│   ├── 03-interesados-raci/               ← Actividad 3 (grupal)
│   ├── 04-gestion-riesgos/                ← Actividad 4 (grupal)
│   ├── 05-plan-comunicaciones/            ← Actividad 5 (grupal)
│   ├── 06-integrador/                     ← Trabajo integrador final
│   └── 07-presentacion/                   ← Presentación del integrador
│
└── plantillas/
    ├── formulario-cambio.md               ← Solicitud de cambio
    ├── acta-reunion.md                    ← Acta de reunión
    └── checklist-entrega.md               ← Verificación previa a cada entrega
```

---

## 📅 Cronograma de actividades

| # | Actividad | Carpeta | Semana de trabajo | Clase síncrona (jueves) |
|---|-----------|---------|-------------------|-------------------------|
| 1 | Selección del ciclo de vida | `01-ciclo-de-vida/` | 4 al 10 de noviembre | Unidad 2 |
| 2 | EDT y estimación de tiempos | `02-edt-estimacion/` | 11 al 17 de noviembre | Unidad 3 |
| 3 | Registro de interesados, RACI y matriz de interesados | `03-interesados-raci/` | 18 al 24 de noviembre | Unidad 4 |
| 4 | Gestión de riesgos | `04-gestion-riesgos/` | 25 de noviembre al 1 de diciembre | OKR |
| 5 | Plan de comunicaciones | `05-plan-comunicaciones/` | [A CONFIRMAR] | [A CONFIRMAR] |
| 6 | Trabajo integrador (7 áreas) | `06-integrador/` | 2 al 8 de diciembre | Unidad 5 y recapitulación |
| 7 | Presentación del integrador | `07-presentacion/` | hasta el 15 de diciembre | Presentación |

> Las **fechas límite de entrega** exactas se publican en el cronograma de Moodle y en el foro de novedades. Este template solo indica la semana de trabajo.

---

## 🎯 Evaluación (según la planificación del curso)

| Componente | Peso | Dónde se evidencia |
|-----------|:----:|--------------------|
| Desempeño semanal | 40 % | Cuestionarios y foros (Moodle, no se entrega en este repo) |
| Trabajo grupal | 30 % | Carpetas `01` a `05` |
| Trabajo final | 30 % | Carpetas `06` y `07` |

La nota mínima para aprobar es **60 %**. Se evalúa también la presentación en tiempo y forma.

---

## 🧭 Marco de referencia: PMBOK 7

El programa del curso está organizado por unidades temáticas. Este template las vincula con los **dominios de desempeño** del PMBOK 7:

| Unidad del programa | Dominio(s) de desempeño PMBOK 7 | Dónde se trabaja |
|---------------------|---------------------------------|------------------|
| U1 · Introducción, ciclos de vida, metodologías | Enfoque de desarrollo y ciclo de vida | `01`, `06/integracion` |
| U2 · Alcance, EDT, tiempos, costos, estimación, requerimientos | Planificación · Entrega | `02`, `06/alcance`, `06/tiempos` |
| U3 · RRHH, comunicaciones, interesados | Equipo · Interesados | `03`, `05`, `06/interesados` |
| U4 · Calidad, adquisiciones, configuración, riesgos | Entrega · Trabajo del proyecto · Incertidumbre | `04`, `06/calidad`, `06/configuracion`, `06/riesgos` |
| U5 · Integración | Trabajo del proyecto · Medición | `06/integracion` |

Los **12 principios** del PMBOK 7 se aplican de forma transversal; la tabla para documentarlos está en [`integracion.md`](docs/06-integrador/integracion.md).

---

## 🧱 Convenciones del template

- Los bloques `[COMPLETAR: ...]` indican dónde el equipo debe ingresar información.
- Los diagramas Mermaid tienen la **estructura** correcta; solo hay que reemplazar los datos de ejemplo.
- Cada carpeta tiene un `README.md` con el objetivo, los archivos y los criterios de evaluación de la entrega.
- Los artefactos de las carpetas `01` a `05` **se reutilizan** en el integrador. Si cambian, se actualizan en su carpeta de origen y se registra el cambio (ver [`plantillas/formulario-cambio.md`](plantillas/formulario-cambio.md)).
- El proyecto base proviene de las asignaturas anteriores: no se redefine, se **planifica**.

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
