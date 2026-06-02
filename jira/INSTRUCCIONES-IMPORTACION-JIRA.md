# Importacion limpia en Jira - QA Manual NexoTech Store

Usar estos archivos solo en un proyecto limpio o despues de eliminar la importacion anterior.

## Orden de importacion

1. `01-nexotech-features-limpio.csv`
2. `02-nexotech-backlog-limpio.csv`

## Codificacion

Seleccionar siempre: UTF-8

## Mapeo de campos

- Summary -> Resumen
- Issue Type -> Tipo de actividad
- Description -> Descripcion
- Priority -> Prioridad
- Labels -> Etiquetas
- Feature sugerida -> No asignar

## Mapeo de valores de Issue Type

Si Jira esta en espanol:

- Funcion -> Funcion
- Tarea -> Tarea / Task
- Historia -> Historia / Story
- Error -> Error / Bug

Si Jira esta en ingles:

- Funcion -> Feature
- Tarea -> Task
- Historia -> Story
- Error -> Bug

## Importante

No debe quedar todo como Epic. Si Jira muestra todo con icono de Epic, la importacion quedo mal y conviene limpiar antes de seguir.

El resultado esperado es:

- 5 issues tipo Funcion/Feature
- 5 tareas QA generales
- 10 historias de usuario
- 26 casos de prueba como Tarea/Task
- 3 observaciones como Error/Bug
- Total: 49 actividades
