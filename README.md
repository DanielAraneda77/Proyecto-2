# Proyecto-2
Análisis Inicial y Selección de Problema
## Descripción del Proyecto
Este proyecto busca analizar y estructurar datos de diferentes fuentes para identificar patrones y tendencias en el contexto de vehículos eléctricos en EE. UU. y inventario de tiendas minoristas. Mediante exploración de datos y técnicas de modelado, se seleccionó un problema relevante para su análisis y resolución.
## Conjuntos de Datos Analizados
Se trabajó con dos datasets distintos, explorando sus variables y relación con distintos factores:

1- Vehículos Eléctricos en EE.UU.
- Datos sobre registros de vehículos eléctricos, infraestructura de carga y precios.
- Variables clave: cantidad de EVs registrados, estaciones de carga, incentivos fiscales.

2- Inventario de Tiendas Minoristas
- Información sobre la gestión de inventarios y demanda en comercios.
- Variables clave: precios, descuentos, promociones y estacionalidad.

## Resumen del EDA Inicial
Principales hallazgos de los análisis exploratorios: Influencia de descuentos y promociones en la demanda de Discount y Promotion mostraron alta correlación con ventas. Impacto de la competencia en precios de Competitor Pricing afecta la demanda de productos en tiendas.
Distribución de registros de EVs por estado, algunas regiones presentan mayor adopción debido a incentivos. Outliers en inventario y pedidos, se detectaron valores extremos en Units Ordered y Inventory Level, que fueron tratados mediante Winsorización e IQR.

## Problema Seleccionado
Justificación:

- La demanda varía por categoría de producto y condiciones externas.
- Es crucial predecir qué productos tendrán alta demanda para optimizar inventario.

- Factores como precios, promociones y competencia afectan directamente las ventas.

Objetivos específicos:

- Clasificar la demanda en baja, media y alta según variables comerciales.
- Optimizar la gestión de inventarios para reducir costos y evitar desabastecimiento.
- Seleccionar el mejor modelo de clasificación (Random Forest, XGBoost) para mejorar predicciones.

## Problema Seleccionado Vehículos Eléctricos en EE.UU.
Justificación:
- La adopción de vehículos eléctricos (EVs) depende de múltiples factores, incluyendo incentivos fiscales, precios de los vehículos, infraestructura de carga y políticas gubernamentales.
- Predecir la cantidad de registros de EVs en distintas regiones permitirá optimizar la infraestructura de carga y ajustar estrategias de promoción.

Objetivos específicos:

- Desarrollar un modelo de regresión para predecir el número de registros de vehículos eléctricos según condiciones económicas y políticas.
- Identificar las variables más influyentes en la adopción de EVs, como incentivos fiscales y disponibilidad de estaciones de carga.
- Optimizar estrategias de expansión para mejorar la red de carga y fomentar el uso de EVs en regiones con menor adopción.

Nombre: Daniel Araneda

## Cómo Ejecutar el Código
```bash
https://github.com/DanielAraneda77/Proyecto-2.git
