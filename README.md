# Predicción de Calidad del Vino con Azure Machine Learning

## Descripción del Proyecto

Este proyecto implementa un flujo de trabajo de MLOps de extremo a extremo para entrenar un modelo de clasificación que predice la calidad del vino (buena/mala) basándose en sus características fisicoquímicas. Todo el proceso de entrenamiento se ejecuta en Azure Machine Learning y el código se gestiona a través de este repositorio de GitHub.

---

### Objetivo del Problema

El objetivo es automatizar el proceso de evaluación de la calidad del vino, proporcionando una alternativa consistente y basada en datos al método tradicional de cata humana.

---

### Dataset

El conjunto de datos utilizado es el "Wine Quality Data Set" del repositorio de Machine Learning de la UCI. Puedes encontrar más información [aquí](https://archive.ics.uci.edu/ml/datasets/wine+quality).

---

### Estructura del Proyecto

├── .github/workflows/ # Define el pipeline de CI con GitHub Actions.
├── data/ # Almacenamiento local temporal de datos (ignorado por Git).
├── notebooks/ # Notebooks para análisis exploratorio (EDA).
├── src/ # Código fuente del proyecto (preprocesamiento, entrenamiento).
├── .gitignore # Archivos y carpetas a ignorar por Git.
├── LICENSE # Licencia del proyecto.
├── README.md # Documentación del proyecto.
├── requirements.txt # Dependencias de Python.
└── job.yml # Definición del Job de entrenamiento para Azure ML.