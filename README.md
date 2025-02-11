Predicting Precipitations

Overview

This project aims to predict precipitation using weather data collected by a NOAA weather station located at John F. Kennedy International Airport (JFK) in Queens, New York. A U.S. weather firm is analyzing local climatological variables, such as temperature, wind speed, humidity, dew point, and pressure, to determine their relationship with precipitation.

Objective

The goal is to perform a high-level analysis of weather patterns at JFK Airport and evaluate how different meteorological variables influence the probability of precipitation. The insights gained will help stakeholders understand precipitation trends, which can impact flight delays and operational planning.

Data Source

The dataset is obtained from a NOAA weather station at JFK Airport.

It contains historical weather records, including temperature, wind speed, humidity, pressure, and precipitation data.

Methodology

Data Preprocessing:

Handling missing values by replacing them with appropriate statistical measures (mean, median, etc.).

Converting necessary columns to numerical format.

Exploratory Data Analysis (EDA):

Generating histograms and box plots to understand variable distributions.

Checking correlations between variables.

Model Training & Evaluation:

Implementing multiple regression models, including:

Multiple Linear Regression (MLR)

Polynomial Regression

Evaluating models using metrics such as RMSE, MAE, and R².

Model Comparison:

Comparing the performance of different models on test data.

Selecting the best model based on predictive accuracy.

Requirements

To run this project, ensure you have R installed with the following packages:

install.packages(c("tidyverse", "parsnip", "yardstick", "ggplot2"))

How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/predicting-precipitations.git
cd predicting-precipitations

Open R or RStudio and set the working directory to the project folder.

Load the dataset and run the R scripts provided.

Results

The final model selection is based on error metrics (RMSE, MAE, and R²).

Insights from the analysis will help stakeholders predict precipitation patterns effectively.

Contributing

If you’d like to contribute, feel free to fork the repository and submit a pull request.

contact: arturofgarza@gmail.com

License

This project is open-source and available under the MIT License.
