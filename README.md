**Project Overview**

In this project, the dataset is preprocessed by handling categorical variables using one-hot encoding and selecting relevant features for predicting house prices. The model is then trained on an 80% training dataset and tested on a 20% test dataset. The performance of the model is evaluated using several metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-Squared (R²). Visualizations are created to compare the predicted house prices to the actual prices.

**Workflow**

Data Preprocessing:
-> Handle missing values (if any).
-> Convert categorical variables (e.g., mainroad, guestroom, etc.) to numerical using one-hot encoding.
Feature Selection:
-> Select relevant independent variables (features) and the dependent variable (price).
Model Training:
-> Split the dataset into training and test sets (80% train, 20% test).
-> Train a Linear Regression model on the training data.
Evaluation:
-> Evaluate the model performance using MSE, MAE, and R².
-> Visualize the comparison between actual and predicted house prices using a scatter plot.
**Technologies Used**

1. Python
2. Pandas (for data manipulation)
3. NumPy (for numerical computations)
4. Matplotlib & Seaborn (for data visualization)
5. Scikit-learn (for machine learning model and evaluation)
