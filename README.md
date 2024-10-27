# Análisis de Series Temporales de Caudales

Este repositorio contiene el análisis de series temporales de caudales para varios pozos en la región del Salar de Atacama. El objetivo principal de este proyecto es comprender la dinámica de los caudales a lo largo del tiempo, aplicando técnicas de modelado estadístico y aprendizaje automático para realizar predicciones y evaluar tendencias generales.

## Contenido del Repositorio

- **Descomposición de Series Temporales**: Se realiza una descomposición para analizar los componentes de los caudales, incluyendo tendencia, estacionalidad y ruido.

- **Modelado Autorregresivo**: Se aplican modelos autorregresivos de orden 1 a 4 utilizando tanto OLS (Ordinary Least Squares) como LinearRegression. Estos modelos se evalúan mediante métricas relevantes como el R² ajustado y el error estándar de predicción.

- **Resultados y Conclusiones**: Se presentan los resultados de los modelos, junto con una discusión sobre la capacidad predictiva y la adecuación de cada modelo en función de su complejidad y rendimiento.

## Requisitos

Para ejecutar el análisis, se requiere tener instaladas las siguientes bibliotecas de Python:

- pandas
- numpy
- statsmodels
- scikit-learn
- matplotlib
- seaborn

## Cómo Usar

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener instaladas las bibliotecas necesarias.
3. Ejecuta los notebooks proporcionados para replicar el análisis y obtener los resultados.

Este proyecto busca no solo analizar los caudales de múltiples pozos, sino también contribuir al entendimiento de la gestión de recursos hídricos en la región, proporcionando un enfoque basado en datos para la toma de decisiones.

