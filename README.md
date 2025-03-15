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

### Data Visualization
Here are some tables and dashboards from Microsoft Excel

|Region|Total Revenue|
|------|-------------|
|North|16,817,972|
|West|16,864,376|
|South|16,899,064|
|East|16,958,763|
|Grand Total|67,540,175|

|Subscription Type|Total Revenue|
|-----------------|-------------|
|Standard|16,864,376|
|Premium|16,899,064|
|Basic|33,776,735|
|Grand Total|67,540,175|

|Region|Amount of Customers|
|------|-------------------|
|West|8,420|
|North|8,433|
|South|8,446|
|East|8,488|
|Grand Total|33,787|

|Subscription Type|Amount of Customers|
|-----------------|-------------------|
|Standard|8,420|
|Premium|8,446|
|Basic|16,921|
|Grand Total|33,787|

![Customer Excel](https://github.com/user-attachments/assets/0b284ab9-e080-42c4-ae28-1b98a987af5b)

<img width="575" alt="New Customer BI" src="https://github.com/user-attachments/assets/76d774da-b980-44d1-a057-5147771e7d04" /
