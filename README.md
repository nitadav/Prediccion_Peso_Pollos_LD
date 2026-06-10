## Prediccion_Peso_Pollos_LD
### Descripción del Proyecto

Este proyecto fue desarrollado como parte del reto técnico para el cargo de Analista de Información en Pronaca.

El objetivo consiste en desarrollar un modelo de Machine Learning capaz de predecir el peso final de pollos de engorde utilizando información productiva, ambiental y biológica proveniente de registros históricos.

### Objetivo

Construir y evaluar modelos predictivos que permitan estimar el peso final de las aves y generar información de apoyo para la toma de decisiones en procesos productivos.

### Metodología

El desarrollo del proyecto incluyó las siguientes etapas:

1.- Comprensión y exploración de los datos.
2.- Evaluación de la calidad de la información.
3.- Tratamiento de variables categóricas mediante Label Encoding.
4.- Creación de la variable derivada Consumo_Acumulado_Estimado.
5.- Análisis exploratorio de datos (EDA).
6.- Entrenamiento de modelos predictivos.
7.- Comparación de resultados mediante métricas de regresión.
8.- Análisis de importancia de variables.
9.- Generación de hallazgos, recomendaciones y conclusiones.

### Modelos Evaluados

- Regresión Lineal
- Random Forest Regressor

### Resultados

Modelo ganador: Regresión Lineal debido a su mejor desempeño general.

- MAE: 72.07
- RMSE: 90.13
- R²: 0.9907

Random Forest:

- MAE: 84.85
- RMSE: 106.71
- R²: 0.9870

### Archivos del Repositorio

- Prediccion_Peso_Pollos_LD.ipynb
- Data_caso_practico.xlsx

### Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
- Power BI (visualización complementaria)
