# DSC530 Final Project EDA and Analysis

## Introduction

This repository contains the Exploratory Data Analysis (EDA) and Analysis for the DSC530 Final Project. The analysis is based on an open-source dataset sourced from Openpsychometrics.org, which collected data on depression and anxiety levels between 2017 and 2019 using an online version of the Depression Anxiety Stress Scales. The dataset includes responses to 42 questions, along with demographic information such as education level, religion, area type, marital status, and family size.

## Data Exploration

The EDA and Analysis process involved exploring various aspects of the dataset, including initial questions and variables, histograms of predictors, histograms of outcome variables, examining outliers, and calculating descriptive statistics.

## Variable Analysis

This section involved further analysis of variables to examine their relationships and distributions. Probability Mass Functions (PMFs) and Cumulative Density Functions (CDFs) were used to visualize the relationships between specific variables, such as marital status and self-worth perception.

## Comparing Variables

The analysis in this section involved comparing variables to understand their relationships and potential predictors. Scatterplots, lines, covariance, and correlation coefficients were used to examine the relationships between education level, family size, and the response to the statement "I was unable to become enthusiastic about anything."

## Testing Significance

This section focused on hypothesis testing and regression analysis to determine the significance of certain relationships. A t-test was performed to compare the mean response to the statement "I felt I wasn't worth much as a person" between married and not married individuals. Additionally, logistic regression was used to predict marital status based on the response to the same statement.

## Conclusion

The analysis revealed interesting insights into the dataset, including the relationship between marital status and self-worth perception, the distribution of education level, and family size, and the predictability of certain responses based on demographic variables.

## Repository Contents

- data.csv: The dataset used for the analysis.
- DSC530_Final_Project_Analysis.ipynb: The Jupyter Notebook containing the EDA and Analysis code.
- README.md: This file, providing an overview of the repository and the analysis conducted.

## Requirements

The code in the Jupyter Notebook requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- pingouin
- statsmodels

## Usage

To reproduce the analysis, you can simply download the data.csv file and run the code in the DSC530_Final_Project_Analysis.ipynb Jupyter Notebook.

## Acknowledgments

The dataset used for this analysis was sourced from Openpsychometrics.org, a nonprofit effort to educate the public about psychology and collect data for psychological research.

## License

This project is licensed under the MIT License. Feel free to use the code and data for your own analyses or projects.

For questions or inquiries, please contact Your Name (your.email@example.com).
