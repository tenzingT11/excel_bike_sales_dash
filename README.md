In the following, I will be cleaning raw data and creating a dashboard for the average income of somebody who either bought or did not buy a bike. Raw data is from [github](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx). 

First, I will select the data and remove any duplicates. 
<img width="1512" alt="p1" src="https://user-images.githubusercontent.com/99940156/217597732-d9e0ac5d-23d0-4e21-bc68-df5a8812e11a.png">


For easier readibility, we'll make a few changes in column B, column C and column D.

Before:
<img width="1512" alt="p2" src="https://user-images.githubusercontent.com/99940156/217597840-4975a13a-b89a-4069-8a32-fb64c5e6ac69.png">

After:
<img width="1512" alt="p3" src="https://user-images.githubusercontent.com/99940156/217597888-97255a34-8f1d-46fa-8c8e-f4cf8263eed4.png">

Since there's a diverse age group in column L, (ages 25 through 89), we'll create a new column M, to make the ages in column L into categories so that it'll be easier to understand and more usable than the individual ages in column L.

Before:
<img width="1512" alt="p4" src="https://user-images.githubusercontent.com/99940156/217597970-28fc8fa2-2941-4e55-8a58-7788cb7e91f6.png">

After: 
<img width="1512" alt="p5 2 47 11 PM" src="https://user-images.githubusercontent.com/99940156/217599795-983a973a-1ce6-41d9-b3a8-1596796e635d.png">

<img width="1512" alt="p5" src="https://user-images.githubusercontent.com/99940156/217598057-2ffacdf9-0c4e-41a0-a2da-bed6b196d5dc.png">

Next, we'll create pivot tables for our dashboard.

Does income have any effect whether or not someone bought a bike?

<img width="870" alt="p6" src="https://user-images.githubusercontent.com/99940156/217598149-40727148-489c-4ac1-a2fd-cbe74ee3c377.png">

Another important factor is commuting distance. Does the person who is buying a bike live one mile away from work or 10 miles? This next visualization will help us answer this question.

<img width="908" alt="p7" src="https://user-images.githubusercontent.com/99940156/217598216-39c2d112-f607-4562-a4eb-be124f379eb6.png">

In the next pivot table and visualization, we'll compare the number of bikes purchased within different age brackets: adolescent(less than 31 years old), middle aged(31-55 years old), and old(55 years or older).

<img width="936" alt="p8" src="https://user-images.githubusercontent.com/99940156/217598322-ccdeff07-ef3a-4c80-91db-1bd92f1b64ab.png">


In the final dashboard, we can filter the visualizations by marital status, region, and education:

<img width="734" alt="p9" src="https://user-images.githubusercontent.com/99940156/217598413-67900c04-f626-4fdf-9c9c-d621ec25f602.png">


In summary, we can see that those who have a higher average income, whose commute is less than a mile, and those who are middle aged have a higher number of purchased bikes. With this trend, we can predict that people that fall into those categories also will be more likely to purchase bikes in the future. On the left hand side, we can compare and contrast the visualizations based on marital status, region, and education. A link to the interactive dashboard is [here.](https://1drv.ms/x/s!Als4RvzLaaBzihhCgzUw_81NvW_l?e=UPbNzx&nav=MTVfezMxMDgzMDNCLTBBNUItNEVCQi05NEE4LTQ1Rjg3RUQ3MTM4OX0)

