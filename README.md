# SFS_DR24

## Chianti Classico Zone of Production
(https://www.google.com/maps/d/u/0/viewer?mid=1ZPW53PJFD8buKCi_KUnV-GnvTCw&femb=1&ll=43.50781501977445%2C11.284325473144458&z=10) 
Zone of production of the Chianti Classico, traced from a map of Chianti Classico's DOCG Limit (https://www.tenzingws.com/blog/2016/4/15/interactive-map-of-chianti-classico-with-subzones-and-producers) 


## ARTEA Graphic Crop Plans 2022
ARTEA piani colturali grafici 2022- divided by province - Complete dataset. Last updated 17 March, 2023.
https://dati.toscana.it/dataset/artea-piani-colturali-grafici-2022 

The Chianti region occupies provinces of Florence, Arezzo, and Siena. Thus we only extract data for these provinces. 

We use the coordinates of our site interview to identify farm parcels that we "know" to be owned by the farm. We then cross-reference the beneficiary ("beneficiar") as per the ARTEA beneficiary registry (Ricerca su ALBO BENEFICIARI ARTEA) to identify parcels that share the same beneficiary. We assume this means they are owned by our farm of interest. 

We do this for every "site" to obtain parcels boundaries for sites 001 to 009, as shown in the included folders. 

## European Soil Database

### Dominant slope class of the STU
Raster name: SLOPEDO
Slope class ranges from 0-4 with the following classification:
0: No information
1: Level (dominant slope ranging from 0 to 8 %)
2: Sloping (dominant slope ranging from 8 to 15 %)
3: Moderately steep (dominant slope ranging from 15 to 25 %)
4: Steep (dominant slope over 25 %)

### Surface textural class
Raster name: TXSRFDO
Surface textural class ranges from 0-9 with the following classification:
0: No information
1: Coarse (18% < clay and > 65% sand)
2: Medium (18% < clay < 35% and >= 15% sand, or 18% < clay and 15% < sand < 65%)
3: Medium fine (< 35% clay and < 15% sand)
4: Fine (35% < clay < 60%)
5: Very fine (clay > 60 %)
9: No mineral texture (Peat soils)


### Dominant land use
Raster name: USEDO
Land use classes range from 0-30 with the following classification:
0: No information
1: Pasture, grassland, grazing land
2: Poplars
3: Arable land, cereals
4: Wasteland, shrub
5: Forest, coppice
6: Horticulture
7: Vineyards
8: Garrigue
9: Bush, macchia
10: Moor
11: Halophile grassland
12: Arboriculture, orchard
13: Industrial crops
14: Rice
15: Cotton
16: Vegetables
17: Olive trees
18: Recreation
19: Extensive pasture, grazing, rough pasture
20: Dehesa (extensive pastoral system in forest parks in Spain)
21: Cultivos enarenados (artificial soils for orchards in SE Spain)
30: Wildlife refuge, land above timberline

### Dominant soil water (moisture) regime
Raster name: WR
Soil water regimes range from 0-4 with the following classification:
0: No information
1: Not wet within 80 cm for over 3 months, nor wet within 40 cm for over 1 month
2: Wet within 80 cm for 3 to 6 months, but not wet within 40 cm for over 1 month
3: Wet within 80 cm for over 6 months, but not wet within 40 cm for over 11 months
4: Wet within 40 cm depth for over 11 months

## Global Rainfall Erosivity 
### Global R-factor


