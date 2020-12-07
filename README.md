<p align="center">
  <img src="https://www.thespruce.com/thmb/IO1gzQwXXLpe1sulArancBb6ZDM=/4288x2848/filters:fill(auto,1)/close-up-of-diamonds-713874959-5b859ff346e0fb0025ece8f3.jpg" width="350" title="hover text">
  
</p>

# Competición Kaggle

En este proyecto vamos a hacer una competición de Kaggle, haciendo la mejor predicción de precios de diamantes.

Vamos a usar distitnos modelos: 
  - LinearRegressor
  - KNNRegressor
  - RandomForest -
  - GradientBoosting

Con distintos encoder:
  - Label encoder
  - Ordinal encoder 
  - Standar Scales

# Descripción
 Lo primero que hicimos fue explorar el data  y comprobamos que había columnas que no eran numéricas y las modificamos con los encoder antes mencionados.


# Mis mejores predicciones.

- RandomForestRegressor, entrenado con todo el set de train : MSE = 0.0012073939648869134.    sample_submission.csv

 - GradientBoostingRegressor, entrenado con todo el set de train escalando el set, 
MSE: 0.004898936459726063,   sample_submission2.csv


- RandomForestRegressor, entrenado con todo el set de train escalando el set,
MSE : 0.0011610609955258926, sample_submission3.csv

 - RandomForestRegressor, entrenado con todo el set de train haciendo un encoding Label Encoder, MSE : 0.0011869787669731807, sample_submission4.csv

# Estructura del repo:
 - data : carpeta donde estas los sets de entrenamiento y test. Y las predicciones que subimos a Kaggle.

 - Notebooks : donde estan todos lo jupyter en los que hemos hecho las predicciones y las limpiezas de los data.

 # Enlaces
 
 https://www.bluenile.com/es/education/diamonds/colour

 [Presentanción google slides](https://docs.google.com/presentation/d/1eShTnp2B3cTbsve9OWEt6qZckL5xDKkcPIv7YytMJjw/edit#slide=id.p)

 # Librerías 
  - sklearn
  - pandas
  - Numpy