# Documentación 

## Cómo se realizó el proceso de visualización

Ya con la base de datos limpia, procedí a codificar la visualización en Google Colab, utilizando las bibliotecas de Pandas (para manipular  y analizar datos) y Altair (para crear el gráfico), todo esto con el objetivo de mostrar la evolucion de turistas por país y mes. 

Una vez cargada la base, procedí a especificar que la separación era con puntos y coma. Después procedí a convertir la tabla a formato largo porque tengo entendido que eso facilita el trabajo con los datos. Además, me aseguré de que estuvieran limpios y tuve especial ojo con que se mostraran bien los meses y en español, para lo que tuve que crear un "diccionario" y etiquetas para incluir en el data frame. 

También creé una columna simplificada con el mes y año (conteniendo la cifra) de cada país de origen entre 2009 y 2025, como aparece originalmente en mi base limpia.

Delimité como países objetivo a Argentina, Brasil, Perú, BOlivia, Estados Unidos y COlombia, al ser estos los países de origen que más aportaron con turistas en 2025. Decidí incluir solo estos para no saturar la visualización y no hacer de esta una experiencia más engorrosa. 

Decidí adempas solo utilizar intervalos de tres meses SOLO EN EL EJE X, esto para no saturarlo, ya que cuando lo visualicé preliminarmente este era inenteligible por el exceso de caracteres.

Finalmente, procedí a codificar el gráfico de barras con altair. Desarrollé incialmente un grafico de lineas, pero como encontré muy engorroso visualizar la información tanto de los países como posibles tendencias, preferí utlizar este, teniendo cuidado con todos los detalles, desde que el titulo fuera lo suficientemente descriptivo como hasta que se visualizaran bien los meses en el eje x.

## Cómo se procesó la base de datos

Utilicé como insumo una serie de bases facilitadas por el Serntaur y la Subsecretaría de Turismo que incluía, entre otros, una tabla con los principales países de procedencia de los turistas que entraban a Chile entre 2008 y 2025, a la cual le hice los siguientes cambios: 

-Reescribí todas las celdas de fechas, eliminando la fila que indicaba solo los años para que quedara solo una con el formato "abr-09". 
-Quité los totales de de los años y de los continentes, ya que al ser un gráfico que muestra los flujos meses a mes esta era una variable que no me interesaba mostrar.
-agregué una columna que especifica el continente en el que se encuentra dicho país, para futuras visualizaciones. 
-Transforme el archivo a un csv delimitado por comas.

## Preguntas que se pueden responder con la visualización 

¿Cuál es el país que aporta más turistas a Chile a lo largo del tiempo?

¿Cómo ha cambiado el flujo de turistas desde el estallido social (2019) o la pandemia de covid-19 (entre 2020 y 2022)?

¿Se observa una recuperación en los últimos años tras las caídas por crisis sociales o sanitarias?

¿Cuáles son los meses con mayor o menor afluencia de turistas por país?
