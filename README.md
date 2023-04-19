# Analysis of Suicide Rate with Taipy 
Everyone is aware that suicide is not a good way to solve problems. But, the cruel reality is that millions of individuals attempt suicide every year, and many have been able to end their lives. I'll analyze the suicide situation globally in this dashboard to see how it has changed over the 35 years since 1985 in different nations.
Data Overview & Questions

# Data Overview
Since the data has no missing values in the fields we will work with, we do not have to worry about this issue. However, as the data on Korea's suicides per 100k in 2020 is all 0, we have the right to suspect the quality of this data. I decided to delete this data from the data set for a more trustful analysis. Furthermore, 7 countries were removed as they have <= 3 years of data total. 

With the information provided, I plan to divide this data set into 3 parts to conduct further analysis. In each part, the analysis will be gradually developed by responding to various questions:

## Global Analysis
I will look at how suicide numbers worldwide have changed over 35 years, since 1985. Specifically, the statistics can be observed from different angles: ages, genders, generations, etc. For example:
- What were the overview numbers of suicides worldwide? (E.g: Trend, Highest/Lowest Average Suicides per 100K,..)
- Were there any differences in suicide numbers between different age groups? Which group appeared to have the most suicides per 100K population? At what time? Did this group's age remain the same as the group with the highest suicide number in 35 years? 
- Were there any differences in suicide rates between women and men?

## Country Analysis
- What were the top 10 countries that have the highest number of suicides? 
- Is there anything in common between these countries? 

## Relationship Analysis
- Are there any relationships detected between GDP and Suicides Rates?

# Insights

## Time view
It is obvious that there was a decrease in suicides after 1995. Yet, it considerably increased in 2016 before sharply falling in 2020. The worldwide COVID-19 pandemic outbreak in 2020 changed the ways how we live dramatically and abruptly. Contrary to what some may have expected, suicide deaths were reduced to a very low number during this difficult time, despite the stress and the fear many people faced. A few reasons are contributing to this: 
- Increase in access to mental health resources: Mental health was the most considered and taken care of when people were quarantined. Remote mental health support services were provided more often and easily accessed than ever.
- As a result of the first reason, mental health concerns are pushed to the center of public debate. This led to a reduction in the stigma related to mental illness and thereby serious solutions were sought and applied.
- Greater sense of community: As a result of individuals joining together to help one another during tough circumstances, the pandemic boosted the social sense of unity and sympathy.  

## Gender view
- Men have committed suicide at a greater rate than women. It wasn't until 2017 that the gap started to narrow down  
- The overall number of suicides among males was, on average, three times that of women  

## Age view 
- The 75+ age group remains the age group with the most people committing suicide from 1985 to 2016. However, after 2016, the number of suicides in this group decreased dramatically, and the 35–54 age bracket replaced the 75+ group position as the age with the most suicide deaths. In total, it appeared that the number of suicides tended to increase in later life when people got older. The main causes, according to AAFMT, can be attributed to serious depression, which is frequently associated with suicide in later life. Besides, older persons do not often seek treatment for mental health issues so that's why their situation tends to become worse as time passes  

## Country view
- While Korea has the most case of suicides per 100K population, 6/10 countries in the top 10 were part of the Soviet Union. Due to some research, the high number of suicide cases in the Soviet Union may be partly associated with its legacy. Economic instability, social unrest, and cultural perceptions of mental health difficulties are some of these reasons

## GDP per capita view
- The suicide rate is highly correlated to the gdp_per_capita of the top 10 countries. Especially, 9/10 countries' suicide rates are negatively related to gdp_per_capita except for Korea. One possible reason to support this is that the more economic growth, the more stable and fulfilled society, which in turn lessens pessimism and despair in individuals. However, Korea is an exception. While having a high GDP per capita, the country still has a very high number of suicide cases. The causes might be due to factors such as social isolation, strong academic and job expectations, and societal attitudes toward mental health.
