# Urban-Density-Mapping
Urban density heat maps extraction from Google Maps Aerial Images.
___

### Objective
This project proposes spatial analisys of urban areas given aerial images, with focus on building and populational density. The main goal is to extract heat maps that describe urban density and provide data for geospatial studies.

### Images and data
The images to be used on the project are brazilian cities snapshots from the [Google Earth plataform](https://www.google.com/earth/). While satelite data is more robust and would make results more precise (greater resolution,more light wavelenght bands), Google Earth images are used for the sake of simplicity.

The images are: 


| Brasilia| Manaus | Rio de Janeiro | Salvador |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
| <img width="200" src="PNGimages/brasilia.png"> | <img width="200" src="PNGimages/manaus.png">|<img width="200" src="PNGimages/riodejaneiro.png"> | <img width="200" src="PNGimages/salvador.png"> | 
| **Santos** | **Sao Carlos** | **Sao Luis** | **Sao Paulo** |
| <img width="200" src="PNGimages/santos.png"> | <img width="200" src="PNGimages/saocarlos.png"> | <img width="200" src="PNGimages/saoluis.png"> | <img width="200" src="PNGimages/saopaulo.png"> | 


| City           | Population | Area(km^2) | filename         | Pixel/km | 
|----------------|------------|------------|------------------|------------| 
| Brasilia       | 2947703    | 5760.783   | brasilia.png     | 70         | 
| Manaus         | 2145444    | 11401.092  | manaus.png       | 99         | 
| Rio de Janeiro | 6688927    | 1200.255   | riodejaneiro.png | 105        | 
| Salvador       | 2857329    | 693.831    | salvador.png     | 140        | 
| Santos         | 432957     | 281.033    | santos.png       | 77         | 
| Sao Carlos     | 249415     | 1136.907   | saocarlos.png    | 77         | 
| Sao Luis       | 1094667    | 582.974    | saoluis.png      | 154        | 
| Sao Paulo      | 12176866   | 1521.11    | saopaulo.png     | 69         | 


The data on the cities was found on [IBGEpopulacao](https://agenciadenoticias.ibge.gov.br/agencia-detalhe-de-midia.html?view=mediaibge&catid=2103&id=2279) and [IBGEArea](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/estrutura-territorial/2225-np-areas-dos-municipios/15761-areas-dos-municipios.html?t=downloads&c=3548906), and the image data was taken from Google Earth. 

### Image Processing Methods


[yet to be  better defined and improved]  
Computer vison methods for extraction of characteristics based on espectral indexes and regression analisys for density estimation.

### Aplication
Designed to aid spatial epidemiology projects, but useful to other geospatial studies, police-making and public interests.
