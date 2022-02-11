# Indeed Web Scraper

## Background

Using an ETL process to scrap Indeed job listing information and analyzing and visualizing word frequencies to optimize resume performance.

## Objective

## Part 1:
### Extract, Transform, and Load

* 4 Functions, including:
  * First extract & transform functions to grab url for each job listing
  * Second extract_expand & transform_expand function to grab the job title, company, job description, website, and date scraped saving information into a dicitonary.
  ![data1](Images/1.PNG)
  ![data1](Images/2.PNG)
  
 * For loop, including:
   * Runs all the above functions to webscrape and save information into a CSV for later use
   ![data1](Images/3.PNG)

## Part 2:
### Data Analysis

* Create an overview table of CSV, including:
  * Company
  * Job Description
  * Website
  * Date Scraped
  ![data1](Images/4.PNG)

### Top Performing Schools (By % Overall Passing)

* Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

![data1](Images/data3.PNG)

### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.
![data1](Images/data4.PNG)

### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
![data1](Images/data5.PNG)

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).
