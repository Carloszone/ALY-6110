# project Summary

In this project, we use the U.S. Traffic Accidents dataset from Kaggle. There are 3.5 million records and 49 columns. This is a countrywide car accident dataset, which covers 49 states of the USA. It was collected from February 2016 to June 2020. The columns contain the Location of accidents, the Severity of accidents and the Weather condition of accidents, etc.

We will use Databricks as our cloud platform for analyzing. Besides, we choose Python language to do the whole process. Include cleaning up the raw data, performing the exploratory data analysis(EDA) and drawing a series of traffic accidents maps to figure out what is the trend of the U.S. traffic accidents. And then, we build a model to do the feature selection. At last, we would provide some relevant insights and suggestions.

## Project Process
- Data clean
- Analyze number of accidents by Time
- Analyze number of accidents by Severity
- Analyze number of accidents by Weather condition 
- Analyze number of accidents by Description
- Draw maps
- Feature Selection and Modeling Prediction

## Conclusion
For EDA part, we come to the following conclusions：
-	There were more cases during 8-12 compared to other months,excluding the data from 2020, guess there are more bad weather conditions in the winter. 
-	Most accidents happened during the day time, and there are two peaks on 7-8 and 16-17 when people are on commute between workplace and home.
-	During 23 to 3 o'clock，before dawn.cases numbers are relatively at the bottom level as most people are in sleep
-	Accidents are categorised into four groups (1-4) based on their Severity.1 being least and 4 being more severe. 67.7 % Accidents fall in the Severity class 2 followed by Severity class 3,4 and 1.
-	Our assumpions generally is that bad weather could lead to more accidents.But here we can see that more accidents occur when the weather is clear. This may be because people drive more carefully when the weather is bad.
-	Blcocked, Accident, Rd Accident, due, Lane Blcoked are the most frequent words in the description of traffic accident.
-	CA has the most accidents happened. Due to the fact that CA has highest population in the US states with logical assumption. Houston has the most accidents among all US cities. Being that Taxes is the 2nd biggest state in USA, this can lead to more drivers Speeding to reach their destination faster.

For the map section, in terms of number, traffic accident cases are increasing sharply. In terms of scope, these cases are spreading from the coastline to the central region. Besides, while performing the model, we believe that the findings in this part are interesting. Among all the factors (over than 200 counts), only 15 of them are constant significant in each run of the model. They are ‘Start_Lat’, ‘Start_Lng’, “'Distance(mi)', ‘Temperature(F)', 'Wind_Chill(F)', 'Humidity(%)', 'Pressure(in)', 'Visibility(mi)', 'Wind_Speed(mph)', 'Precipitation(in)’,’ Crossing’, ‘Junction’, ‘Traffic_Signal’, ‘Side_L’, and ‘Side_R’. 

The forecasting of severity of accidents is 67.76%, which means the model is appropriate. We think that in the reshaping process, we probably need to make some improvements to reaching the higher accuracy.

## Reference
Nikam, Swapnil Kisan, "ANALYSIS OF US ACCIDENTS AND SOLUTIONS" (2020). Electronic Theses,Projects, and Dissertations. 979.  https://scholarworks.lib.csusb.edu/etd/979

Binu. (November, 2020). Road Accidents in US. Retrieved December 1, 2020 from https://www.kaggle.com/biphili/road-accidents-in-us.

William Roosevelt. (July, 2020). US Accidents data cleaning + eda. Retrieved December 1, 2020 from https://www.kaggle.com/williamrroosevelt/us-accidents-data-cleaning-eda.


