# CEMA Data Science Tasks
## Task 1: Exploring HIV Trends and Poverty Dimensions Across WHO Regions

### Problem Statement
HIV continues to be a major public health issue in Africa, with a high number of people living with the virus, especially in sub-Saharan regions. While prevention and treatment efforts have improved, HIV is a lifelong condition, making it crucial to track data on this affected. This data helps us identify infection trends, prepare healthcare services to accommodate these patients, and address challenges like stigma and inequality.  Beyond health, HIV also impacts jobs, healthcare costs, and poverty levels, making it important to use data to create targeted interventions. By analyzing this information, governments and organizations can better allocate resources and create policies to help reduce transmission and improve the quality of life for those affected. </br>

### Data Analysis
#### Create a visualization that shows the trend of HIV cases in the countries that contribute to 75% of the global burden </br>

![image](https://github.com/user-attachments/assets/a18f49d8-4afa-4706-8a06-ed533d63fa74)

The overall HIV burden globally remained high from 2000 to 2023 — no sharp drop is visible.

Certain countries like South Africa, Nigeria, and Mozambique appear to contribute very large portions to the global burden every year (these countries have thicker bands in the stack).

The number of people living with HIV slightly increases between 2000 and around 2015–2020, and then appears to stabilize or slightly decrease.

The HIV epidemic remains highly concentrated in a small number of countries — that's why top contributors are enough to represent 75% of the global burden.

#### Generate a visualization that displays the trend of HIV cases in the countries contributing to 75% of the burden within each WHO region (column called ParentLocationCode contains the WHO regions) </br>

![image](https://github.com/user-attachments/assets/f02eca1f-2d43-4da2-8951-d12b3ae4fcee)

In the AFR region, South Africa, Nigeria, Uganda, Kenya, and Zimbabwe dominate the HIV burden.

The HIV burden shows a gradual increase up to around 2015–2020, after which it levels off or shows early signs of decline.

Just like globally, a few countries in Africa carry a disproportionate share of the HIV burden.

The pattern highlights regional inequality: even within Africa, a small subset of countries carry the majority of cases.

#### Merge this dataset with the HIV data above and analyze the relationship between people living with HIV and multidimensional poverty, and the individual factors that contribute to the ratio. Remember to account for the random effects (country, year).

![image](https://github.com/user-attachments/assets/a523d3f5-f545-4128-9d13-3a88c74969d7)

## Task 2: Mapping Child Mortality Trends Across the East African Community
### Problem Statement
Child mortality remains a major public health concern in the East African Community (EAC), where disparities in healthcare access and socioeconomic factors contribute to varying outcomes across countries. This analysis aims to explore spatial and temporal patterns of under-five and neonatal mortality rates within the EAC region. By leveraging geospatial data and time-series visualizations, the project seeks to identify countries with the highest burden of child mortality and uncover regional trends, supporting evidence-based interventions and policymaking. </br>

### Data Analysis
#### Filter data for the eight countries belonging to the East African Community (list here: https://www.eac.int/overview-of-eac) </br>
#### Visualize the latest estimate of each indicator at the country level using shapefiles, which can be downloaded from www.gadm.org. </br>
![image](https://github.com/user-attachments/assets/82b31589-b069-4ef4-82bc-ddf69ec91470)
South Sudan and Somalia consistently have the highest under-five mortality rates (above 100 deaths per 1000 live births for much of the period). </br>
Kenya, Rwanda, Tanzania, and Uganda show much lower rates — below 70 deaths/1000 births, and they keep decreasing over time. </br>
The average mortality rate across East Africa shows a steady decline over the years. </br>
Some countries (like Somalia and South Sudan) have a lot more fluctuations, while others (like Rwanda and Kenya) show a smoother decline.

![image](https://github.com/user-attachments/assets/7cd995a3-ab77-4ed2-b562-705f9d3299b6)
The rates are lower than under-five mortality overall (as expected), but similar country patterns. </br>
South Sudan and Somalia again show the highest neonatal mortality rates (around 40–45 deaths per 1000 births). </br>
Kenya, Rwanda, and Tanzania again have much better outcomes (around 20–25 deaths per 1000). </br>
The average neonatal mortality across the region is steadily declining, although the decline is slower compared to the under-five mortality rate.

#### Show the average trends in the mortality rates over time (plot the average trend line and add the points in the graphic for the country level estimates for each indicator. Expectation: two plots). </br>
![image](https://github.com/user-attachments/assets/65659267-1591-4692-9d9f-b8e9fc5dc6e6)
South Sudan and Somalia are deep red, meaning very high under-five mortality (>100 deaths/1000). </br>
Kenya, Tanzania, and Rwanda are much lighter, indicating lower under-five mortality (closer to 40-50 deaths/1000). </br>

![image](https://github.com/user-attachments/assets/b8394175-b171-4c64-9db6-b5fbab036ee0)
Again, South Sudan and Somalia are the darkest, meaning they have the highest neonatal deaths (>37 deaths/1000). </br>
Kenya, Rwanda, and Tanzania show the lowest neonatal mortality, shaded much lighter. </br>
Most other countries fall somewhere in between. </br>

#### Based on your visualizations, identify the countries with the highest under-five mortality rates in East Africa and the highest neonatal mortality. </br>
![image](https://github.com/user-attachments/assets/b055e4e9-f98e-4175-82ce-3166610566e6)




