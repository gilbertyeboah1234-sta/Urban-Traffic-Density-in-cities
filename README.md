# Urban-Traffic-Density-in-cities

<img width="474" height="270" alt="image" src="https://github.com/user-attachments/assets/cd13fcc1-bfb2-487f-8291-92b756a32398" />

This dataset provides a detailed view of traffic data in a futuristic urban environment, containing over 1.2 million records. Each record represents a unique snapshot of various factors affecting traffic conditions in six fictional cities.

Project Overview

This project analyzes urban traffic patterns across multiple futuristic cities using Microsoft Excel. The analysis focuses on traffic flow, traffic density, weather conditions, vehicle types, energy consumption, days of the week, and variations between cities.

The workbook uses data preparation, calculated fields, PivotTables, charts, interpretation of results, and a dashboard to transform the raw traffic dataset into useful insights that can support traffic planning and transportation analysis.

Dataset Overview

The dataset contains 1,299 observations covering traffic activity across six cities.

Cities Included
AquaCity
Ecoopolis
MetropolisX
Neuroburg
SolarisVille
TechHaven
Main Variables
Variable	Description
City	City where the traffic observation was recorded
Vehicle Type	Type of vehicle involved
Weather	Weather condition during the observation
Economic Condition	Economic environment of the city
Day Of Week	Day on which the traffic observation occurred
Hour Of Day	Hour of the day from 0 to 23
Speed	Recorded vehicle or traffic speed
Is Peak Hour	Indicates whether the observation occurred during peak hours
Random Event Occurred	Indicates whether a random event affected traffic
Energy Consumption	Amount of energy consumed
Traffic Density	Level of traffic concentration
Dummy Vehicle Type	Numerical encoding of vehicle categories
Dummy Weather	Numerical encoding of weather categories
Dummy Economic Condition	Numerical encoding of economic conditions
Traffic Flow	Calculated measure of traffic movement

Traffic Flow is calculated as:

Traffic Flow = Speed × Traffic Density

Data Categories

The dataset contains four vehicle types: Autonomous Vehicle, Car, Drone, and Flying Car.

Five weather conditions are represented: Clear, Rainy, Snowy, Solar Flare, and Electromagnetic Storm.

Economic conditions are grouped into Booming, Stable, and Recession.

The dataset covers all seven days of the week and all 24 hours of the day.

Business Questions

The project addresses the following five business questions:

What is the traffic flow pattern in urban areas?
How does traffic density vary under different weather conditions?
Which vehicle types consume the most energy on average?
How does traffic flow vary across the days of the week?
Which cities experience the highest and lowest average traffic flow?
Analysis Approach

The data was prepared and analyzed using Microsoft Excel. PivotTables were used to summarize the major variables, while charts were used to visually communicate the results.

The workbook is organized into the following worksheets:

Worksheet	Purpose
Business Question	Contains the five questions guiding the analysis
Dataset	Contains the original dataset and calculated variables
Analysis	Contains PivotTable analyses and charts
Interpretation of Analysis	Explains the results obtained from each analysis
Dashboard	Provides a visual summary of important findings
Executive Summary	Section for summarizing the overall project findings
Key Findings
1. Traffic Flow Pattern by Hour

Average traffic flow changes throughout the day, showing that traffic activity is not constant across different hours.

The highest average traffic flow was recorded around 9:00, at approximately 20.09, while one of the lowest levels occurred around 21:00, at approximately 10.12.

The overall average traffic flow in the dataset is approximately 15.93.

2. Traffic Density and Weather Conditions

Traffic density differs across the weather conditions represented in the dataset.

Weather Condition	Average Traffic Density
Clear	0.285
Electromagnetic Storm	0.283
Snowy	0.280
Rainy	0.259
Solar Flare	0.244

Clear weather recorded the highest average traffic density, while Solar Flare recorded the lowest.

These results show an association between weather conditions and traffic density within the dataset but do not establish that weather directly causes the differences.

3. Energy Consumption by Vehicle Type

Average energy consumption differs considerably between vehicle types.

Vehicle Type	Average Energy Consumption
Flying Car	65.95
Car	60.49
Autonomous Vehicle	53.96
Drone	32.34

Flying Cars have the highest average energy consumption, while Drones have the lowest.

The overall average energy consumption across the dataset is approximately 49.90.

4. Traffic Flow by Day of the Week
Day	Average Traffic Flow
Monday	14.36
Tuesday	16.90
Wednesday	15.17
Thursday	16.38
Friday	16.08
Saturday	16.44
Sunday	15.94

Tuesday recorded the highest average traffic flow at approximately 16.90, while Monday recorded the lowest at approximately 14.36.

This indicates that traffic activity varies throughout the week.

5. Traffic Flow Across Cities
City	Average Traffic Flow
MetropolisX	29.29
AquaCity	24.41
SolarisVille	17.07
Ecoopolis	11.54
TechHaven	10.32
Neuroburg	4.14

MetropolisX recorded the highest average traffic flow, followed by AquaCity.

Neuroburg recorded the lowest average traffic flow.

The large differences between cities suggest that traffic conditions vary substantially depending on location.

Key Performance Measures

The dataset has the following overall characteristics:

Measure	Value
Total Observations	1,299
Number of Cities	6
Vehicle Types	4
Weather Conditions	5
Average Traffic Flow	15.93
Average Traffic Density	0.270
Average Energy Consumption	49.90
Average Speed	59.71
Tools and Techniques Used
Microsoft Excel
Data Cleaning and Preparation
Categorical Data Encoding
Calculated Fields
PivotTables
PivotCharts
Descriptive Analysis
Dashboard Development
Data Interpretation
Conclusion

The analysis demonstrates that urban traffic behaviour differs significantly depending on the time of day, weather condition, vehicle type, day of the week, and city.

Traffic flow is particularly different across cities, with MetropolisX recording substantially higher average flow than cities such as Neuroburg and TechHaven. Vehicle type also plays an important role in energy consumption, with Flying Cars recording the highest average energy use.

The findings can support further investigation into urban transportation planning, energy efficiency, traffic management, and the factors associated with traffic congestion.

Limitations

The findings describe patterns and relationships observed within this dataset. They should not automatically be interpreted as causal relationships.

Additional variables such as population size, road capacity, number of vehicles, infrastructure quality, accidents, and geographic characteristics could provide a more complete explanation of the traffic patterns observed.

Project File

Workbook: Gilbert - Project 2 -.xlsx

The workbook contains the complete dataset, analyses, interpretations, charts, dashboard, and supporting calculations for the project.

I’m open to connecting with others interested in Data Analysis, Excel, Business Intelligence, and similar projects. Feel free to explore the project, share your thoughts, or collaborate on future data-driven projects. Contact via E-mail: gilbertyeboah1234@gmail.com
