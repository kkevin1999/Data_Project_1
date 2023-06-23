# Project 1: The Impact of COVID-19 on the US by State
## By Mohamed Aamer, Kevin Jeong, Tracey Geneau, Ana Torres


## Abstract
This research project aims to conduct an investigatory data analysis of COVID-19 cases across the United States from 2020 to 2022. By looking at data taken from Data.gov, this project will seek to answer several questions about the impact of COVID-19 on the US by state as well as aggregating the data to observe impact by region: the Northeast, the Midwest, the South, and the West. Subsequently, the data would then be presented in a visually comprehensive manner. In doing so, the project posits the following questions to answer:

•	What were the total number of COVID-19 cases and COVID-19 deaths by region over the 2020-2022 period?

•	How did each region experience the spread of COVID-19 over time?

•	What was the rate of death caused by COVID-19 for each state? Which 5 states experienced the most death caused by COVID-19 as a % of total cases? Which 5 states experienced the least death caused by COVID-19 as a % of total cases?

•	Can we predict a given state’s COVID-19 spread in 2023 following a scatter plot’s regression analysis of new COVID-19 cases reported in that state between 2020-2022?

The dataset used was pulled from the US government’s data.gov website which offers data sets in several formats, including CSV: https://catalog.data.gov/dataset/united-states-covid-19-cases-and-deaths-by-state-over-time

## Tasks

•	Data cleaning/munging

•	Aggregating COVID-19 case data (total number of cases, total number of deaths) for each state into a list for each given region as understood by the US Census Bureau (https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf)

•	Presenting the regional data in easily understandable data visualizations (bar charts, line graph showing each region’s case numbers over time)

•	Calculating the rate of death caused by COVID-19 as a proportion of total COVID-19 cases for each state in the data set

•	Presenting the 5 states with the highest fatalities and the 5 states with the lowest fatalities as bar charts
•	Selecting a specific state and creating a scatter plot reflecting the number of new COVID-19 cases reported in the data set over time

•	Building a regression analysis model of that scatter plot# Data_Project_1


## Results

For this project, the regional analysis was derived from the US Census Regional nd Divisions of the United States (see Fig 1).

### Figure 1:  Map indicating the States that were included in each region.
![Map](https://github.com/kkevin1999/Data_Project_1/assets/128385495/92ff4dc2-c8f2-4e82-93c3-9c57aff5e881)

Initially, the total population of each of these regions was compared to the Covid 19,case distrobution for the three year time span (2020 to 2022).  Using pie charts, the two sets of data were compared and it was determined that they were quite similar (see Fig 2. 

### Figure 2:  Pie charts of the regional distribution of Covid 19 cases from 2020 to 2022 as well as the total population of the US (2022) by Region.  (kevin could you confirm the us population data)
![RegionalPie](https://github.com/kkevin1999/Data_Project_1/assets/128385495/116100c4-5de5-4cc5-a9d7-c49cf1126956)

To gain a better understanding of the regional analysis on a yearly basis, bar charts were created using the mean total Covid 19 case counts.  In 2020 the North East Region had the lowest mean case count while the South had the highest.  In 2021 the South had the highest mean with the Mid West and Noeth East having similar means.  By 2022, both the West and South regions displayed hiher mean case counts than the North East or South. (see figure 3)

### Fig 3:  Mean total Covid Cases by Region for 2020 to 2021
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/regionalbar.png)

By comparing boxplots of this yearly analysis, it was determined that the median for the regions in each of the three years was similar to one another.  It was observed that two states in the South were higher and one in the West were consistently well above theh top quartile (See figure 4,5 & 6).

### Fig 4:  Boxplot representing total covid cases by region for 2020.
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/boxplot2020.png)


### Fig 5: Boxplot representing total covid cases by region for 2021.
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/boxplot2021.png)

### Fig 6: Boxplot representing total covid cases by region for 2022.
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/boxplot2022.png)

From this information, it was determined that further analysis was required at the state level in each region.

# (Kevin can you insert your notes in here)

### Fig 7:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_cases.png)

### Fig 8:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_deaths.png)

### Fig 9:  
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Southern_total_cases.png)

### Fig 10:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Southern_total_deaths.png)

### Fig 11:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_cases.png)


### Fig 12:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_deaths.png)


### Fig 13:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Northeastern_total_cases.png)


### Fig 14:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Northeastern_total_deaths.png)


# (Mohamed could you please add your notes here)

### Fig 15:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/bar_top5_fatality.png)

### Fig 16:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/bar_bottom5_fatality.png)

### Fig 17:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/Highest_Fatality_DF.png)

### Fig 18:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/Lowest_Fatality_DF.png)

# (Ana could you put your analysis here)

### Fig 19:  (need title)
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/State.png)

### FIg 20:  (Need Title)
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/states2.png)

### Fig 21:  (need title)
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/CA.png)

### Fig 22:  (need title)
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/cor.png)

##  Conclusion

There was no significant difference in the average total cases from 2020 to 2022 between all four regions in the US (West, Mid-West, South and North-East).  Boxplots indicated that there were two states as outliers in the South and one in the West.  State analysis indicated the states were California, Florida and Texas.  

Fatality rate of 0.5-1.5% indicates the virus has evolved to become endemic but not acute with newer variants being less lethal.  California, Texas and Florida had the highest infection and death rates in the U.S. due to their population size, obesity and an older population.
 
The high infection and death rates in California were impacted by the working conditions on farms, the relaxed sanitary measures (use of masks, cleaning and social distancing) and the early reopenings of establishments.  
Lax sanitary measures in the use of masks and social distancing.

The relation between Confirmed Cases and Total Deaths was almost 1, which shows a high correlation. Population testing could be key to early decision making by governments and health departments for identification and control of the virus. 

In the future, it would be beneficial to futher the analysis by looking at the differences in patients using Midicare versus Insurance coverage and the population size versus age distrobution.  The effect of the impacts of closures on students at all levels, especially in math and reading would be interesting and the effects of on methanl health at all ages.






