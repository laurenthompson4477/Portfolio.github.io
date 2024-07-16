---
title: "Predictive Health Insurance Cost"
excerpt: "Health insurance is a contract that requires your health insurer to pay some, or all of your health care costs in exchange for a premium. The insurance company asks the individual for personal information such as location, gender, health habits, etc. to gain information to determine what plan is available for purchase. For this project the dataset includes the age, sex, BMI, number of children, smoker, region, and charges for individuals who have health insurance. The objective of this project is to see what variables are most likely to influence the charges. The charges variable is the target. A linear regression model will be used to predict the medical charges based on the features age, sex, BMI. children, smoker, and region."
collection: portfolio
---

GitHub Link: [Predictive Health Insurance Cost](https://github.com/laurenthompson4477/laurenthompson4477.github.io/tree/main/Health_Insurance_Predictive)

Language: Python

Libraires used: <br>
	&ensp;&ensp;&ensp;Pandas
	&ensp;&ensp;&ensp;Numpy
	&ensp;&ensp;&ensp;Matplotlib
	&ensp;&ensp;&ensp;Seaborn
	&ensp;&ensp;&ensp;sklearn
 
Project Description: <br>
Health insurance is a contract that requires your health insurer to pay some, or all of your health care costs in exchange for a premium. The insurance company asks the individual for personal information such as location, gender, health habits, etc. to gain information to determine what plan is available for purchase. For this project the dataset includes the age, sex, BMI, number of children, smoker, region, and charges for individuals who have health insurance. The objective of this project is to see what variables are most likely to influence the charges. The charges variable is the target. A linear regression model will be used to predict the medical charges based on the features age, sex, BMI. children, smoker, and region.

Files Needed:<br>
	&ensp;&ensp;&ensp;Predictive_Health_Insurance_Cost.ipynb
	&ensp;&ensp;&ensp;Insurance.csv


How to Run:<br>
Download the files needed, see list above, and ensure they are saved in the same directory. Open Jupyter Notebook and navigate to the directory where the files are stored. Run the notebook, no alterations to code should need to be made.

Summary: <br>
The Ridge coefficients are similar to the linear regression mode with slight differences due to regularization. The lasso coefficients show greater difference in smoker_yes, sex_male, region_northwest, region_southeast, and region_southwest all reduced to zero showing these variables have little to no impact on the model.
Both the Ridge and Lasso models show similar performance to the linear regression model with slight differences in coefficients. The Lasso model highlights the variables the influence the target variable of medical charges.
This model does a good job at modeling the costs however there is always room for improvement. I would like to explore this model using more variables such as race and health habits. This is a gray area however do to encroaching ethical violations as it is personal and sensitive information. This data would need to be obtained with consent from the patient which is usually granted or declined at the time of treatment by the medical center.

