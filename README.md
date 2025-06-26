# Olympics Games Analysis (1896-2016) (Interactive Dashboard creation using Power Bi) - IN PROGRESS .........



![image](https://globallygrounded.com/wp-content/uploads/2016/08/olympic-games.jpg)


## Table of Contents

- [Project Overview](#project-overview)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)  
- [Insights](#insights)


## Project Overview
From its inception, The Olympic games have grown to become an important and honored global event, where almost all nation represent by fielding thier teams to compete for medals. Before the 1970s, the Games were officially limited to few competitors but in the 1980s many events were opened to professional athletes. Currently, the Games are open to all, even the top professional athletes in basketball and football (soccer). 

This project aims to provide valuable insights from this data on the performance of the event over time, such as the participation, medals won by country and athletes, gender analysis, the various sports and the overal Olympic trends.
 



## Data Preparation

### Sample Data

The primary data used for this analysis is the "athlete_events.cvs" file, which contains 15 columns such as the ID, Name, Sex, Age, Height, Weight, Team, NOC, Games, Year, Season, City, Sport, Event, Medal.

The data was downloaded from a Youtube channel, DataMinds Academy.

Get data from here [download](https://www.youtube.com/watch?v=2orCOI4q_qc)

### Tools Used
- Power Bi
  
  * Cleaned the data with Power Query.
    
  * Visualization.
  
### Data Cleaning 
- Missing Values: Identify and handle missing values in the data. Techniques used includes imputation (filling missing values with estimate) or deletion depending on the data and its importance.

- Data types: Ensure that values in each column is in the right data type such as text, interger etc. 

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) is a data analytics process performed to gain an in-depth understanding of  the data and learn the different data characteristics.

- ETL: I begun the ETL process by importing (Extract) the csv file into Power Bi, transformed the data in Power Query before Loading it into Power Bi for analysis and visualization.

- Headers: I corrected the column headers by making the first row as headers and also checked for any incorrect or misspelled header.

- Data Type: I checked for the data type in each column such as text, intergers etc.

- Missing Values: Columns such as the Age, Height, Weight and Medal contained missing values which was replaced with Null.

- The data contained 271,116 rows and 15 columns.

- For this project, I wanted to analyse the age group of athletes that participated and won medals, therefore created a new column namely age group.






### Dashboard

![Dashboard](https://github.com/user-attachments/assets/a40c746c-4dd3-4cfb-9c0a-93044b7b4f3e)

  
## Insights

From the data the following insights were acquired;

- Total Athletes - 135,571
- Total Medals Won - 39,783 (Gold - 13,372 / Silver - 13,116 / Bronze - 13,295)
- Sports - 66 Differrent sports
- Events - 765 different events
- Host - 42 Host Cities
  
![Total Athletes   Medal Won per Sports](https://github.com/user-attachments/assets/972f7f27-e284-476a-bb12-63cd2d1ed8d8)

![No  Athletes over the Years](https://github.com/user-attachments/assets/b274a7f5-5a8a-4bdf-9fe0-89a8b9c75ca8)

![All Time Medalist](https://github.com/user-attachments/assets/a8d70418-ba67-47c8-b75f-c3fb985fe176)

![Medal won per age group](https://github.com/user-attachments/assets/740e37c9-c2b7-4ed7-a9ac-d7f734b56a94)

![Country Appearance](https://github.com/user-attachments/assets/ecf203a1-26de-4919-8d74-6329eb3ac334)

![Medal won by Country](https://github.com/user-attachments/assets/5c005ee4-cd14-420e-93aa-a679b1bd4dc9)







