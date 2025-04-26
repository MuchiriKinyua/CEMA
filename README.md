# CEMA Data Science tasks
## Task 1: Exploring HIV Trends and Poverty Dimensions Across WHO Regions

<p align="center">
  <img src="https://github.com/user-attachments/assets/23735a41-50f6-485e-87aa-51e7687e3a40" alt="HIV Awareness Ribbon" width="300" height="300">
</p>

### Problem Statement
HIV continues to be a major public health issue in Africa, with a high number of people living with the virus, especially in sub-Saharan regions. While prevention and treatment efforts have improved, HIV is a lifelong condition, making it crucial to track data on this affected. This data helps us identify infection trends, prepare healthcare services to accommodate these patients, and address challenges like stigma and inequality.  Beyond health, HIV also impacts jobs, healthcare costs, and poverty levels, making it important to use data to create targeted interventions. By analyzing this information, governments and organizations can better allocate resources and create policies to help reduce transmission and improve the quality of life for those affected. </br>

### Data Analysis
-	Create a visualization that shows the trend of HIV cases in the countries that contribute to 75% of the global burden </br>

![image](https://github.com/user-attachments/assets/a18f49d8-4afa-4706-8a06-ed533d63fa74)

-	Generate a visualization that displays the trend of HIV cases in the countries contributing to 75% of the burden within each WHO region (column called ParentLocationCode contains the WHO regions) </br>

![image](https://github.com/user-attachments/assets/f02eca1f-2d43-4da2-8951-d12b3ae4fcee)

You have also been provided with World Bank data on the multidimensional poverty headcount ratio, which includes factors such as income, educational attainment, school enrolment, electricity access, sanitation and drinking water. </br>

We would like you to merge this dataset with the HIV data above and analyze the relationship between people living with HIV and multidimensional poverty, and the individual factors that contribute to the ratio. Remember to account for the random effects (country, year).

![image](https://github.com/user-attachments/assets/a523d3f5-f545-4128-9d13-3a88c74969d7)

## Task 2
You have been provided with data on the under-five mortality rate and neonatal mortality rate for the African region, which has been downloaded from the UN Inter-agency Group for Child Mortality Estimation. Your task is to: </br>



### Filter data for the eight countries belonging to the East African Community (list here: https://www.eac.int/overview-of-eac) </br>
### Visualize the latest estimate of each indicator at the country level using shapefiles, which can be downloaded from www.gadm.org. </br>
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

### Show the average trends in the mortality rates over time (plot the average trend line and add the points in the graphic for the country level estimates for each indicator. Expectation: two plots). </br>
![image](https://github.com/user-attachments/assets/65659267-1591-4692-9d9f-b8e9fc5dc6e6)
South Sudan and Somalia are deep red, meaning very high under-five mortality (>100 deaths/1000). </br>
Kenya, Tanzania, and Rwanda are much lighter, indicating lower under-five mortality (closer to 40-50 deaths/1000). </br>

![image](https://github.com/user-attachments/assets/b8394175-b171-4c64-9db6-b5fbab036ee0)
Again, South Sudan and Somalia are the darkest, meaning they have the highest neonatal deaths (>37 deaths/1000). </br>
Kenya, Rwanda, and Tanzania show the lowest neonatal mortality, shaded much lighter. </br>
Most other countries fall somewhere in between. </br>

### Based on your visualizations, identify the countries with the highest under-five mortality rates in East Africa and the highest neonatal mortality. </br>
![image](https://github.com/user-attachments/assets/b055e4e9-f98e-4175-82ce-3166610566e6)

You should work on an RMD document that is saved in your name, e.g juma_fulani.rmd. </br>
Kindly ensure you show the code in your data. </br>

The rmd should be uploaded on this link (https://docs.google.com/forms/d/e/1FAIpQLSd2gFkhTt1KP9vb74pYCsvFgrO0QZb_1js5fK2Aak-phAYxiA/viewform?usp=sharing ) by this 27th April 2025 at 8pm EAT. Kindly note that documents uploaded past the deadline will not be considered.




