
# 📊 Análisis exploratorio de datos - Evaluación final BDA Módulo 3

Este proyecto es la evaluación final del Módulo 3 del bootcamp de análisis de datos (BDA) de Andalab. El objetivo es realizar un **análisis exploratorio de datos (EDA)** de una base de datos con información de viviendas, enfocado en entender su estructura, limpieza y patrones clave.

---

## 🧠 Objetivos del proyecto

- Cargar y explorar un conjunto de datos de viviendas
- Limpiar datos nulos y valores atípicos
- Analizar las variables principales (precio, superficie, habitaciones, ubicación)
- Generar visualizaciones informativas y representativas
- Obtener insights que permitan una mejor comprensión del mercado de vivienda

---

## 🛠️ Herramientas utilizadas

- **Python**  
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- Jupyter Notebook

---

## 📁 Estructura del notebook

1. **Carga y revisión inicial de datos**  
   Visualización general de los datos, tipos de variables y valores nulos

2. **Limpieza de datos**  
   - Eliminación de columnas irrelevantes  
   - Gestión de valores nulos  
   - Conversión de tipos de datos

3. **Análisis exploratorio**  
   - Distribución de precios, habitaciones, metros cuadrados  
   - Correlaciones entre variables  
   - Análisis por provincias y localizaciones destacadas  
   - Identificación de outliers

4. **Visualizaciones**  
   Gráficos de dispersión, histogramas, boxplots, mapas de calor

---

## 📌 Principales hallazgos

- Existe una alta variabilidad de precios según la provincia.
- Las viviendas con más de 5 habitaciones tienden a tener mayor dispersión de precio.
- Se identificaron valores atípicos que distorsionaban la media general.
- La superficie es uno de los factores más correlacionados con el precio.

---

## 📎 Cómo usar este proyecto

1. Clona el repositorio o descarga el archivo `.ipynb`
2. Asegúrate de tener instaladas las siguientes bibliotecas:

```bash
pip install pandas numpy matplotlib seaborn plotly

