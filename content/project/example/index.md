---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
slides: example
summary: Explorando el impacto de las sobre la actividad comercial y residencial en los barrios de CABA.
# tags:
# - Deep Learning
title: Impacto de las ciclovías sobre los alquileres en CABA
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

La red de ciclovías protegidas de la Ciudad Autónoma de Buenos Aires (CABA) es un entramado de carriles exclusivos para bicicletas de más de 300 km de longitud.

Este proyecto de investigación busca indagar sobre el impacto que tuvo esta infraestructura víal sobre el precio de los bienes raíces adyacentes, bien sean comerciales o residenciales.

Este impacto pudiera ser negativo o positivo en ambos casos:

-   Alquileres comerciales: pudieran apreciarse ante las mejoras de accesibilidad de peatones y cicliestas. Sin embargo, denuncias de comerciantes sugieren que entorpecen los servicios de carga/descarga, la accesibilidad de clientes en automovil, y la instalación de plataformas gastronómicas en la calzada. 

-   Alquileres residenciales: Las ciclovías mejoran la accesibilidad de peatones y ciclistas, pero los propietarios de vehículos automotores afirman experimentar lo contrario. Por ende, los alquileres residenciales demandados por peatones deberían verse apreciados, mientras que aquellos demandados por propietarios de automotores deberian verse depreciados. 

Usaremos un Diff-in-Diff con controles espaciales para testear si hay un salto discreto en los precios relativos de los inmuebles afectados tras la construcción de las ciclovías. Para ello usaremos datos de la ubicación y fecha de construcción de 40% de las ciclovías protegidas de CABA, y precios de publicaciones de alquiler residenciales y comerciales en el mismo período.