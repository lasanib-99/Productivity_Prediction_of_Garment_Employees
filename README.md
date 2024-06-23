# Productivity Prediction of Garment Employees
A regression analysis project to predict the productivity of garment employees using multiple linear regression models.

## Objective
This project aims to predict the productivity of garment employees using regression analysis techniques. 

## Dataset Information
The dataset used is publicly available on Kaggle and includes important attributes of the garment manufacturing process and the productivity of the employees. 

### Predictor Variables:
- `day`: Day of the Week
- `quarter`: A portion of the month, divided into four quarters
- `department`: Associated department with the instance
- `no_of_workers`: Number of workers in each team
- `no_of_style_change`: Number of changes in the style of a particular product
- `smv`: Standard Minute Value, allocated time for a task
- `wip`: Work in progress, includes the number of unfinished items
- `over_time`: Amount of overtime by each team in minutes
- `incentive`: Amount of financial incentive in BDT
- `idle_time`: Amount of time when production was interrupted
- `idle_men`: Number of workers idle due to production interruption

### Response Variable:
- `actual_productivity`: The actual percentage of productivity delivered by the workers, ranging from 0 to 1.

## Methodology
The analysis includes:
- Descriptive statistics of the dataset.
- Multiple linear regression models, including forward selection, backward elimination, and stepwise selection, to identify significant predictors of productivity.

## Key Findings
- Significant predictors of productivity are recognized.
- Understanding these factors can help improve efficiency and productivity in the garment industry.
