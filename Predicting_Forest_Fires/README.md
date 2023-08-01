# Predicting Burned Area of Forest Fires Using Meteorological Data

**Author**: Taylor Callahan
**Date**: June 13, 2023

This repository contains the code and data for predicting the burned area of forest fires using meteorological data. The analysis involves building and evaluating several machine learning models on a dataset containing various meteorological features and the corresponding burned area of the forest.

## Prerequisites

To run the code in this repository, you will need the following R packages installed:

- gridExtra
- ggplot2
- kableExtra
- grid
- dplyr
- caret
- ranger
- rpart
- nnet
- e1071
- kernlab

You can install these packages using the following R code:

`install.packages(c("gridExtra", "ggplot2", "kableExtra", "grid", "dplyr",
"caret", "ranger", "rpart", "nnet", "e1071", "kernlab"))`


## Data

The dataset used for this analysis is stored in a CSV file named "forestfires.csv". The dataset contains the following variables:

- X: X-axis spatial coordinate within the Montesinho park map
- Y: Y-axis spatial coordinate within the Montesinho park map
- Month: Month of the year (jan to dec)
- Day: Day of the week (mon to sun)
- FFMC: Fine Fuel Moisture Code from the FWI system
- DMC: Duff Moisture Code from the FWI system
- DC: Drought Code from the FWI system
- ISI: Initial Spread Index from the FWI system
- Temp: Temperature in Celsius degrees
- RH: Relative humidity in percentage
- Wind: Wind speed in km/h
- Rain: Rainfall in mm/m^2
- Area: Burned area of the forest (in hectares)

## Data Exploration and Visualization

The R code provided in this repository reads the data and performs the following tasks:

1. Checks for missing data and prints the variables with missing values.
2. Provides a data dictionary that describes each variable.
3. Creates a histogram to visualize the distribution of the burned area.
4. Generates scatterplots to examine the relationships between numeric variables and the burned area.
5. Plots the average burned area by month.

## Modeling

The code also includes a machine learning pipeline that trains and evaluates three models: Random Forest, Support Vector Machine (SVM), and Neural Network. The dataset is split into training and testing sets, and the models are tuned using cross-validation. The evaluation metrics, Root Mean Squared Error (RMSE), and R-squared, are calculated for each model.

## Code Appendix

The code for data processing, exploration, and modeling is provided in the code appendix. You can find the full R code with all the necessary functions and steps for reproducing the analysis.

For more details, please refer to the R code provided in this repository.

---

Please make sure to have R and RStudio installed with the required packages to run the code successfully. For any questions or issues, feel free to contact the author, Taylor Callahan. Happy analyzing!
