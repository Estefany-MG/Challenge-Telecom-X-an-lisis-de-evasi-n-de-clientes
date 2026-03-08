# 📡 Proyecto Telecom X: Análisis de Churn y Proceso ETL

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-orange.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Visualization-green.svg)

## 🎯 Propósito del Proyecto
Este proyecto fue desarrollado para **Telecom X**, una empresa de telecomunicaciones que enfrenta un alto índice de abandono de clientes (*Churn*). 

El objetivo principal es ejecutar un proceso completo de **ETL (Extracción, Transformación y Carga)** para:
1. Extraer los datos brutos de los clientes desde una API en formato JSON.
2. Limpiar y transformar los datos (manejo de nulos, normalización de tipos de datos).
3. Realizar un Análisis Exploratorio de Datos (EDA) para identificar patrones clave.
4. Entregar un conjunto de datos limpio y estructurado al equipo de Ciencia de Datos para la creación de modelos predictivos.

## 📂 Estructura del Proyecto
El repositorio está organizado de la siguiente manera para garantizar la reproducibilidad y el orden:

```text
telecom-x-churn/
├── data/                   # Carpeta para almacenar los datos crudos y procesados (excluida en .gitignore)
├── notebooks/
│   └── telecom_x_etl.ipynb # Notebook principal con la ejecución del ETL y EDA
├── images/                 # Gráficos generados exportados para este README
├── README.md               # Documentación del proyecto
└── requirements.txt        # Dependencias necesarias para ejecutar el proyecto
