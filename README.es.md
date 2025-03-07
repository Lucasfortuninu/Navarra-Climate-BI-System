# Sistema BI sobre el Clima de Navarra

## 📌 Descripción
Este repositorio contiene el desarrollo de un **Sistema de Business Intelligence (BI)** para analizar el clima en Navarra, utilizando un **proceso ETL (Extracción, Transformación y Carga)** y almacenamiento en un **Data Warehouse** en MySQL.

Este proyecto fue desarrollado como trabajo final de la asignatura de Analisis de aplicaciones empresariales en tercer curso del grado de Ingeniería Informática en la Universidad Pública de Navarra (UPNA).

## 🏆 Objetivos del Proyecto
- Desarrollar un **proceso ETL** en Python para recopilar y transformar datos meteorológicos.
- Diseñar un **Data Warehouse** con un esquema en estrella para almacenamiento estructurado.
- Implementar **informes y gráficos interactivos** para visualizar tendencias climáticas.
- Analizar el **rendimiento de consultas** con pruebas de carga y concurrencia.

## 🚀 Tecnologías Utilizadas
- **Python** 🐍 para la implementación del proceso ETL y análisis de datos.
- **MySQL** para el almacenamiento estructurado en Data Warehouse.
- **Grafana** 📊 para la visualización de datos en dashboards interactivos.
- **Jupyter Notebook** para documentación y experimentación.

## 📂 Contenido del Proyecto
1. **Proceso ETL**:
   - **Extracción**: Descarga de datos meteorológicos desde fuentes externas.
   - **Transformación**: Normalización y limpieza de datos.
   - **Carga**: Inserción de datos en MySQL.
2. **Diseño del Data Warehouse**:
   - Tablas de Dimensiones (LK_comarcas, LK_pueblos, LK_tiempo).
   - Tabla de Hechos (DT_temperaturas) con registros de temperatura y precipitaciones.
3. **Generación de Informes**:
   - Gráficos de precipitaciones y temperaturas por año, mes y semana.
   - Dashboards interactivos en Grafana.
4. **Pruebas de Rendimiento**:
   - Evaluación del tiempo de respuesta de consultas SQL.
   - Simulación de concurrencia con hasta 100 usuarios.

## 📊 Resultados y Conclusiones
- Se implementó un **ETL eficiente** para la carga de datos climáticos históricos.
- Se diseñó un **Data Warehouse estructurado** para facilitar el análisis.
- Se crearon **gráficos y dashboards** interactivos para visualizar tendencias.
- Se analizaron tiempos de consulta con **carga de usuarios concurrentes**.
