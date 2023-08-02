# Retail sales prediction-Machine Learning Project-(Regression)

Welcome to my Machine Learning Regression project! This is a personal project where I aim to build a predictive model capable of forecasting the sales of Rossmann stores. The project is based on supervised machine learning, where historical data about 1115 stores, both operating and non-operating, will be utilized to train the model.

### Problem Statement
The objective of this project is to develop a regression model that can accurately predict the sales of Rossmann stores. We are provided with two CSV datasets containing information about the stores, which we will merge based on the "Store" column to create a comprehensive dataset.

### Dataset Overview
After merging the datasets, we have a total of 1017209 rows and 18 columns. During the data preprocessing phase, we handled missing values, Data wrangling and feature engineering techniques were applied to prepare the dataset for analysis.

### Exploratory Data Analysis
In the project, we performed exploratory data analysis (EDA) to gain insights into the dataset. This included univariate, bivariate, and multivariate analysis to understand the relationships between different features and their impact on sales.

### Model Building
To build our predictive model, we first split the dataset into a training set (75%) and a test set (25%). We then applied data transformation and normalization techniques to prepare the data for modeling.

 Several regression algorithms were experimented with, including:

- Linear Regression
- Ridge Regression
- Elastic Net Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression

### Model performance
Upon evaluating the different regression models, we found that the Random Forest Regression yielded the highest accuracy on the test dataset.

### Repository Contents
- Retail_sales_ML_Submission_Template.ipynb: The Jupyter Notebook containing the Python code and step-by-step data analysis process.
- Rossmann Stores Data.zip: The 2 CSV datasets used in the analysis.
- README.md: You are reading it right now! This file serves as the project's README to provide an overview.

### How to Use
Feel free to explore the Jupyter Notebook (Retail_sales_ML_Submission_Template.ipynb) to understand the data analysis process, model building, and evaluation. The notebook contains detailed explanations and code for each step of the project.

### Conclusion
This Machine Learning Regression project has allowed me to explore the world of predictive modeling and apply various regression algorithms to forecast the sales of Rossmann stores. The use of Random Forest Regression resulted in the highest accuracy, demonstrating its effectiveness for this particular prediction task.

Thank you for visiting my project repository. I hope you find the analysis and insights valuable. Feel free to provide any feedback or reach out to me with any questions or suggestions!
