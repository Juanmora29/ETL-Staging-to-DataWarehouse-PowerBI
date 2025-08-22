# ETL-Staging-to-DataWarehouse-PowerBI

En este proyecto corresponde se implementó un **proceso de ETL con SSIS**, un **Data Warehouse en SQL Server** y un **dashboard en Power BI** para el análisis de ventas de una empresa de retail.

---

## ⚙️ Tecnologías utilizadas

- **SQL Server** → Modelado de base de datos relacional y Data Warehouse  
- **SSIS (SQL Server Integration Services)** → Procesos ETL (extracción, transformación y carga)  
- **Power BI** → Visualización y análisis de datos  
- **GitHub** → Versionado y publicación del proyecto  

---

## 📊 Modelo de datos

Se implementó un **modelo estrella (Star Schema)** compuesto por:  
- **Tabla de hechos:** `Fact_ventas`  
- **Dimensiones:** `Dim_clientes`, `Dim_empleados`, `Dim_productos`, `Dim_region`, `Dim_tiempo`, `Dim_stock`, `Dim_holiday`

Este diseño facilita el análisis de métricas de negocio, como:  
- Ventas totales  
- Análisis por cliente, producto, región y empleado  
- Evolución temporal  
- Aplicación de descuentos y variaciones de stock  

---

## 📈 Dashboard en Power BI

El reporte en **Power BI** permite explorar:  
- Evolución de ventas  
- Análisis de clientes por rango etario  
- Ranking de productos y clientes  
- Impacto de descuentos aplicados  
- Análisis por zonas geográficas  





---

