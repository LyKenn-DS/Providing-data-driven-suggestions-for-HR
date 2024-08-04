# **Providing-data-driven-suggestions-for-HR**
Predict whether an employee will leave the company, and discover the reasons behind their departure.

## Overview 
The goals of this project were to identify factors that contributed to employees leaving and to build a model that predicts whether or not an employee will leave. This project utilized data and analytics in the space of human resources. Because each classification algorithm had its own quirks and was based on certain assumptions, several different models were built to facilitate the selection of an optimal classifier based on the computational performance as well as the predictive power. The random forest model performed with an unrealistic generalized accuracy of 98.6% and a balanced f1 score of 95.3%, which deemed to have a careful inspection in the following rounds. From the combined exploratory and mining results, many of the employees were disdained with the poor management and work culture that was practiced in the company such as disproportionate workloads, extensive working hours, as well as the lack of perceived opportunities for growth.      

## Business Understanding
Currently, there is a high rate of turnover among Salifort employees (In this context, turnover data includes both employees who choose to quit their jobs and let go). Salifort's senior leadership team is concerned about how many employees are leaving the company. With the increasing numbers of turnover, Human Resources has to undergo the tedious process of identifying, interviewing, and selecting more suitable candidates as replacements for the roles. Because the hiring process is time-consuming and costly in the financial sense, increasing employee retention will be beneficial to the company. 

## Data Understanding
The data was collected by Human Resources via a survey of a sample of employees to learn about what might be driving their turnover. It consisted of 15,000 respondents and 10 features. The features included meaningful information that gives increasing precision about the classification target such as evaluation_score, average working hours, the room for growth, and most importantly— whether an employee had left. The bar chart below shows the breakdown of the  employee tenures that exist in the data set. 
![image](https://github.com/user-attachments/assets/70a26aff-400a-4623-bb26-5ebb098fafba)

It appeared that the company had failed to retain talents for long-term tenure, and most were inclined to leave at the beginning of the 3rd tenure.  

## Modeling and Evaluation
Both logistic regression and random forest machine learning algorithms were used to construct models for the classification task. The random forest model outperformed logistic regression model, and has the advantages of reduced bias & variance. However, other factors like computational cost, latency, and complexity of implementations may also be considered depending on the production setting.    
