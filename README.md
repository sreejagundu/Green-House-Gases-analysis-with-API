# 🤖 [NASA Space Apps Hackathon 2020] 🛰️ 

## Challenge: Carbon Footprint

The carbon footprint shows how much carbon dioxide and other greenhouse gases a person produces in everyday life.Today, the term “carbon footprint” is often used as shorthand for the amount of carbon (usually in tonnes) is emitted by an activity or organization. The carbon footprint is also an important component of the Ecological Footprint, since it is one competing demand for biologically productive space. Carbon emissions from burning fossil fuel accumulate in the atmosphere if there is not enough bio capacity dedicated to absorb these emissions. Therefore, when the carbon footprint is reported within the context of the total Ecological Footprint, the tonnes of carbon dioxide emissions are expressed as the amount of productive land area required to sequester those carbon dioxide emissions. This tells us how much bio capacity is necessary to neutralize the emissions from burning fossil fuels.

The amount of GHGs released into the atmosphere by any particular human activity is known as the carbon footprint. This footprint can be defined across an individual, a family, an organization or group, or an entire nation. It is usually measured as tons of carbon dioxide (CO2) emitted per year, a number that can be supplemented by tons of CO2-equivalent gases, including methane (CH4) and other greenhouse gases.

Carbon dioxide, methane, and other greenhouse gases (GHGs) are an important input to the global radiation budget, which strongly impacts the past, present, and future climate. These gases are exchanged between the atmosphere, ocean (through dissolution of carbon gases), and plants (through photosynthesis and respiration). They are also emitted by human activities, such as burning of fossil fuels, clearing land for agricultural purposes, producing and consuming food, manufacturing goods, materials, buildings, and roads, and by the transportation sector.

The major issue that we are facing today is increase in green house gas emissions. It is causing climatic variations. 
Here we find a solution for carbon footprint to build a clean and green atmosphere.

### Sources of Green House Gases
![image](https://user-images.githubusercontent.com/69813792/188518848-e04c4009-5c33-4d94-9609-43292c40f9cd.png)

Global greenhouse gas emissions can also be broken down by the economic activities that lead to their production.
Electricity and Heat Production:- The burning of coal, natural gas, and oil for electricity and heat is the largest single source of global greenhouse gas emissions.

Industry:- Greenhouse gas emissions from industry primarily involve fossil fuels burned on site at facilities for energy.

Forestry:- Greenhouse gas emissions from this sector come mostly from agriculture (cultivation of crops and livestock) and deforestation.

Transportation:- Greenhouse gas emissions from this sector primarily involve fossil fuels burned for road, rail, air, and marine transportation.

Building:- Greenhouse gas emissions from this sector arise from onsite energy generation and burning fuels for heat in buildings or cooking in homes.

Other Energy:- This source of greenhouse gas emissions refers to all emissions from the Energy sector which are not directly associated with electricity or heat production, such as fuel extraction, refining, processing, and transportation.

### Green House Gas Emissions by Gas
![image](https://user-images.githubusercontent.com/69813792/188518898-c7c3e8e5-8f2b-462e-b802-b93d224aa37a.png)

### Global Map of the CO2 column-averaged volume mixing ratios in 2.5 deg by 2.5 deg mesh(FTS SWIR L2 XCO2)
![image](https://user-images.githubusercontent.com/69813792/188518947-c77def19-477c-4c2b-9b11-11f1b859f5ce.png)

### Data

We have used labeled data https://github.com/NASA-IMPACT/space-apps/tree/master/data/labeled from NASA data resources.

Monitoring surface air quality helps ensure the protection of human health and property. However, surface air quality data is sparsely monitored. To help fill in these gaps, inferences are derived from other sources including remote sensing. The CSV formatted data and labels are provided below. It contains the following fields which have been described.

air_data_value: EPA air data PM2.5 readings
RH: relative humidity from HRRR
UGRD, VGRD: Wind speed vectors from HRRR
HPBL: Height of Planetary Boundary Layer from HRRR
TMP: Temperature recorded from HRRR
goes_measurement: AOD reading from GOES R

![image](https://user-images.githubusercontent.com/69813792/188519758-9387107f-9d31-4573-a136-221cca58202b.png)


### Libraries

1. Pandas
2. Numpy 
3. Seaborn
4. Matplotlib
5. Sklearn

### Machine Learning Models

1. Linear Regression
2. Random Forest Reggresion
3. Decision Tree

### Data Processing

Data is being cleaned and processed. Irrelevant columns, null values and duplicates are dropped from the dataset. an outlier is an observation point that is distant from other observations.The outliers can be a result of a mistake during data collection or it can be just an indication of variance in your data. Sometimes they can be very high or very low. It's often a good idea to detect and remove the outliers. Because outliers are one of the primary reasons for resulting in a less accurate model. Often outliers can be seen with visualizations using a box plot.

Correlation matrix and other various plots depicting outliers, missing values, correlations, etc are plotted for visualiztion and analysis of data.

Correlation Matrix
![image](https://user-images.githubusercontent.com/69813792/188519384-16cc42dc-caf6-4935-908e-639b6eb55a28.png)

### Detection Model

We are building a detection model with target variable as Temperature. Here we study variation of data with temperature.

## API Visualization

API url: "https://sreejagundu.github.io/NASA/"  
This url visualizes the temperature variations due to increase in GHG emissions. To visualize satellite data and variations of CO, CH4 and NO2, edit the 'layers' in path  NASA/GIBSapi/main.js/.


## Solution

Prepare a paint with artificial chloroplast as one of its constituent element.

Tint the paint on any outer surfaces like buildings, cars, etc.

Chloroplast will capture carbondioxide from the atmosphere. Further, it may be possible that it releases oxygen in presence of sunlight.

It can be used with basic knowledge and economically feasible.

![image](https://user-images.githubusercontent.com/69813792/188519804-37993781-8020-4419-8b55-e30c6ed51cd1.png)


This solution optimizes carbon footprints from environment in a eco-friendly way.
