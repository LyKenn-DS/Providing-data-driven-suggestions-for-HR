# Why Employees Quit
Eyeing on the data of employee turnover that is preventable but often ignored - [Python EDA & ML](End-to-end_Machine-Learning-Project.ipynb).

## Overview 
This research project attempts to identify the reasons for employee turnover using data and analytics in the space of human resources. Usually this kind of study is conducted following a voluntary employee turnover as practiced by many Human Resources representatives—for example, through programs of exit interviews in a dire attempt to hold valuable or mass termination down. While it may be practical in some, the exit interview approach often fails to account for the employees' emotions and well-being during their work, which can potentially leave the manager with lost opportunities to intervene, that is, after the employees have made up their minds to leave.<br> 

By proactively managing the issue upfront, we'll gain more control of the matter in our hands and mitigate the need for costly replacements. In this project, the supervised machine learning techniques typically logistic regression, decision tree, and random forest were used to learn complex patterns from the available data and create a reliable model that is useful for making predictions on the binary classification task in the future.         
  
## Data Understanding
The data was collected by Salifort's Human Resources via a survey of a sample of employees, consisting of 10 features and 15,000 responses. The features included are meaningful information that gives increasing precision about the classification target such as evaluation_score, workload/scheduling, career advancement, job satisfaction, and the most recent employment status in Salifort— whether an employee had left. The bar chart below shows the breakdown of the  employee tenures that exist in the data set. 

![image](https://github.com/user-attachments/assets/d2dea926-ede1-4cc9-8782-69168ad1d47c)

From the trend, it appeared that the company failed to retain talents for long-term tenure, and many were inclined to leave after their 3rd tenure.  

## Modeling and Evaluation
Both logistic regression and random forest machine learning algorithms were used to construct models for the classification task. Notably, the random forest model outperformed the logistic regression model, and has the advantages of reduced bias & variance. However, other factors like computational cost, latency, and complexity of implementations might also be considered depending on the production settings. When weighing against all the meaningful variables provided in the dataset, the no of projects, rate of overtime work above standard working hours, and tenure showed the most significant effect on an employee's decision to leave. By no means, these 3 factors are a mere coincidence and the management should look more closely into the company's work culture to mitigate the issue.       

![image](https://github.com/user-attachments/assets/a3fd7640-bec7-4d1e-98a8-2bedd22dac72)

Combined with the exploratory results, it rendered a more holistic view of the subject as well as how the most influential factors may interact. So stakeholders could tailor an effective solution based on the insights. 

## Conclusion
This model can be inherently valuable to help the company increase retention and job satisfaction for current employees, and save money and time training new employees. However, it can be skeptical for all with such overwhelming evaluation scores from a model. There is a chance that some data leakage was occurring during the development process and it will be prudent to incorporate feature engineering to build improved models in the next round.     
