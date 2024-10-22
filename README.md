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

2.Data formatting: Data types above were converted from number to text to improve data description for analysis

- Education
1 'Below College'
2 'College'
3 'Bachelor'
4 'Master'
5 'Doctor'

- EnvironmentSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

- JobInvolvement
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

- JobSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

- PerformanceRating
1 'Low'
2 'Good'
3 'Excellent'
4 'Outstanding'

- RelationshipSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

- WorkLifeBalance
1 'Bad'
2 'Good'
3 'Better'
4 'Best'

3. Create new columns:
- Etary group
- Generation
- Distance to work
- Year with current manager
- Performance rating
- Relationship with manager in years
- Job experience

### Exploratory Data Analysis

EDA involved exploring the company's attrition to adress key questions, such as:

- What is the profile and demographical information of the employees leaving the company?
- What is the impact of wellness over employees in attrition?
- How the employees' work performance is related to attrition?
  

### Data analysis


