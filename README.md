# Employee Statisfaction & Attrition Correlation
This project utilized people analytics to identify drivers of employee attrition, uncovering insights to improve retention. The dashboard aims to help the HR department and the management understand the human side of the organization and make data-driven decisions for sustainable growth.
The organization was facing unacceptably high attrition rates across functions. The goal was to identify factors correlated with turnover to guide strategies for enhancing workforce stability.

## Data Overview
The dataset contains 1470 rows and 35 columns, with information such as: 
- Demographics: age, gender, education, marital status  
- Job profile: role, department, experience
- Workspace: location, commute distance
- Performance: ratings, salary, overtime 
- Satisfaction: work-life balance, relationship, environment

## Data Cleaning
The data cleaning process involved the following steps:
- Removing redundant columns, such as EmployeeCount, EmployeeNumber, Over18, and StandardHours, that had no variation or relevance for the analysis.
- Renaming the columns to make them more consistent and descriptive.
- Dropping duplicates, if any.
- Cleaning individual columns, such as replacing missing values, correcting data types, and formatting values.
- Removing the NaN values from the dataset.
- Checking for some more transformations, such as creating new variables, binning categories, or encoding labels.

## Features
The dashboard offers the following features:
- *Active Employees*: A snapshot of the current team size.
- *Average Age*: Insights into the generational diversity of the workforce.
- *Attrition Count*: A closer look at the number of employees leaving the company.
- *Attrition Rate*: The percentage of employees leaving the company over time.
- *Employee Count*: The trend of the team size over time.
- *Attrition by Gender*: The breakdown of attrition by gender.
- *Department-wise Attrition*: The distribution of attrition by the department.
- *Job Satisfaction Ratings*: The average ratings of job satisfaction by department and gender.
- *Education Field-wise Attrition*: The correlation between education field and attrition.
- *Attrition Rate by Gender*: The comparison of attrition rate by gender.
- *Correlation Map*: A heatmap of the correlation between all numeric variables.
- *Overtime*: The impact of overtime on attrition and job satisfaction.
- *Marital Status*: The relationship between marital status and attrition.
- *Job Role*: The variation of attrition and job satisfaction by job role.
- *Gender*: The difference between attrition and job satisfaction by gender.
- *Education Field*: The influence of the education field on attrition and job satisfaction.
- *Department*: The contrast of attrition and job satisfaction by department.
- *Business Travel*: The effect of business travel on attrition and job satisfaction.
- *Total Working Years*: The association between total working years and attrition and job satisfaction.
- *Education Level*: The link between education level and attrition and job satisfaction.
- *Number of Companies Worked*: The connection between the number of companies worked and attrition and job satisfaction.
- *Distance from Home*: The relation between distance from home and attrition and job satisfaction.

## Analysis Approach
1. **Data Exploration**: Calculated attrition rates and trends in Power BI, identified patterns through visualizations
2. **Statistical Analysis**: Correlation analysis, ANOVA, regression modelling in Power BI 
3. **Segmentation**: Broke down attrition by department, job role, demographics, satisfaction levels 
4. **Hypothesis Testing**: Formulated and tested hypotheses on drivers of attrition

## Dashboard Chapters
The interactive Power BI dashboard was created with drill-down capability. It was organized into three key chapters:-
- **Employee Demographics**: *Analyzed attrition by factors like age, marital status, and distance from home*
  
   ![demographics](https://github.com/kalra-muskan/employee-attrition/assets/142618498/878a7479-1f26-4a1c-a04c-8aa93ad302ec)
  
- **Employee Wellness**: *Explored satisfaction, performance, and work-life balance with attrition*
  
  ![wellness](https://github.com/kalra-muskan/employee-attrition/assets/142618498/3eb1e949-685e-43fe-96f3-1e3640b82d16)
  
- **Employee Turnover**: *Identified differences in turnover across roles, departments, and other factors*
  
   ![turnover](https://github.com/kalra-muskan/employee-attrition/assets/142618498/79cfb96d-4964-4d8e-9fa2-d493c38b0555)
 

The dashboard can be downloaded and viewed as a Power BI file (`hr_dashboard.pbix`).
      
## Recommendations
- Improve satisfaction via flexible policies, career growth  
- Enable remote work for eligible roles
- Train managers in high-attrition divisions on retention  
- Revise overtime policy to promote work-life balance

