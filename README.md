# QA Manual - NexoTech Store

Documentación de pruebas manuales realizada sobre **NexoTech Store**, una tienda online de tecnología desarrollada con HTML, CSS y JavaScript.

El proyecto reúne el análisis funcional, el plan de pruebas, el diseño y ejecución de casos, observaciones, métricas, evidencias visuales y la organización del trabajo en Jira Scrum.

**Autor:** Federico Sosa  
**Aplicación evaluada:** https://leanfed.github.io/Nexo-tech-store/  
**Informe visual:** publicar GitHub Pages desde la carpeta `/docs`  
**Jira Scrum:** el tablero real puede requerir acceso autorizado a Atlassian. Las evidencias principales están incluidas en este repositorio.

---

## Vista general

| Área | Detalle |
|---|---|
| Tipo de pruebas | Manuales funcionales, interfaz, responsive, regresión básica y persistencia local |
| Aplicación bajo prueba | NexoTech Store |
| Modalidad de gestión | Scrum en Jira |
| Épicas | 5 |
| Historias de usuario | 10 |
| Casos de prueba | 26 |
| Observaciones / defectos | 3 |
| Sprints documentados | 3 |
| Evidencias incluidas | Capturas de la aplicación y del espacio Jira |

---

## Alcance validado

Se validaron los principales flujos de una tienda online:

- visualización del catálogo;
- búsqueda de productos;
- filtros por categoría;
- detalle de producto;
- carrito de compras;
- persistencia mediante LocalStorage;
- acceso al panel administrador;
- alta, edición y eliminación de productos;
- restauración del catálogo;
- comportamiento responsive en vista mobile.

---

## Documentación principal

| Documento | Descripción |
|---|---|
| [`00-resumen-ejecutivo.md`](docs/00-resumen-ejecutivo.md) | Síntesis general del análisis QA |
| [`01-requerimientos.md`](docs/01-requerimientos.md) | Requerimientos funcionales y no funcionales |
| [`02-plan-de-pruebas.md`](docs/02-plan-de-pruebas.md) | Objetivo, alcance, ambiente, criterios y riesgos |
| [`03-casos-de-prueba.md`](docs/03-casos-de-prueba.md) | Casos de prueba manuales |
| [`04-ejecucion.md`](docs/04-ejecucion.md) | Resultado de ejecución |
| [`05-defectos-observaciones.md`](docs/05-defectos-observaciones.md) | Observaciones y limitaciones detectadas |
| [`06-metricas.md`](docs/06-metricas.md) | Métricas del ciclo QA |
| [`07-jira-scrum.md`](docs/07-jira-scrum.md) | Organización del trabajo en Jira Scrum |
| [`08-trazabilidad.md`](docs/08-trazabilidad.md) | Relación entre épicas, historias y casos |

---

## Evidencias visuales

Las evidencias están guardadas dentro del repositorio para que puedan consultarse aunque el tablero Jira requiera permisos.

| Evidencia | Archivo |
|---|---|
| Vista de productos evaluada | [`nexotech-productos.png`](docs/evidencias/nexotech-productos.png) |
| Carrito de compras | [`nexotech-carrito.png`](docs/evidencias/nexotech-carrito.png) |
| Panel administrador | [`nexotech-admin.png`](docs/evidencias/nexotech-admin.png) |
| Resumen e informes de Jira | [`jira-resumen-estado.png`](docs/evidencias/jira-resumen-estado.png) |
| Sprint e historia de usuario | [`jira-sprint-historia-detalle.png`](docs/evidencias/jira-sprint-historia-detalle.png) |
| Cronograma de épicas | [`jira-cronograma-epicas.png`](docs/evidencias/jira-cronograma-epicas.png) |

---

## Jira Scrum

El trabajo fue organizado en Jira mediante:

- 5 épicas;
- 3 sprints;
- historias de usuario;
- tareas de documentación QA;
- casos de prueba;
- observaciones/errores.

El tablero de Jira puede requerir acceso autorizado. Por ese motivo, el repositorio incluye capturas del backlog, cronograma, sprint, detalle de historia e informes para que la evidencia sea consultable desde GitHub.

Los CSV utilizados para la carga inicial se encuentran en la carpeta [`jira`](jira/).

---

## Estructura del repositorio

```text
qa-manual-nexotech-store/
├── README.md
├── docs/
│   ├── index.html
│   ├── 00-resumen-ejecutivo.md
│   ├── 01-requerimientos.md
│   ├── 02-plan-de-pruebas.md
│   ├── 03-casos-de-prueba.md
│   ├── 04-ejecucion.md
│   ├── 05-defectos-observaciones.md
│   ├── 06-metricas.md
│   ├── 07-jira-scrum.md
│   ├── 08-trazabilidad.md
│   └── evidencias/
├── jira/
│   ├── 01-nexotech-features-limpio.csv
│   ├── 02-nexotech-backlog-limpio.csv
│   ├── INSTRUCCIONES-IMPORTACION-JIRA.md
│   └── sprints-y-epicas.md
├── resources/
│   └── qa-manual-nexotech-store.xlsx
├── data/
│   ├── requerimientos.csv
│   └── casos-de-prueba.csv
└── .gitignore
```

---

## Publicación con GitHub Pages

Para publicar el informe visual:

1. Ir a **Settings → Pages**.
2. Seleccionar **Deploy from a branch**.
3. Branch: `main`.
4. Folder: `/docs`.
5. Guardar.

El archivo que se publica es:

```text
docs/index.html
```

---

## Estado del proyecto

Proyecto QA documentado, con evidencias visuales, métricas, trazabilidad y gestión Scrum registrada.

---

## Autor

**Federico Sosa**
