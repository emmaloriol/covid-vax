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
```````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
Another crucial component is updating the libraries over time, yet we can observe that many modules depreciate within a month. So please pay attention to the syntaxes and the parameters being supplied to the methods. (Since Python programming language is an open source).

Follow the syntax listed below to install a library and run the code:

IN JUPYTER NOTEBOOK: ! PIP INSTALL <MODEULE NAME>
IN TERMINAL : PIP INSTALL <LIBRARY NAME>

For Instance,
  if we want to install Folium library thats not by default attached in the python default libraries (IN BIN FOLDER):
  So we need to explicitly do that using : !PIP INSTALL FOLIUM(MINIMAL INTERNET CONNECTION REQUIRED)
  We advise you to collect the dataset from the website listed in the citations as our use of the dataset from github may result in static data visualizations; instead, try utilizing raw github to obtain real-time data (Trend in the Current times).
  
  
IN ORDER TO RUN THE CODE(ONLY PYTHON TERMINAL(PROMPT) AND PYTHON PACKAGES ARE FINE TO GET THE CODE RUNNING):

Step 1:
Install all necessary libraries at once, then attempt to run each cell individually using the output of the cell before it as the input for the cell after it.

Step 2:
Make sure to examine any warning messages with the syntax(Modified) at the time you are executing the code because it might also become obsolete the next time you access the code..

Step 3:
There you go the project is about Covid -19 Deaths and Vaccines. Have an glance at the ouputs and some realtime plots and visualizations.


Check the below links to have the correct syntaxes:

  https://docs.python.org/3/installing/index.html
  
  https://docs.python.org/3.7/howto/cporting.html
  
  https://pypi.org
  
And for tuning in the parameters in graphs we reffered :
(As we have mostly used seaborn and matlplot lib)

  https://matplotlib.org/stable/tutorials/introductory/customizing.html
  
  https://www.w3schools.com/python/numpy/numpy_random_seaborn.asp
  
  https://towardsdatascience.com/seaborn-python-8563c3d0ad41
  
  
  
  
  

