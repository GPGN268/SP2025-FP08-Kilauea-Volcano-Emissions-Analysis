# Kīlauea Volcano Emissions Analysis

#### Lillian Hanson: git @lillian-hanson
#### Clara Pugh: git @claranp
---

### Summary:
This project analyzes volcanic emissions and activity monitoring indices associated with the Kīlauea volcano in Hawaii. This includes lava flow rates and patterns, SO2 emissions, plume height, and lava.

### How To Use This Repository:
This repository contains one main Jupyter Notebook file, final_analysis.ipynb, in the /notebooks folder. This file contains the code needed to reproduce all three flow graphs, the lava lake elevation graph, the SO2 emissions graph, and the plume height graph. The presentation.md file, also in the /notebooks folder, contains all of these figures in a more readable format, along with additional information and context. The dev folder contains code used in the development of the final notebook. 

### Background:
Kīlauea is an active shield volcano on the island of Hawaii. It is one of the world's most active volcanoes. It stems from Mauna Loa, another large shield volcano in the area. It presents as a basaltic volcano [1]. It most recently erupted in February 2025. Kīlauea may also be referred to as Volcano Number 332010. It reaches a peak elevation of 1222 m. 70% of the volcano's surface is comprised of rock from lava flows that are less than 600 years old. Kīlauea is considered to be an intraplate volcano, and it sits on oceanic crust. 3,122 people live within 10 km of the peak, and 8,495 live within 30 km [2], and several hundred thousand people live less than 100 km from the peak. Ensuring the safety of this population is a driving factor for volcanic research. 

### Objective Question:
How are lava flows, lava lakes, plume heights, and SO2 emissions related?

### Datasets used:

Datasets with GIS shapefiles of lava flows at Kīlauea, analyzed with GeoPandas:
- [June 2014 - June 2016](https://www.sciencebase.gov/catalog/item/5cdd9871e4b029273746360f)
- [May 2016 - May 2017](https://www.sciencebase.gov/catalog/item/597230e4e4b0ec1a4885edc1)

This dataset has volcanic plume data also from Kīlauea, CSV files that are accessed with pandas: 
- https://www.sciencebase.gov/catalog/item/6000a312d34e592d8671f57f

Data from Kilauea relating to SO2 emissions: 
- https://www.sciencebase.gov/catalog/item/5abb448be4b081f61abb68ae

Elevation of Lava Lake on Kīlauea:
- https://www.sciencebase.gov/catalog/item/5f8feb0e82ce06b040f1ffa4

### Tools/packages used:
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [GeoPandas](https://geopandas.org/en/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Contextily](https://contextily.readthedocs.io/en/latest/)
- [PyProj](https://pypi.org/project/pyproj/)

### Project methodology/approach:
- We will analyze lava flows in relation to lava lake elevations, SO2 emissions, and plume heights at the Kīlauea volcano. 
- We will compare this data numerically to lava plume/gas release volume for the same eruptions.

### Summary of Results:
- There are positive correlations between activity and volume in lava flow rates, SO2 emissions, and lava lake elevations. Inferred relationships were found specifically between high SO2 emissions and high lava lake elevations. There was possibly a relationship between new lava flow areas and additional SO2 emissions as well. These findings could be expanded in the future with a statistical analysis, or by comparing to data from other basaltic volcanoes.

### Anticipated Challenges:
- The lava flow data is GIS shapefiles, which is not a format we have not used before, so it could be challenging initially to figure out how to open and work with that data

### Contribution Statement:
- Clara made the graphs of the 2016-2017 lava flow, the plume heights, and the lava lake elevations, and made the environment.yml file.
- Lillian made the animation of the 2014-2016 lava flow, the graph of the SO2 emissions, the graph of both lava flows on the same space, and figured out how to put satellite images behind the 2016-17 lava flow graphs.
- Both of us worked on writing the analysis in the presentation.md file and also writing the readme file.

### References:
[1] [https://www.usgs.gov/volcanoes/kilauea](https://www.usgs.gov/volcanoes/kilauea)
[2] [https://volcano.si.edu/volcano.cfm?vn=332010](https://volcano.si.edu/volcano.cfm?vn=332010)
