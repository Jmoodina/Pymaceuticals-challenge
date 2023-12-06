# Pymaceuticals SCC Study Analysis Repository

## Project Introduction
Welcome to the Pymaceuticals, Inc. GitHub repository dedicated to the comprehensive analysis of our recent animal study focused on screening potential treatments for squamous cell carcinoma (SCC), a prevalent form of skin cancer. As a senior data analyst at Pymaceuticals, my role involves dissecting the complete dataset from this study, which involved 249 mice with SCC tumors subjected to various drug regimens. Throughout a 45-day period, the development and measurement of tumor progression were meticulously observed.

The executive team has specifically assigned me the task of providing a top-level summary of the study results, and this repository will showcase the code, visualizations, and analyses that contribute to our findings. Your engagement with this repository is key to gaining insights into the performance of Capomulin and other treatments in addressing SCC, ultimately advancing our understanding of potential cancer therapies.

## Objective
The primary objective of this study was to evaluate the efficacy of Pymaceuticals' key anti-cancer drug, Capomulin, in comparison to other treatment regimens. This repository serves as a centralized hub for the generation of tables and figures essential for the technical report detailing our clinical study.



## Project Tasks Overview
- Data Preparation
- Summary Statistics Generation
- Chart Creation
- Quartile Calculation, Outlier Identification, and Box Plot Creation
- Line Plot and Scatter Plot Creation
- Correlation and Regression Analysis
- Final Analysis Submission

### Summary Statistics Generation
Created a DataFrame containing summary statistics for each drug regimen, with regimen names as the index. Included mean, median, variance, standard deviation, and SEM of the tumor volume.

### Bar Charts and Pie Charts Creation
Generated two identical bar charts depicting the total number of rows (Mouse ID/Timepoints) for each drug regimen. One chart using Pandas DataFrame.plot() and the other using Matplotlib's pyplot methods. Additionally, produced two identical pie charts illustrating the distribution of female versus male mice in the study.

### Quartiles, Outliers, and Box Plot Analysis
Calculated the final tumor volume for mice under Capomulin, Ramicane, Infubinol, and Ceftamin. Determined quartiles, IQR, and identified potential outliers. Utilized Matplotlib to create a box plot showcasing the distribution of final tumor volumes, highlighting any potential outliers.

## Final Analysis Insights

- The data displayed on the graph shows a correlation between the weight and volume of the tumor.
- An almost equal amount of male and female mice were in the study. This removes any gender bias infleunce for the results of the test.
- Capomulin had the most time point tests out of any of the drugs and Propriva was the opposite. 
- The results also show the success of capomulin in reducing the volume of the tumor
- The results of the study are very consistent with only 1 outlier detected within infunobil and none on the other 3 drugs analyzed.
This further enhances the realibility of the tests with accurate and consistent data. 

