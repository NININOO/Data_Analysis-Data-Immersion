# Data-Analysis_Data-Immersion
Discover Python scripts from Career Foundry's Data Analyst course. 

## About the project
This project is part of the Career Foundry Data Analysis course. The objective is to build an interactive dashboard that will visually showcase well-curated results of an advanced exploratory analysis conducted in Python. I used a sample project "UN Sustainable Development Goals - goal 7"

## Exercises 
Exercise 6.1: Sourcing Open Data
Exercise 6.2: Exploring Relationships
Exercise 6.3: Geographical Visualizations with Python
Exercise 6.4: Supervised Machine Learning: Regression
Exercise 6.5: Unsupervised Machine Learning: Clustering
Exercise 6.6: Sourcing & Analyzing Time Series Data
Exercise 6.7: Creating Data Dashboards


# Project Brief

## Context
<img width="608" alt="Screenshot 2023-10-03 at 23 03 01" src="https://github.com/NININOO/Data_Analysis-Data-Immersion/assets/85222999/5b039a77-de3d-48b5-aff4-1832ed975054">

Sustainable Development Goal 7 is to “ensure access to affordable, reliable, sustainable, and modern energy for all”, according the United Nations.
The visualizations and data below present the global perspective on where the world stands today and how it has changed over time.

### About the data set
The dataset used in this analysis is a comprehensive collection of sustainable energy indicators and related factors for all countries spanning the years from 2000 to 2020. It encompasses a wide range of critical aspects, including electricity access, renewable energy, carbon emissions, energy intensity, financial flows, and economic growth. The data has been meticulously curated from various reliable sources, primarily the World Bank, the International Energy Agency, and ourworldindata.org. Additionally, some columns and features have been derived from other top Kaggle datasets, ensuring a rich and multifaceted dataset.

### Data Source
Global Data on Sustainable Energy (2000-2020)
https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy?resource=download


### Data Collection
1.	Data for access to electricity are collected among different sources: mostly data from nationally representative household surveys were used.  
https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators
2.	A non-parametrical statistical model based on household survey data and time as inputs is applied to derive estimates. Based on the recommendations included in the WHO Guidelines for indoor air quality: household fuel combustion, the fuels and technologies that are considered clean include electricity, natural gas, liquified petroleum gas, biogas, ethanol, and solar.
https://ghoapi.azureedge.net/api/
3.	Data from multiple sources compiled by the UN
https://unstats.un.org/sdgs/metadata/files/Metadata-07-02-01.pdf
4.	This indicator is obtained by dividing total primary energy supply over gross domestic product measured in constant 2017 US dollars at purchasing power parity.
https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators


### Data Profile
1.	Entity: The name of the country or region for which the data is reported.
2.	Year: The year for which the data is reported, ranging from 2000 to 2020.
3.	Access to electricity (% of population): The percentage of population with access to electricity.
4.	Access to clean fuels for cooking (% of population): The percentage of the population with primary reliance on clean fuels.
5.	Renewable-electricity-generating-capacity-per-capita: Installed Renewable energy capacity per person
6.	Financial flows to developing countries (US $): Aid and assistance from developed countries for clean energy projects.
7.	Renewable energy share in total final energy consumption (%): Percentage of renewable energy in final energy consumption.
8.	Electricity from fossil fuels (TWh): Electricity generated from fossil fuels (coal, oil, gas) in terawatt-hours.
9.	Electricity from nuclear (TWh): Electricity generated from nuclear power in terawatt-hours.
10.	Electricity from renewables (TWh): Electricity generated from renewable sources (hydro, solar, wind, etc.) in terawatt-hours.
11.	Low-carbon electricity (% electricity): Percentage of electricity from low-carbon sources (nuclear and renewables).
12.	Primary energy consumption per capita (kWh/person): Energy consumption per person in kilowatt-hours.
13.	Energy intensity level of primary energy (MJ/$2011 PPP GDP): Energy use per unit of GDP at purchasing power parity.
14.	Value_co2_emissions (metric tons per capita): Carbon dioxide emissions per person in metric tons.
15.	Renewables (% equivalent primary energy): Equivalent primary energy that is derived from renewable sources.
16.	GDP growth (annual %): Annual GDP growth rate based on constant local currency.
17.	GDP per capita: Gross domestic product per person.
18.	Density (P/Km2): Population density in persons per square kilometer.
19.	Land Area (Km2): Total land area in square kilometers.
20.	Latitude: Latitude of the country's centroid in decimal degrees.
21.	Longitude: Longitude of the country's centroid in decimal degrees.


## Tools
For the project, the following Python libraries were used:
- pandas - for data analysis
- seaborn - for visualisation

- Tableau - presentation & visualisation
 
## Executing the code
The code is available in jupyter notebooks, available under /03 scripts/
