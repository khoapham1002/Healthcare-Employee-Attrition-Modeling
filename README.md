YOU CAN CHECK OUT MY [PROJECT NOTEBOOKS](https://github.com/khoapham1002/Healthcare-Employee-Attrition-Modeling/blob/main/notebooks/Employee%20Attrition%20with%20Logistic%20Regression.ipynb) FIRST!

## Employee Attrition Prediction – McCurr Healthcare Consultancy
### Tools & Technologies:
Python, Pandas, Scikit-Learn, Decision Tree, Logistic Regression, Matplotlib, Seaborn

### Project Overview:
Developed predictive models to identify employees at risk of attrition for McCurr Healthcare Consultancy, aiming to optimize retention strategies and reduce costs associated with turnover.

### Key Contributions:
#### Exploratory Data Analysis (EDA):
* Identified 16% attrition rate, with Sales and HR roles experiencing the highest turnover.
* Found key attrition drivers: overtime, frequent business travel, low salary, and lack of promotions.

#### Model Development:
* Classification Tree (Decision Tree):
    * Trained a Decision Tree model to classify employees as likely to attrite or stay.
    * Achieved 89% test accuracy, with overtime and monthly income as top predictors.
* Logistic Regression:
    * Applied feature scaling and one-hot encoding for categorical data.
    * Achieved 88% test accuracy, with business travel, job level, and salary growth identified as significant factors.
    * Optimized threshold for higher recall (58%), reducing false negatives.

#### Feature Importance & Insights:
* Employees with frequent business travel and overtime had higher attrition risk.
* Higher salaries, strong job satisfaction, and career growth opportunities reduced attrition likelihood.
* Employees in early-career stages (lower job levels) showed higher attrition rates.

### Impact & Insights:
* Suggested reducing overtime dependency, improving work-life balance, and offering retention incentives for at-risk employees.
* Identified promotion delay and salary growth trends as key areas for HR intervention.