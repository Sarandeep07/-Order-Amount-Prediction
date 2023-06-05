# -Order-Amount-Prediction

This project aims to build a Machine Learning model to predict the order amount that customers can place in the upcoming days based on their past order information and behavior.

(This project is an assignment for the HighRadius unpaid internship for the 2024 passing out batch.)

Project Structure
The project is structured as follows:

data/ : This directory contains the dataset used for training and evaluation.
README.md : This file provides an overview of the project and its objectives.
Requirements
The project requires the following packages to be installed:

Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
To install these packages, you can run the following command:

pip install -r requirements.txt
Milestones
The project consists of several milestones, each focusing on a specific task. Here is a summary of the milestones:

Data Sanity : In this milestone, we perform data cleaning and preprocessing tasks such as handling missing values, formatting date columns, removing inconsistent records, and converting currency values to USD.

EDA (Exploratory Data Analysis) : This milestone involves analyzing the dataset to gain insights and understand the relationships between variables. We create visualizations such as histograms, pie charts, line plots, and box plots to explore different aspects of the data.

Feature Engineering and Selection : In this milestone, we perform feature engineering techniques such as encoding categorical variables, applying log transformations to continuous columns, and creating new features through grouping. We also analyze the correlation between variables using a heatmap and select relevant features for prediction.

ML Models and Evaluations : This milestone focuses on building and evaluating different machine learning models for order amount prediction. We try various models such as Linear Regression, Support Vector Machine, Decision Tree, Random Forest, AdaBoost, and XGBoost. We perform model evaluations using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-Squared. We compare the accuracies of the models and select the best-performing one. We also perform hyperparameter tuning to further improve the model's accuracy.

Please refer to the individual Jupyter notebooks in the notebooks/ directory for detailed explanations and code implementation for each milestone.

Usage
To use this project, follow these steps:

Clone the repository to your local machine:

git clone https://github.com/jaywyawhare/Order-Amount-Prediction.git
Navigate to the project directory:

cd Order-Amount-Prediction
Install the required packages:

pip install -r requirements.txt
Open the Jupyter notebooks in the notebooks/ directory to view and run the code for each milestone.

Conclusion
This project provides a framework for predicting order amounts using Machine Learning techniques. By following the milestones and implementing the necessary tasks, you can build and evaluate models for order amount prediction. Feel free to customize and expand upon the project to suit your specific requirements.

If you have any questions or need further assistance, please feel free to reach out.

About
Order Amount Prediction is a machine learning project that predicts customer order amounts based on past behavior. It includes milestones for data cleaning, exploratory data analysis, feature engineering, and model building. The framework can be customized to suit specific needs and provides insights for better decision-making.
