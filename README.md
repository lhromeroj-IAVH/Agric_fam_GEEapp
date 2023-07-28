# Agric_fam_GEEapp
Aplicación desarrollada en Google Earth Engine para la visualización de variables agroclimáticas y su solapamiento con polígonos de interés

# Objetivo
Desarrollar una plataforma de visualización e interpretación de datos climáticos para favorecer la agricultura familiar en los países latinoamericanos. Caso de estudio: Colombia.

# Descripción
Esta plataforma de visualización fue desarrollada para la Hackaton organizada por la Red CLARA (Cooperación Latino Americana de Redes Avanzadas), BELLA II (Building the Europe Link to Latin America and the Caribbean) y Géant (Networks * Services * People), por los investigadores Sergio Enrique Rojas Sánchez, Gabriel Alejandro Perilla Suárez, Elkin Alexi Noguera Urbano, Cristian Alexander Cruz Rodríguez y Luis Hernando Romero Jiménez del Instituto de Investigación de Recursos Biológicos Alexander von Humboldt.

Entre el amplio catálogo de productos disponibles del programa Copernicus, se eligió el producto ERA5 - Land Monthly Aggregated - ECMWF Climate Reanalysis, priorizando las siguientes variables:

- Temperatura del aire a 2 m sobre la superficie de la tierra (°C)
- Temperatura del suelo entre 0 y 28 cm de profundidad (Esta capa se obtuvo promediando las temperaturas del suelo entre 0 y 7 cm y entre 7 - 28 cm) (°C)
- Volumen de agua en el suelo entre 0 y 28 cm (promediando el volumen de agua del suelo entre 0 y 7 cm y entre 7 y 28 cm) (%)
- Evaporación en suelo (mm)
- Evaporación en dosel (mm)
- Evapotranspiración (mm)
- Evaporación potencial (mm)
- Evaporación total (mm)
- Precipitación total (mm)
- Índice de área foliar

Entre los polígonos de importancia, se presentan tres productos que obedecen a las delimitaciones de áreas político-administrativas, definidas como entidades territoriales de manejo para la población y el control de la expansión agrícola:

- **Veredas:** corresponden a la primera expresión territorial, social y económica de un municipio, definidas por el Estado colombiano.
- **Frontera Agrícola:** área en donde se armoniza el emprendimiento agropecuario competitivo con el desarrollo sostenible. En otras palabras, el desarrollo rural de la mano con la protección de la biodiversidad. En Colombia, esta área corresponde aproximadamente a 40 millones de hectáreas (MinAgricultura, 2018).
- **Reservas Campesinas:** Estas zonas tienen por objeto fomentar y estabilizar la economía campesina, superar las causas de los conflictos sociales que las afecten y, en general, crear las condiciones para el logro de la paz y  la justicia social en las áreas respectivas (MinAgricultura).
- **Áreas probables de agricultura familiar:** Sistema de producción y organización gestionado y operado por mujeres, hombres, familias, y comunidades campesinas, in-dígenas,  negras,  afrodescendientes,  raizales  y  palenqueras  que  conviven  en  los  territorios  rurales  del  país (Arévalo et al, 2020). En  este  sistema  se  desarrollan  principalmente  actividades  de  producción, transformación y comercialización de bienes y servicios agrícolas, pecua-rios, pesqueros, acvícolas y silvícolas; que suelen complementarse con actividades no agropecuarias. Esta diversificación de actividades y medios de vida se realiza predo-minantemente a través de la gestión y el trabajo familiar, asociativo o comunitario, aunque también puede emplearse mano de obra contratada (MinAgricultura, 2017).

# Bibliografía
Arévalo, L., Cortés, C., Gamboa, W., Cruz, R., Moyano, A., Nieto, Á., y Rodríguez, Y. (2020). Mapa de la agricultura familiar en Colombia 2019. Bogotá: UPRA.

Ministerio de Agricultura y Desarrollo Rural. 2018. Frontera agrícola nacional: la cancha del sector agropecuario para el desarrollo rural sostenible. Disponible en: [Frontera Agrícola](https://www.minagricultura.gov.co/noticias/Paginas/-Frontera-agr%C3%ADcola-nacional-la-cancha-del-sector-agropecuario-para-el-desarrollo-rural-sostenible-.aspx) 

Ministerio de Agricultura y Desarrollo Rural. 2017. Resolución Número 000464 de 2017. Disponible en: [Resolución No. 000464 de 2017](https://agriculturafamiliar.co/resolucion-464-del-2017/)

Ministerio de Agricultura y Desarrollo Rural. Zonas de reserva campesina. Disponible en [Zonas de Reserva Campesina](https://www.minagricultura.gov.co/Normatividad/Paginas/Decreto-1071-2015/Zonas-de-reserva-campesina.aspx)
