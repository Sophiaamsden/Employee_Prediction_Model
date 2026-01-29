# Employee Analysis Project

**Author:** Sophia Amsden  
**Tools:** R, R Markdown, tree, caret, gmodels, readxl  
**Data:** EmployeePerformance.xlsx, EmployeeAttrition.xlsx  

## Project Overview
This project explores two aspects of HR analytics: employee performance prediction and attrition analysis. 

1. **Employee Performance Analysis**
   - Regression tree model to predict employee performance scores based on experience, work hours, training, and communication skills.
   - Visualized tree structure and analyzed terminal nodes.
   - Made predictions for new employees.

2. **Employee Attrition Analysis**
   - Logistic regression model to predict the probability of employee attrition based on age, gender, education field, job satisfaction, and tenure.
   - Split data into 70% training and 30% testing sets.
   - Predicted attrition probability for a hypothetical new employee.

## How to Run
1. Place both Excel files in the `data/` folder.  
2. Open `notebooks/Project4_Section2.Rmd` in RStudio.  
3. Knit the R Markdown file to HTML to view results and visualizations.  

## Key Insights
- Regression tree helped identify the most important factors affecting employee performance.
- Logistic regression highlighted demographic and job-related predictors of attrition.
