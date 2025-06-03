# Earthquake Data Analysis (1990–2023)

This project explores earthquake data from around the world with a focus on identifying regional trends, magnitude distributions, and relationships with tectonic activity.

## Overview

The goal of this project is to analyze global earthquake activity between 1990 and 2023, focusing on:
- The distribution and frequency of magnitudes
- Depth and significance correlations
- Relationships between earthquakes and tsunami warnings
- Spatial distribution with respect to tectonic plate boundaries

## Tools & Libraries

- Python (Jupyter Notebook)
- pandas – data cleaning and manipulation
- geopandas – geospatial filtering and plotting
- matplotlib and seaborn – visualizations

## Key Questions & Insights

This analysis investigates the following questions:

**Q1. What is the distribution of earthquake magnitudes between 1990 and 2023?**  
Most earthquakes have a magnitude around 1.25.  
Very few earthquakes are below magnitude 0 or above 5.

**Q2. Is there an increasing trend in the number of earthquakes?**  
There is no clear increasing trend across any magnitude category.

**Q3. Does the depth of an earthquake affect its significance?**  
Shallower earthquakes (close to the surface) tend to have higher significance.  
Earthquakes with lower significance occur across a broader range of depths.

**Q4. What magnitude ranges are more likely to trigger tsunami warnings?**  
Magnitudes above 7.0 are much more likely to set the tsunami flag.

**Q5. Which regions experience the largest earthquakes?**  
The largest earthquakes are concentrated around the Ring of Fire, the tectonic belt around the Pacific Ocean.

**Q6. Do large earthquakes occur near tectonic plate boundaries?**  
Yes — large earthquakes correlate strongly with tectonic plate borders.

## Project Structure

- `README.md`: Project description  
- `earthquake_data_analysis.ipynb`: Main analysis notebook  
- `data/`: Contains shapefiles for visualization 
  	- `50m_cultural/`: Geospatial boundary data  
  	- `techtonicplates-master/`: Tectonic plate shapefiles

## Data Source

The main earthquake dataset (`Earthquakes-1990-2023.csv`) used in this project is not included in this repository due to file size limitations.

You can download it directly from Kaggle:
https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-earthquake-dataset-from-1990-2023

