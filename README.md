# Determining Factors of Life Expectancy Across Continents and Countries

This project was completed as a group project for the University of Calgary course DATA604 - Working with Data at Scale.

## Introduction

Life expectancy is one of the key indicators of well-being and development of a population. 
In this project we aim to study and investigate the effect of various broad factors such as Economy, Food/Agriculture, Air Pollutants, and Violence on life expectancy across different countries and continents. 

We will learn which factors are most correlated and influential in the calculation of life expectancy.
Life expectancy can vary a lot around the world and finding out why people in some areas live longer than people in other areas could help us all live longer and healthier lives.

## Datasets

Our primary dataset for life expectancy was found on Our World in Data and includes information such as country, year, and life expectancy at birth.
The main field we were interested in was life expectancy at birth, but we used country and year to match the life expectancy data with other datasets. We explored this dataset and other relevant datasets using SQL databases and queries.

The datasets used to investigate the **economy** from *Our World In Data* were used to explore the effect of economic factor on the life expectancy of the population.

* Economic Growth

The datasets used to investigate **food and agriculture** were all found on Our World in Data and were used to explore the overall topic of life expectancy by comparing how a population’s food supply, crop yield, and undernourishment were related to overall life expectancy. 
We suspected that all the datasets related to food and agriculture were correlated with life expectancy, where countries with high crop yield & food supply, and low malnourishment generally had higher life expectancies.

* Hunger and Undernourishment
* Crop Yields
* Food Supply

The dataset used to investigate air pollutants explored the effect of different types of emissions on life expectancy. 
We suspected that all different types of pollutants had a negative impact on life expectancy and explored whether any one was more impactful than the others.

* Emissions of Air Pollutants

The datasets used to investigate violence explored the effect of different factors that contribute to overall peace and violence of countries and how they might affect total life expectancy.

* Civilian and combatant deaths in armed conflicts based on where they occured
* GPI
* The Safety and Security Score
* The Homicide Score


## Main Results

We identified the variable with the greatest impact on life expectancy within each category. 
In the Economy, the most influential variable is GDP; in Violence, it is the Safety and Security Score; in Air Pollution, it is Nitrogen Oxides; and in Food/Agriculture, it is Food Supply.

![download](https://github.com/user-attachments/assets/a150d7b0-890b-4553-9656-350255af1aac)

The factor with the highest correlation to life expectancy is Agriculture (Food Supply), with a positive correlation of 0.71, meaning that as food supply increases, life expectancy also increases. 
The second strongest correlation is with Economic Factors (GDP), showing a positive correlation of 0.65, indicating that higher GDP is associated with increased life expectancy.

On the other hand, Violence Levels exhibit a negative correlation of -0.342, meaning that as violence decreases, life expectancy tends to rise. 
Lastly, Air Pollution shows a weak positive correlation of 0.1476; however, this could be due to a dataset-wide increase in both air pollution and life expectancy, potentially introducing bias into the correlation. 
Further analysis is necessary to better understand this relationship.


![download](https://github.com/user-attachments/assets/5bd4cf74-9111-40b7-b656-0b60630bf247)

For a more comprehensive analysis, the variables were adjusted to be displayed on a single graph: Life Expectancy was divided by 10, GDP by 10,000, Air Pollution by 100,000, and Food Supply by 1,000.

In this graph, we can observe that air pollution has been declining since 2008, which reflects the political, economic, and social shifts driven by growing awareness of the dangers of these gases. 
This has led to a global reduction in nitrogen oxide emissions.

GDP has increased significantly, particularly since the 2000s, maintaining an upward trend. 
However, there is a noticeable dip in 2009, likely due to the global economic instability between 2008 and 2010.

Another major achievement for humanity is Agriculture (Food Supply), which has shown a steady upward trend since 1992. 
As previously noted, this factor has the highest correlation with life expectancy, reinforcing the idea that ensuring proper nutrition—one of the most fundamental human needs—is essential for increasing lifespan


## Conclusion

On a global scale, we observed that the factor with the strongest correlation was agriculture (food supply), which confirms that basic human needs, such as food, have a significant impact on life expectancy. 
The second most influential factor was the economy, highlighting the importance of a country's economic stability in improving life expectancy. 
In the evolution of the air pollution factor, we can see a significant decrease in nitrogen oxide emissions, a change driven by political, economic, and social trends addressing the dangers of polluting gases and efforts to reduce their emissions.

## Refrences

* Our World in Data. (n.d.). Our World in Data. Retrieved March 2, 2025, from https://ourworldindata.org/
* World Health Organization. (n.d.). World Health Organization. Retrieved March 2, 2025, from https://www.who.int/
* World Bank. (n.d.). World Bank Open Data. Retrieved March 2, 2025, from https://data.worldbank.org/
* United Nations Development Programme. (n.d.). United Nations Development Programme. Retrieved March 2, 2025, from https://www.undp.org/
* Institute for Economics & Peace. Global Peace Index March 2, 2024. https://www.visionofhumanity.org/maps/#/



