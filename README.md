# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del Challenge de Data Science. El objetivo principal es analizar una base de datos de clientes de la empresa de telecomunicaciones **Telecom X** para identificar los factores y patrones que influyen en la tasa de cancelación de servicios (Churn).

Los *insights* obtenidos de este Análisis Exploratorio de Datos (EDA) servirán como base estructurada para el futuro desarrollo de modelos predictivos de Machine Learning.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Manipulación de Datos:** Pandas (`json_normalize`, manejo de nulos, transformaciones)
* **Visualización:** Matplotlib y Seaborn
* **Entorno de Desarrollo:** Google Colab / Jupyter Notebook

## ⚙️ Estructura del Proyecto y Metodología
El análisis se dividió en las siguientes fases:
1. **Extracción de Datos:** Consumo de datos en formato JSON desde una API simulada y desanidación de múltiples diccionarios internos a columnas planas.
2. **Limpieza y Tratamiento:** Eliminación de registros vacíos en la variable objetivo (`evasion`), corrección de tipos de datos y manejo de valores nulos en cargos totales.
3. **Ingeniería de Características:** Creación de la métrica `cuentas_diarias` y estandarización de datos (traducción de columnas al español y mapeo binario 1/0).
4. **Análisis Exploratorio (EDA):** Generación de estadísticas descriptivas y visualizaciones (gráficos circulares, de barras y de distribución KDE) para cruzar el Churn con variables categóricas y numéricas.

## 💡 Principales Hallazgos (Insights)
* **Ventana Crítica de Fuga:** La mayor tasa de cancelación ocurre en los primeros **0 a 5 meses** de contrato.
* **El Riesgo del "Mes a Mes":** Los clientes con contratos mensuales tienen una probabilidad de abandono drásticamente mayor que aquellos con contratos anuales.
* **Fricción Financiera:** El método de pago por "Cheque Electrónico" presenta anomalías en la retención, y los clientes con cargos mensuales más altos son los más propensos a cancelar.

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio en tu máquina local:
   ```bash
   git clone [https://github.com/tu-usuario/challenge2-data-science-LATAM.git](https://github.com/tu-usuario/challenge2-data-science-LATAM.git)
