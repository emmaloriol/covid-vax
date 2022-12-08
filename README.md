# covid-vax


Introduction:

We are answering the questions of “What states have the most/least access to vaccine providers?”, “What states are the most/least vaccinated?”, and ”What are the death rates from COVID by state?”. 
Overall, we are trying to assess if there is a relationship between the variables of vaccine provider density, vaccination rate, and COVID-19 death rates by state. These are important questions 
because they give insight to levels of access to vaccination by state and the effect that may have on vaccination rate, which is a critical measure of pandemic response and preparedness. 
These are the initial questions we are investigating, but we may expand our scope depending on what the data elucidates.



The Data Sources and Files in github contain full data from our sources or cleaned data we did ourselves in excel prior to analysis


Vaccines.gov 
#Data about COVID-19 vaccine provider locations
#Data includes location, vaccine stock, hours of operation, etc.
#Some data values are missing, but each vaccine provider does have location #information available
#Data is up-to-date (as of Oct 18)
#Does not contain historical information
#Over 455,000 rows of data entries

CDC COVID Data Tracker Cases, Deaths, and Testing 
Collection of COVID-19 data including cases, hospitalizations, deaths, etc. by state
Over 36,000 rows of data points
Data sourced from the CDC, collected through self reporting from each state
Very little missing data/data cleaning needed
Missing data was removed
Each state has its own data collection practices- assumed informed consent maintained
All data anonymized

CDC United States COVID-19 Cases and Deaths by State over Time (Jeffrey)
Collection of historical data since 10/18/2022
Reported by CDC, relying on data from state sources
60,000+ data entries

United States Census Bureau
#Extensive demographic data of American population
#Numerous attributes of American population recorded, only state populations used for #this project
#Data collected from reporting by every American household

2020 Census collection was impacted by COVID-19, may be less accurate than previous decades
#Data compiled and presented by US Census Bureau
#Americans needed to willingly provide information
#Data presented at population level, and PII is protected for 72 years

The COVID-19 US State Policy (CUSP)  (Jeffrey)
#Collection of data to understand how policies impact population health and health #equity in the US
#Reported information on when Closures and Reopenings and Mask mandates  within the #US states overtime. 
#Dates included were dates before and after 04/08/2022 for Mask Mandates and dates #before and after 06/08/2022 for Closure and Reopening of businesses. 
#However some states did not have any dates recorded

The Python file contains all the collaborative code for analysis we did with all the COVID data we mentioned above. 






