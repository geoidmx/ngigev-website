---
layout: post
title:  "Fuente de Datos Institucionales"
date:   2022-11-10 12:15:38 -0600
categories: datos
author: "Zitlaly Flores, Antonio de Jesús"
permalink: /fuentes-de-datos/
image: /assets/img/fuentes.jpg
---

Los datos de los institutos oficiales de los Estados Miembros del IPGH que participan en este proyecto son una de las fuentes mas importantes para la herramienta, sin ellos no seria posible realizar una comparación que nos permitiera visualizar las diferencias con los datos voluntarios. 

Para este propósito, se examinaron las características de los portales de información geográfica de los institutos participantes, y se realizaron los acercamientos con cada uno de ellos, en los que se presentaron las características de la información disponible, formatos, escalas, proyecciones cartográficas, tipos de representaciones espaciales y metadatos.

De este ejercicio, listamos las fuentes oficiales publicas de cada país participante con las coberturas de información requeridas para el ejercicio de comparación:


##### Colombia
Pagina Oficial:  
[https://www.colombiaenmapas.gov.co/][mapas-colombia]

Servicios WFS:
* https://mapas.igac.gov.co/server/services/carto/carto500000colombia2016/MapServer/WFSServer
* https://mapas.igac.gov.co/server/services/carto/carto100000colombia2019/MapServer/WFSServer
* https://mapas.igac.gov.co/server/services/carto/carto25000colombia2017/MapServer/WFSServer

Coberturas de Información Requerida:  
Vialidades con nombres (limitados) de ejes viales, no cuenta con información de poblados o topónimos.

##### Costa Rica
Pagina Oficial:  
[https://www.snitcr.go.cr][mapas-costarica]

Servicios WFS:
* https://geos.snitcr.go.cr/be/IGN_5/wfs
* https://geos.snitcr.go.cr/be/IGN_NG/wfs
* https://geos.snitcr.go.cr/be/IGN_25/wfs

Coberturas de Información Requerida:  
Vialidades con nombres, información de poblados o topónimos.

##### México
Pagina Oficial:  
[https://www.inegi.org.mx/default.html][mapas-mexico]

Servicios WFS:
No cuenta con servicio WFS  

Coberturas de Información Requerida: 
cuenta con basta información, red vial y poblados a nivel Nacional y por estados, en formato Shape.

##### Panamá
Pagina Oficial:  
[http://www.ipde.gob.pa][mapas-panama]

Servicios WFS:
* WFS de poblados:  
https://aig-hg-portal.innovacion.gob.pa/aigserver/services/Hosted/Lugar_Poblado/MapServer/WFSServer?service=wfs&request=getcapabilities
* https://geo-01.innovacion.gob.pa/geoserver/wfs?access_token=3d966b2d4f1011ed997e005056871877?format_options%3Dcharset%3AUTF-8&typename=geonode%3Acarretera&outputFormat=SHAPE-ZIP&version=1.0.0&access_token=3d966b2d4f1011ed997e005056871877

Coberturas de Información Requerida:  
Información de poblados o topónimos.

##### República Dominicana
Pagina Oficial:  
[http://iderd.ign.gob.do/][mapas-republicadominicana]

Servicios WFS:
* http://iderd.ign.gob.do/geoserver/wfs?SERVICE=WFS&VERSION=1.1.0&REQUEST=GetCapabilities
* https://inventariovial.mopc.gob.do/gvsigonline/core/load_public_project/DIGRE/

Coberturas de Información Requerida:  
Información de poblados o topónimos.


[mapas-colombia]: https://www.colombiaenmapas.gov.co/
[mapas-costarica]: https://www.snitcr.go.cr
[mapas-mexico]: https://www.inegi.org.mx/default.html
[mapas-panama]: http://www.ipde.gob.pa
[mapas-republicadominicana]: http://iderd.ign.gob.do/