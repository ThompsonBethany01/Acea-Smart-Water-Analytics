![repo-header](https://github.com/ThompsonBethany01/Acea-Smart-Water-Analytics/blob/main/images/Repo%20Headers.gif?raw=true)
# About the Project
## Goals
Predict the water level in a waterbody to handle daily consumption and therefor improve water preservation. While the data consists of nine seperate waterbodies with different features, it is still important to understand the water levels as a whole in order to preserve water for the entire country of Italy. To be concise, the goal is to build a story to predict the amount of water in each unique waterbody, ensuring water availability for each time interval of the year.

## Background
According to the Kaggle competition overview [here](https://www.kaggle.com/c/acea-water-prediction/overview),
> "The Acea Group is one of the leading Italian multiutility operators. Listed on the Italian Stock Exchange since 1999, the company manages and develops water and 
> electricity networks and environmental services. Acea is the foremost Italian operator in the water services sector supplying 9 million inhabitants in Lazio, 
> Tuscany, Umbria, Molise, Campania."

## Deliverables
- A notebook that can generate four mathematical models, one for each category of waterbody (acquifers, water springs, river, lake) that might be applicable to each single waterbody

## Project Outline

## Acknowledgments
# Data Dictionaries
The dataset consists of nine independent data frames for various waterbodies in Italy. These waterbodies can be categorized as one of the four four listed...  

### Aquifer
An underground layer of water-bearing permeable rock, rock fractures or unconsolidated materials  
![aquifer](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.ICKxianJANfUw5zpTY_o2AHaEx%26pid%3DApi&f=1)

### Water Spring
A point at which water flows from an aquifer to the Earth's surface  
![spring](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Flh6.ggpht.com%2F_EMEcU1rXEEQ%2FSV_6KuNIYLI%2FAAAAAAAAAe4%2Fbn9HBi90ZPo%2Fborehole%5B2%5D.gif&f=1&nofb=1)

### Lake
A large inland body of fresh water or salt water.  
![lake](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.wateratlas.org%2Fi%2Fwb%2Fphotos%2Fmed2%2Fboyd-lake.jpg&f=1&nofb=1)

### River
A large natural stream of water emptying into an ocean, lake, or other body of water and usually fed along its course by converging tributaries.  
![river](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Flaurasriverfeatures.weebly.com%2Fuploads%2F4%2F0%2F2%2F0%2F40209157%2F4020409.png&f=1&nofb=1)

How does this tie into the dataset? There are four aquifers, three water springs, one lake, and one river. Further descriptions of each waterbody in the dataset is below. 

## Dataset Description
| Waterbody Name     | Waterbody Type | Output "Predictive" Feature(s) | Description                                                                                                                                                                                                                                                                 |
|--------------------|----------------|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Auser              | Aquifer        | Depth to Groundwater (3)       | Consists of two subsystems, that we call NORH and SOUTH, where the former partly influences the behaviour of the latter.<br>Levels of the NORTH sector are represented by the values of the SAL, PAG, CoS and DIEC wells, while levels of the SOUTH sector by the LT2 well. |
| Amiata             | Water Spring   | Flow Rate (4)                  | Accessed through the Ermicciolo, Arbure, Bugnano and Galleria Alta springs. <br>The levels and volumes of the four springs are influenced by the parameters: pluviometry, sub-gradation, hydrometry, temperatures and drainage volumes.                                     |
| Petrignano         | Aquifer        | Depth to Groundwater (2)       | Fed by three underground aquifers separated by low permeability septa; the water table can be considered groundwater and is also fed by the Chiascio river.                                                                                                                 |
| Doganella          | Aquifer        | Depth to Groundwater (9)       | Fed by two underground aquifers: <br>the upper stratum is a water table with a thickness of about 30m while the lower one is a semi-confined artesian aquifer with a thickness of 50m.                                                                                      |
| Luco               | Aquifer        | Depth to Groundwater (1)       | An underground aquifer not fed by rivers or lakes but fed by meteoric infiltration and it is accessed through wells called Pozzo_1, Pozzo_3 and Pozzo_4.                                                                                                                    |
| Arno               | River          | Hydrometry                     | Second largest river in peninsular Italy and the main waterway in Tuscany and it  has a relatively torrential regime, <br>due to the nature of the surrounding soils (marl and impermeable clays)                                                                           |
| Bilancino          | Lake           | Lake Level, Flow Rate          | An artificial lake in Mugello, in the province of Florence. <br>It has a maximum depth of thirty-one metres and a surface area of 5 square kilometres.                                                                                                                      |
| Madonna di Canneto | Water Spring   |                                | Situated at an altitude of 1010m above sea level in the Canneto valley. <br>It does not consist of an aquifer and its source is supplied by the water catchment area of the river Melfa                                                                                     |
| Lupa               | Water Spring   |                                | Located in the Arrone area and is used for drinking use.                                                                                                                                                                                                                    |
# Initial Thoughts & Hypotheses
## Thoughts
## Hypotheses
# Project Steps
## Acquire
## Prepare
## Explore
## Model
## Conclusions
# How to Reproduce
## Steps
## Tools & Requirements
# Creator
