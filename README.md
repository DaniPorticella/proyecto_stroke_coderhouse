Proyecto Final – Data Science (CoderHouse): Predicción de ACV

Este repositorio contiene el proyecto final de la carrera de Data Science de CoderHouse, desarrollado de manera progresiva a lo largo de dos entregas.
El objetivo es aplicar técnicas de análisis de datos, visualización y modelado predictivo sobre un dataset clínico, siguiendo un flujo completo de Data Science desde la exploración hasta la evaluación del modelo.

📂 Contenido
🩺 ProyectoParteIII_Porticella.ipynb

Notebook único que integra las tres etapas del proyecto:

Abstracts de ambas entregas (análisis exploratorio y modelado predictivo)

Planteo de preguntas e hipótesis

Análisis exploratorio inicial del dataset

Identificación y tratamiento de valores faltantes

Creación de variables derivadas (obesidad, hiperglucemia, edad ≥60 años)

Visualizaciones univariadas, bivariadas y multivariadas con interpretaciones

Construcción de un pipeline completo con preprocesamiento, selección de características (SelectKBest) y modelo de Regresión Logística

Optimización de hiperparámetros (k y C) mediante GridSearchCV

Evaluación final del modelo con métricas:

ROC-AUC: 0.84

Recall: 0.82

Precision: 0.14

📊 Dataset

Stroke Prediction Dataset – Kaggle
🔗 https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Dataset con información clínica y demográfica de 5110 individuos, incluyendo:

Variables sociodemográficas: edad, género, estado civil, tipo de trabajo, tipo de residencia

Factores clínicos: hipertensión, enfermedad cardíaca, IMC, glucemia

Hábitos: tabaquismo

Variable objetivo: stroke (indica si el paciente presentó o no un accidente cerebrovascular).

🚀 Objetivo del proyecto

Explorar los factores asociados al riesgo de accidente cerebrovascular (ACV), identificar patrones relevantes y construir un modelo predictivo supervisado que permita estimar la probabilidad de ACV.
El enfoque prioriza la sensibilidad (recall), buscando minimizar los falsos negativos, ya que en contextos clínicos resulta más relevante detectar posibles casos de riesgo, aunque se generen falsos positivos.

🛠️ Tecnologías utilizadas

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook / Google Colab

✨ Autoría

Proyecto realizado por Daniela Porticella
Carrera de Data Science – CoderHouse (Comisión 77695, 2025)
