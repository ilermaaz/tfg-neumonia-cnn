<!-- Insignias -->
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
[![Release](https://img.shields.io/github/v/release/ilermaaz/tfg-neumonia-cnn?label=release)](https://github.com/ilermaaz/tfg-neumonia-cnn/releases)
![DOI](https://img.shields.io/badge/DOI-pending-lightgrey.svg)

🚀 *Repositorio del TFG sobre clasificación de neumonía en rayos X usando CNN personalizada y transfer learning (DenseNet121 y ResNet101). Incluye notebooks, resultados y guías para reproducir los experimentos.*  

# Clasificación de Neumonía en Rayos X (TFG)

Este repositorio contiene el trabajo de Fin de Grado (TFG) orientado a la detección automática de neumonía en imágenes de rayos X de tórax mediante **redes neuronales convolucionales (CNN)** y **transfer learning**.

Se ha trabajado con una **CNN personalizada** y con los modelos **DenseNet121** y **ResNet101**, evaluando tanto en modo **Feature Extraction (FE)** como en **Fine Tuning (FT)**.  
Los experimentos se realizaron con múltiples semillas (0–4) para asegurar la robustez de los resultados.

---

## ✨ Modelos utilizados

- **Custom CNN** (diseñada y entrenada desde cero).  
- **DenseNet121**  
  - Feature Extraction (FE)  
  - Fine Tuning (FT)  
- **ResNet101**  
  - Feature Extraction (FE)  
  - Fine Tuning (FT)  

---

## 📂 Estructura del repositorio

- `notebooks/` → cuadernos de entrenamiento, validación y test (5 semillas).  
- `results/` → métricas, gráficas y matrices de confusión.  
- `models/` → pesos del modelo (no incluidos por tamaño; ver nota).  
- `data/` → instrucciones para obtener el dataset original.  

---

## 📊 Resultados principales

- Se evaluaron **Accuracy, AUC, Loss, Precision, Recall y Especificidad** en test.  
- Se reportan métricas promediadas en 5 ejecuciones con distintas semillas.  
- Ejemplo de visualizaciones:  
  - Boxplots de distribución de métricas.  
  - Matrices de confusión por modelo.  

---

## 📁 Datos

El dataset utilizado es **[Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)** (Kaggle).  

> ⚠️ Por limitaciones de tamaño, el dataset **no está incluido en este repositorio**.  
Está disponible públicamente bajo licencia **CC BY 4.0**, más detalles en la página oficial.  

---

## 📌 Semillas y configuración experimental

- Entrenamiento con 5 semillas distintas (0–4).  
- División de datos en train/val/test fija.  
- Se aplicaron técnicas de balanceo de clases y data augmentation.  

---

## 📖 Citar

Si utilizas este repositorio o parte del código, por favor cita:  

> Autor: *Isidro Lerma Sanz*  
> Título: *Clasificación de Neumonía en Rayos X con CNN y Transfer Learning* (TFG)  
> Universidad: [nombre de tu universidad]  
> Año: 2025  

---

## 📜 Licencia

Este proyecto está publicado bajo licencia **MIT**.  
El dataset está bajo licencia **CC BY 4.0** (Kaggle/Mendeley Data).
