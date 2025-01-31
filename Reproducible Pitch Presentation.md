Course Project - Shiny Application and Reproducible Pitch
========================================================
author: sarah
date: 25-10-2024
autosize: true

Overview
========================================================

This was built for the course: **Developing Data Products** as part of the Coursera Data Science Specialization.

The shiny app developed for this assignment is avalilable: 
https://narayanareddt12.shinyapps.io/Shiny-Application-and-Reproducible-Pitch-master/

The source codes of ui.R and server.R and also Rpresentation are available on the GitHub repo: https://github.com/narayanareddy12/Shiny-Application-and-Reproducible-Pitch-master

Exam Marks Calculation and Interpretation
========================================================
The average mark for the three exams written is calculated based on the following formula:

Average mark = (x + y + z)/3

Where:

- x = Databases Score 
- y = Data Analytics score 
- z = Project Management score 

Exam Intrepretation
========================================================

**Example:**
For a score of **80** in Database, **97** Data Analytics and **64** Project Management.

Average Score is **80,333**

- Average <70, : Failed
- Average [70-79] , : Considered for the database administrator position
- Average [80-89] , :Considered for the data administrator position
- Average >= 90 : Considered for the business intelligence manager position


Shiny App: Interactive BMI Calculator
========================================================

### Sidebar panel

- numericInput: Value of Database score
- numericInput: Value of Data Analytics score
- numericInput: Value of Project Management score

### Main panel

- Short description of Average value
- Make calculation on server side
- Display the calculated average value
- Display Intepretation
