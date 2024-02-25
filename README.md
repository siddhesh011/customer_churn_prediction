# customer_churn_prediction


Overview:
This GitHub project focuses on predicting customer churn using TensorFlow sequential models. The dataset consists of customer information including Customer ID, Gender, Senior Citizen status, Partner, Dependents, tenure, and various services subscribed to, among other details.

Dataset:
The dataset is structured with columns representing customer attributes such as Customer ID, Gender, Senior Citizen status, Partner, Dependents, tenure, and various services subscribed to (e.g., Phone Service, Internet Service, Online Security, etc.). The target variable is 'Churn', indicating whether a customer has churned or not.

Models:
Two TensorFlow sequential models have been implemented to predict customer churn:

Simple Sequential Model: Initially, a simple sequential model was built to predict churn based on the dataset attributes.

Improved Sequential Model: To enhance accuracy, an improved sequential model was developed. This model incorporates regularization techniques, utilizes the Adam optimizer, and introduces an additional layer to the neural network architecture. These enhancements aim to refine the model's predictive capabilities and achieve higher accuracy in identifying potential churners.
