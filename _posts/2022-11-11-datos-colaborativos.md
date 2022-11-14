---
layout: post
title:  "Fuente de Datos Colaborativos"
date:   2022-11-10 12:15:38 -0600
categories: datos
author: "Antonio de Jesus"
permalink: /datos-colaborativos/
image: /assets/img/map.jpg
---

Otra fuente de datos importante para este proyecto son los datos colaborativos, OpenStreetMaps - OSM es comunidad de colaboradores que esta continuamente realizando contribuciones para crear, mantener y actualizar datos a lo largo de todo el mundo. 

Basada en datos abiertos, OSM es la mayor base de datos gratuita, con la que puedes usar libremente la información para cualquier propósito, siempre y cuando des crédito a OpenStreetMap y a sus colaboradores, y que cuenta con el tipo de información y detalle que se busca para este proceso.

No obstante, es necesario obtener esta información desde OSM para realizar los análisis pertinentes de nuestra objetivo.

##### Extracción de Datos en OSM

Para obtener los datos de OSM usamos la [API Overpass][overpass-api], que mantiene una copia de la base de datos principal al día con estas actualizaciones minuciosas y las proporciona para su búsqueda. No sólo existen instancias públicas a las que se puede enviar una solicitud. También es posible tener una instancia propia porque la API de Overpass es de código abierto, con una instalación sencilla y requisitos de hardware razonables.

La API de Overpass está diseñada para responder a las consultas de otro software a través de Internet. Por esa razón recibió el nombre de API. Por lo tanto, en el capítulo Herramientas descendentes se explica la conexión directa de muchas aplicaciones descendentes populares.

Una manera simple de conocer la extracción de datos es a través de [Overpass Turbo][overpass-turbo] una aplicación web que permite puede ejecutar consultas Overpass API y analizar los datos resultantes de OSM de forma interactiva en un mapa.

![image tooltip here]({{ site.url }}/assets/img/overpass.jpg){:class="img-fluid"}
Consulta de caminos en Overpass Turbo


[overpass-api]: https://overpass-api.de/
[overpass-turbo]: https://overpass-turbo.eu/