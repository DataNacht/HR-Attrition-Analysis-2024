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

This is a People Analytics' project focus on providing insights about Employee's Attrition on an IBM fictional data set. This project is uniquely created with the intention of learning and practice analytical skills. The objectives are to analyse the employeee's profile, identify possible trends and make data-driven recommendations so as to develop a crucial understanding of the staff's attrition inside the company.


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

### Exploratory Data Analysis
--- 
![1](https://github.com/user-attachments/assets/da7a8510-24d9-40fd-8f91-07bb99afa545)

EDA involved exploring the company's attrition to adress key questions, such as:

- What is the profile and demographical information of the employees leaving the company?
- What is the impact of wellness over employees in attrition?
- How the employees' work performance is related to attrition?
  

### Results and Findings
--- 


### Recommendations
--- 

