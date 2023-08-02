# Employee Termination Prediction Model

## Overview

This project aims to develop a predictive model for employee termination using historical employee data. The dataset includes various employee attributes such as annual salary, department, time off records, generation, and more. The goal is to build a machine learning model to identify potential employees at risk of termination.

## Table of Contents

- Project Milestone 1
- Project Milestone 2
- Project Milestone 3
- Conclusion
- Prerequisites
- Installation
- Usage
- Results
- Contributing
- License
- Contact

## Project Milestone 1

In this milestone, the exploratory data analysis (EDA) is performed on the dataset. The dataset is loaded, cleaned, and analyzed to gain insights into the distribution of data, patterns, and relationships between variables. Various visualizations are used to explore the data and understand the factors that may be related to employee termination.

## Project Milestone 2

Data preparation steps are performed in this milestone. The dataset is preprocessed, and features are engineered to be used in the predictive models. Categorical variables are converted to dummy variables, unnecessary columns are dropped, and new features, such as monthly and yearly hours taken off, are added. The dataset is then split into training and testing sets to train and evaluate the models.

## Project Milestone 3

In this milestone, predictive models are developed and evaluated. Two machine learning models, K-Nearest Neighbor (KNN) and Decision Tree Classifier, are chosen based on their strengths and suitability for the data. Hyperparameter tuning is performed using halving grid search to find the optimal parameters for each model. The models are then fitted on the training data and evaluated using various metrics, such as accuracy, area under the curve (AUC), and Matthew's correlation coefficient (MCC).

## Conclusion

Based on the evaluation of the KNN and Decision Tree models, it is concluded that the KNN model is a stronger predictor for employee termination. The KNN model outperforms the Decision Tree model in terms of AUC and MCC, indicating its better ability to handle imbalanced data and accurately predict termination outcomes.

## Prerequisites

- Python (>=3.6)
- Jupyter Notebook

## Installation

1. Clone the repository:

git clone https://github.com/your-username/employee-termination-prediction.git


2. Install the required packages:


pip install -r requirements.txt


## Usage

1. Open Jupyter Notebook:


jupyter notebook


2. Navigate to the project directory and open the `employee_termination_prediction.ipynb` notebook.

3. Run the cells in the notebook sequentially to perform data analysis, preprocessing, model tuning, and evaluation.

## Results

The results of the predictive models can be observed in the Jupyter Notebook. Model accuracy, AUC, and MCC scores are displayed, along with confusion matrices to visualize model performance on true and predicted classes.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

