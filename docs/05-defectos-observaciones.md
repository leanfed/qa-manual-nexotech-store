# Defectos y observaciones

Las siguientes observaciones se registran como limitaciones conocidas del alcance actual del proyecto frontend.

| ID | Tipo | Severidad | Prioridad | Estado | Descripción |
|---|---|---|---|---|---|
| OBS-001 | Observación técnica | Baja | Media | Documentado | La autenticación del panel administrador es simulada del lado del cliente y no valida contra backend. |
| OBS-002 | Mejora funcional | Media | Media | Documentado | El flujo de carrito no genera una orden de compra ni integra checkout real. |
| OBS-003 | Limitación técnica | Media | Media | Documentado | La administración del catálogo se limita a LocalStorage, por lo que los cambios no son compartidos entre usuarios o navegadores. |

## Recomendaciones

- Implementar backend para autenticación y persistencia centralizada.
- Agregar validaciones más completas en formularios del panel administrador.
- Incorporar flujo de checkout simulado o real.
- Agregar pruebas automatizadas de regresión en una etapa posterior.
