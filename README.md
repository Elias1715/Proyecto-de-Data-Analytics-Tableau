# 📊 Análisis de Ventas — Tableau Portfolio

Proyecto de Data Analytics desarrollado con **Tableau** a partir de una base de ventas trabajada previamente en Excel.

## 🎯 Objetivo

Construir un dashboard profesional que permita analizar:

- Facturación.
- Ganancia.
- Margen.
- Facturación por producto.
- Facturación por vendedor.
- Evolución temporal.
- Relación anual entre facturación y ganancia.
- Detalle de ventas mediante navegación.

## 🛠️ Herramientas

- Microsoft Excel / Excel con macros (`.xlsm`) — fuente de datos.
- Tableau — análisis y visualización.
- GitHub — documentación y presentación del portfolio.

## 📁 Estructura

```text
Analisis-Ventas-Tableau/
│
├── Analisis_Ventas_Portfolio_FINAL.twb
├── README.md
├── INFORME_PROYECTO.md
├── CAMBIOS_PROYECTO_FINAL.md
├── INSIGHTS_Y_CONCLUSIONES.md
├── COMO_REPRODUCIR.md
└── datos/
    └── README_DATOS.txt
```

## 📌 Dashboard principal

El dashboard final presenta la información siguiendo una lógica de storytelling:

**KPIs → Producto/Vendedor → Facturación vs. Ganancia → Evolución temporal → Detalle**

### KPIs

- Facturación total
- Ganancia total
- Margen

### Visualizaciones

- Facturación por Producto
- Facturación por Vendedor
- Facturación vs. Ganancia por Año
- Evolución de Facturación
- Vista de detalle de ventas

## 🔎 Interactividad

La evolución temporal funciona como filtro del dashboard: al seleccionar un período, se actualizan las demás visualizaciones y los KPIs.

También se incorporó navegación entre:

**ANÁLISIS DE VENTAS → DETALLE DE VENTAS → ANÁLISIS DE VENTAS**

## 📈 Principales resultados observados

Con la base utilizada durante el proyecto:

- Facturación total: **$160.678.100**
- Notebook: **$88.560.000** de facturación.
- Vendedor con mayor facturación: **Ana — $47.141.000**
- Canal Online: **$109.083.600**, aproximadamente **67,89%** de la facturación.
- Ciudad con mayor facturación: **Buenos Aires — $79.014.300**
- Facturación anual:
  - 2024: **$16.680.700**
  - 2025: **$78.577.400**
  - 2026: **$65.420.000**

Para 2025 → 2026, el producto con mayor caída identificado en el análisis fue **Notebook (-22%)**, mientras que **Teclado aumentó 8,95%**.

## 📂 Fuente de datos

El workbook recibido referencia originalmente un archivo Excel `.xlsm`. El archivo fuente utilizado en el proyecto es el mismo dataset trabajado durante el curso; únicamente cambió su nombre por motivos relacionados con macros.

Para una reproducción completa en otro equipo, agregá tu archivo Excel fuente dentro de `datos/` y reconectá la fuente desde Tableau si Tableau solicita la ubicación.

## 👤 Proyecto de portfolio

Este proyecto demuestra competencias en:

- Conexión a datos.
- Dimensiones y medidas.
- Campos calculados.
- Parámetros.
- Análisis temporal.
- KPIs.
- Dashboards.
- Storytelling con datos.
- Interactividad.
- Acciones de filtro.
- Navegación entre dashboards.
- Diseño orientado a negocio.
