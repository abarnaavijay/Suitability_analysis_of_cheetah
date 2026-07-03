# Cheetah Habitat Site Suitability Analysis using GIS and AHP

## Overview

This project presents a **GIS-based Site Suitability Analysis** to evaluate the potential of the **Nallamala Forest landscape** in Andhra Pradesh and Telangana for supporting the long-term survival and possible reintroduction of cheetahs (*Acinonyx jubatus*). The study integrates remote sensing, geospatial analysis, and the **Analytical Hierarchy Process (AHP)** to identify environmentally suitable habitats based on ecological, topographic, climatic, and anthropogenic factors.

A Multi-Criteria Decision Analysis (MCDA) framework was developed by combining several environmental variables, each weighted according to its ecological importance for cheetah habitat. The resulting suitability map provides valuable spatial insights for wildlife conservation planning and habitat management.

## Project Objectives

* Assess habitat suitability for cheetah reintroduction within the Nallamala Forest landscape.
* Integrate multiple geospatial datasets into a unified decision-making framework.
* Apply the Analytical Hierarchy Process (AHP) to determine parameter importance.
* Generate a habitat suitability map highlighting areas with varying levels of ecological suitability.
* Support evidence-based conservation and wildlife management decisions.

## Study Area

The study focuses on the **Nallamala Forest region**, spanning parts of Andhra Pradesh and Telangana, covering districts including:

* Kurnool
* Prakasam
* Guntur
* Kadapa
* Nellore
* Nalgonda
* Nagarkurnool

This landscape represents one of the largest continuous forest ecosystems in southern India and plays an important role in biodiversity conservation.

## Methodology

The analysis followed a structured GIS workflow:

1. Collection of multisource geospatial datasets.
2. Data preprocessing, including clipping, reprojection, and resampling.
3. Generation of thematic layers.
4. Reclassification of individual parameters into suitability classes.
5. Assignment of parameter weights using the **Analytical Hierarchy Process (AHP)**.
6. Weighted Overlay Analysis to produce a composite suitability index.
7. Classification of the final output into different habitat suitability zones.

## Parameters Considered

The suitability model incorporated multiple ecological and environmental variables, including:

* Grassland Coverage
* Tree Cover Density
* Land Use/Land Cover (LULC)
* Road Network
* Water Bodies
* Elevation
* Slope
* Maximum NDVI
* Integrated NDVI
* Long-term Mean Temperature (2004–2024)
* Long-term Mean Precipitation (2004–2024)
* Relative Humidity

## Data Sources

The project utilized a variety of open geospatial datasets, including:

* Copernicus Tree Cover Density (10 m)
* Global Pasture Watch
* GLC-FCS30D Land Cover Dataset
* USGS SRTM DEM
* Landsat 8 Level-2 Imagery
* OpenStreetMap
* NASA SEDAC Road Network
* WeatherSnap Climate Data (2004–2024)

## Tools & Technologies

* QGIS
* Python
* Remote Sensing
* Raster Analysis
* Multi-Criteria Decision Analysis (MCDA)
* Analytical Hierarchy Process (AHP)
* Weighted Overlay Analysis
* Geospatial Data Processing

## Results

The generated habitat suitability map revealed that the Nallamala landscape currently contains only isolated pockets of moderate suitability for cheetah habitat. Although climatic conditions are generally favourable, limited continuous grassland cover, fragmented vegetation, rugged terrain, and existing ecological constraints significantly reduce the region's potential to sustain viable cheetah populations.

The study highlights the importance of integrating ecological, climatic, and topographic variables into conservation planning and emphasizes the need for habitat restoration, improved connectivity, and field-based ecological validation before considering future reintroduction efforts.

## Skills Demonstrated

* GIS Spatial Analysis
* Habitat Suitability Modelling
* Multi-Criteria Decision Analysis (MCDA)
* Analytical Hierarchy Process (AHP)
* Remote Sensing
* Raster Processing
* Geospatial Data Integration
* Environmental Modelling
* Cartographic Visualization
* Conservation GIS

<img width="602" height="337" alt="Study Area" src="https://github.com/user-attachments/assets/ec7c1d68-dc93-4758-9dcd-ce0c2201561b" />
<img width="909" height="522" alt="Screenshot 2026-07-03 123947" src="https://github.com/user-attachments/assets/15a00abc-9e8b-407a-8c9f-8ddf57cdbe29" />
<img width="1001" height="289" alt="Screenshot 2026-07-03 130122" src="https://github.com/user-attachments/assets/278b47b3-1cc3-4ba1-a4c6-2063076e03db" />
<img width="2802" height="998" alt="methodology" src="https://github.com/user-attachments/assets/97d21df6-376f-49c5-82ac-f4cf11a2d575" />
<img width="2139" height="677" alt="method2" src="https://github.com/user-attachments/assets/3d6e655d-b089-407c-9437-38bf1c06da45" />
<img width="3507" height="2480" alt="LULC" src="https://github.com/user-attachments/assets/5240840d-a71e-49ed-a58a-5352602e2a4e" />
<img width="800" height="566" alt="Natural_grs" src="https://github.com/user-attachments/assets/0e8df594-06f2-463f-bdd8-735f2e6b1621" />
<img width="800" height="566" alt="TCD" src="https://github.com/user-attachments/assets/e461d495-23b2-476f-8cb2-f506e0145cee" />
<img width="800" height="566" alt="Ndvimax" src="https://github.com/user-attachments/assets/25116c01-8abc-4e22-9fd7-eb7f8060e313" />
<img width="3507" height="2480" alt="ndvi in" src="https://github.com/user-attachments/assets/4037cbc5-b8c7-49a4-8297-6e58a4b0b199" />
<img width="3507" height="2480" alt="tmin" src="https://github.com/user-attachments/assets/64f4a8f5-1d0f-4447-88ac-a454113fa8db" />
<img width="3507" height="2480" alt="tmax" src="https://github.com/user-attachments/assets/020cd103-6a39-44d9-9737-b7f49942a1a1" />
<img width="3507" height="2480" alt="Rhmax" src="https://github.com/user-attachments/assets/d6351df6-7d94-41a9-99b3-c94763eae9d0"/>
<img width="3507" height="2480" alt="prcp" src="https://github.com/user-attachments/assets/113f14f8-b19b-4dd8-909a-e984a9f54207"/>
<img width="800" height="566" alt="ROAD" src="https://github.com/user-attachments/assets/f7803de1-4ce4-403f-b207-e37d97e2d9de" />
<img width="800" height="566" alt="water" src="https://github.com/user-attachments/assets/808c643c-0bcc-4e5b-b518-f74584e13c6d" />
<img width="14031" height="9921" alt="Suitabilitymap" src="https://github.com/user-attachments/assets/8f47bd84-59bf-48dd-9649-cac8ac469274" />
Special Thanks and Credits to Niruthi Climate and Ecosystems https://www.bing.com/ck/a?!&&p=3399384c2c7b832197b4e5ff280bf3d63814aea30b374fad80e70702e22eeaabJmltdHM9MTc4MzAzNjgwMA&ptn=3&ver=2&hsh=4&fclid=2216fb67-2eb0-6702-1bbb-ed052f58662b&psq=niruthi+climate+and+ecosystems+pvt+ltd&u=a1aHR0cHM6Ly9uaXJ1dGhpLmNvbS8
