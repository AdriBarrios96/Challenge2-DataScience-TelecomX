# Challenge2-DataScience-TelecomX
Segundo challenge de Alura Latam ONE sobre Análisis de Datos

# 📊 Telecom X: Análisis de Fuga de Clientes (Churn)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge)

## 🎯 Objetivo del Proyecto
Este proyecto analiza el comportamiento de los clientes de la empresa **Telecom X** para identificar patrones que derivan en la cancelación del servicio (**Churn**). El objetivo final es transformar datos técnicos y financieros en estrategias comerciales para aumentar la retención de usuarios.

## 🚀 Pasos Realizados
1. **ETL y Normalización:** Extracción de datos desde un JSON complejo y aplanado de estructuras anidadas.
2. **Limpieza de Datos:** Identificación de errores de formato en variables financieras y tratamiento de valores nulos/duplicados.
3. **Ingeniería de Características:** Creación de la métrica `Cuentas_Diarias` para un análisis de gasto más granular.
4. **Análisis Exploratorio (EDA):** Visualización de la distribución de evasión y cruce de variables categóricas y numéricas.
5. **Insights Estratégicos:** Identificación de perfiles de riesgo (contratos mensuales y métodos de pago específicos).

## 🛠️ Instalación y Dependencias

Para ejecutar este proyecto localmente, asegúrate de tener instalado Python 3.x y las siguientes librerías:

```bash
pip install pandas requests matplotlib seaborn
```
💻 Cómo ejecutar el proyecto
Clona este repositorio o descarga el archivo .ipynb.

Abre el archivo en Google Colab o Jupyter Notebook.

Asegúrate de ejecutar las celdas en orden secuencial.

Nota: El script descarga automáticamente el dataset desde el repositorio oficial de Alura.

📈 Conclusiones Clave
La tasa de evasión ronda el 26.5%.

Los contratos mes a mes representan el mayor riesgo de fuga.

El método de pago Electronic Check está altamente correlacionado con la cancelación del servicio.

✍️ Autor: AdrielBarrios96
🎓 Contexto: Challenge Data Science - Alura LATAM
