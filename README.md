# US Flight Exploratory Data Analysis(EDA)
## by Chaojun Cao 


## Dataset

The data consists of a sampling of 20,000 US flights from 2007 and 2008 US flights datasets which contain over 700,000 and 800,000 records. There are 29 columns in the original data, including dates and timestamps, the time of arrival delay of each flight, the origin and destination airport and the causes of delays etc. The dataset can be found[here](http://stat-computing.org/dataexpo/2009/the-data.html),
with feature documentations like carrier codes and airport codes available[here](http://stat-computing.org/dataexpo/2009/supplemental-data.html).
since the datasets are too big, I randomly selected 10,000 records in each of the datasets. 


## Summary of Findings
After briefly cleaned the dataset, I found that the target variable, arrival delay, 
which is strongly related to the five causes. The histogram distribution of the time of arrival delay has a long tail on the right, showing a unimodal distribution afterusing a log scale for the x-axis with a peak from 15 to 50 minutes. For the delay causes, 
nas_delay and late aircraft delay have the most counts, and Nov, Dec, Jan have the most delays due to the weather condition. WN(Southwest Airlines Co.) and AA(American Airlines Inc.) 
show more delays than other carriers. Friday shows more delays than other days of the week. 

Weather delay happens more in TX, FL and IL, those places are also famous for some extreme weathers. 
As explore more, I found that weather delay also happens a lot in June, July and weather delay in JFK, PHL, CLT, IAH, 
MCO etc.have the longest average delay in minutes than other delay causes. 


## Key Insights for Presentation
The dataset gives very dynamic views and insights. I have explored the dataset at different angles. 
I try to present the big picture of the aspects that will affect the delay first and then dig in. The portion of delays
in the datasets, the distribution of the delay and then display each feature in a relationship with the delay, like the count of
delay in each unique carrier, on each day of the week, each month and the five causes of the delay. After the exploration of the relationship between each feature variable and the target variable in frequency, I explored the average value of the feature variables with the target variable. 

In terms of counts, nas-delay, WN count the most delays while weather delay and B6 have the highest value considering on average. 
When using the selected airports to explore the target variable, we can also see that weather delay act always as the top one in the average delay in minutes among all the causes. To better understand the arrival delay variable, we'd better considering the aspects that we want to look into first. There is no relationship will fit all the features but we can find a different relationship using varies points or angles. 