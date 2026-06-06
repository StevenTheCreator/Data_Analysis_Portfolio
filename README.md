# Data_Analysis_Portfolio
Sales Analysis: Superstore Dataset
Este proyecto consiste en un análisis detallado del desempeño de ventas de la 'Superstore Dataset', una base de datos orientada al sector minorista. El objetivo principal es transformar datos brutos en inteligencia de negocio procesable mediante consultas SQL estructuradas.

A través de este análisis, busco identificar patrones de consumo, evaluar el rendimiento por regiones y segmentos de clientes, y detectar oportunidades de optimización en la distribución. Este informe documenta el proceso completo: desde la ingesta y modelado de datos en MySQL, hasta la extracción de insights clave que permiten una toma de decisiones informada y estratégica.

## Tecnologías Utilizadas
- **SQL (MySQL)**
- **MySQL Workbench**
- **Markdown**

## Análisis y Resultados

### 1.¿Cuál es la categoría de productos con más ventas?
Ventas totales por categoría:

![Captura de pantalla de tu query](images/query&result_1.jpg)

R/ La categoria con mas ventas es la de Furniture con un total_ventas de 13811.02

### 2.¿Qué región vende más?
Se seleccionan todas las regiones de la tabla y en base a las ventas se categorizan de mayor a menor (DESC):

![Captura de pantalla de tu query](images/query&result_2.jpg)

R/ La region con mas ventas es la West con un total_ventas de 10189.26 y una cantidad de 48 ventas sacadas con el COUNT(sales).

### 3.¿Qué segmento de clientes genera más ventas?

![Captura de pantalla de tu query](images/query&result_3.jpg)

R/ El segment que mas ventas genero es el de Consumer con total_ventas de 19343.58 y una cantidad de num_ordenes (cada una con distinto order_id) de 39. Se evidencia que los Consumer son los que mas generan mas en sales al negocio

### 4.¿Cuáles son los 5 productos más vendidos?



