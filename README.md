# Malaria-Data-Analysis 
This shows one of the group projects I worked on during my externship with LearnwithWIDA

[Project Title](project-title)

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

### Project Title: Malaria Data Analysis

### Project Overview
The aim of this project is To analyze malaria trends, costs, mortality, and hospital utilization for 100 patients from February 2024 to February 2025 in Nigeria.
### Data Sources
The data used was obtained from ChatGPT by prompting it to provide messy data with some specific columns.

### Tools Used
- Microsoft Excel- Data Cleaning, Analysis and Visualization
- GitHub- Documentation and Portfolio Building

### Data Cleaning and Preparations
The following actions were performed before the data was worked on for analysis and visualization:
1. Data loading and inspection
2. Standardization of data types

### Exploratory Data Analysis
The data was explored to answer questions like:
- the average age.
- the age with the most hospital admissions.
- the average length of stay.
- the average treatment cost per patient.
- the average drug cost per patient.
- the mortality rate.
- the top 3 cities with the most hospitals.
- the top 3 states with highest treatment costs.

### Data Analysis
Listed below are some formulas I used in answering the questions:

- =AVERAGE(Table1[Age])
- =MODE(Table1[[#All],[Age]])
- =SUM(Table1[Duration (Days)])/100
- =SUM('Cleaned Patient Data'!M2:M101)/100
- =SUM(Table1[[Drug Cost ]])/100
- =COUNTIF(Table1[Mortality],'Cleaned Patient Data'!L83)/100

### Data Visualization
Here are some tables and dashboards from Microsoft Excel

|States|Amount of Hospitals|
|------|-------------------|
|Borno|43|
|Sokoto|41|
|Lagos|40|
|Kano||40|
|Enugu|37|
|Edo|36|
|Delta|35|
|Rivers|35|
|Kaduna|33|
|Oyo|30|
|Grand Total|370|


![Dashboard](https://github.com/user-attachments/assets/3e28a676-d806-422b-be5b-08485aff0b2b)

