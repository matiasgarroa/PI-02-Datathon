
​
<h1> Proyecto individual 2 - Matias Garro Alou</h1>

## Descripción
​
Simulando ser parte del equipo de Machine Learning de una importante empresa inversora dentro del rubro de la inmobiliaria en Estados Unidos, me han propuesto dos posibles predicciones para elegir. La primera es implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de las propiedades en venta utilizando los datos a mi disposición. Para ello, debo crear la columna category_price, en la cual se consideran las categorías 'low', 'medium' y 'high' y así, el objetivo es predecir si una propiedad pertenece a la categoría de precios bajos (low). La segunda predicción es implementar un modelo de clasificación con aprendizaje no supervisado, utilizando clustering que agrupe las propiedades por las 3 categorías a las que pueden pertenecer, solo usando el dataset de test provisto, eliminando previamente las caracteristicas que presenten nulos.

## Pasos a seguir
​
  * Primero, obtendremos los datos proporcionados, que incluyen información sobre las propiedades en venta, como el precio, la ubicación, el tamaño, entre otros.

  * Despues analizamos nuestros datos y procedemos a transformarlos quitando datos innesesarios, nulos y outliers.

  * Luego, creamos la columna category_price, clasificando las propiedades en las categorías 'low' (precios entre 0 y 999 dólares), 'medium' (precios entre 1000 y 1999 dólares) y 'high' (precios a partir de 2000 dólares).

  * Una vez categorizadas las propiedades, preparamos los datos para el entrenamiento del modelo de clasificación. Esto ya teniendo nuestra limpieza de datos y la selección de las características relevantes, hacemos la división en conjuntos de entrenamiento y prueba.
  
  * Entrenamos un modelo de clasificación supervisado, utilizando varios algoritmos de aprendizaje automático hasta encontrar el más adecuado para el problema.
  
  * Utilizamos el modelo entrenado para hacer predicciones sobre el conjunto de prueba y evaluamos su desempeño.
  
  * Finalmente, finalmente guardamos los archivo en .csv

## Contacto

  * [LinkedIn](https://www.linkedin.com/in/mat%C3%ADasgarroalou/)
​