# Housing Price Prediction

## Project Overview

In this project, the goal is to predict house prices using a dataset containing several features related to the houses. The dataset is preprocessed by handling categorical variables through one-hot encoding and selecting relevant features for the prediction. A Linear Regression model is trained on 80% of the data and tested on the remaining 20%. The performance of the model is evaluated using key metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-Squared (R²). Visualizations are created to compare the predicted house prices to the actual prices.

## Workflow

### 1. Data Preprocessing
- Handle missing values (if any).
- Convert categorical variables (e.g., mainroad, guestroom, etc.) into numerical variables using one-hot encoding.

### 2. Feature Selection
- Select relevant independent variables (features) and the dependent variable (`price`).

### 3. Model Training
- Split the dataset into training and test sets (80% train, 20% test).
- Train a Linear Regression model on the training data.

### 4. Evaluation
- Evaluate the model performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-Squared (R²).
- Visualize the comparison between actual and predicted house prices using a scatter plot.

## Technologies Used

- **Python**
- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning model and evaluation.

## How to Run

1. Clone the repository or download the dataset.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
