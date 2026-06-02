# Plan de pruebas

## Objetivo

Validar el correcto funcionamiento de NexoTech Store mediante pruebas manuales sobre los principales flujos funcionales y de interfaz.

## Alcance

Se incluyen pruebas sobre:

- home;
- catálogo;
- búsqueda;
- filtros;
- detalle de producto;
- carrito;
- LocalStorage;
- panel administrador;
- CRUD de productos;
- responsive mobile.

## Fuera de alcance

- Integración con pasarela de pago real.
- Autenticación con backend.
- Base de datos real.
- Envío de órdenes de compra.
- Pruebas de seguridad avanzadas.
- Pruebas de carga o performance avanzada.

## Tipos de prueba

| Tipo | Descripción |
|---|---|
| Funcionales | Validación de comportamiento esperado según requerimientos. |
| Interfaz | Validación visual de elementos principales. |
| Responsive | Revisión en ancho mobile. |
| Persistencia | Validación de datos guardados en LocalStorage. |
| Negativas | Validación de búsquedas sin resultado y login incorrecto. |
| Regresión básica | Revisión de flujos principales luego de cambios. |

## Ambiente de prueba

| Elemento | Detalle |
|---|---|
| Aplicación | NexoTech Store |
| URL | https://leanfed.github.io/Nexo-tech-store/ |
| Navegador | Google Chrome |
| Sistema operativo | Windows |
| Gestión | Jira Scrum |
| Documentación | Markdown y Excel |

## Criterios de entrada

- Sitio publicado y accesible.
- Catálogo inicial cargado.
- Archivos principales disponibles en GitHub.
- Flujos principales implementados.

## Criterios de salida

- Casos de prueba diseñados.
- Ejecución documentada.
- Observaciones registradas.
- Métricas calculadas.
- Evidencias cargadas o preparadas para cargar.
- Sprint QA cerrado en Jira.

## Riesgos

| Riesgo | Impacto | Mitigación |
|---|---|---|
| Datos previos en LocalStorage | Medio | Limpiar almacenamiento o usar navegador incógnito. |
| Cambios de versión del sitio | Medio | Registrar fecha de ejecución y versión evaluada. |
| Falta de backend | Bajo | Documentar como limitación técnica del alcance frontend. |
| Capturas incompletas | Medio | Definir una lista mínima de evidencias. |
