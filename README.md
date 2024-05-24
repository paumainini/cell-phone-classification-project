# Cell Phone Classification Project

This repository contains the code and materials for the Cell Phone Classification Project, developed by Group 5 as part of a final project. The project aims to predict the category of mobile phones based on their features using ensemble tree models.

## Objective
- Predict the category range of cell phones based on their features.
- Explore various ensemble tree models for classification.
- Optimize hyperparameters to improve model performance.
- Analyze feature importance and dimensionality reduction techniques.

## Directory

- **CellPhone.csv**: CSV file containing the dataset of cell phone features.
  
- **Presentation TP final group 5 (1).pptx**: PowerPoint presentation used to present the final project results.

- **README.md**: Markdown file containing project description, repository directory, and other relevant information in both English and Spanish.

- **TP final group 5.ipynb**: Jupyter Notebook containing the code used for data preparation, model building and evaluation, and result analysis.

## Brief Description
The project utilizes ensemble tree models, particularly XGBoost, to predict the category range of cell phones. The dataset includes various features such as battery energy, processor speed, memory capacity, camera quality, dimensions, and weight of the device. Through hyperparameter optimization and feature analysis techniques, the project achieves a classification accuracy of 91%. Feature importance analysis reveals that attributes like rear camera quality, battery energy, and device weight are significant predictors. However, Recursive Feature Elimination with Cross-Validation (RFECV) highlights additional features like RAM memory and front camera quality. The project contributes to understanding the factors influencing cell phone categorization and the effectiveness of ensemble tree models in predictive tasks.

# Proyecto de Clasificación de Teléfonos Celulares

Este repositorio contiene el código y los materiales para el Proyecto de Clasificación de Teléfonos Celulares, desarrollado por el Grupo 5 como parte de un proyecto final. El objetivo del proyecto es predecir la categoría de teléfonos móviles en función de sus características utilizando modelos de árboles de ensamble.

## Objetivo
- Predecir el rango de categoría de teléfonos celulares en función de sus características.
- Explorar varios modelos de árboles de ensamble para clasificación.
- Optimizar hiperparámetros para mejorar el rendimiento del modelo.
- Analizar la importancia de las características y técnicas de reducción de dimensionalidad.

## Directorio

- **CellPhone.csv**: Archivo CSV que contiene el conjunto de datos de características de teléfonos celulares.
  
- **Presentation TP final group 5 (1).pptx**: Presentación en PowerPoint utilizada para presentar los resultados finales del proyecto.

- **README.md**: Archivo Markdown que contiene la descripción del proyecto, el directorio del repositorio y otra información relevante en inglés y español.

- **TP final group 5.ipynb**: Cuaderno Jupyter que contiene el código utilizado para la preparación de datos, construcción y evaluación de modelos, y análisis de resultados.

## Descripción Breve
El proyecto utiliza modelos de árboles de ensamble, particularmente XGBoost, para predecir el rango de categoría de teléfonos celulares. El conjunto de datos incluye diversas características como la energía de la batería, la velocidad del procesador, la capacidad de memoria, la calidad de la cámara, las dimensiones y el peso del dispositivo. A través de la optimización de hiperparámetros y técnicas de análisis de características, el proyecto logra una precisión de clasificación del 91%. El análisis de la importancia de las características revela que atributos como la calidad de la cámara trasera, la energía de la batería y el peso del dispositivo son predictores significativos. Sin embargo, la Eliminación Recursiva de Características con Validación Cruzada (RFECV) destaca características adicionales como la memoria RAM y la calidad de la cámara frontal. El proyecto contribuye a comprender los factores que influyen en la categorización de teléfonos celulares y la efectividad de los modelos de árboles de ensamble en tareas predictivas.
