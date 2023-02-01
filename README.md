# Insight from Data Professionals Survey Data using Power-BI

### Objective:
The aim of this project is to analyse the survey data submitted by Data Professionals across different countries and to gain meaningful insights.

Key Questions:
1. Average Salary of Data Professional by Job Title across different different
2. Average Salary by Gender across different countries
3. Most popular programming language preferred by most Data professionals
4. Happiness with Work/Life balance across gender across countries
5. Happiness with Salary across gender across countries

### About Data:
The data used for the analysis is real-time survey data by Data Professionals across different countries. Around 630 records of data is used for the analysis. The Survey data contains information such as: 
 1. Which Title Best Fits your Current Role? <br/>
 2. Did you switch careers into Data? <br/>
 3. Current Yearly Salary (in USD) <br/>
 4. What Industry do you work in? <br/>
 5. Favorite Programming Language <br/>
 6. How Happy are you in your Current Position with the following? <br/>
     i. Salary <br/>
     ii. Work/Life Balance <br/>
     iii.Coworkers <br/>
     iv.Management <br/>
     v. Upward Mobility <br/>
     vi. Learning New Things <br/>
7. How difficult was it for you to break into Data? <br/>
8. If you were to look for a new job today, what would be the most important thing to you? <br/>
9. Gender <br/>
10. Current Age <br/>
11. Which Country do you live in? <br/>
12. Highest Level of Education <br/>
13. Ethnicity <br/>

### Data Import:
The data was stored in excel workbook and was imported into Power BI Desktop using Get Data from Excel Workbook option. 

### Data View:
Before loading the data, the following transformations were applied to the data:
1. Empty columns were removed using "Remove columns" option
2. Salary was provided as a range. For ex: 40k-60k. Split the salary column using "digit to non-digit" option to get the starting and ending salary range. 
Created a new column named "Average Salary" by adding the minimum and maximum salary / 2 
3. For better analysis, grouped countries apart from United States, India, Canada, United Kingdom into Others Category since there were very few surveys from countries in the other category.
4. Grouped Favourite Programming languages values as duplicates existed For ex: SQL, sql, PL/SQL, " I mostly use SQL", etc were grouped together as SQL
5. Grouped all Job titles that were specified under Others category 

Replace Values, Add Custom columns, Split column, Conditional column, Group by, Remove columns, String functions such as UPPERCASE, TRIM, ect were some of the Data cleaning and transformation steps applied to the data.

### Report View:
Built the following visualization in the Report Canvas: 
![image](https://user-images.githubusercontent.com/123318961/215926543-7a8114af-78fe-4a1b-8ce3-b4faf88683df.png)

### Publish Report:
The report was published to My Workspace in Power BI Service. <br/>
URL: https://app.powerbi.com/links/q6SPNrOYCP?ctid=88d59d7d-aecb-41b2-90c5-55595de02536&pbi_source=linkShare

### Insights:
Below are the key insights from the report:
1. Python is the most preferred programming language by data professionals as it received 66.67% votes followed by R (16.03%), and SQL (7.78%)
2. Data Scientist received the highest average salary following by Data Analyst, Data Engineer, and Data Architects.
3. Happiness with Salary were pretty low among Data professionals. The average happiness with salary was higher for data professionals in the United States over other countries. Data professional in India were least happy with their salary.
4. Happiness with Work/Life balance was highest in United States followed by Canada and United Kingdom. Again India showed least happiness with work/life balance.
5. Male vs Female salary was almost equal in all countries except India. Average Salary of Male professionals very significantly higher than female professionals in India.

**Country Specific Report:**

India:

![image](https://user-images.githubusercontent.com/123318961/215930170-2b3ef217-8903-4d8b-a088-e2d1d2099946.png)

United States:

![image](https://user-images.githubusercontent.com/123318961/215931071-a19b464f-26b7-4884-98b4-e11724eb7fbd.png)

United Kingdom:

![image](https://user-images.githubusercontent.com/123318961/215931164-03af0864-2277-43ca-ad75-ac2889808c2b.png)

Canada:

![image](https://user-images.githubusercontent.com/123318961/215931239-095dce24-1aa3-49e7-8ef0-e83d6e756059.png)

Others:

![image](https://user-images.githubusercontent.com/123318961/215931320-c32742fa-f72f-4d01-9f21-7703cfb1482a.png)


### Reference:
https://www.youtube.com/watch?v=pixlHHe_lNQ
