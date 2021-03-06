# Space AG Data Analyst Challenge

SpaceAG es una empresa que da herramientas para ayudar al agricultor a tomar mejores decisiones. Dentro de las herramientas usadas están los datos adquiridos de las imágenes de satélite, entre ellos el NDVI.

## NDVI

El NDVI es un índice de vegetación que mide el vigor de las plantas, es decir, una medición indirecta de la salud de la planta. Los valores de este índice van de -1 a 1.  A mayor valor de NDVI en un determinado pixel de la imagen entonces se espera una mayor biomasa del cultivo, es decir un cultivo más sano. A menores valores de NDVI se espera una menor biomasa o un área de vegetación o cultivo enferma. Asimismo, los valores de vegetación están entre 0.2 a 1 de NDVI. Así también, el suelo generalmente tienen valores negativos de NDVI hasta valores de 0.2 en este índice. Como información adicional, la presencia de nubes sobre el área evaluar afecta el promedio del NDVI.

Algunos agricultores de paltos piensan que puede existir una relación entre el NDVI con el rendimiento (Kg/Ha) del cultivo.

## El desafío

En este reto vamos a explorar el ndvi de un campo. Estos son los objetivos a lograr:

1.  Extraer las bandas de satélite de Sentinel 2 usando Sentinel Hub para la lista de fechas disponibles que te brindamos en [SentinelHubImage-available_dates.xlsx](SentinelHubImage-available_dates.xlsx).
Puedes encontrar más información de como lograr esto [aquí](https://sentinelhub-py.readthedocs.io/en/latest/examples/ogc_request.html).
2.  Extraer los valores de NDVI promedio para cada lote para cada una de las fechas. __Cada lote es un feature del [geojson adjunto](farm_map.json) en el repositorio.__
3.  Guardar las imágenes de NDVI de cada lote y cada fecha.
4.  Hacer un análisis de los datos obtenidos para obtener insights de cómo el NDVI se comporta en el tiempo para los diferentes lotes.

__Tienes 72h para completar este desafío. Te sugerimos usar Colab o Jupyter Notebook para este desafío.__

### Dudas o preguntas ?

Si tienes alguna duda o pregunta escribe a adolfo@spaceag.co

__Mucha suerte :)__
