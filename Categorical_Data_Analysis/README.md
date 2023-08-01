# README

## Introduction

This repository contains the analysis and findings related to the research question: "How does desired weight change impact how individuals evaluate their health?" The data used for this analysis comes from the Behavioral Risk Factor Surveillance System (BRFSS) survey.

## Files

- data.csv: This file contains the raw data obtained from the BRFSS survey, which includes information on individuals' age, health evaluation, smoking status, exercise habits, desired weight change, and health plan status.
- analysis.Rmd: This R Markdown file contains all the code used for data cleaning, data visualization, statistical analysis, and model fitting. The R Markdown file is well-commented and organized into sections for easy understanding.
- analysis.html: The HTML output generated from the analysis.Rmd file. It includes all the code, plots, and results.

## Data Cleaning

Before conducting the analysis, the data was cleaned to handle missing values, recode variables, and prepare the data for visualization and modeling.

## Exploratory Data Analysis (EDA)

The EDA section explores the relationship between desired weight change and how individuals evaluate their health. Various visualizations, such as box plots and scatter plots, were used to identify patterns and trends in the data.

## Modeling: Research Question 1

This section includes the modeling process to investigate the relationship between age and how individuals evaluate their health. Polynomial regression was used to capture the non-linear relationship, and the results were visualized through regression lines and model diagnostics.

## Modeling: Research Question 2

In this section, we analyzed the relationship between desired weight change and how individuals evaluate their health. Multinomial regression was used due to the multi-level response variable. The nested likelihood ratio test was conducted to assess the significance of the exercise variable in the model.

## Conclusions

The final section summarizes the findings and conclusions based on the analysis. Predicted probabilities of health evaluation by age were presented for individuals who do not smoke, exercise, have a health plan, and desire to lose 20 pounds.

## Instructions

To reproduce the analysis and explore the findings, follow these steps:

1. Clone or download this repository to your local machine.
2. Ensure you have R and RStudio installed.
3. Open the analysis.Rmd file in RStudio.
4. Install any necessary packages if prompted.
5. Run the code chunks sequentially to perform the data cleaning, EDA, and modeling.
6. The output, including plots and results, will be generated in the analysis.html file.

Please note that the analysis is based on the data available at the time of the study. For any questions or further inquiries, feel free to contact the author.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code and findings, but kindly acknowledge the source.

**Author**: [Your Name]

**Contact**: [Your Email]
