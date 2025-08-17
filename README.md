<!-- Insignias -->
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
[![Release](https://img.shields.io/github/v/release/ilermaaz/tfg-neumonia-cnn?label=release)](https://github.com/ilermaaz/tfg-neumonia-cnn/releases)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16890850.svg)](https://doi.org/10.5281/zenodo.16890850)


# Clasificación de Neumonía en imágenes de Rayos X con CNN y Transfer Learning

Este repositorio contiene el Trabajo de Fin de Grado (TFG) orientado a la detección de neumonía a traves de imágenes de rayos X de tórax, usando para ello **redes neuronales convolucionales (CNN)** y **transfer learning**.

Se ha trabajado con una **CNN personalizada**, construida y entrenada desde cero con pesos iniciales aleatorios, asi como con los modelos **DenseNet121** y **ResNet101**, evaluando **Feature Extraction (FE)** y **Fine Tuning (FT)**. Para hacer un análisis posterior entre modelos y técnicas aplicadas.
 
Los experimentos se realizaron con múltiples semillas (0–4) para asegurar la robustez de los resultados, aleatorizando tanto los datos como la inicialización de los modelos.

---

## Modelos utilizados

- **Custom CNN** 
- **DenseNet121**  
  - Feature Extraction (FE)  
  - Fine Tuning (FT)  
- **ResNet101**  
  - Feature Extraction (FE)  
  - Fine Tuning (FT)  

---

## Estructura del repositorio

- `notebooks/` → código de entrenamiento y test 
- `results/` → gráficas, métricas, matrices de confusión, y Excel con resultados
- `models/` → (no incluye pesos, solo documentación)  
- `data/` → instrucciones para descargar el dataset.  

---

## Resultados 

- Evaluación del Rendimiento: **Accuracy, Loss, AUC, Precision, Recall, F1-Score y Especificidad** en test.
- Métricas promediadas en 5 ejecuciones con distintas semillas para: training, validation y test
- Visualizaciones gráficas:  
  - Boxplots de distribución de métricas.
  - History de Accuracy y Loss vs Epochs
  - Matrices de confusión por modelo.
  - Ejemplos de resultados finales, correctos e incorrectos

---

## Datos

El dataset utilizado es **[Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)** (Kaggle).  

> El dataset **no está incluido en este repositorio**.  
Está disponible públicamente bajo licencia **CC BY 4.0**, más detalles en la página oficial.

- Entrenamiento con 5 semillas.  
- División de datos en train/val/test fija.  
- Se aplicaron técnicas de balanceo de clases y data augmentation.

---

## Citar

Si utilizas este repositorio o parte del código, por favor cita:  

> Autor: *Isidro Lerma Sanz*  
> Tutores: *Víctor Manuel Vargas Yun*, *Rafael Ayllón Gavilán*   
> Título: *Clasificación de Neumonía en imágenes de Rayos X con CNN y Transfer Learning*   
> Universidad: [Universidad de Córdoba](https://www.uco.es)  
> Año: 2025  

---
