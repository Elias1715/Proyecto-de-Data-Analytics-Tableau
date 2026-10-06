# Informe del Proyecto — Análisis de Ventas con Tableau

## 1. Resumen ejecutivo

El proyecto transforma una base de operaciones comerciales en un dashboard interactivo desarrollado en Tableau.

El análisis se concentra en facturación, rentabilidad, productos, vendedores, evolución temporal y canales de venta.

La solución fue construida progresivamente a partir del trabajo realizado previamente en Excel y luego trasladada a Tableau para desarrollar capacidades de Business Intelligence y visualización.

## 2. Datos

La fuente contiene información de ventas con variables como:

- ID de venta
- Fecha
- Vendedor
- Cliente
- Producto
- Categoría
- Cantidad
- Precio unitario
- Costo unitario
- Facturación
- Costo total
- Ganancia
- Margen
- Ciudad
- Canal
- Método de pago
- Segmento de cliente
- Mes
- Año
- Trimestre

El dataset utilizado en Tableau es el mismo trabajado durante el proyecto de Excel. El archivo cambió de nombre por motivos relacionados con macros, no por cambios en el contenido analizado.

## 3. KPIs

### Facturación

Mide el volumen monetario total generado por las operaciones.

Resultado observado:

**$160.678.100**

### Ganancia

Representa el resultado económico después de considerar los costos asociados.

### Margen

Se presenta como porcentaje y se trabaja como promedio en el KPI, evitando sumar porcentajes individuales.

## 4. Análisis por producto

La visualización de Facturación por Producto permite identificar los productos con mayor aporte al negocio.

El principal resultado observado fue:

**Notebook — $88.560.000**

Esto representa una participación muy relevante dentro de la facturación total.

## 5. Análisis por vendedor

La visualización permite comparar el aporte comercial de cada vendedor.

El mayor valor observado fue:

**Ana — $47.141.000**

## 6. Análisis por canal

El canal Online alcanzó:

**$109.083.600**

equivalente aproximadamente al:

**67,89%**

de la facturación total.

Esto muestra una fuerte concentración de la actividad comercial en el canal digital.

## 7. Análisis geográfico

La ciudad con mayor facturación observada fue:

**Buenos Aires — $79.014.300**

## 8. Evolución anual

La facturación observada por año fue:

| Año | Facturación |
|---|---:|
| 2024 | $16.680.700 |
| 2025 | $78.577.400 |
| 2026 | $65.420.000 |

El comportamiento muestra un crecimiento muy fuerte entre 2024 y 2025 y una disminución en 2026 respecto del máximo de 2025.

## 9. Comparación 2025 → 2026

En el análisis específico de productos se identificó:

- **Notebook:** -22%
- **Teclado:** +8,95%

La visualización de Facturación vs. Ganancia por Año permite complementar este análisis observando simultáneamente ambas métricas.

## 10. Storytelling

El dashboard se estructuró siguiendo una secuencia de lectura:

1. **Resultado general:** KPIs.
2. **Situación comercial:** productos y vendedores.
3. **Comparación anual:** facturación vs. ganancia.
4. **Evolución temporal:** comportamiento mensual.
5. **Profundización:** detalle de ventas.

## 11. Interactividad

Se implementó selección sobre la evolución temporal como filtro del resto del dashboard.

También se implementó navegación entre dashboards para acceder a una vista de detalle.

## 12. Decisiones de diseño

Se evitó utilizar un eje dual para la comparación anual de Facturación y Ganancia. Se optó por barras agrupadas sobre un eje común porque la comparación resulta más directa.

También se descartó una acción de resaltado Producto → Vendedor porque no aportaba una relación analítica suficientemente clara para este dataset.

## 13. Conclusión

El proyecto demuestra cómo una base de ventas puede transformarse en una herramienta interactiva para análisis comercial.

El dashboard permite pasar de una visión ejecutiva mediante KPIs a un análisis más profundo por producto, vendedor, período y detalle de operaciones.

La principal conclusión de negocio es que existe una concentración relevante de la facturación en determinados productos, vendedores, ciudades y canales, mientras que la evolución temporal muestra un máximo en 2025 y una reducción posterior en 2026.

Desde el punto de vista técnico, el proyecto demuestra el uso de Tableau para conexión de datos, campos calculados, parámetros, visualizaciones, dashboards, storytelling, filtros e interactividad.
