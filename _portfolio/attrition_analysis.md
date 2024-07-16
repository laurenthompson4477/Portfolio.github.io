---
title: "Predictive Attrition Analysis"
excerpt: "The goal of this project is to identify work related variables that can be used to predict an employee’s attrition in hopes to create a healthy work environment to improve overall retention and lower the avoidable attrition rates of companies. The model used to analysis the variables leading to attrition is Tuned Random Forest. "
collection: portfolio
---

**GitHub Link:** [Predictive Attrition Analysis](https://github.com/laurenthompson4477/laurenthompson4477.github.io/tree/main/Employee_Attrition_Predictive)

**Language:** Python

**Libraires used:**<br>
&ensp;&ensp;&ensp;Pandas<br>
&ensp;&ensp;&ensp;Numpy<br>
&ensp;&ensp;&ensp;Matplotlib<br>
&ensp;&ensp;&ensp;Seaborn<br>
&ensp;&ensp;&ensp;Sklearn<br>
&ensp;&ensp;&ensp;Pickle<br>
&ensp;&ensp;&ensp;xgboost

**Project Description:**<br>
The goal of this project is to identify work related variables that can be used to predict an employee’s attrition in hopes to create a healthy work environment to improve overall retention and lower the avoidable attrition rates of companies. The model used to analysis the variables leading to attrition is Tuned Random Forest. 

**Files Needed:**<br>
&ensp;&ensp;&ensp;HR.csv<br>
&ensp;&ensp;&ensp;Predictive_Attrition_Analysis.ipynb

**How to Run:**<br>
Download the files needed, see list above, and ensure they are saved in the same directory. Open Jupyter Notebook and navigate to the directory where the files are stored. Run the notebook, no alterations to code should need to be made. 

**Summary:**<br>
The goal of this project was to identify work related variables that can be used to predict an employee’s attrition in hopes to create a healthy work environment to improve overall retention and lower the avoidable attrition rates of companies. The features identified by the Tuned Random Forest model show that project count, monthly hours, satisfaction levels, work intensity, and work life balance are the top contributers. 

The project count had some outliers which seemed to contribute to employee attrition as some employees had 7 projects at once most likely leading to burnout. Monthly hours on average for this company are 150-250 hours with some outliers reaching 350 hours. The satisfaction levels shown through a KDE plot reveal a relationship between satisfaction levels and employee attrition as higher satisfaction scores lead to retention. The satisfaction level is heavily dependent on the work intensity. Those who left the company had a higher work intensity compared to employees who stayed. Lastly is work life balance, employees who balance work and their personal life show more satisfaction which leads to higher retention rates.

These conclusions lead to the following recommendations. Monitoring and managing employee workloads and working hours to reduce burnout, especially employees with a higher project count. Those who do have higher project counts and higher working hours need to feel compensated for their efforts such as overtime payments or bonuses. Offering trainings and workshops for employees can also give them skills to improve their work habits with project workload efficiency resulting in higher satisfaction levels. 

Forbes has looked in to attrition and found that even outside of an attrition crisis, research has shown that “culture comes first” and is a predictor or leading indicator of organization performance. To further help employees meet a healthy work life balance and continue to have a good work culture flexible work hours and arrangements such as teleworking should be considered. This would allow employees to craft their own schedule within means, allowing employees the opportunity to balance life events and work. The last recommendation is to do a semi-annual check in using a survey with the same fields the predictive model used. This will allow tracking attrition and retention in the years to come and identifying what feature may need improving.

