# Project 1: The Impact of COVID-19 on the US by State
## By Mohamed Aamer, Kevin Jeong, Tracey Geneau, Ana Torres


## Abstract
This research project aims to conduct an investigatory data analysis of COVID-19 cases across the United States from 2020 to 2022. By looking at data taken from Data.gov, this project will seek to answer several questions about the impact of COVID-19 on the US by the state as well as aggregating the data to observe the impact by region: the Northeast, the Midwest, the South, and the West. Subsequently, the data would then be presented in a visually comprehensive manner. In doing so, the project posits the following questions to answer:

•	What were the total number of COVID-19 cases and COVID-19 deaths by region over the 2020-2022 period?

•	How did each region experience the spread of COVID-19 over time?

•	What was the rate of death caused by COVID-19 for each state? Which 5 states experienced the most death caused by COVID-19 as a % of total cases? Which 5 states experienced the least death caused by COVID-19 as a % of total cases?

•	Can we predict a given state’s COVID-19 spread in 2023 following a scatter plot’s regression analysis of new COVID-19 cases reported in that state between 2020-2022?

The dataset used was pulled from the US government’s data.gov website which offers data sets in several formats, including CSV: https://catalog.data.gov/dataset/united-states-covid-19-cases-and-deaths-by-state-over-time

## Tasks

•	Data cleaning/munging

•	Aggregating COVID-19 case data (total number of cases, total number of deaths) for each state into a list for each given region as understood by the US Census Bureau (https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf)

•	Presenting the regional data in easily understandable data visualizations (bar charts, line graphs showing each region’s case numbers over time)

•	Calculating the rate of death caused by COVID-19 as a proportion of total COVID-19 cases for each state in the data set

•	Presenting the 5 states with the highest fatalities and the 5 states with the lowest fatalities as bar charts
•	Selecting a specific state and creating a scatter plot reflecting the number of new COVID-19 cases reported in the data set over time

•	Building a regression analysis model of that scatter plot# Data_Project_1


## Results

For this project, the regional analysis was derived from the US Census Regional and Divisions of the United States (see Fig 1).

### Figure 1:  Map indicating the States that were included in each region.
![Map](https://github.com/kkevin1999/Data_Project_1/assets/128385495/92ff4dc2-c8f2-4e82-93c3-9c57aff5e881)

Initially, the total population of each of these regions was compared to the Covid-19,case distribution for the three-year time span (2020 to 2022).  Using pie charts, the two sets of data were compared and it was determined that they were quite similar (see Fig 2. 

### Figure 2:  Pie charts of the regional distribution of Covid 19 cases from 2020 to 2022 as well as the total population of the US (2022) by Region. 
![RegionalPie](https://github.com/kkevin1999/Data_Project_1/assets/128385495/116100c4-5de5-4cc5-a9d7-c49cf1126956)

To gain a better understanding of the regional analysis on a yearly basis, bar charts were created using the mean total Covid 19 case counts.  In 2020 the North East Region had the lowest mean case count while the South had the highest.  In 2021 the South had the highest mean with the Mid West and North East having similar means.  By 2022, both the West and South regions displayed higher mean case counts than the North East or South. (see Figure 3)

### Fig 3:  Mean total Covid Cases by Region for 2020 to 2021
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/regionalbar.png)

By comparing boxplots of this yearly analysis, it was determined that the median for the regions in each of the three years was similar to one another.  It was observed that two states in the South were higher and one in the West were consistently well above the top quartile (See figure 4,5 & 6).

### Fig 4:  Boxplot representing total covid cases by region for 2020.
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/boxplot2020.png)


### Fig 5: Boxplot representing total covid cases by region for 2021.
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/boxplot2021.png)

### Fig 6: Boxplot representing total covid cases by region for 2022.
![](https://github.com/kkevin1999/Data_Project_1/blob/main/output_data/boxplot2022.png)

From this information, it was determined that further analysis was required at the state level in each region.

# (Kevin can you insert your notes here)

 
### Fig 7:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_cases.png)

### Fig 8:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_deaths.png)

Analysis of the Western United States showed California (CA) having the highest total cases by the end of 2022. However, other Western states did not display exponential increases in total cases. The timeline analysis of total cases for the Western region was able to identify the outlier we observed in the boxplot analysis. Similarly, the death timeline for the Western United States showed California (CA) having the highest total deaths in the Western region.  

### Fig 9:  
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Southern_total_cases.png)

### Fig 10:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Southern_total_deaths.png)

The total case timeline for the Southern United States showed Texas (TX) having the highest total cases by the end of 2022. However, we observed Florida (FL) experiencing similar trends as Texas. This led to the conclusion of Texas and Florida were the main contributors to the Covid-19 cases in the Southern region. Other southern regions did not experience drastic increases in total cases and stayed below 3,000,000 cases. Through this analysis, we were able to identify the two outliers in the Southern region's boxplots. Similarly, the death timeline for the Southern United States showed Texas and Florida having the highest total deaths by the end of 2022. 

### Fig 11:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_cases.png)

### Fig 12:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Mid_Western_total_deaths.png)

The Midwestern United States showed Illinois (IL), Ohio (OH), and Michigan (MI) experiencing similar trends of increasing cases throughout the pandemic. By 2022, we observed Illinois surpassing Ohio and Michigan  in total cases. These results may be a reflection of Ohio's (OH) and Michigan's (MI) vaccine shortages they experienced in early 2022. Other Midwestern states did not follow these trends which showed Illinois, Ohio, and Michigan were the main contributors to the Midwestern Covid-19 cases. However, the death timeline analysis showed Illinois, Ohio, and Michigan have similar total deaths. These results may be indicative of Ohio's and Michigan's flaws in Covid relief plans such as vaccinations and restrictions.   

### Fig 13:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Northeastern_total_cases.png)

### Fig 14:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Northeastern_total_deaths.png)

The analysis of the Northeastern region showed two states that were ahead of the other states in total case counts. Pennsylvania (PA) and New York (NY) had the highest total Covid-19 cases by the end of 2022. However, we observed New Jersey (NJ) and Massachusetts (MA) having similar trends of increasing cases in early 2022. From this analysis, we found that New York and Pennsylvania were the main contributors to the Northeastern region's total Covid-19 cases. The death timeline for the Northeastern region showed Pennsylvania (PA) having the highest number of deaths by the end of 2022. Compared to the total case timeline, New York had a lower total number of deaths than New Jersey. These results reflect the benefits of New York's stricter restrictions and vaccine efforts. 

### Fig 15: 
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/bar_top5_fatality.png)

The 5 states with the highest proportion of COVID-19 cases leading to a fatality are Pennsylvania, Missouri, Georgia, Arizona, and New Mexico. Fatality rates for those 5 states were around 1.4% of total COVID-19 cases reported by October 2022.

### Fig 16:
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/bar_bottom5_fatality.png)

The 5 states with the lowest proportion of COVID-19 cases leading to a fatality are New Hampshire, Vermont, Utah, Hawaii, and Alaska. Of those 5 states, New Hampshire had the highest at just below 0.8%, with the other 4 states hovering around 0.5% of COVID-19 cases reported by October 2022. 

### Fig 17: Population Sizes, Medicare Spending, and Insurance Coverage for States with Highest COVID-19 Fatalities
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/Highest_Fatality_DF.png)

### Fig 18: Population Sizes, Medicare Spending, and Insurance Coverage for States with Lowest COVID-19 Fatalities
![](https://github.com/kkevin1999/Data_Project_1/blob/main/Resources/Lowest_Fatality_DF.png)

Three factors were looked at to determine if there are any patterns with respect to states that suffered from COVID-19 fatalities and states that had relatively low COVID-19-related deaths. The mean population size for those states with the higher proportion of deaths was 7.9 million, whereas the mean population size for the states with the lowest proportion of deaths was 1.5 million. Medicare spending per person per year for the former group of states was $9,688.20 and for the latter group of states, it was $8,710.20. As for the percentage of the population who had no health insurance, the former five states had a mean of 9.6% uninsured and the latter five states 6.38%.

Although causal analyses are beyond the scope of this study, there are some observations to raise with respect to the data. It is apparent more sparsely populated states suffered fewer COVID-19 deaths as a % of cases than more densely populated states. As for medical insurance, US healthcare relies on a patchwork of private insurance plans, largely offered through workplaces but also bought individually. Those who are above the age of 65 as well as certain cases of disabled younger uninsured people would qualify for Medicare, a federal insurance scheme. Thus, it is noted that the states that experienced higher proportions of COVID-19 deaths had an average of 9.6% of the state population uninsured, as opposed to 6.38% for the states with the lowest fatalities. This disparity could provide a gateway for further research on the effects of private insurance on varying levels of the quality of healthcare and the likelihood of positive health outcomes when hospitalized. 

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

There was no significant difference in the average total cases from 2020 to 2022 between all four regions in the US (West, Mid-West, South, and North-East).  Boxplots indicated that there were two states as outliers in the South and one in the West.  State analysis indicated the states were California, Florida, and Texas.  

A fatality rate of 0.5-1.5% indicates the virus has evolved to become endemic but not acute with newer variants being less lethal.  California, Texas, and Florida had the highest infection and death rates in the U.S. due to their population size, obesity, and older population.
 
The high infection and death rates in California were impacted by the working conditions on farms, the relaxed sanitary measures (use of masks, cleaning, and social distancing), and the early reopenings of establishments.  
Lax sanitary measures in the use of masks and social distancing.

The relation between Confirmed Cases and Total Deaths was almost 1, which shows a high correlation. Population testing could be key to early decision-making by governments and health departments for identification and control of the virus. 

In the future, it would be beneficial to further the analysis by looking at the differences in patients using Medicare versus Insurance coverage and the population size versus age distribution.  The effect of the impacts of closures on students at all levels, especially in math and reading would be interesting as the effects on mental health at all ages.

## References

California Department of Public Health (2022, Sept 16). Tracking Confirmed and Probable COVID-19 Cases. https://www.cd ph.ca.gov/Programs/C ID/DCDC/Pages/COVID-19/Probable-Cases.aspx.

Ohio Department of Health. (2023, June 15). Covid-19 Vaccination Dashboard - Ohio. COVID-19 Dashboard. https://coronavirus.oh io.gov/wps/portal/gov/covid-19 /dashboards/covid-19-vaccine/covid-19-vaccination-dashboard 

Michigan Department of Health & Human Services. (2023, June 14). Covid 19 Dashboard. SOM - State of Michigan. https://www.michigan.gov/coronavirus/resourc es/covid-19 - vaccine/covid-19-dashboard 

Illinois Department of Public Health. (2023, May 12). COVID-19 Vaccine Administration Data. Vaccine Data. https://dph.illinois.gov/covid19/vaccine/vaccine-data.html?county=Illinois 

Publisher Centers for Disease Control and Prevention. (2021, May 10). United States covid-19 cases and deaths by State over time. United States COVID-19 Cases and Deaths by State over Time - Catalog. https://web.archive.org/web/20230601195047/https://catalog.data.gov/dataset/united-states-covid-19-cases-and-deaths-by-state-over-time 

News Medical Life Sciences (2022, September 21)  COVID-19 activity peaks during winter in the United States and Europe. https://www.news-medical.ne t/news/20220921/Study-shows-CO VID-19-activity-peaks-during-winter-in-the-United-States-and-Europe.aspx

Los Angeles Times, (2023, January 12)  L.A. County COVID-19 deaths hit a new winter high. Why? https://www.latimes.com/california/story/2023-01-12/covid-deaths-exceed-summer-surge

The New York Times, (2021, June 15), A Timeline of the Coronavirus in California. https://www.nytimes.com/2021/06/15/us/coronavirus-california-timeline.html

California Department of Public Health. (As of September 15, 2022) Tracking Confirmed and Probable COVID-19 Cases. https://www.cdph.ca.gov/Programs/CID/DCDC/Pages/COVID-19/Probable-Cases.aspx

Population Reference Bureau (2021, December 22), Which U.S. States Have the Oldest Populations? https://www.prb.org/resources/which-us-states-are-the-oldest/

Centers for Disease Control and Prevention (2022, Sep 27) Adult Obesity Prevalence Maps. https://www.cdc.gov/obesity/data/prevalence-maps.html

Spectrum Local News, (2023, Jan 14) Study finds Texas has one of the highest obesity rates in U.S.. https://spectrumlocalnews.com/tx/south-texas-el-paso/news/2023/01/07/texas-obesity-inequities-#:~:text=Texas%20is%20ranked%20the%2012th,and%2032.2%25%20of%20white%20people.

## Link to our presentation
https://docs.google.com/presentation/d/1lhQlyAWrkFKcpSCQu1FBuV_lKb86fHAG-wJBblcVm28/edit?pli=1#slide=id.p

