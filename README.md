# US Residential Energy Consumption Analysis


## Objective

Analyze data collected from the 2015 Residential Energy Consumption Survey and identify key factors that impact total household energy consumption.  Main analysis questions included:
 
1. What are the primary end uses for household energy consumption? 
2. What factors have the strongest relationship with total household energy consumption? 
3. What is the relationship between temperature and total household energy consumption? 
4. How does total household energy consumption vary across US regions?


## Dataset

Data for the analysis was obtained from the 2015 Residential Energy Consumption Survey (RECS) conducted by the U.S. Energy Information Administration (EIA).

[Data Set](https://www.eia.gov/consumption/residential/data/2015/index.php?view=microdata)

[Technical Documentation](https://www.eia.gov/consumption/residential/data/2015/index.php?view=methodology)

## Analysis Tools

- Python  
- Anaconda 3
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib
- Scipy
- Numpy
- Sklearn
- Folium
- Statsmodels

## Analysis Results

Analysis found that total household energy consumption in the United States is driven by many factors but a few key ones include type of home, space heating usage, and location temperature.   

1. Correlation analysis revealed space heating usage to have the strongest linear relationship with total household energy consumption, while number of rooms and type of home have moderately strong linear relationships with total household consumption.  

2. Linear regression modeling confirmed a statistically significant linear relationship between total energy used for space heating and total household energy consumption, with space heating usage accounting for 73% of the variance in total household energy consumption.  

3. Cluster analysis revealed that temperature does have a significant impact on total household energy consumption with colder locations experiencing higher total household energy consumption compared to warmer locations. In the United States, northern states experience colder temperatures and have higher energy consumption than southern states that experience warmer temperatures.

[Final Tableau Presentation](https://public.tableau.com/views/RECSAnalysis/USHouseholdEnergyConsumptionAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
