# HR Attrition Analysis (2024)

### Project Overview

This is a People Analytics' project focus on providing insights about Employee's Attrition on an IBM fictional data set. This project is uniquely created with the intention of learning and to develop analytical skills, thus the objectives are to analyse the employeee's profile, identify possible trends and make data-driven recommendations with the intention of develop a crucial understanding of the staff's attrition inside the company.


### Data sources
Employee Attrition Data: The primary dataset for this analysis is the "WA_Fn-UseC_-HR-Employee-Attrition.csv" file, containing detailed information about employees' attributes.
The data set was downloaded from this source:

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset



### Tools
- Qliksense -Data Cleaning, Data modelling, Data Analysis, Data Visualization and Storytelling-

### Data Cleaning/Preparation

In the initial data preparation phase, the following task were performed:

1.Data loading and inspection

2.Data cleaning: The following columns were deleted due to a lack of utility for the analysis
- Employeecount
- Over18
- StandardHours
- JobLevel
- StockOptionsLevel

### Data transformation: 
1.Renaming columns
- EmployeeNumber for EmployeeID
- BusinessTravel for TravelFrequency
- DistanceFromHome for DistanceFromHomeKM

2.Creating columns: 
- Age group
- Generation
- Distance
- Year with current manager

