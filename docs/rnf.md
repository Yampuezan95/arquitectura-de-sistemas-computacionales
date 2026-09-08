# Requerimientos no funcionales

Sistema de inventario de una tienda.

| # | Atributo | Metrica | Umbral | Condicion de carga | Verificacion | Consecuencia si no se cumple |
|---|---|---|---|---|---|---|
| 1 | Rendimiento | p95 de latencia al consultar stock | menor a 400 ms | 200 usuarios concurrentes consultando inventario | Prueba de carga | El empleado no puede confirmar disponibilidad a tiempo y se pierde la venta |
| 2 | Costo | Gasto mensual de infraestructura | menor a 100 USD/mes | Operacion normal del sistema | Revision de factura mensual del proveedor | El negocio pierde margen y el proyecto deja de ser viable |
| 3 | Recuperacion | RTO y RPO ante falla de la base de datos de inventario | RTO menor a 4 horas, RPO menor a 24 horas | Ante falla del servidor o corrupcion de datos | Simulacro de restauracion desde backup diario | Se pierden registros de stock y movimientos del ultimo dia, generando descuadres de inventario |

## Escenarios completos

### Escenario 1
- Fuente:
- Estimulo:
- Artefacto:
- Entorno:
- Respuesta:
- Medida:
