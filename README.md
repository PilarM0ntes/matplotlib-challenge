# Matplotlib-Challenge
## General Description
This repository includes a project called "pymaceuticals_starter.ipynb" which analyzes the study of 249 mice identified with SCC tumor growth that were treated through a variety of drug regimens.
## Main Objective
Discover insights related to the effectiveness of the different drug regimens based on the data from the mice study.The data from the study is included in the data folder. This folder includes two folders: Mouse_metadata.csv and Study_results.csv. All calculations and graphs were performed using the combination of these 2 files. The total dataset is composed of 8 columns: Mouse ID, Drug Regimen, Sex, Age_months, Weight (g), Timepoint, Tumor Volume (mm3), and Metastatic Sites. The notebook is called pymaceuticals_starter.ipynb and provides the following information:
- Data cleaning, which checks if there's any duplicate based on the Mouse ID and the timepoint.
- A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- A bar plot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
- A pie chart that shows the distribution of female or male mice in the study.
- A summary table of the quartiles and IQR of the 4 most promising regimens:  Capomulin, Ramicane, Infubinol, and Ceftamin and its corresponding boxplot.
- A line plot that shows the tumor volume over time of a random mouse treated with Capomulin
- A scatter plot mouse weight versus average tumor volume for the Capomulin treatment regimen with the correlation coefficient and linear regression model.
