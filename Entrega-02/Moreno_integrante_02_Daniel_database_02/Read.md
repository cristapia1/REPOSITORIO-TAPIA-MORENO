# Documentación

## Cómo se realizó el proceso 

Como mencioné en la ficha técnica, me mantuve enfocado en responder nuestra hipótesis grupal "La percepción de inseguridad de nuestro país no ha afectado la llegada de turistas extranjeros", por lo que busqué fuentes de datos que me hablaran de una percepción de seguridad desde la comunidad internacional (ya que nos interesa el turismo externo) y datos cuantitativos duros que me dieran información sobre el flujo de viajeros desde el exterior hacia nuestro país. 

Por otra parte, no hay un fecha exacta en la que  se pueda determinar el comienzo de la crisis de seguridad: algunos la adjudican al estallido social inciado en [octubre de 2019](https://www.dw.com/es/la-cronolog%C3%ADa-del-estallido-social-de-chile/a-51407726), mientras que [otros medios la sitúan en 2023](https://www.elmostrador.cl/noticias/opinion/columnas/2024/01/09/el-2024-y-la-crisis-de-seguridad-no-mas-excusas/), con el auge de delitos de mayor connotación social. Es por esto que decidí incluir en el intervalo de tiempo por lo menos 2 años antes del estallido, por lo que el estudio abarca entre 2017 y 2024, considerando también la disponibilidad de datos.

Una vez determinado todo esto. procedí a descargar la base principal y eliminar los datos que no me fueran de utilidad. DEspúes procedí a buscar estudios periódicos sobre la seguridad de los países. Aquí incorporé el índice de paz global, ya que, entre la información, dispuesta se incluía un ranking en el que se posiciona a todos los países del mundo de acuerdo a la "paz" (seguridad) en la que viven sus habitantes (mientras mas próximo al 0, mas pacífico es el país).La recolección de esta información fue manual, ya que encontré los informes de cada año en distintas páginas.

A continuación, quise incluir indicadores de percepción de países específicos hacia Chile, por lo que incluí los niveles de alerta que recomiendan los gobiernos de Canadá y Estados Unidos a sus ciudadanos que quieran venir como turistas hacia acá. Los niveles de alerta estaban clasificados en categorías descriptivas (precauciones normales, precauciones altas, evitar viajes no esenciales y evitar cualquier viaje) , por lo que tuve que transformar a números estas clasificaciones (del 1 al 4, respectivamente). 

Después de esto, junto todos los datos en un archivo excel separado, los reordené (los años en las filas, para tener una noción más clara de las tendencias, por columnas el n° de turistas, porque el turismo es lo que más nos interesa en este proyecto, despúes el ranking del país en el índice, para tener una idea más general y clara de como se distingue a caída de Chile en materias de seguridad y por último los niveles de alerta de los países, para tener una aproximación más detallada a través de casos particulares) y los convertí a formato CSV.

## Lista de fuentes de datos utilizadas: 

Servicio Nacional del Turismo (SERNATUR): Utilizado para obtener los datos de los ingresos de turistas extranjeros a Chile. Estadísticas disponibles en https://www.sernatur.cl/dataturismo/movimiento-turistico-internacional/

Global Peace Index (Índice de Paz Global, abreviado como GPI): Índice elaborado de manera anual por el Institute for Economics and Peace (IEP) que buscar medir que tan pacífico es un país a partir de 23 indicadores agrupados en 3 áreas: Seguridad social e interna (criminalidad, violencia, conflictos sociales, etc.), Conflictos nacionales e internacionales en curso (guerras civiles, disputas externas, tensiones fronterizas, etc.) y grado de militarización (gasto militar o número de armas). Utilizado para obtener el ranking global de Chile año por año (mientras menor sea el número en el ranking, más pacífico es el país) para incluir una referencia indicativa de la percepción que puede tener el resto del mundo de la seguridad en nuestro país. Información recolectada a partir de los informes del estudio de cada año, obtenidos en una vierdad de sitios académicos (ver  carpeta de datos originales para acceder a todos los links).

Recomendaciones de viaje del Gobierno de Canadá https://travel.gc.ca/destinations/chile#risk Utilizado como indicador de la percepción que tiene Canadá hacia nuestro país desde el ámbito del turismo.

Recomendaciones de viaje del Departamento de Estado de EE.UU.: https://travel.state.gov/content/travel/en/traveladvisories/traveladvisories/chile-travel-advisory.html Utilizado como indicador de la percepión que tiene Estados Unidos hacia nuestro áis en el ámbito del turismo.

## Preguntas que se pueden responder: 
-De acuerdo con el Peace Global Index, ¿Como evolucionó la situación de seguridad en Chile entre 2017 y 2024?

-¿Cómo ha variado el ingreso de turistas extranjeros en los últimos años?

-¿Existe una relación entre la percepión que tiene la comunidad internacional hacia Chile y el fluje de turistas extranjeros que este recibe?

