# Cyclicstic-Bike-Share--SQL-Code
This repository is for a capstone project from Google Data Analytics Professional Certificate.
Project Name: Cyclistic Bike Share 

<ABOUT THE COMPANY>

Cyclistic is a bike share program with over 5,800 bicycles locked in a network of 692 stations across Chicago, United States. Cyclistics offer a variety of bike types such as: reclining bikes, hand tricycles and cargo bikes making bike share more inclusive to people with disabilities and riders who cannot use a standard two-wheeled bike. Cyclistic also have a flexible pricing plans: single-ride passes, full-day passess and annual membeships. 

**BUSINESS GOAL**

The company aims to design marketing strategies to convert casual riders into annual member as it is has been concluded that annual members are much more profitable thancasual riders. The marketing team needs to better understand how annual members and casual riders differ and why casual riders will buy annual membership. 

**BUSINESS TASK**

Analyse 12 months data of the cyclistic bike share program to study trends of users inorder to help create a good marketing strategy.

**DATA SOURCE**

The data was gotten from https://divvy-tripdata.s3.amazonaws.com/index.html

**DATA PREPARATION AND PROCESSING**

For this analysis, i used the data from 2021-05 to 2022-04. The data was downloaded from the provided link as zip files after which they were converted into CSV. Considering the volume of the data, i decided to analyze using MySQL Workbench and Tableau was used for visualization.
The CSV files were imported into MySQL Workbench. A new schema was created and then the 12 months data was imported into seperate tables using "Table Data Import Wizard". 

The repository shows every step taken to clean and analyse the data in MySQL Workbench. 
Check out my visualizations on Tableau Public via this link https://public.tableau.com/app/profile/zainab.tobun/viz/GoogleDataAnalyticsCapstoneProject-CyclisticBikeShare/Story1?publish=yes

**CONCLUSION AND RECOMMENDATIONS**

Based on the analysis of the 12 months data to compare and discern how annual members and casual riders use cylistic bikes differently, the following were observed;

1. The percentage of Annual members that use cyclists bike is 11.96% more than casual riders
2. Bikes are generally used a lot more during summer but the number of casual riders using the bikes are more than annual members in that season. Annual members use the bikes more during the other season of the year. 
3. Casual riders tend to use the rides more for longer duration. There is a significance increase in the duration on Fridays and in December. 
4. Casual riders use the bikes more on weekends while annual members tend to use rides more on weekdays 
5. Both Annual members and casual riders prefer to use the classic bikes followed by the electric bikes. Annual members do not use the docked bikes.  
6. There is no significant difference in the distance of rides but casual riders tend to use the bikes for a slightly longer distance than annual members.

**Recommendations**
1. Marketing campaign should focus more on the start stations with more casual riders. It could be by sharing flyers or in person advert.
2. The campaign should be done mostly during the summer as a lot more casual riders use the bike at that time of the year.
3. An email could be sent to all casual riders informing them about the benefits of annual membership.
4. Yearly bonus or rewards should be offered  to riders with annual membership. 


