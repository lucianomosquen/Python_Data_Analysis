# 📊 Python Data Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)  
![Pandas](https://img.shields.io/badge/Library-Pandas-green?logo=pandas)  
![Repo Status](https://img.shields.io/badge/Status-En%20Progreso-yellow)  

Este repositorio contiene un flujo de trabajo completo para el **análisis de datos de ventas** utilizando Python.  
El objetivo es mostrar paso a paso cómo transformar datos crudos en información lista para el análisis, con notebooks bien documentados y datasets organizados.  

---

## 📂 Estructura del repositorio

```text
Python_Data_Analysis/
│
├── Data/
│   ├── Ventas.csv
│   ├── Ventas_clean.csv
│   ├── medallas.csv
│   └── medallas_clean.csv
│
├── Notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_data_analysis.ipynb
│
├── Images/
│   ├── preview_top10.png
│   └── preview_top5.png  
│
└── README.md

```
---

## 📓 Notebooks

### 01_data_cleaning.ipynb
- Conversión de fechas a formato datetime.  
- Normalización de categorías en la columna Producto.  
- Detección de valores faltantes y registros duplicados.  
- Verificación de consistencia: Total Venta = Cantidad * Precio Unitario.  
- Exportación de dataset limpio → Ventas_clean.csv.  

### 02_data_analysis.ipynb
- Limpieza adicional de datos del medallero olímpico.  
- Conversión segura de columnas numéricas (manejo de valores no válidos).  
- Métricas descriptivas: Top 10 países por medallas de oro y medallas totales.  
- Visualizaciones:
  - 📊 Gráfico de barras: Top 10 países con más medallas totales.  
  - 🥇 Comparación Oro, Plata y Bronce en los 5 países principales.  

---

## 🚀 Roadmap

- [x] 01_data_cleaning.ipynb → Limpieza y normalización.  
- [x] 02_data_analysis.ipynb → Métricas descriptivas y primeras visualizaciones.  
- [ ] 03_visualizations.ipynb → Gráficos avanzados y storytelling con datos.  
- [ ] 04_modeling.ipynb → (opcional) Modelos predictivos simples.  

---

## ⚙️ Requisitos

Este proyecto usa Python 3 y las siguientes librerías:  

```bash
pip install pandas numpy matplotlib seaborn
```
- `pandas` → Manipulación de datos  
- `numpy` → Operaciones numéricas  
- `matplotlib` / `seaborn` → Visualización (para siguientes etapas)  

---

## ✨ Autor

**Luciano Mosquén**  
🔗 [LinkedIn](https://www.linkedin.com/in/lucianomosquen)  
🌐 [GitHub](https://github.com/lucianomosquen)  

---



## 📸 Preview

<img src="Images/preview_top10.png" alt="Top 10 países con más medallas" width="500"/>

<img src="Images/preview_top5.png" alt="Distribución de medallas en el Top 5" width="500"/>
