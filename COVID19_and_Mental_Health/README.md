# COVID-19 and Mental Health Analysis

This repository contains code for analyzing the relationship between COVID-19 and mental health. The code processes and visualizes data related to indicators of mental health, including prescription medication usage, counseling or therapy, and unmet counseling or therapy needs.

## Table of Contents

- [Graphs](#graphs)
- [Data Preparation and Modeling](#data-preparation-and-modeling)

## Graphs

The code in this section generates graphs to visualize the data related to mental health indicators. It uses the `ggplot2` library for creating the visualizations.

### Indicator 1

The graphs in this section focus on **Indicator 1**: "Took Prescription Medication for Mental Health And/Or Received Counseling or Therapy, Last 4 Weeks." The code generates graphs for different demographic groups such as gender, age, state, and race/ethnicity. Each graph represents the average percentage for each subgroup within the demographic category.

### Indicator 2

The graphs in this section focus on **Indicator 2**: "Needed Counseling or Therapy But Did Not Get It, Last 4 Weeks." Similar to Indicator 1, the code generates graphs for different demographic groups, showing the average percentage of individuals who needed counseling or therapy but did not receive it.

## Data Preparation and Modeling

This section of the code focuses on data preparation and modeling techniques for the COVID-19 and mental health analysis. It uses various libraries such as `dplyr`, `tidyr`, `mltools`, `data.table`, `FNN`, `caret`, `rpart`, and `rpart.plot` for data manipulation and modeling.

### Data Transformation and Cleaning

The code in this section handles data cleaning tasks, including removing missing values and selecting specific features for analysis.

### Indicator Data

The code subsets the original dataset based on the two indicators, Indicator 1 and Indicator 2. It creates separate datasets for each indicator, considering demographic groups such as gender, age, state, and race/ethnicity.

### Data Analysis

The code then performs data analysis tasks, including generating visualizations and applying modeling techniques to explore the relationship between COVID-19 and mental health.

---

This README file provides an overview of the code and its purpose. For more details and specific implementation, refer to the code file(s) in this repository.

