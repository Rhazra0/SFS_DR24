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

## Regione Toscana-SIPT: Database Pedologico 
### Rockiness (%)

### Soil Use Capacity (Capacita di uso dei suoli)

Calculated according to the 'Land Capability Classification (LCC).' Has the following 8 classes:

Class I: Soils with very few limiting factors, suitable for all crops.

Class II: Soils with moderate limitations that require an appropriate choice of crops and/or moderate conservative practices.

Class III: Soils with severe limitations that drastically reduce the choice of crops and require special conservative practices.

Class IV: Soils with very severe limitations that drastically reduce the choice of crops and require accurate cultivation practices.

Class V: Soils that, despite not showing signs of erosion, have other difficultly-eliminable limitations that restrict their use to pasture, forestry, or as a natural habitat.

Class VI: Soils with severe limitations that render them unsuitable for cultivation and restrict their use, albeit with some obstacles, to pasture, forestry, and as a natural habitat.

Class VII: Soils with very severe limitations that show difficulty even for silvo-pastoral use.

Class VIII: Soils with limitations that preclude any agricultural, forestry, or pastoral use, and can therefore be used for creative, aesthetic, naturalistic purposes, or as a water collection area. This class also includes gullies and rock outcrops.


### Land Use and Cover 2019

Class 111: Residential areas with continuous fabric

Class 112: Residential areas with discontinuous fabric

Class 1121: Residential appurtenance, scattered buildings

Class 121: Industrial, commercial and public and private service areas

Class 1212: Photovoltaic system

Class 122: Road, railway and technical infrastructure networks

Class 1221: Roads in wooded areas

Class 124: Airports

Class 131: Mining areas

Class 132: Landfills, scrap yards

Class 133: Construction sites

Class 141: Urban green areas

Class 1411: Cemetery

Class 142: Recreational and sports areas

Class 210: Irrigated and non-irrigated crops

Class 2101: Greenhouses

Class 2102: Nurseries

Class 221: Vineyards

Class 222: Orchards

Class 2221: Arboriculture

Class 223: Olive groves

Class 231: Permanent meadows

Class 241: Temporary crops associated with permanent crops

Class 242: Complex cropping and particle systems

Class 243: Agricultural crops with presence of significant natural spaces

Class 244: Agroforestry areas

Class 311: Broadleaf forests

Class 312: Coniferous forests

Class 313: Mixed coniferous and broadleaf forests

Class 321: Natural pastures and meadows

Class 324: Evolving woodland and shrub vegetation

Class 332: Bare rocks, cliffs, crags, outcrops

Class 333: Sparse vegetation

Class 411: Internal marshes

Class 511: Watercourses, canals, and waterways

Class 512: Water bodies
