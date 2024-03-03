# pymaceuticals-challenge
pymaceuticals-challenge

# Cancer Treatment Analysis
This data highlights significant differences in treatment efficacy among the drug regimens studied. Capomulin and Ramicane demonstrate comparable effectiveness, both surpassing Infubinol and Ceftamin. Additionally, a strong correlation (r = 0.95) between mouse weight and treatment response suggests heavier mice tend to exhibit less favorable outcomes. Notably, the study's consistency is underscored by the presence of only one outlier among the top-performing drugs and none for Capomulin, enhancing the reliability of the findings.

## Overview
This project involves the analysis of cancer treatment data collected from a study conducted on mice. The study evaluates the effectiveness of different drug regimens in reducing tumor volume and metastatic sites in mice.

## Data Sources
- **Mouse Metadata**: `Mouse_metadata.csv`
- **Study Results**: `Study_results.csv`

## Data Cleaning
- Removed duplicate data for mice with the same ID and timepoint.
- Checked for and removed any null values.
- Identified and removed outliers.

## Summary Statistics
- Calculated summary statistics including mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volume for each drug regimen.

## Bar and Pie Charts
- Generated bar plots using both Pandas and Matplotlib to visualize the total number of observations (mouse ID/timepoints) for each drug regimen.
- Created pie charts to show the distribution of male and female mice in the study.

## Quartiles, Outliers, and Boxplots
- Calculated quartiles and identified potential outliers for four specific treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Generated boxplots to visualize the distribution of tumor volume for each treatment regimen.

## Line and Scatter Plots
- Plotted line graphs to show the change in tumor volume over time for a single mouse treated with Capomulin.
- Created scatter plots to explore the relationship between mouse weight and average tumor volume for mice treated with the Capomulin regimen.

## Correlation and Regression
- Calculated the correlation coefficient and performed linear regression analysis to examine the relationship between mouse weight and average tumor volume for mice on the Capomulin regimen.
- Plotted the regression line along with the scatter plot to visualize the relationship.

## Assistance

AskBCS assisted with:
- Creating a clean DataFrame by dropping the duplicate mouse by its ID.

Instructor and TA assisted with:
- Generating a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using pyplot.
- Generating a pie plot showing the distribution of female versus male mice using pyplot.