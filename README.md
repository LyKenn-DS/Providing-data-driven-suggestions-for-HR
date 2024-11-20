# Why Employees Quit
Eyeing on the data of employee turnover that is preventable but often ignored - [Python EDA & ML](End-to-end_Machine-Learning-Project.ipynb).

## Overview 
This research project attempts to identify the reasons for employee turnover using data and analytics in the space of human resources. Usually this kind of study is conducted following a voluntary employee turnover as practiced by many Human Resources representatives—for example, through programs of exit interviews only in a dire attempt to hold down valuable or mass termination. While it may be practical in some, the exit interview approach often fails to account for the employees' emotions and well-being during their work, which can potentially leave the manager with lost opportunities to intervene, that is, after the employees have made up their minds to leave. By proactively managing the issue upfront, we're more likely to gain control of the matter in our hands and mitigate costly replacements in the future, along with boosting team engagement.        
  
## Data Understanding
The data was collected by Salifort's Human Resources via a survey of a sample of employees to learn about what might be driving their turnover. It consisted of 15,000 respondents and 10 features. The features included meaningful information that gives increasing precision about the classification target such as evaluation_score, average working hours, the room for growth, and most importantly— whether an employee had left. The bar chart below shows the breakdown of the  employee tenures that exist in the data set. 

![image](https://github.com/user-attachments/assets/70a26aff-400a-4623-bb26-5ebb098fafba)

It appeared that the company failed to retain talents for long-term tenure, and most of the employees were inclined to leave after their 2nd tenure.  

## Modeling and Evaluation
Both logistic regression and random forest machine learning algorithms were used to construct models for the classification task. The random forest model outperformed logistic regression model, and has the advantages of reduced bias & variance. However, other factors like computational cost, latency, and complexity of implementations might also be considered depending on the production settings. When weighing against all the meaningful variables provided in the dataset, the no of projects, rate of overtime work above standard working hours, and tenure showed the most significant effect on an employee's decision to leave. By no means, these 3 factors are a mere coincidence and the management should look more closely into the company's work culture to mitigate the issue.       

![image](https://github.com/user-attachments/assets/a3fd7640-bec7-4d1e-98a8-2bedd22dac72)

Combined with the exploratory results, it rendered a more holistic view of the subject as well as how the most influential factors may interact. So stakeholders could tailor an effective solution based on the insights. 

## Conclusion
This model can be inherently valuable to help the company increase retention and job satisfaction for current employees, and save money and time training new employees. However, it can be skeptical for all with such overwhelming evaluation scores from a model. There is a chance that some data leakage was occurring during the development process and it will be prudent to incorporate feature engineering to build improved models in the next round.     
