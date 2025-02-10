# Proactive Employee Turnover Prediction: A Data-Driven Approach
Eyeing on the data of employee turnover that is preventable but often ignored - [Python EDA & ML](End-to-end_Machine-Learning-Project.ipynb).

**Techniques applied:** `Data Cleaning`  `Exploratory Data Analysis` `Data Visualization` 
`Feature Engineering` `Scikit-learn Classification Algorithms` `Scikit-learn Pipeline`
`Fine Tuning & Evaluation of Models`

## Overview 
This research project investigates the root causes of employee turnover by leveraging data analytics and machine learning, offering a proactive alternative to traditional, reactive methods like exit interviews.  While exit interviews provide some insights, they often fall short by addressing the issue after an employee has decided to leave, missing crucial opportunities for intervention.  This project aims to shift the focus to proactive prediction, empowering organizations to identify at-risk employees and implement targeted retention strategies before they resign, ultimately mitigating the significant costs associated with employee replacement.

The core of this research lies in developing a predictive model using supervised machine learning techniques.  Specifically, algorithms like Logistic Regression, Decision Tree, and Random Forest will be employed to learn complex patterns from a rich dataset of employee information.         

## Data 
![image](https://github.com/user-attachments/assets/d2dea926-ede1-4cc9-8782-69168ad1d47c) 

It appears in the trend that the company had failed to retain talents for long-term tenure, and many were inclined to leave soon after their 3rd tenure.

Exploration and analysis of the data show 3 distinct groups who left the company:
1. **Highly dissatisfied employees with high evaluation scores:** These employees have low satisfaction levels, high monthly hours, and no promotions.
2. **Dissatisfied employees with low evaluation scores:** These employees have high satisfaction levels, low monthly hours, and no promotions.
3. **Satisfied employees with high evaluation scores:** These employees have high satisfaction levels but high monthly hours and still leave the company.

Often, top talents in the first group can be retained with effective short-term reward strategies that offer both monetary and non-monetary recognition.  These strategies should be tailored to the specific company culture and individual employee needs. For example, profit-sharing programs and bonuses can provide direct financial incentives tied to company performance, aligning employee goals with organizational success.  Flexible work arrangements, including remote work options, can significantly improve work-life balance, a key factor for many top performers. 

By combining these strategies, companies can tap into employees' intrinsic motivations, fostering a sense of appreciation, belonging, and ultimately, encouraging them to stay.  

## Model
To better classify and predict whether an employee will leave the company, a range of sophisticated models was investigated to establish a baseline performance metric. 
Through an iterative process of feature engineering and parameter tuning, the influence of various feature variables and model parameters was carefully examined.  Notably, the Random Forest model significantly outperformed Logistic Regression, achieving a generalized accuracy of 97.5% and a balanced F1-score of 91.4%.  This superior performance is further supported by the Random Forest's inherent advantages in reducing both bias and variance.  These results suggest a strong potential for the Random Forest model in accurately predicting employee turnover. <br>       

![image](https://github.com/user-attachments/assets/8439a866-0d6e-4c89-8dc2-12c881668cd3)

The best-performing model, which considered all available predictor variables, identified the number of projects, overtime rate, and tenure as the most significant factors influencing an employee's decision to leave.  These findings suggest a potential connection to inadequate ownership and a lack of genuine fulfillment in work.  For example, the high overtime rate, perceived productivity problems, and disproportionate workload (reflected in the number of projects) may contribute to employee dissatisfaction.
