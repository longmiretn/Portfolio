# Depression and Happiness Analysis

This project aims to explore the relationship between depression, happiness, and various factors such as country, personality type, religion, age, sexual orientation, marital status, and country-specific indicators. The code provided performs data import, cleaning, analysis, and visualization to uncover insights related to mental health and well-being.

## Table of Contents
- [Introduction](#introduction)
- [Code Files](#code-files)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Data Sources](#data-sources)
- [Results](#results)

## Introduction

Mental health and well-being have become significant concerns in today's society, with depression rates increasing over time. This project focuses on identifying individual predictors of depression while also examining broader factors such as country-specific indicators and happiness levels. By analyzing various data points, the project aims to provide insights into the causes and impacts of depression.

## Code Files

- `Full_Wellbeing_Analysis.Rmd`: R Markdown file containing the code for data import, cleaning, analysis, and visualization.
- `depression.csv`: Data file containing the survey responses related to depression and other variables.
- `countries.csv`: Data file containing country-specific information such as population density and literacy rates.
- `world_happiness_2019.csv`: Data file containing World Happiness Report indicators for countries.

## Usage

To use this code, follow these steps:

1. Clone the repository or download the code files.
2. Ensure that you have R and the necessary packages installed (listed in the Dependencies section).
3. Modify the file paths in the code to match the location of the data files on your system.
4. Run the code in an R environment or notebook.
5. Review the generated analysis, tables, and visualizations to gain insights into the relationship between depression, happiness, and various factors.

## Dependencies

The code relies on the following R packages:

- `countrycode`
- `dplyr`
- `stringr`
- `tidyverse`
- `kableExtra`
- `ggplot2`
- `reshape2`
- `ggpubr`
- `qqplotr`
- `rpart`
- `rpart.plot`

Ensure that these packages are installed in your R environment before running the code.

## Data Sources

The analysis uses the following data sources:

- `depression.csv`: Contains survey responses related to depression and other variables.
- `countries.csv`: Provides country-specific information such as population density and literacy rates.
- `world_happiness_2019.csv`: Includes World Happiness Report indicators for different countries.

Make sure to have these data files available in the specified file paths or modify the code to match the locations of your data files.

## Results

The analysis produces various outputs, including correlation matrices, tables, and visualizations. These results provide insights into the relationship between depression and different factors such as personality type, religion, age, sexual orientation, marital status, and country-specific indicators. The README file can be extended to summarize the key findings or link to a separate document for a detailed analysis of the results.
