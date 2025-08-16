# data/

En esta carpeta irán los datos utilizados para entrenar y evaluar los modelos.  
Por limitaciones de tamaño, el dataset no está incluido en este repositorio.
El dataset está disponible públicamente bajo licencia CC BY 4.0, más detalles en la página oficial del dataset

## Cómo obtener los datos

El dataset utilizado es **Chest X-Ray Images (Pneumonia)** de Kaggle:  
[https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

### Pasos para descargarlo:

1. Crea una cuenta en [Kaggle](https://www.kaggle.com/).
2. Descarga el dataset desde la pestaña **Download** o ejecútalo directamente en un notebook de Kaggle añadiéndolo como *Dataset*.
3. La estructura de carpetas es la siguiente:

```text
chest_xray/
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
