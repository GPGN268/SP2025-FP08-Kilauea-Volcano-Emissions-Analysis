# Volcanic Flow Hazard Analysis

#### Lillian Hanson: git @lillian-hanson
#### Clara Pugh: git @claranp
---

### Short 1-2 sentence summary:
This project will analyze geohazards associated with the Kīlauea volcano. The analysis will specifically focus on lava-flow-induced hazards. 

### Some introductory background information:
Kīlauea is an active shield volcano on the island of Hawaii. It is one of the world's most active volcanoes. It stems from Mauna Loa, another large shield volcano in the area. It presents as a basaltic volcano. It most recently erupted in June 2024. [1] 

### Problem statement, question(s) and/or objective(s):
How are the size/volumes of lava flows and lava plumes related?

### Datasets you will use (with links, if available):

Datasets with GIS shapefiles of lava flows at Kīlauea, can be analyzed with GeoPandas:
- [June 2014 - June 2016](https://www.sciencebase.gov/catalog/item/5cdd9871e4b029273746360f)
- [May 2016 - May 2017](https://www.sciencebase.gov/catalog/item/597230e4e4b0ec1a4885edc1)

This dataset has volcanic plume data also from Kīlauea, formatted in csv files that are accessed with pandas: 
- https://www.sciencebase.gov/catalog/item/6000a312d34e592d8671f57f

Data from Kilauea relating to SO2 emissions: 
- https://www.sciencebase.gov/catalog/item/5abb448be4b081f61abb68ae

Elevation of Lava Lake on Kīlauea:
- https://www.sciencebase.gov/catalog/item/5f8feb0e82ce06b040f1ffa4

### Tools/packages you’ll use (with links):
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [GeoPandas](https://geopandas.org/en/stable/)
- [Pandas](https://pandas.pydata.org/)

### Planned methodology/approach:
- We will analyze lava flows in relation to time at the Kīlauea volcano. 
- We will compare this data numerically to lava plume/gas release volume for the same eruptions.

### Expected outcomes:
- We expect that higher volumes of lava flow would be correlated with higher volumes of gas emissions and more/higher volumes of volcanic plumes.

### Any other relevant information, images/tables, references, etc.:
Lava flow viscosity relating to mineralogy:
- https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/jgrf.20111

### Anticipated Challenges:
- The lava flow data is GIS shapefiles, which is not a format we have not used before, so it could be challenging initially to figure out how to open and work with that data

### References:
[1] https://www.usgs.gov/volcanoes/kilauea
