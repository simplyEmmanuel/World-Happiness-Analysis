# World Happiness Data Analysis

![](intro_image.jpg)

## Introduction
This repository contains data on the **World Happiness Report 2017,** which ranks 155 countries by their happiness levels. The data was fetched from Kaggle, and it includes the following variables:

- Country: The name of the country.
- Happiness Score: A measure of happiness, based on a survey of respondents' life evaluations.
- Economy: GDP per capita.
- Social Support: The extent to which people feel supported by their social networks.
- Healthy Life Expectancy: The number of years a person can expect to live in good health.
- Freedom: The extent to which people feel free to make life choices.
- Generosity: The extent to which people give to charity or help others in need.
- Trust: The extent to which people trust their government and other institutions.

## Objective
The project is to analyze, visualize, and derive insights to answer important questions in order to make data-driven decisions. 

_Disclaimer: All datasets and reports do not represent any institution or country, but a personal project to demonstrate capabilities of using Power BI for data visualization._ 

## Problem Statement
1. What are the factors that contribute to happiness? 
2. Are there any differences in happiness levels between countries?
3. What is the relationship between happiness and social economic factors, such as GDP, Life Expectancy, and Freedom?

_These are just three of the many possible problem statements that could be explored using the World Happiness data. By answering these questions, we can gain a better understanding of what makes people happy, and we can begin to identify ways to improve happiness levels around the world._

## Skills/Concepts demonstrated 
The following Power BI features were incorporated:
- Data cleaning and preparation
- Data analysis
- Filters
- Modelling
- Data Analysis Expression (DAX)
- Measures
- Data visualization
- Reporting

## Data Modelling
The data represents a single year of data which automatically derived a relationship. However, a custom column was created to have a separate table - **CountryRanks** for the purpose of the analysis. 

![](data_model.png)

The derived table is joined to the fact table with a one-to-many relationship. 

## Data Visualization 
Considering the problem statements, and the questions that need to be answered. The happiness score and ranks were compared across all countries, thereby filtering the countries by their top and lower 10 in their ranks. 
The report contains three (3) pages:
1. Report page
2. Correlation and Map Analysis
3. Top most failed states affected by factors like corruption etc.

## Analysis
![](report_page.png)

You can interact with the data [here](https://app.powerbi.com/groups/me/reports/de722f57-acae-4389-8751-aef3df59af8c/ReportSection?experience=power-bi)


![](Correlation_map_page.png)

### Features:
- The scatter plots represents each country's happiness score on the GDP scale. Lower GDP countries below the Average GDP per Capita respresents a proportional happiness score, and vice-versa.
- The map shows the interractivity between the scatter plots, as well as countries selected on the slicer

Again, you can interact with the data [here](https://app.powerbi.com/groups/me/reports/de722f57-acae-4389-8751-aef3df59af8c/ReportSection?experience=power-bi)

## Conclusion
- The World Happiness Report ranks 155 countries by their levels of happiness 
- The score is based on responses to the main life evaluation question in Gallup World Poll 
- Norway ranks the highest World's happiness score, while Central Africa Republic ranks the lowest based on the happiness score and ranks among other countries
- These factors are economic production, social support, life expectancy, freedom, absence of corruption and generosity  
- The Dystopia Residual metric is the Dystopia Happiness Score plus the residual value for each country. 
- Singapore ranks the highest in countries that have less trust for their government.
- In addition to these variables, future reports could also consider using more qualitative methods to measure happiness, such as surveys and interviews. This would help to provide a more comprehensive understanding of what makes people happy.

## Recommendations
Based on the above conclusions, here are some recommendations for future reports:
- Collect data from a wider range of countries, including more countries from the global south to capture all 195 countries in the world.
- Use more qualitative methods to measure happiness, such as surveys and interviews.
- Consider using other corresponding variables to measure happiness, such as time spent working versus time spent in leisure, youth unemployment, and general unemployment level.

By following these recommendations, future reports could provide a more accurate and comprehensive picture of global happiness levels.

![](thank_you.jpg)
