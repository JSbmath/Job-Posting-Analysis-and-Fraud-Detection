# Job Posting Analysis and Fraud Detection / Análisis de Ofertas de Empleo y Detección de Fraude

This repository contains two Jupyter Notebooks that perform an exploratory data analysis (EDA) and predictive modeling on a dataset of job postings. The goal is to identify patterns, trends, and characteristics that can help detect fraudulent job postings.

Este repositorio contiene dos cuadernos de Jupyter que realizan un análisis exploratorio de datos (EDA) y modelado predictivo en un conjunto de datos de ofertas de empleo. El objetivo es identificar patrones, tendencias y características que puedan ayudar a detectar ofertas de empleo fraudulentas.

---

## Notebooks / Cuadernos

### 1. **EDA_and_Data_Preprocessing.ipynb**

This notebook focuses on the exploratory data analysis and preprocessing of the job postings dataset. It includes:

- Data cleaning and handling missing values.
- Visualization of key variables such as location, salary range, and job titles.
- Generation of word clouds for text fields like company profiles, job descriptions, and requirements.
- Discretization of continuous variables like salary.
- Interactive visualizations using Plotly, including choropleth maps to show the geographical distribution of job postings.

Este cuaderno se centra en el análisis exploratorio de datos y el preprocesamiento del conjunto de datos de ofertas de empleo. Incluye:

- Limpieza de datos y manejo de valores faltantes.
- Visualización de variables clave como ubicación, rango salarial y títulos de trabajo.
- Generación de nubes de palabras para campos de texto como perfiles de empresa, descripciones de puestos y requisitos.
- Discretización de variables continuas como el salario.
- Visualizaciones interactivas utilizando Plotly, incluidos mapas coropléticos para mostrar la distribución geográfica de las ofertas de empleo.

### 2. **Fraud_Detection_Modeling.ipynb**

This notebook builds on the preprocessed data to create a predictive model for detecting fraudulent job postings. It includes:

- Transformation of categorical variables using Weight of Evidence (WoE) and calculation of Information Value (IV).
- Training and evaluation of a logistic regression model.
- Model performance metrics such as AUC-ROC and accuracy.
- Analysis of model coefficients to understand the importance of each feature in predicting fraud.

Este cuaderno se basa en los datos preprocesados para crear un modelo predictivo que detecte ofertas de empleo fraudulentas. Incluye:

- Transformación de variables categóricas utilizando Weight of Evidence (WoE) y cálculo del Information Value (IV).
- Entrenamiento y evaluación de un modelo de regresión logística.
- Métricas de rendimiento del modelo, como AUC-ROC y precisión.
- Análisis de los coeficientes del modelo para comprender la importancia de cada característica en la predicción de fraudes.

---

## Requirements / Requisitos

To run these notebooks, you need the following Python libraries:

Para ejecutar estos cuadernos, necesitas las siguientes bibliotecas de Python:

- pandas
- numpy
- matplotlib
- plotly
- scikit-learn
- wordcloud
- nltk

You can install the required libraries using pip:

Puedes instalar las bibliotecas necesarias usando pip:

```bash
pip install pandas numpy matplotlib plotly scikit-learn wordcloud nltk
