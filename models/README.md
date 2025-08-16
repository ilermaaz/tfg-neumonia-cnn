# models/

En esta carpeta irían los modelos entrenados en formato `.h5` (Keras/TensorFlow).  

En este repositorio **no se incluyen los pesos entrenados** porque:  
- No se guardaron en disco durante los entrenamientos en Kaggle (eran temporales en RAM).  
- Además, suelen ocupar bastante espacio y GitHub no permite subir ficheros >100 MB.  

Los modelos pueden regenerarse fácilmente ejecutando los notebooks en `notebooks/`.  

## Modelos utilizados en este trabajo
- **Custom CNN** (entrenada desde cero).  
- **DenseNet121**  
  - Feature Extraction (FE)  
  - Fine Tuning (FT)  
- **ResNet101**  
  - Feature Extraction (FE)  
  - Fine Tuning (FT)  

En el futuro, si se desea publicar los pesos, podrían añadirse aquí como *release* de GitHub o mediante [Git LFS](https://git-lfs.com/).
