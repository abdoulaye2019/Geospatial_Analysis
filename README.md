# Geospatial_Analysis

L'analyse de données spatiales consiste à explorer, visualiser et modéliser des données géographiques pour en extraire des informations utiles. R et RStudio sont des outils puissants pour l'analyse de données spatiales en raison de la disponibilité de packages tels que `sf`, `sp`, `raster` et `leaflet` qui permettent de travailler facilement avec des données géospatiales.

## Cartographie avec `geom_sf()`

![Cartographie-Senegal-Demographic](map.png)

### Réaliser une Carte avec la fonction **geom_sf**

`geom_sf()` est une géométrie dans le package `ggplot2` qui permet de visualiser des données spatiales dans __R__. Il est spécialement conçu pour travailler avec des données géospatiales structurées dans le format sf (simple features) et est conçu pour remplacer la géométrie `geom_map()` utilisée dans les versions antérieures de `ggplot2`.

Pour utiliser `geom_sf()`, vous devez d'abord avoir des données géospatiales sous forme de sf object, puis les charger dans ggplot2 en utilisant la fonction `ggplot()`.Example d'utilisation: