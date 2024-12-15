# Customer Churn Prediction Using Python

## Project Overview

The dataset used in this project contains various customer attributes, such as age, vehicle ownership, driving experience, past accidents, and credit score,DUIs along with a target variable indicating whether the customer waived their car insurance policy.


## Data Description
The dataset used in this project contains various customer attributes, such as age, balance, and number of products used, along with a target variable indicating whether the customer has exited (churned) or not.

## Repository Contents
- `train.csv`: Training dataset containing customer attributes and the target variable.
- `test.csv`: Test dataset for predicting churn.
- `churn_prediction.ipynb`: Jupyter notebook with the analysis and model training.
- `submission.csv`: Predictions for the test dataset.
- `README.md`: Documentation of the project.

## Key Steps
1. Data Preprocessing: Cleaning and encoding of the data, making it suitable for model training.
2. Exploratory Data Analysis (EDA): Analyzing the data to understand patterns and relationships, such as the impact of driving experience and credit score on waivers.
3. Feature Engineering: Selecting and transforming features for model training, such as categorizing credit scores or vehicle types.
4. Model Training: Building and training an XGBoost classifier.
5. Model Evaluation: Evaluating the model's performance using metrics like accuracy, precision, and recall.
6. Feature Importance Analysis: Understanding which features are most impactful in predicting insurance waivers.
7. Predictions: Generating churn predictions on the test dataset.

## Technologies Used
- Python
- Pandas
- Matplotlib and Seaborn for visualizations
- Scikit-learn for data preprocessing and model evaluation
- SAS for the prediction model

## How to Run
To run the analysis and model training:
1. Ensure you have Python installed along with the required libraries.or can download Jupyter Notebook/Google Colab
2. Clone this repository.
3. Open and run the `Customer Churn Prediction Using XGBoost.ipynb` notebook in a Jupyter environment.

## Author
Yen Nguyen
LinkedIn: www.linkedin.com/in/tracyyennguyen

