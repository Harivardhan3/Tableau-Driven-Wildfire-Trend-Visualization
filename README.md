
DATA VISUALIZATION PROJECT



TOPIC: Wildfire Trends USA




Professor: Dr. Andrew Bond



                                                             



                                          PREPARED BY:

                                                Name: HARIVARDHANA NAGA NAIDU POLIREDDI
                                                Name: Yashasvi Kotra






I. Abstract:

An uncontrollable fire in a wildland area, such as a forest, shrubland, or grassland, is called a wildfire. In recent years, wildfires have become more destructive due to factors such as climate change, there are more burnable materials in Western forests, and more people now live near areas where wildfires are likely to happen. Background, effects and chief causes of wildfires in the United States are covered in this explainer, along with their effects on the environment, the economy, and public health. Because of the severity of wildfire impacts in the America East, a significant amount of this explainer will concentrate on Eastern wildfires, even though we will discuss trends, causes, and effects of fire across the United States.
The losses and costs from these fires can greatly impact homeowners, communities, public spaces, and the environment. Utility companies have started to shut off power grids to prevent fires, causing significant disruptions to daily life. In our study, we examine the factors that influence wildfires and how changes in these factors over time can affect wildfire behavior and risk levels.
The findings from this project could be used by residents, firefighters, and policymakers for more effective wildfire risk management and mitigation strategies.


GitHub Link: 

https://github.com/Harivardhan3/Wildfires-Trends-USA---TableauDV-Project

II. Introduction and Context:

Humans have been working for decades to identify the causes of pollution and develop mitigation strategies. Certain elements of the environment are undoing decades' worth of advancements, despite knowledge and deliberate effort. One of them is air quality; over the years, wildfires' fierce rage has left a lasting scar on the ecosystems. Around the world, wildfires are frequent occurrences. Some of them, like the one in Australia in 2019–2020, have been extremely destructive, destroying millions of animals and plants in addition to nearly 2000 dwellings. Regarding the United States in a 2021 CNN news report (Western wildfire smoke is contributing to New York City's worst air quality in 15 years | CNN), strong winds have carried smoke from intense wildfires in the Western US to the East Coast.
Large wildfires that eventually spread to the city limits are one of the indirect and silent impacts of wildfires, and there are many more that have an impact on the environment's pyramid.  Understanding the origins and history of wildfires is essential for developing preventative measures, concentrating attention on high-risk areas, and enhancing air quality for better human health.



III. Objectives and Goals: 

The main goal of the project is to look at how often wildfires happen in the US over the years. This will help us see patterns and understand how to take steps to reduce the impact of wildfires better. Our primary goal is to dissect the causes of wildfires, the effects they have had on each state, and the steps that can be taken to lessen their frequency.

The goal is to determine the following:

1. Finding the States Most Affected by Wildfires: Examine the geolocation data to identify the states most impacted by wildfires. 
2. Highest Temperature Recorded: Examine temperature characteristics to see which states have had the highest number of recorded temperature events in previous years. 
3. What starts wildfires? enumerate the reasons why wildfires occur and determine which reason occurs most frequently. 
4. Examine current employee practices in various states that mitigate the risk of wildfires to lower the likelihood of them occurring. 
5. Time Analysis: Evaluate the behavior of wildfires on a yearly and monthly basis to raise public awareness of their occurrence. 
6. Examine fire classes to find common fire class occurrences in wildfires. 
7. Population Density and Wildfires: To analyze the spatial relationship between population density and wildfire occurrence and spread, as well as the impact on human settlements. 

I think that by pursuing these goals, will be able to reduce wildfires and develop beneficial preventative measures.



IV. Collection of Data:

Source: 

From Kaggle I got the wildfire dataset and cleaned the dataset through Excel and python – pandas.

https://www.kaggle.com/datasets/4735dcf84228370db9a551c153b520cc6d9166aaeadffaf6205745c31c3585ae

The dataset includes a database of wildfire incidents that happened in the US between 1992 and 2015. The initial purpose of its collection was to support the National Fire Program Analysis Systems (FPA). State and municipal fire organizations recorded the observations that are included in the database. The date of discovery, the magnitude of the end-fire, the number of temperature readings, vegetation, and distance are the main publications in the dataset. Creating graphs at the city/county and state levels using the dataset, which has 17,000 observations from every state in the United States. The information can be used for timeline analysis and spans the years 1992 through 2015. 

Changing factors:

Categories:
A summary of the reasons that wildfires occur
Finding out Year: The period from 1990 to 2015. years of incidents of wildfires 
Finding out Month: The number of months in a year that the wildfire was found. January through December 
Flames Name: Over the years, fires have been given names. 
States: United States list of states
Classification of Fire Types: B - flammable liquids, C - flammable gas, D - combustible material, E (electric flames), F (oils or fuels), and G (larger fires).

Calculated values:
 Flames Magnitude: The wildfire's magnitude was recorded. 
Size of Fire: The fire's size is the factor. Extension/Dispersal of fire inside a specific area
Exert time: The amount of time or minutes needed to douse the wildfire 
Remoteness: The population count within a state
Temperature count: Total temperature that has been recorded.
Vegetation: The plantation population in a state is known as vegetation.

Limitations: 
Our data set satisfies the purpose and goal and attempts to develop the expected responses; therefore, it is not required to adhere to any limitations about my research goal.


V. Stories Using Data:
1. Title of Chart: States Most Affected by Wildfires
Variables used: 
State (categorical): United States
Fire magnitude (measure): The wildfire's fire magnitude

Chart:

 

Explanation:
Investigate and determine which states had the greatest fire intensity. With a color range legend, this graph shows the states of the United States about the intensity of the fire. The darker the color, the greater the fire magnitude, and the lighter the color, the lesser the fire magnitude. 
Results: 
Nevada is the state with the largest number of fires. The states that border it from the east are California, Idaho, and New Jersey. 

2. Title of Chart: States with Highest Temperature Records
Variables used:
State (Categorical): United States
Temperature count (measurement): Total number of temperature readings

Chart:

 

Explanation:
Examining the states with the highest temperatures ever recorded in previous years is the description. With temperature as the primary property, the graph displays the states of the United States in terms of size and color. Higher temperature values are seen in states with larger populations, whereas lower temperature values are found in states with smaller populations. 

Results: 
Based on the graph, the states with the highest reported temperatures were Nevada, Idaho, and California.


3. Title of Chart: Reasons for Wildfires
Variables used:
Causes (Categorial): a summary of the reasons behind wildfires 
State (Categorical): United States
Fire magnitude (Measure): The wildfire's fire magnitude

Chart:

 

Explanation:
Analyze the list of wildfire causes and determine which states have the highest/most frequent wildfire occurrences. The wildfire causes are represented as a stacked bar graph, where each state's cause is indicated by a different hue. 

Results: 
Every state has found that lightning strikes are one of the most frequent causes of wildfires. According to this research, lightning is the primary cause of wildfires.

4. Title of Chart: Time of the wildfire extinguishment
Variables used:
Causes (Categorical): a compilation of wildfire causes.
Put-out time (Measure): The time/minutes required to put out the wildfire
Chart:

 

Explanation:
Examine reasons for causing wildfires in an amount of time needed to put them out. The table graph lists all of the wildfire causes and shows the time it took to put out each one in descending order for analysis. 

Results: 
Lightning strikes require the longest time to extinguish, while factors such as buildings, pyrotechnics, and kid-started fires require the least time. 

5. Title of Chart: Time Analysis - Annual
Variables used:
Finding out Year (categorical): the years 1990 through 2015. years of incidents of wildfires 
Fire Magnitude (Measure): The wildfire's fire magnitude 
Temperature Measurement - Temperature Measurement





Chart:

 

Explanation:
The project involves examining data on temperatures and the size of fires from 1990 to 2015. By using a dual-axis chart that combines a bar graph and a line graph, we'll be able to track changes over time. The bar graph will show the number of temperature measurements, while the line graph will display the size of fires for each year. This way, we can analyze the relationship between temperature and wildfires over 25 years. 

Results: 
The highest recorded temperature counts were in 2006 and 2011. 2011 was also the year with the highest fire magnitude ever recorded. Upon conducting intriguing research, we find that although 2006 saw the highest temperature, it was not the year with the largest fire magnitude.

6. Title of Chart: Time Analysis – Monthly
Variables used:
Finding out Month (categorical): when the wildfire was found, it had been months from January to December
Fire Magnitude (Measure): The wildfire's fire magnitude 
Temperature Measurement - Temperature Measurement

Chart:

 

Explanation:
Examining monthly time series to determine the months with the highest number of wildfires reported in a given year. We create a bar graph and line chart to illustrate the analysis, which we put out over a monthly period and compare to the fire magnitude and temperate count. The line chart shows the fire's magnitude over a period of months, while the bar graph shows the recorded temperature. 

Results: 
According to the data, the months with the greatest temperatures and fire magnitudes ever recorded were July and June.

7. Title of Chart: Examination of the Fire Class
Variables used:
Finding out Month (categorical): when the wildfire was found, it had been months from January to December
Fire Size Class: Refers to the several categories of fire classes, which are B - Flammable liquids, C - Flammable gas, D - Combustible material, E - Electric fires, F - Oils and Fuels, and G - Larger fires.



Chart:

 

Explanation:
Investigations into size of fires classes were placed throughout every month. We utilized a stacked bar graph to illustrate the goal, showing various colored fire classifications over the course of each month. 

Results: 
Throughout the course of several months, fire size class "G" has been found to have the greatest occurrence size class; class "F" comes in second.

8. Title of Chart: Impact of Population Density on Wildfires
Variables used:
State (Categorical): United States
Fire Magnitude (Measure): The wildfire's fire magnitude 
Remoteness (Measure) – State’s Population count





Chart:

 

Explanation:
The Aim is to find out if there's a link between how much wildfires affect an area and how many people live there. To show this, we're using tree maps. In these maps, the color shows the intensity of the fires in each state, with green for less intense fires and orange for more intense ones. The size of each section in the treemap shows how remote the area is: bigger sizes mean the area is more remote, which usually means fewer people live there.

Results:
It is clear from an observation that California is the state with the greatest degree of distance relative to population. States with higher remoteness levels include Arizona and Arkansas. There exists a correlation between the states with the lowest population density and the biggest magnitude of fire. However, the states with the biggest population density and least amount of remoteness, such as Colorado, Nevada, and Kansas, experience smaller fires.





VI. Story Telling: Dashboards
Dashboard1 - Most Affected vs Highest Recorded Temp. States
It is clear from an observation that California is the state with the greatest degree of distance relative to population. States with higher remoteness levels include Arizona and Arkansas. There exists a correlation between the states with the lowest population density and the biggest magnitude of fire. However, the states with the biggest population density and least amount of remoteness, such as Colorado, Nevada, and Kansas, experience smaller fires.

  

Dashboard2 - Wildfire causes vs Put out time
Examined the reasons behind the wildfires. After examining the causes, it was determined that lightning was the primary source of the wildfire and that it required the longest to put out.

  
Dashboard3 - Yearly vs Monthly time analysis
On looking into monthly and annual time series. As a result, 2011 was the year with the highest temperature and fire intensity. According to monthly findings, July is the month with the most wildfires. This can be connected to the earlier discovery regarding the origin of wildfires. July is lightning month, and lightning is a common source of wildfires. With the help of this forecast, we might implement several tactics to stop wildfires during lighting month.

 

Dashboard4 - Examination of fire class vs Population density
After establishing a link, our goal was to establish a second correlation between population density and the frequency of wildfires. Before doing this, we cross-check the most common fire classifications. Class "G," which defines major flames, is the outcome of it. We looked at the correlation between population impacts and big fire occurrences. Higher remoteness (low population) has increased the risk of wildfires as a result.

 
VII. Wildfire Analysis Dashboard:
Thorough analysis of wildfire data, with a focus on the consequences of wildfires in different states, their causes, and several related factors like temperature, fire type, and putout time. Below is a detailed analysis of the components and functions of the dashboard:

 

States Most Affected by Wildfires (Map):
Goal: Showcase the severity of wildfires in every state in the US.
Interactivity: Selecting a state likely removes information from other dashboard representations to display only the state’s information.

States with Highest Temperature Records (Bubble Chart):
Goal: The goal is to display the states with the highest temperature ever measured, as this is a major cause of wildfires. 
Interactivity: Data on the map or other charts may be able to be filtered or highlighted when a certain state or temperature range is selected.

Reasons for Wildfires (Stacked Bar Chart):
Goal: Determine the primary causes of wildfires in each state.
Interactivity: Filtering more visualizations to show data about fires with that particular cause by selecting a reason.


Put Out Time for Wildfires (List/Text Table):
Goal: The objective is to list the causes of wildfires and the time required to put them out.
Interactivity: By interacting with other charts, the precise distribution of put-out times may be displayed, depending on the selected cause.

Time Analysis - Yearly (Dual Line Chart):
Goal: Shows the number and size of fires over time, annually.
Interactivity: The data on the dashboard to only display information from a particular year by choosing that year.

Time Analysis - Monthly (Bar and Line Chart):
Goal: Illustrates the seasonal distribution of temperatures and wildfires.
Interactivity: Selecting a month could lead to additional visualizations displaying more detailed information from that time frame.

Examination of the Fire Class (Circle Chart):
Goal: Over a few months, investigates fire accidents according to size class.
Interactivity: Users may be able to inspect the details of fires in a given class, depending on that class.

Impact of Population Density on Wildfires (Tree Map):
Goal: Shows how each state’s population density and fire severity are related.
Interactivity: Users can highlight or filter data in various representations by selecting parts of the tree map based on population density statistics.

Comprehensive Evaluation:
Cohesion: The dashboard provides a holistic view by merging multiple data types that are necessary to understand wildfires.
Usability: This interactive feature is a helpful analytical tool since it allows users to dig deeply into specific states, causes, or periods within the data.
Design: The dashboard is easy to view thanks to its simple, uncomplicated layout. The color palette seems to be deliberately chosen to communicate the type and seriousness of the data.
Data Insights: The dashboard may include information on trends such as the relationship between high temperatures and the frequency or intensity of wildfires, the success of suppression operations across different regions, and the frequency of wildfires in connection to specific seasons.


VIII. Building the Tableau dashboard in HTML web page:
The dashboard has been published in Tableau Cloud which generates an embed link. This link is integrated through an HTML code using D3.js by copying the link of the published dashboard. Opening the file in a web browser allows you to display the project dashboard embedded in the HTML page.

Published dashboard link:
<script type='module' src='https://us-west-2b.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://us-west-2b.online.tableau.com/t/yashasvidataviz/views/WildfireTrendsUSA/PopulationDensity/6e41cf1b-3975-4c30-bc97-05d299cf22fd/a787d478-2b89-45c9-9f19-e74cc7b8c044' width='1518' height='1027' toolbar='bottom' ></tableau-viz>

HTML code:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wildfire Trends USA Dashboard</title>
    <script type='module' src='https://us-west-2b.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>
</head>
<body>
    <tableau-viz id='tableau-viz' src='https://us-west-2b.online.tableau.com/t/yashasvidataviz/views/WildfireTrendsUSA/PopulationDensity/6e41cf1b-3975-4c30-bc97-05d299cf22fd/a787d478-2b89-45c9-9f19-e74cc7b8c044' width='1518' height='1027' toolbar='bottom'></tableau-viz>
</body>
</html>

Webpage link:

http://localhost:8000/wildfiretrends.html


Screenshots of the project dashboard embedded in the HTML page.

 


 



IX. Synopsis and Conclusions:
The report's insights about the incidence of wildfires in the United States over a period of years highlight key trends and highlight the need for wildfire mitigation. Creating and implementing plans that prevent wildfires and limit damage is one way to achieve this. We have discovered important results from this thorough analysis of historical data and pertinent variables, including the most affected states, the highest temperature ever recorded in a state, the primary causes, such as lightning, and a time series analysis that revealed July to be the month with the highest frequency of occurrence. To establish a correlation, we can look at the fact that July is the lightning month and that lightning is typically the leading cause of wildfires. Our results also offer crucial proof of the relationship between population and wildfire danger: isolated locations often have higher wildfire risk than inhabited ones. 

To sum up, the balance between the environment and humans is at risk because of wildfires. In my research, I've taken steps to raise awareness and tackle the specific challenges that come with wildfires. By applying what I've learned, I can help create a safer and more robust future against the risk of wildfires.
X. References:

[1] Citations: Short, Karen C. 2017. Data on spatial wildfire occurrences in the United States from 1992 to 2015 [FPA_FOD_20170508]. Fourth Edition. Forest Service Research Data Archive, Fort Collins, CO, https://doi.org/10.2737/RDS-2013-0009.4
[2] Integrated Surface Hourly, NOAA National Centers for Environmental Information (2001) [1992-2015] - ftp://pub/data/noaa/@ftp.ncdc.noaa.gov
[3] Prasanth, Meiyappan, and Atul K. Jain. "Three distinct global estimates of historical land-cover change and land-use conversions for over 200 years." 122-139 in Frontiers of Earth Science 6.2 (2012).
[4] "World Cities Database." World cities, simple maps, simplemaps.com/data.
[5] K. C. Short, 2014. a geographical database of US wildfires from 1992 to 2011. Earth System Science Data, Volume 6, Issue 1, and 27, doi:10.5194/essd-6-1-2014 
[6] Karen C. Short [FPA_FOD_20130422], 2013. Spatial wildfire occurrence data for the United States, 1992-2011. First Edition. Rocky Mountain Research Station, USDA Forest Service, Fort Collins, CO. https://doi.org/10.2737/RDS-2013-0009



