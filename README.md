# Accurate-Used-Car-Selling-Price-Prediction-for-Informed-Market-Transactions


# Abstract:

The aim of this project is to develop a robust machine learning model that accurately predicts the selling prices of used cars. The objective is to empower both sellers and buyers to make informed decisions by leveraging reliable price predictions, facilitating fair and efficient market transactions.

To achieve this, we explore and compare multiple regression models including Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Classifier, Random Forest, and Ordinary Least Squares (OLS). By evaluating their performance metrics such as R-squared values, we determine the most effective model for predicting car resale prices.

After conducting thorough analysis and evaluation, we conclude that the Random Forest regressor optimized with Optuna, using all available features, demonstrates promising results. This model yields high R-squared values of 0.78, indicating its ability to explain approximately 80% of the variance in the resale price. This suggests that the Random Forest model is effective in capturing the complex relationships between the car features and its selling price.

# Dataset Attribute Information:

The dataset contains the following attributes:

Car_Name: The name or model of the car.

Year: The year in which the car was manufactured.

Selling_Price: The price at which the car is being sold.

Kms_Driven: The total distance driven by the car in kilometers.

Fuel_Type: The type of fuel used by the car (Petrol, Diesel, CNG, etc.).

Seller_Type: Indicates whether the seller is an individual or a dealer.

Transmission: The type of transmission system in the car (Manual or Automatic).

Owner: The number of previous owners the car has had.

These attributes provide relevant information about the cars in the dataset, including their characteristics, usage history, and pricing details.


# Real-life Implementation:

The developed machine learning model for predicting car selling prices can have practical applications in the used car market. It can be integrated into online platforms or mobile applications that facilitate car transactions. The model can provide reliable price estimates to both sellers and buyers, enabling them to negotiate fair prices based on accurate market value predictions. This implementation can promote transparency, efficiency, and informed decision-making in the used car market, benefiting all stakeholders involved.


