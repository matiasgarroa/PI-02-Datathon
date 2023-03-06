# Proyecto individual 2 - Matias Garro Alou

En este proyecto simulamos ser parte del equipo de Machine Learning de una importante empresa inversora en el rubro de la inmobiliaria en Estados Unidos. Se nos han propuesto dos posibles predicciones para elegir: implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de las propiedades en venta, o implementar un modelo de clasificación con aprendizaje no supervisado utilizando clustering.

## Descripción del problema

La primera predicción consiste en crear la columna category_price, donde las propiedades se clasifican en las categorías 'low', 'medium' y 'high', y luego utilizar un modelo de clasificación supervisado para predecir si una propiedad pertenece a la categoría de precios bajos (low). </br>

La segunda predicción consiste en utilizar un modelo de clasificación con aprendizaje no supervisado, utilizando clustering, para agrupar las propiedades por las 3 categorías a las que pueden pertenecer, solo utilizando el dataset de test provisto y eliminando previamente las características que presenten nulos.

## Pasos a seguir

* Obtener los datos proporcionados que incluyen información sobre las propiedades en venta, como el precio, la ubicación, el tamaño, entre otros.
* Analizar y transformar los datos quitando los datos innecesarios, nulos y outliers.
* Crear la columna category_price, clasificando las propiedades en las categorías 'low' (precios entre 0 y 999 dólares), 'medium' (precios entre 1000 y 1999 dólares) y 'high' (precios a partir de 2000 dólares).
* Preparar los datos para el entrenamiento del modelo de clasificación, realizando la limpieza de datos y la selección de las características relevantes y la división en conjuntos de entrenamiento y prueba.
* Entrenar un modelo de clasificación supervisado, utilizando varios algoritmos de aprendizaje automático hasta encontrar el más adecuado para el problema.
* Utilizar el modelo entrenado para hacer predicciones sobre el conjunto de prueba y evaluar su desempeño.
* Guardar los archivos en formato .csv.

## Contacto

  * [LinkedIn](https://www.linkedin.com/in/mat%C3%ADasgarroalou/)
