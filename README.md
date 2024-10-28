# Linear-Regression
House Price Prediction Model
This repository contains a linear regression model designed to predict house prices based on square footage, number of bedrooms, and number of bathrooms. The model is built using Python and various data science libraries.

Project Overview
In this project, we use a dataset of house prices to develop a predictive model. The aim is to use features such as square footage (GrLivArea), the number of bedrooms (BedroomAbvGr), and the number of bathrooms (FullBath) to accurately estimate the price of a house. The project utilizes a linear regression algorithm for its simplicity and effectiveness in continuous value prediction tasks.

Features
Square Footage (GrLivArea): The total living area of the house in square feet.
Number of Bedrooms (BedroomAbvGr): The number of bedrooms in the house.
Number of Bathrooms (FullBath): The number of bathrooms in the house.
Model Evaluation
The model's performance is evaluated using the Root Mean Squared Error (RMSE), which provides a measure of how closely the model's predictions align with actual values.

Requirements
To run this project, you need the following libraries:

pandas
numpy
scikit-learn
matplotlib
Getting Started
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/house-price-prediction.git
Install Dependencies
Install the required libraries using pip:


pip install pandas numpy scikit-learn matplotlib
Prepare Data
Place your dataset files (train.csv, test.csv, and sample_submission.csv) in the appropriate directory.

Run the Model
Execute the script to train the model and view the results:


python house_price_prediction.py
Usage
The script:

Loads the dataset and explores it for missing values and data types.
Selects and preprocesses features.
Splits the data into training and validation sets.
Trains a linear regression model.
Evaluates the model’s performance using RMSE.
Results
The model’s performance is evaluated by comparing actual vs predicted sale prices. A scatter plot visualization helps identify the alignment of predictions with real sale prices.

License
This project is licensed under the MIT License.

