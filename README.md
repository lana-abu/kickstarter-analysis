# Kickstarting with Excel

## Overview of Project

### For our Module 1 challenge, we were tasked with analyzing how different campaigns faired in relation to both their fundraising goal as well as the time of the fundraiser. We took a large set of data and used formulas and techniques available via excel to answer questions such as: 1) Which goal ranges were the most/least successful? 2) Were there certain months in which achieving fundraising goals were more successful? 3) Did certain categories perform better than others? 4) When should someone fundraise for a particular category? These are just a few questions that analysis of the data allowed us to answer. 

## Analysis of Outcomes Based on Launch Date

![image](https://user-images.githubusercontent.com/96541632/148714899-f393d609-6738-49d9-91b0-c686431ad90c.png)

![image](https://user-images.githubusercontent.com/96541632/148714747-0acc2749-ebbd-41b2-af13-f6dc5033b527.png)

![image](https://user-images.githubusercontent.com/96541632/148714607-44266136-9691-4eff-8435-eb518129b704.png)

In order to analyze outcomes based on the date a fundraiser was launched, I created a pivot table using the excel sheet that contained all the data. I wanted to be able to filter by the parent categories in order to be able to hone in on theater specifically as well as by the year so I could look at specific years or all years. I also created a line chart which helped to easily notice any trends in the data. On the x-axis we had the month that the fundraiser was launched and on the y-axis we had the number of successful, cancled, and failed campaigns, denoted by the color of the line. 

##Analysis of Outcomes Based on Goal

![image](https://user-images.githubusercontent.com/96541632/148717123-8d4a0f52-938e-44c1-ac7b-18454bfdd392.png)


In order to analyze outcomes based on goals, I created another excel sheet. This sheet had 12 different goal ranges and broke down the goal ranges by the absolute numbers that were successful, failed, and canceled and looked at those as a percentage of total projects in that goal range. To determine the number of successful, canceled, and failed projects, I used the COUNTIFS() formula and pulled the data from the original data set. An example of a formula is shown in the above screenshots. In order to determine the total projects for each goal range, I used the SUM() formula and to add all the successful, failed, and canceled projects for that range. To determine the percentage of successful, failed, and canceled projects, I just divided the number successful/failed/canceled projects by the total projects specific to that goal range. Then, I created a line chart to get an easy visualization. 

### Challenges and Difficulties

The pivot table was easy to create but a challenge that could be had, especially without the guide in the module, would be determining what data to include in the filters, columns, rows, and values section of the pivot table. I think it would be easy to get confused. However, because it is so simple to move the data around, it would be easy to play around with the data and get the pivot table looking the way you want it to look. The analysis of outcomes based on goals was not too challenging. However, even though I copied a formula to different cells, it was laborious to have to go in each one and change the data inside of it to be specific to that cell. I wonder if there is an easier way because with a larger data set it may prove difficult. 

##Results

Looking at the theater outcomes based on launch date, I can draw a couple conclusions. The first would be that most theater projects are successful in the months of May and June (most of the summer months.) The second would be that towards the end of the year, the number of successful projects begins to decrease and the number of failed projects begins to increase. 

Looking at the outcomes based on goals, I can draw a couple of conclusions. The first would be that most projects with a goal less than $1000 fail. The second conclusion is that every goal category with a goal above $1000 had more successful than failed and canceled projects. 

Limitations for theater outcomes based on launchdate: 
We don't look at where the most successful outcomes occur. While we can say that the summer months have the most successful goals, we cannot tell WHY this is true. We also don't have a breakdown of how big the goals are in the summer and if that plays a part in how successful the goals are. 

Limitations for outcomes based on goals: 
While we can say that goals less than $1000 are mainly unsuccessful, we cannot say why. How are these projects attempting to get funding? What is the breakdown, based on category, of these projects. When are these projects trying to get funded? 

Other tables/graphs:
Creating a pivot table with the goal ranges and being able to filter the goals by category and looking at the number of successful, failed, and canceled projects. Essentially, combining the two tables above. 
