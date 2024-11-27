# Análisis de Churn de Clientes

Este proyecto tiene como objetivo predecir la tasa de abandono (churn) de clientes utilizando técnicas de Machine Learning. A través de un análisis exploratorio de datos (EDA) y la implementación de varios modelos, se busca identificar patrones en el comportamiento del cliente que puedan ayudar a las empresas a mejorar la retención.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Datos](#datos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Modelos Implementados](#modelos-implementados)
- [Resultados](#resultados)

## Descripción del Proyecto

Este proyecto utiliza un conjunto de datos extraído de Google Sheets que contiene información sobre clientes y su comportamiento. Se realiza un análisis exploratorio para limpiar y preparar los datos, seguido de la implementación de varios modelos de Machine Learning para predecir el churn.

## Tecnologías Utilizadas

El proyecto se desarrolla utilizando varias bibliotecas y herramientas en Python, incluyendo:

- **Python**: Lenguaje de programación utilizado para el análisis y modelado.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **NumPy**: Biblioteca para operaciones numéricas y manejo de arrays.
- **Seaborn**: Biblioteca para visualización de datos basada en Matplotlib.
- **Matplotlib**: Biblioteca para crear gráficos y visualizaciones.
- **Scikit-learn**: Biblioteca para implementar algoritmos de Machine Learning.
- **Keras**: API de alto nivel para construir y entrenar modelos de redes neuronales.
- **XGBoost**: Biblioteca optimizada para el entrenamiento de modelos basados en árboles.

## Datos

Los datos utilizados en este análisis provienen de una hoja de cálculo de Google Sheets. El identificador de la hoja es:
Id_planilla = '1lJuHZIl-8iYOoi5cfYmnVoQq-RBl_2Yu2XIsqsjOvQA'


El conjunto de datos incluye características demográficas y comportamentales de los clientes, así como la variable objetivo `Churn`, que indica si un cliente ha abandonado la compañía (1) o no (0).

## Instalación

Para ejecutar este proyecto, asegúrate de tener Python instalado en tu sistema. Luego, puedes instalar las dependencias necesarias utilizando pip:

bashpip
install pandas numpy seaborn matplotlib scikit-learn keras xgboost

## Modelos Implementados
Se implementaron los siguientes modelos para predecir el churn:
Random Forest: Un modelo basado en árboles que combina múltiples árboles de decisión para mejorar la precisión.
Support Vector Machine (SVM): Un potente clasificador que busca encontrar el hiperplano óptimo que separa las clases.
Gradient Boosting: Un método que construye modelos secuenciales que corrigen los errores del modelo anterior.
XGBoost: Una implementación optimizada del boosting que es rápida y eficiente.
Redes Neuronales: Un modelo flexible que utiliza múltiples capas para aprender patrones complejos en los datos.
Cada modelo fue evaluado utilizando métricas como la matriz de confusión, F1-score y AUC-ROC.
## Resultados
Los resultados obtenidos mostraron que el modelo Gradient Boosting tuvo el mejor rendimiento con un AUC-ROC aproximado de 0.8561, seguido por Random Forest con un AUC-ROC de 0.8554. Estas métricas indican la capacidad del modelo para discriminar entre clientes que abandonan y aquellos que permanecen.
