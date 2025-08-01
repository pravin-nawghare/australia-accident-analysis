# Australian Road Accidents Analysis


## Project Overview
The goal of this project is to analyze historical road accident data in Australia from 1960 to 2024 and to identify key trends, contributing factors, and the effectiveness of past safety measures. 

The analysis will focus on various aspects of road safety, including accident severity, location, driver demographics, and the impact of different road types. By examining these factors, we aim to uncover long-term trends and assess the effectiveness of past safety measures.

By leveraging the insights, this analysis aims to provide recommendations for improving road safety policies, infrastructure, and public awareness initiatives to reduce accident rates and enhance 
overall traffic safety. 

The data used in this project is sourced from the Australian Road Deaths Database, which is a comprehensive collection of road accident statistics and information. The dataset includes details about the number of accidents, fatalities, injuries, and various factors contributing to road safety. The data is updated regularly to reflect the most current information available.
(The data is updated till *31st December 2024*).

[Click here to go visit the Australian Road Deaths Database](https://catalogue.data.infrastructure.gov.au/dataset/australian-road-deaths-database)

## Background and Overview
Road safety has been a significant concern in Australia for decades, with thousands of accidents occurring each year. Since 1960, government agencies, policymakers, and researchers have worked to understand the factors contributing to road accidents and develop strategies to improve traffic safety. Various policies, technological advancements, and awareness campaigns have influenced accident trends over the years, but challenges remain in reducing fatalities and injuries on Australian roads.  

This project analyzes historical road accident data from 1960 to 2024, examining key factors such as accident severity, location, driver demographics, speed-limit, time of day, etc. 

Now, with an increasing focus on road safety, policymakers and transportation authorities seek a deeper understanding of accident patterns. The primary objectives of this analysis are:  
1) To identify the major causes and risk factors associated with road accidents in Australia.  
2) To provide actionable insights for reducing accident rates and improving road safety policies.

## Summary
Overall trend of deaths happening in road accidents are decreasing  from 1990 but after covid restrictions were relaxed an increase in deaths has been observed whereas number of accidents are still decreasing.
[<img src="visuals/Trend line overview.png" alt="Trend line" height="500px">](https://github.com/pravin-nawghare/australia-accident-analysis/blob/main/visuals/Trend%20line%20overview.png)
- **72882** total accidents has been recorded in Australia till *31st December 2024* and **56756** peoples are died in these fatal accidents which means in *every 10 accidents 8 people dies*. 
- In 2024, 1549 accidents happened in which 1279 people died. This figure is **4.3%** more than people died in 2023.
- The trend in accidents and deaths is increasing since 2020. The number of accidents in 2024 is **2.5%** more than the previous year.
- **Heavy vehicles** like trucks, containers, etc. caused *16%* of total accidents and accounts for *11%* of total deaths.
- **December** accounts for highest number of deaths (4601) whereas **February** for lowest (3899). 
- On weekends (Friday and Saturday) majority of accidents happens.
- **50%** of total accidents are happening only in *New South Wales and Victoria.*

State wise distribution of all deaths happended in Australia
[<img src="visuals/State wise distribution.png" alt="State wise distribution" height="500px">](https://github.com/pravin-nawghare/australia-accident-analysis/blob/main/visuals/State%20wise%20distribution.png)

## Insights deep dive
**Breakdown by months**
- **December** is considered as a holiday season therefore this month accounts for number of accidents more than *5000* followed by March and the same trend is also seen in terms of deaths also.
- It is unclear why **March ranks second** in terms of accidents as well as in death count where *February* have least number of accidents and therefore, lesser number of deaths.
- On an average around **130** accidents happens every month in Australia in which around **107** peoples dies every month.

Monthly breakdown of all fatalities happended
[<img src="visuals/Month wise death distribution.png" alt="Month wise distribution" height="500px">](https://github.com/pravin-nawghare/australia-accident-analysis/blob/main/visuals/Month%20wise%20death%20distribution.png)

**Speed of Vehicle**
- **Overspeeding** is the main cause of accidents. Most accidents happens when the vehicle is going above **90km/h** in a city region.
- It is observed that most of the times the driver of the overspeeding vehicle is either a *teenager* or a *young adult* less than 25 years of age.
- Death to accident ratio is lowest when speed is greater than 120km/hr that is because this type of speed is acheivable mostly on highways. 
- But in cities if the speed is in between 30-60km/hr the ratio rises to 92%. The rise is because cities are densly populated _(because most accidents happened in two city which have largest population density in Australia)_ as compared to highways and because of this most of the **accidents** happening on *highways involves heavy trucks and vehicles.*
- If the speed is greater than *30km/hr*, either **pedestrain** or **pedal cyclist** is involved in an accident then *95%* of times they are dead. This count is highest compared to other road user type.
- Out of total accidents 45% of the time the driver dies. Followed by the passenger 22.73% and 15.4% is the pedestrian.

Accidents happended at various vehicle speed ranges
[<img src="visuals/Speed wise distribution.png" alt="Speed wise distribution" height="500px">](https://github.com/pravin-nawghare/australia-accident-analysis/blob/main/visuals/Speed%20wise%20distribution.png)


**Road Type**
- 32000 cases are their were the exact loaction of accident is unknown.
- *Arterial Road and National* or *State Highway* are the one where generally the vehicle speed is greater than 60km/hr and therefore accounts for most number of accidents.
- *Pedestrian Thoroughfare* and *Busway* only recorded few accidents but every time people invovled in accident died.

**Time**
- **Mondays** are best because on monday  *least* number of accidents happens. But as we progress towards the end of the week this number rises rapidly.
- People likes to enjoy their weekends and therefore this time of the week most number of accidents happens mainly on *Friday*.
- **50%** of total accidents are recorded on weekends only.
- On weekdays from 6 in the morning till 6 in the evening the accident count is highest whereas on weekends at evening after 6 o'clock till 2am accidents mostly happens at this time.
- Reasons are not clear but at 3am at the midnight on weekdays a sudden spike in number of accident is observed.

Accidents happening all around the week
[<img src="visuals/Day wise ditribution.png" alt="Day wise distribution" height="500px">](https://github.com/pravin-nawghare/australia-accident-analysis/blob/main/visuals/Day%20wise%20ditribution.png)

## Recommendations to Reduce Accidents
- **Awareness Campaigns**: Launch targeted awareness campaigns focusing on the dangers of overspeeding, especially among young drivers. Use social media, schools, and community events to reach this demographic.
- **Speed Limit Enforcement**: Overspeeding is a major cause of accidents, so increase the enforcement of speed limits, particularly in urban areas. Use speed cameras and police patrols to deter overspeeding. Implement stricter penalties for speeding violations and increase the use of speed cameras, especially in city regions and highways.
- **Driver Education**: Implement educational programs for new drivers, emphasizing the importance of adhering to speed limits and understanding the risks associated with overspeeding.
- **Improve Road Infrastructure**: Upgrade and maintain arterial roads and highways to reduce accident-prone areas. Install proper lighting and reflective signs on highways and pedestrian crossings to improve visibility at night.
- **Road Design Improvements**: Consider redesigning high-accident areas, especially in urban settings, to include features that naturally slow down traffic, such as speed bumps or roundabouts.
- **Pedestrian Safety Measures**: Enhance pedestrian safety measures, especially in areas with high pedestrian traffic. This could include better signage, crosswalks, and traffic signals.
- **Increase Police Patrols During High-Risk Hours**: Deploy more traffic police during peak accident times, such as weekends after 6 PM and early mornings on weekdays. Conduct random breath tests to deter drunk driving, especially during late-night hours.
- **Data Monitoring**: Continuously monitor accident data to identify trends and adjust safety measures accordingly. This will help in understanding the effectiveness of implemented strategies and making necessary adjustments.
- **Collaboration with Local Authorities**: Work with local authorities to address specific high-accident areas, ensuring that road safety measures are tailored to the unique needs of each region.
- **Focus on High-Risk Areas**: Prioritize safety measures in New South Wales and Victoria, which account for 50% of total accidents. Conduct detailed studies to identify and address accident hotspots in these regions.
- **Public Transport Awareness**: Increase awareness about the safety of public transport and encourage its use, especially during weekends when accidents are more frequent.


**By implementing these measures, we can work towards reducing the number of accidents and fatalities on Australian roads, making them safer for everyone.**

**Caveats**

**Some data like road type, weather conditions, road conditions, health of driver, whether the driver was under the influence of alcohol or drugs, etc. are not available in the dataset.**
**This analysis is based on the available data and may not cover all aspects of road safety.**

