# Desafio_politicas_azules
Colaboradores:

1.- Alberto Gracía de Lara

2.- Alberto Martín Gelado

3.- Ángel Cebriá Morales

4.- Diego J Martínez Tortosa
 
5.- Jorge Férnandez Ávila

6.- Silvia Quintana González
## Estracción de datos
Hemos volcado datos de los siguientes enlaces:

https://aedyr.com/cifras-desalacion-espana/#:~:text=Si%20bien%20el%20principal%20uso,en%20otros%20lugares%20del%20mundo.	

https://especiales.datadista.com/medioambiente/acuiferos-sobrexplotados-contaminados-espana/	

https://www.miteco.gob.es/es/agua/temas/planificacion-hidrologica/plan_dsear_libro_castellano_tcm30-538718.pdf	

https://www.elconfidencial.com/medioambiente/agua/2022-12-03/esperamos-reutilizar-depuradora-llover-cantaros_3530828/

https://www.epdata.es/datos/graficos-situacion-agua-mundo-espana/333	

https://www.epdata.es/datos/embalses-boletin-hidrografico/54

https://www.newtral.es/cuencas-capacidad/20220813/

https://miteco.maps.arcgis.com/apps/dashboards/912dfee767264e3884f7aea8eb1e0673	

https://www.iagua.es/data/infraestructuras/embalses

https://www.epdata.es/datos/graficos-situacion-agua-mundo-espana/333

https://www.miteco.gob.es/es/agua/legislacion/Observatorio_Nacional_Sequia_2_legislacion.aspx	

https://www.iagua.es/blogs/ignasi-servia-goixart/bulos-sequia-capitulo-1-hidroelectricas-vacian-embalses	

http://www.madrid.org/iestadis/fijas/estructu/sociales/estructuagua.htm	

https://www.ine.es/jaxiT3/Datos.htm?tpx=48783#!tabs-tabla	

https://tableau.apps.fao.org/views/ReviewDashboard-v1/result_country?%3Adisplay_count=n&%3Aembed=y&%3AisGuestRedirectFromVizportal=y&%3Aorigin=viz_share_link&%3AshowAppBanner=false&%3AshowVizHome=n


https://www.embalses.net/ 

## Gestión y limpieza de datos (EDA)
Una vez descargado los datos, hemos realizado un análisis inicial para investigar la utilidad de los datos. Limpiamos aquellos que resultarón interesantes y que estaban relacionados con lo que queríamos realizar, para acabar realizando una serie de preguntas cuyas respuestas salían de los datos obtenidos.

Por otro, también hemos realizado algunos EDAs mostrando información y tablas sobre los datos anteriores.

## Machine Learning
Con el objetivo de obtener respuesta de la última pregunta, hemos entrenado un modelo de regresión para predecir el volumen de agua de los embalses dentro de 1 año y así poder compararlo con el dato actual.

## Cloud 
Hemos realizado una instancia en EC2 para que la rama de Full Stack pueda consumirla como APIrest el modelo de regresión anterior. Además, también les facilitamos un json con la ubicación de todos los embalses de España para que pudiesen representarlo con OpenStreetMap.


