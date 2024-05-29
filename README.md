**Car Price Prediction**

This project aims to predict the selling price of cars using machine learning models. The dataset includes features such as the car's name, year of manufacture, kilometers driven, fuel type, seller type, transmission, and owner history.


**Data Description**
The dataset used in this project contains the following columns:

name: The name of the car.
year: The year the car was manufactured.
selling_price: The price at which the car is being sold.
km_driven: The total kilometers driven by the car.
fuel: The type of fuel used by the car (e.g., Petrol, Diesel, CNG, LPG).
seller_type: The type of seller (e.g., Individual, Dealer).
transmission: The type of transmission (e.g., Manual, Automatic).
owner: The number of previous owners (e.g., First Owner, Second Owner).



**Steps Involved:**

1. **Data Preprocessing**:
    - Load the dataset.
    - Encode categorical variables using one-hot encoding.
    - Split the data into training and testing sets.

2. **Model Training**:
    - Train a Linear Regression model.
    - Train a Lasso Regression model to handle potential multicollinearity and feature selection.

3. **Model Evaluation**:
    - Predict car prices on the test set.
    - Evaluate the models using R-squared value to measure the proportion of variance explained by the model.

4. **Visualization**:
    - Plot actual vs. predicted car prices to visualize model performance.

**Results**:
- The Linear Regression model achieved an R-squared value of 0.43, indicating moderate predictive power.
- The Lasso Regression model was also evaluated for its ability to improve prediction accuracy.

The car price prediction models developed in this project provide a solid foundation for estimating the selling prices of cars. While the Linear Regression model captures the basic relationships, the Lasso Regression model helps in dealing with potential overfitting, providing a more robust solution. 
Future work can focus on incorporating additional features, exploring more advanced regression techniques, and fine-tuning the models for even better accuracy.
