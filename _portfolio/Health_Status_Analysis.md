---
title: "Health Status Analysis"
excerpt: "This project came about due to the increase of illness in the United states. Outbreaks of new viruses such as COVID-19 will never be predictable but common diseases that have an established history do have some predictability. This project’s goal is to explore the health status of the countries. This project will investigate the health status of countries in attempts to identify an individual’s likelihood of various health outcomes based on location, age, and gender. This study could be used to apply to statistics to an individual or a country at whole to help identify where more preventative care is needed."
collection: portfolio
---


Project Title: [Health Status Analysis](https://github.com/laurenthompson4477/laurenthompson4477.github.io/blob/main/Health_Status/Health_Status_Analysis.Rmd)

Language: R

Libraries Used: <br>
&ensp;ggplot2 <br>
&ensp;dplyr

Project Description: <br>
This project came about due to the increase of illness in the United states. Outbreaks of new viruses such as COVID-19 will never be predictable but common diseases that have an established history do have some predictability. This project’s goal is to explore the health status of the countries. This project will investigate the health status of countries in attempts to identify an individual’s likelihood of various health outcomes based on location, age, and gender. This study could be used to apply to statistics to an individual or a country at whole to help identify where more preventative care is needed.

What files are needed:<br>
	&ensp;HEALTH_STAT_29102023123216517.csv<br>
	&ensp;Health_Status_Analysis.Rmd

How to install and Run the Project:<br>
Download the files needed, see list above, and ensure they are saved in the same directory. Open RStudio and navigate to the directory where the files are stored to open the .Rmd file. Load the data into the environment. The only alternation to the code is the file path while the data is stored. To alter this open folder explorer locate the directory the .csv file is save and copy the filepath

Summary:<br>
When first analyzing the data, the plan was to create subsets using the dplyr package to prep the data and create subsets of each country. After the separation a general data analysis is performed through a bar graph for each country. With the number of variables under each country this bar graph would not be readable so the data will need to be grouped by the common factor. For example, the data identifies at least 20 diseases. This disease can be grouped by the area they affect such as respiratory disease, heart disease, cancer, etc. This limits the level of data but will make the finding more readable. An analysis of the groupings could be done with the top contender. If cancer is the leading cause of mortality a subset of just cancer related deaths can be made and analyzed with the deeper level of specific types of cancer.

Machine learning would be extremely beneficial here, being about to formulate a model of predictive outcomes is what this project is about so designing a model that takes in the data set, identifies patterns, and produces a likely outcome of a health status for a country would be ideal for this project. To do so the current data set would be used to train the neural network. I would first start to train the model to produce likely mortality causes. I would like to try and use one model to predict both the counties health status as well as an individual’s health status however do to the complexity of humans (moving to other countries, family medical history, etc.) I think a separate model is appropriate.

When it comes to health status nothing is a 100% guarantee, this project looks at a health status of countries and identifies leading causes of mortality. This could be useful to research within the health field, support to funding preventive measure, and as a tool to educate individuals on health risks tailored to them.

A resource common amongst all research projects are time and manpower. Using data to identify areas of improvement is fascinating but with the size of the dataset and how new I am to data science and analysis I found that I would need more time and a mentor to fully execute all the models with this dataset. 
The biggest limitation I have found within the dataset is the size of the data and the codes/labels provided. From the source the dataset was retrieved the data was formatted very nicely in a GUI. The data when exported to a csv file still held everything shown from the original course, however, the labels of the variables became abbreviated codes, such as "EVIEFE00" which represents females’ life expectancy at birth. For the female life expectancy at 40yrs old the code is "EVIEFE40". There are many diseases and mortality rate this dataset houses each with a different code. The limitation I was faced with was a lack of knowledge, this was overcome by researching a solution, and then applying the solution. 

Another useful variable would be data on family history, for example someone with an older family member who carry an inheritable disease are more likely to have said disease. Treatment history of family members may also be beneficial when looking on the micro end of this project. Having the treatment history of the family member could allow trying a different approach to treatment early on when the disease is in its early stages. However, this would require handling sensitive information, multiple datasets, and more time to clean, explore, and analysis the data to produce findings.

This dataset has a lot of good information in it! It has a breakdown of mortality which I`ll admit isn`t a fun thing to research, however by knowing what causes high mortality or a poor health status, that country can focus resources to develop preventative measures. By identifying the cause of the problem, a solution can be formulated within our power, ethics, and morals. Or at the very least the population of the countries included in this project can be more informed and do with that information as they will.

