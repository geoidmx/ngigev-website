---
layout: post
title: "Analísis Exploratorio de Datos"
date: 2022-11-10 12:15:38 -0600
categories: datos
author: "Zitlaly Flores, Antonio de Jesús"
permalink: /analisis-exploratorio/
image: /assets/img/analisis.jpg
---

Para abordar el tema de integración de información geográfica voluntaria por medio de una comparación con fuentes de datos oficiales, se realizó un análisis contextual desarrollado en las siguientes fases:

##### Análisis de información. 
Se disgregó el alcance del proyecto en los siguientes cuestionamientos:  
* ¿Qué información se va a comparar?,
* ¿En qué formato se encuentra disponible?,
* ¿Cómo hacer una comparación a nivel de elementos espaciales y de atributos?, y,
* ¿Qué herramientas tecnológicas permiten el análisis?  

Se estudiaron las estructuras de las fuentes de información y sus limitantes, considerando dos opciones: la información puede ser obtenida y manipulada por medio de un servicio WFS o bien en formatos estándar para la representación espacial de objetos (GeoJSON o Shapefile). A su vez, se definió la comparación de vialidades (líneas) y poblados (puntuales).  

En la vertiente de herramientas tecnológicas, una vez conocidos los formatos de información y trazando los primeros esquemas de análisis a implementar, se eligieron algunas herramientas que pudieran hacer posible la consulta, descarga, procesamiento, análisis y visualización.  

Por parte de la fuente de datos colaborativos, OSM cuenta con las etiquetas que representan objetos físicos existentes sobre el terreno, y proporciona detalle de la red vial y poblados en diferentes clasificaciones, a nivel mundial.

![image tooltip here]({{ site.url }}/assets/img/toponimos.jpg ){:class="img-fluid"}
Poblados Oficiales vs OSM  


##### Procesamiento de datos.
Una parte medular era saber ¿cómo hacer la comparación espacial y a nivel de atributos para identificar los nombres geográficos?, en esta fase se fueron probando y seleccionando metodologías de análisis espacial mediante ejercicios preliminares con información que los institutos consideraron para esta actividad.  

![image tooltip here]({{ site.url }}/assets/img/data.jpg ){:class="img-fluid"}
Analisis de Geometrias  


##### Análisis de resultados del ejercicio exploratorio.
Aplicando análisis espacial como por ejemplo: sobreposición por diferencia e intersección, definición de áreas de influencia, se trazó un diagrama de operaciones espaciales que fueran más allá del análisis visual, se obtuvieron los primeros resultados con la comparación de áreas pequeñas.  

En esta fase se logró definir toda la arquitectura del desarrollo. El resultado fue una capa de información con los elementos que no existen en la otra fuente de datos, y un archivo de atributos principales (con los nombres de las dos fuentes comparado uno a uno).  

![image tooltip here]({{ site.url }}/assets/img/diferencias.jpg){:class="img-fluid"}
Diferencias entre Datos Institucioles vs OSM
