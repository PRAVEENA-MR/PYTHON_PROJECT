# PYTHON_PROJECT
Working with a dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. Tasks include preprocessing the dataset, analyzing the data, and presenting  findings graphically. Here's a breakdown of what need to do:
Preprocessing:
Correct the data in the "height" column by replacing it with random numbers between 150 and 180. Ensure data consistency and integrity before proceeding with analysis. 

Analysis Tasks:
1. Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees. <br>
2. Segregate employees based on their positions within the company. 
3. Identify the predominant age group among employees. 
4. Discover which team and position have the highest salary expenditure. 
5. Investigate if there's any correlation between age and salary, and represent it visually.

   # Dataset
   https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link

   # Preprocessing
   First and foremost imported libraries and Loaded the dataset.Then performed data exploration using different available functions. 
   Prepossing Steps includes <br> <br>
   1. Finding and deleting duplicated rows in the dataset  <br>
   2. Values in height column is not valid ,so generated random numbers between 150 and 180 for 'Height' column and changed datatype <br>
   3. Finding and deleted null values which is very less compared to size of dataset <br>
   4. Replaced null value in salary column by salary mean <br>

   # Analysis
   1. The distribution of employees across each team and calculated the percentage split relative to the total number of employees<br>
        For distributin of employee across each team is ploted using pie chart. Pie chart named 'Team Composition by Percentage' visually represents each team 
      composition <br><br>

   2. Segregate employees based on their positions within the company.<br>
         Employee segregation is ploted using bar chart, from the bar chart it is clear that no.of employee in Shooting guard - SG is higher than other positions 
       which is 102. The  Power forward - PF  is the second highest position in  number of employees which is 100 . Least number of employee is in the position 
       Center - C that is 79 employees, SF and  PG position have 85 and  92 number of employees respectively <br><br>

   3. Identifying the predominant age group among employees.<br>
       first of all created a new column called 'Age group' ,Then ploted histogram to identifying the predominant age group among employees.From the histogram and 
   value_counts() its clear that the age group 24-29 has highest count of enployee(229),then age group 18-24 have second highest no.of employees(107), age group 
   from 36 to 41 has least no.of employee ie,23 <br><br>

   4.Discoveed which team and position have the highest salary expenditure <br>
      Finding top 5 salary expenditure team,then ploted top 5 salary expenditure  team using bar plot.From the bar chart and calculations it is clear that Maximum 
    salary expenditure is31866445.0 for the Team Los Angeles Lakers and Position is SF.The next top 4  salary expenditure  teams are Miami Heat, Houston Rockets , 
    Phoenix Suns and Denver Nuggets respectivly. <br><br>

   5.Investigated if there's any correlation between age and salary <br><br>
    Ploting Age and Salary to find correlation using scatter plot,

   



   
   
      


   

