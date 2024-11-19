# Why Employees Quit
Eyeing on the data of employee turnover that is preventable but often ignored.

## Overview 
The goals of this project were to identify factors that contributed to employees leaving and to build a model that predicts whether or not an employee will leave. This project utilized data and analytics in the space of human resources. Because each classification algorithm had its own quirks and was based on certain assumptions, several different models were built to facilitate the selection of an optimal classifier based on the computational performance as well as the predictive power. The random forest model performed sufficiently well with a generalized accuracy of 97.5% and a balanced f1 score of 91.4% (all weighted averages) after tweaking the model for a few rounds. From the combined exploratory and mining results, many of the employees were disdained with the poor management and work culture that was practiced in the company such as disproportionate workloads, extensive working hours, as well as the lack of perceived opportunities for growth.      

## Business Understanding
Currently, there is a high rate of turnover among Salifort employees (In this context, turnover data includes both employees who choose to quit their jobs and let go). Salifort's senior leadership team is concerned about how many employees are leaving the company. With the increasing numbers of turnover, Human Resources has to undergo the tedious process of identifying, interviewing, and selecting more suitable candidates as replacements for the roles. Because the hiring process is time-consuming and costly in the financial sense, increasing employee retention will be beneficial to the company. To help with this, the leadership team suggests designing a model that predicts whether an employee will leave the company based on the attributes, as well as discovering the reasons behind their departure to better understand the problem and develop a solution.    

## Data Understanding
The data was collected by Human Resources via a survey of a sample of employees to learn about what might be driving their turnover. It consisted of 15,000 respondents and 10 features. The features included meaningful information that gives increasing precision about the classification target such as evaluation_score, average working hours, the room for growth, and most importantly— whether an employee had left. The bar chart below shows the breakdown of the  employee tenures that exist in the data set. 

![image](https://github.com/user-attachments/assets/70a26aff-400a-4623-bb26-5ebb098fafba)

It appeared that the company had failed to retain talents for long-term tenure, where most of the employees were inclined to leave after their 2nd tenure.  

## Modeling and Evaluation
Both logistic regression and random forest machine learning algorithms were used to construct models for the classification task. The random forest model outperformed logistic regression model, and has the advantages of reduced bias & variance. However, other factors like computational cost, latency, and complexity of implementations might also be considered depending on the production settings. When weighing against all the meaningful variables provided in the dataset, the no of projects, rate of overtime work above standard working hours, and tenure showed the most significant effect on an employee's decision to leave. By no means, these 3 factors are a mere coincidence and the management should look more closely into the company's work culture to mitigate the issue.       

![image](https://github.com/user-attachments/assets/a3fd7640-bec7-4d1e-98a8-2bedd22dac72)

Combined with the exploratory results, it rendered a more holistic view of the subject as well as how the most influential factors may interact. So stakeholders could tailor an effective solution based on the insights. 

## Conclusion
This model can be inherently valuable to help the company increase retention and job satisfaction for current employees, and save money and time training new employees. However, it can be skeptical for all with such overwhelming evaluation scores from a model. There is a chance that some data leakage was occurring during the development process and it will be prudent to incorporate feature engineering to build improved models in the next round.     
