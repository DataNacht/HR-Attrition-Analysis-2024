# HR Attrition Analysis (2024)

# Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Transformation](#data-transformation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
  

### Project Overview
--- 

This is a People Analytics' project focus on the creation of an analitical app that can provide insights about Employee's Attrition for Human Resources, which was based on an IBM fictional data set. This project was solely created with the intention of learning and practice analytical skills. The objectives are to analyse the employeee's profile, identify possible trends and make data-driven recommendations so as to develop a crucial understanding of the staff's attrition inside the company.


### Data Sources
--- 
Employee Attrition Data: The primary dataset for this analysis is the "WA_Fn-UseC_-HR-Employee-Attrition.csv" file, containing detailed information about employees' attributes.
The data set was downloaded from this source:

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset


### Tools
--- 
Qliksense:
- Data Extract and Load
- Data Cleaning
- Data Transformation
- Data Analysis
- Data Visualization
- Storytelling

### Data Cleaning and Preparation
--- 

In the initial data preparation phase, the following task were performed:

1.Data loading and inspection

2.Data cleaning: The following columns were deleted due to a lack of utility for the analysis
- Employeecount
- Over18
- StandardHours
- JobLevel
- StockOptionsLevel

### Data transformation 
--- 

1.Renaming columns
- EmployeeNumber for EmployeeID
- BusinessTravel for TravelFrequency
- DistanceFromHome for DistanceFromHomeKM

2. Creation of new columns for grouping by:
- Etary group
- Generation
- Distance to work
- Year with current manager
- Performance rating
- Relationship with manager in years
- Job experience
- Education
- EnvironmentSatisfaction
- JobInvolvement
- JobSatisfaction
- PerformanceRating
- RelationshipSatisfaction
- WorkLifeBalance


### Data visualization and report

Here it is the final data model for the HR team users:

1. Main hub: Navigational buttons to move across pages ![1](https://github.com/user-attachments/assets/da7a8510-24d9-40fd-8f91-07bb99afa545)

2.Employees demographical data: It contains information about employees in company like etary group, generation,marital status, KPI's with total employees and job experience, but also about their academical background:
![2](https://github.com/user-attachments/assets/8491a8e1-8d51-4f25-b285-d0476555a7b0)

3.Wellness data: It shows different attributes that impacts on employees' wellness such as job and relationships satisfaction, work-life balance:
![3](https://github.com/user-attachments/assets/9be58b88-3ec1-4f0a-a876-b303543e5947)

4.Exploratory Data Analysis: This sector involves cross analysis data between attrition employees and demographics/wellness levels to adress human resources related questions:
![4](https://github.com/user-attachments/assets/ad4ec4ff-939b-4806-add1-dee8e34ce3a4)
![5](https://github.com/user-attachments/assets/c6e764bc-0149-4dc9-98ff-86fc6509904f)
![6](https://github.com/user-attachments/assets/b94d7e8b-19df-4ad3-8894-4dce7f2c8c32)



- What is the profile and demographical information of the employees leaving the company?
- What is the impact of wellness over employees in attrition?
- How the employees' work performance is related to attrition?
  

### Results and Findings
--- 


### Recommendations
--- 

