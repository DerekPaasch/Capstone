# Detriments of Health

#Welcome
-This is a Capstone project in conjunction with Nashville Software Schools Data Analytics bootcamp program cohort 12. 
-It is a requirement for each student to find data, clean it, analyze it, and present the findings.


## Table of Contents
* [Tableau Dashboard](#Tableau-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)


## Tableau Dashboard
https://public.tableau.com/views/Capstonepresentation_17138037251140/Capstone?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link


## Motivation:
Being a respiratory therapist, I want to further explore any and all correlations between tobacco consumption and alcohol to cancers. With my healthcare background I believe I can help provide a great insight into the data question.  The insights gained from this analysis can then be used to develop evidence-based public health strategies aimed at reducing cancer prevalence and improving global health outcomes.


## Questions
1) What is the correlation between tobacco consumption, alcohol consumption and the incidence rates of malignant neoplasms (specifically focusing on lung, and liver cancers) across different countries globally?
2) How does this compare to the US?
3) Are any regional patterns in the correlation between tobacco and alcohol consumption and the incidence rates of lung and liver cancers?
4) Are certain regions more heavily affected than others? Are there any notable outliers or clusters of countries with similar trends?
5) How can this information inform targeted public health interventions to reduce cancer prevalence?


## Normalizing the Data
The datasets I selected were from the OECD and had years dating back to 1960. I selected the most recent and consistent years in which had the least amount of missing information to get the most accurate assessment. I also narrowed down multiple other criteria including cancer types and countries. I created multiple dataframes and ended up using years between 2012-2020.


## Problems and Hurdles
It was difficult cleaning the data in Python. There were many unnecessary columns that needed to be removed and or renamed due to information limitations or missing data dictionaries. Trying to correlate data in two seperate values was difficult. Tables were need to be merged and then converting values into other values in order to correlate.


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) Tableau - for creating interactive dashboard
3) PowerPoint - for introduction of Project
4) Git - for version control


## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis

1) World population data
https://data.worldbank.org/indicator/SP.POP.TOTL?end=2020&start=2012

2) OECD Alcohol Consumption
https://data-explorer.oecd.org/vis?df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_HEALTH_LVNG%40DF_HEALTH_LVNG_AC&df[ag]=OECD.ELS.HD&df[vs]=1.0&pd=2010%2C&dq=.A.....&to[TIME_PERIOD]=false&vw=tb&ly[rw]=REF_AREA&ly[cl]=TIME_PERIOD&ly[rs]=AGE

3) OECD Tobacco Consumption
https://data-explorer.oecd.org/vis?df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_HEALTH_LVNG%40DF_HEALTH_LVNG_TC&df[ag]=OECD.ELS.HD&df[vs]=1.0&pd=2010%2C&dq=.A.....&to[TIME_PERIOD]=false&vw=tb

4) OECD Risk factors for Health
https://data-explorer.oecd.org/vis?tm=total%20fat%20supply&pg=0&hc%5bMeasure%5d=Fat%20supply&hc%5bSex%5d=Total&hc%5bAge%5d=Total&snb=10&vw=ov&df%5bds%5d=dsDisseminateFinalDMZ&df%5bid%5d=DSD_HEALTH_LVNG%40DF_HEALTH_LVNG&df%5bag%5d=OECD.ELS.HD&df%5bvs%5d=1.0&pd=2010%2C&dq=.A..._T..&ly%5brw%5d=REF_AREA&ly%5bcl%5d=TIME_PERIOD&ly%5brs%5d=MEASURE%2CAGE&to%5bTIME_PERIOD%5d=false

5) OECD Health status including Cancers
https://data-explorer.oecd.org/vis?tm=malignant%20neoplasms&pg=0&hc[Cancer%20site]=Malignant%20neoplasms&snb=8&vw=tb&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_HEALTH_STAT%40DF_HEALTH_STATUS&df[ag]=OECD.ELS.HD&df[vs]=1.0&pd=%2C&dq=.A...........&to[TIME_PERIOD]=false&lo=5&lom=LASTNPERIODS


## Conclusion
The data analysis shows that the United States and Japan are the top2 in the world leading in Lung cancer and Liver cancer deaths. The data shows that there is a strong correlation between smoking and lung cancer, as well as alcohol and liver cancer. There weren't any regions more heavily affected than others and there weren't and notable outlies or clusters of countries with similar trends. This information can target public health interventions to reduce cancer here in the US.