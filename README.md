# Challenge-TelecomX-1-DataScience
Proyecto de análisis de evasión de clientes para Telecom X

# 📊 Análisis de Evasión de Clientes: TelecomX_LATAM

Este proyecto forma parte del **Challenge 2 de Data Science** de **Alura Latam**. El objetivo principal es identificar patrones y factores clave que influyen en la deserción (churn) de clientes para una empresa de telecomunicaciones.

## 📋 Propósito del Proyecto
Comprender la distribución de la variable **"Evasión"** y cómo se relaciona con diferentes perfiles de clientes y comportamientos de facturación. Este análisis permite orientar acciones estratégicas para mejorar la retención de clientes.

## 🛠️ Tecnologías y Librerías
* **Python** como lenguaje principal.
* **Pandas** para la manipulación y limpieza de datos.
* **Matplotlib** y **Seaborn** para la generación de gráficos avanzados.
* **Google Colab** como entorno de desarrollo.

## 📂 Estructura del Análisis
1.  **Limpieza y Tratamiento de Datos:** Identificación de tipos, manejo de nulos y estandarización de columnas como `gender` y `Contract`.
2.  **Análisis Exploratorio (EDA):**
    * **Distribución de Evasión:** Visualización del balance entre clientes activos y bajas.
    * **Variables Categóricas:** Impacto del tipo de contrato, género y métodos de pago.
    * **Variables Numéricas:** Análisis de densidad (KDE) para antigüedad y cargos.
3.  **¡Extra! Análisis de Correlación:** Uso de matrices de correlación para cuantificar relaciones entre variables numéricas (como `Cuentas_Diarias`) y la evasión.

## 💡 Insights Principales
* **Zona Crítica:** Los nuevos clientes tienen la tasa de deserción más alta en sus primeros meses de contrato.
* **Impacto de Facturación:** Existe una correlación positiva (0.19) entre cargos mensuales elevados y la evasión.
* **Fidelidad:** Los contratos a largo plazo (1 o 2 años) reducen drásticamente la tasa de evasión.

## 🚀 Cómo ejecutar el proyecto
1. Clonar este repositorio.
2. Abrir el archivo `TelecomX_LATAM.ipynb` en Google Colab o Jupyter Notebook.
3. Asegurarse de tener instaladas las librerías `pandas`, `seaborn` y `matplotlib`.
