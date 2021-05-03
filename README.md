# Challenge 1: Kickstarting with Excel
## Objectives
This project is aimed at covering basic Excel functions and familiarizing the students with pivot charts/tables. The purpose of this project is to discover the relationship between "release date" and the "success rate" of entertainment articles. 

## Output File
The excel file were this analysis took place can be found here: [Kickstarter Challenge](https://github.com/arianakhakpour/Data-Analytics/blob/main/Kickstarter_Challenge.xlsx)

## Analysis and Challenges
Raw data was modified for analysis. Date formats (launch date and deadline) were converted to YYYY-MM-DD from timestamp format. The "Month" was also extracted from the launch date. 

## Analysis of Outcomes Based on Launch Date
A pivot table was developed that reports the total count of successful, failed and canceled shows for each "launch month". "Launch year" and "parent company" were set as filters and the "outcomes" were constituting the columns. The results can be viewed here: [Outcome based on launch date](https://github.com/arianakhakpour/Data-Analytics/blob/main/Theater_Outcomes_vs_Launch.PNG).

## Analysis of Outcomes Based on Goals
Raw data was modified to categorize the "Goals" into 5K intervals. Number of successful, failed and canceled shows were seperately counted for each goal interval. Total occurances were calculated by adding up these numbers, and percentages were calculated using this formula:

%Succes = 100 * (No. of successful  / total count)
%Failed = 100 * (No. of failures / total count)

The success/failure ratio was plotted against goal range and can be found here: [Outcome based on goals](https://github.com/arianakhakpour/Data-Analytics/blob/main/Outcomes_vs_Goals.PNG).

## Challenges and Difficulties Encountered
Major challenged faced during this project was the conversion of "stamped time" into a normal date format. Online resources helped me find the conversion formula and overcome this obstacle. 

## Discussion of Results
>What are two conclusions you can draw about the Outcomes based on Launch Date?

It can be concluded that the total number of shows are higher during May through August. Success rate, however, tends to be higher during this peak period. It can also be observed that the occurance of canceled shows is fairly steady throughout the year.
See:  [Outcome based on launch date](https://github.com/arianakhakpour/Data-Analytics/blob/main/Theater_Outcomes_vs_Launch.PNG).

>What can you conclude about the Outcomes based on Goals?

Success rate tends to drop with an increased goal. See: [Outcome based on goals](https://github.com/arianakhakpour/Data-Analytics/blob/main/Outcomes_vs_Goals.PNG).

>What are some limitations of this dataset?

High computational demand due to large size data. 

>hat are some other possible tables and/or graphs that we could create?

Success rate based on show category, success rate based on spotlight history, etc...
