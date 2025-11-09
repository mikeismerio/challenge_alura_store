# 🏪 Alura Store Data Challenge

> 📊 Análisis de ventas, reseñas y rendimiento para identificar la tienda menos eficiente de la cadena **Alura Store**.

---

## 📘 Descripción General

Ayudarás al **Sr. Juan** a decidir **qué tienda vender** para iniciar un nuevo emprendimiento. Analizarás datos de **ventas, reseñas y desempeño** de las **4 tiendas** y entregarás una **recomendación sustentada en datos**.

---

## 🎯 Objetivos del Proyecto

### ✅ 1. Manipulación y limpieza de datos  
- Carga de archivos CSV con **pandas**.  
- Normalización de columnas, conversión de tipos y tratamiento de nulos.  
- Construcción de datasets consolidados (`raw → processed`).

### ✅ 2. Análisis Exploratorio (EDA)  
- Ingresos totales por tienda.  
- Margen bruto estimado.  
- Ticket promedio.  
- Ranking de vendedores.  
- Distribución de calificaciones y % de reseñas negativas.  
- Tendencias de ventas a nivel mensual y trimestral.  

### ✅ 3. Visualización de Datos  
Creación de más de **3 visualizaciones** con **matplotlib**, **seaborn** y **folium**, como:

- Gráficos comparativos de ingresos y margen.  
- Mapas de calor por tienda y lugar de compra.  
- Series temporales mensuales y trimestrales.  
- Choropleth por departamento (mapa interactivo).  

### ✅ 4. Recomendación Ejecutiva  
Basada en:

- Ingresos  
- Margen  
- Ticket promedio  
- Estabilidad mensual  
- Participación por categorías  
- Rendimiento de vendedores  
- Calificaciones y reseñas  

---

## 🗂️ Estructura del Proyecto

```plaintext

challenge_alura_store/
├── data/
│   ├── raw/
│   │   ├── tienda_1.csv
│   │   ├── tienda_2.csv
│   │   ├── tienda_3.csv
│   │   └── tienda_4.csv
│   └── processed/
│       ├── tiendas.csv
│       └── tiendas_con_margen.csv
├── notebooks/
│   ├── 01_analisis.ipynb            # EDA + métricas base
│   ├── 02_visualizaciones.ipynb     # gráficas comparativas + mapas + series
│   └── assets/
│       └── colombia.geo.json         # recurso para mapas
├── requirements.txt
└── README.md
```
