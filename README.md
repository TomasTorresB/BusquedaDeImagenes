# BusquedaDeImagenes

Consiste en un buscador de imágenes a partir de su descripción en palabras.
Para hacer la busqueda primero se hace un conversión de la oración de descripción a un descriptor de texto, luego usará un modelo de 
regresión ya entrenado para obtener como salida un descriptor visual. Con el vector de descripción se busca entre los vectores visuales de 
de la colección de imágenes y se retorna la imágen más cercana.

Los datos de training y testing se pueden encontrar en el siguiente drive 
https://drive.google.com/open?id=1ZTIyH35KVE0WK0QdWzi_b8Ltg9FaEWSI.

Si el método de obtener descriptores de texto es usando FastText de Jorge Perez, es necesario descargar el vocabulario de: 
https://drive.google.com/open?id=1ZTIyH35KVE0WK0QdWzi_b8Ltg9FaEWSI.

Es necesario ejecutar el código en jupyter notebook. Ahí se encuentran más detalles de como entrenar la red y que métodos
de evaluación se ocuparon.
