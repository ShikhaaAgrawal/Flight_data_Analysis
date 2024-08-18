Flight Price Prediction
Project Overview
This project focuses on predicting flight prices based on various features such as flight duration, the number of stops, departure and arrival times, and more. By leveraging different machine learning models, the aim is to provide accurate predictions that can help travelers make informed decisions.

Table of Contents
Introduction
Dataset
Installation
Exploratory Data Analysis
Modeling
Results
Conclusion
Future Work
Contributing
License
Introduction
The airline industry is a dynamic and complex field, with flight prices fluctuating based on a multitude of factors. This project aims to predict flight prices by analyzing various features using machine learning algorithms. The goal is to identify patterns and relationships that can provide accurate pricing predictions.

Dataset
The dataset used in this project was scraped from Google Flights and includes features such as:

Flight Duration (minutes)
Number of Stops
Departure Time
Arrival Time
Airline
Source
Destination
Data Collection
The data was collected using web scraping techniques on Google Flights, ensuring that the dataset is both up-to-date and relevant for predicting current flight prices.

Exploratory Data Analysis
The exploratory data analysis (EDA) process included:

Data Cleaning: Handling missing values, outliers, and ensuring data consistency.
Data Visualization: Plotting distributions and relationships between features.
Feature Engineering: Creating new features based on existing data to improve model accuracy.
Modeling
The following machine learning models were applied:

Linear Regression: To understand the relationship between flight duration and the number of stops.
Multiple Linear Regression: To capture the combined effect of multiple features on flight prices.
Support Vector Regression (SVR): To handle non-linearities in the data.
Random Forest Regression: To improve prediction accuracy by averaging the results of multiple decision trees.
Decision Tree Regression: To gain insights into how different features influence flight prices.
Results
The model performances are summarized below:

Linear Regression:
MSE: 2888.44
R²: 0.08
Decision Tree:
MSE: 1997.96
R²: 0.36
Random Forest:
MSE: 1997.00
R²: 0.36
Support Vector:
MSE: 3241.98
R²: -0.03
The best performing model was Random Forest Regression with an MSE of 1997.00 and R² of 0.36.

Conclusion
This project demonstrates the effectiveness of various machine learning models in predicting flight prices. The Random Forest model, in particular, provided the most accurate predictions. These models can serve as a foundation for developing more advanced price prediction systems.

Future Work
Hyperparameter Tuning: Further optimization of the model parameters to improve accuracy.
Incorporate More Features: Adding features like airline reputation, seasonal factors, and historical prices.
Deploy Model: Develop a web application or API for real-time price prediction.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any ideas or improvements.
