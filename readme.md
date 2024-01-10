This is a creative dashboard made with the help of Power Bi from the hospital data that contains two major sets of data named Inpatient and Outpatient and apart from these two we also have another section of data called day case.

We created a dashboard that helps to find out the rate of patients in the defined categories (Inpatient, Outpatient, Day case) and the availability of the specialization type.

Inpatient - patient who are admitted into the hospital with any kind of illness or injury.

Outpatient- patients who attend the hospital for a clinical checkup rather than getting admitted into the hospital.

Day case- cases where patients are treated with in the same day and are discharged within the same day.

Speciality_Name: we have a lot of departments of hospital that deals with wide kind of illness with regards to various organs of the body, such as ortho - for bones, dermatology - for skin, etc...


Steps:
Requirement gathering
data collection
transformation and modelling 
data viz blueprint
dashboard layout and design
interactivity and navigation
testing
sharing
maintenance and refresh


1. Requirement gathering
> identifying stakeholders
> understand business objectives
>high level data study
>define scope
 
** Overall objective
Project Goals
1. Track status of patient waiting list
2. Analyse historical monthly trend of waiting list in Inpatient and outpatient categories
3. Detailed specialty level and age profile analysis

Data Scope
2018-2021

Metrics Required
1. Average and Median waiting list
2. Current Total wait list

Views Required
1. Summary page
2. Detailed page for granular analysis.

we have 200+ connectors in power bi for data.
What we use 
Folder data connector


DATA COLLECTION
input data into powerbi
click on Get Data-> All->Folder
you get an option to browse 
now we need to load them individually the Inpatient data once and the outpatient data once.

TRANSFORM AND LOAD

we have an option called Transform data (available in home section with an pencil icon)


to get the number of rows that have been loaded with the data set can be found in the transform section we find a count rows option

after some transform (if needed) we club both the outpatient and inpatient data

** always remember when we append two data sets we need have similar number of columns (in terms of numbers) in both the datasets. if now change accordingly.
in our data case we added a column called case_type to the outpatient dataset and in the outpatient dataset we also changed a column name to speciality_name that was previously to be found as speciality. we do this in order to avoid the errors while combining the datasets


combining two datasets

Home->(right top corner)-> append queried-> append queries as new-> select the first and second tables from the dropdown list
after combining the tables we just rename it . that is found in the left corner.

in the top left corner click -> close and apply..

Modelling the data
on the left vertical bar click on the model view

DATA VIZ BLUEPRINT
drawing out rough sketches to viz the data that could help in easily building the dashboard with clear idea from start.

creative workflow:

1. Draw inspiration
a. search google images
b. adobe stock images

2. Extract colours
a. adobe colors

3. take a report screenshot 

4. paste in a PowerPoint




To find the detailed explanation of creating this end to end professional dashboard kindly refer to this link -> link from the channel of Pivotalstats
