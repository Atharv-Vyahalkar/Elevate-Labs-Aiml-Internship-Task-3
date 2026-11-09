# Task 3: Multiple Linear Regression – House Price Prediction

## Project Overview
This project is part of the Elevate Labs AI & ML Internship (Task 3). It focuses on implementing Multiple Linear Regression using Python and Scikit-learn to predict house prices based on property features.

The model uses two independent variables, Area and Floors, to predict the house Price.

## Objective
- Understand and implement Multiple Linear Regression.
- Load and explore a house price dataset.
- Split data into training and testing sets.
- Train a Linear Regression model.
- Evaluate model performance using regression metrics.
- Visualize predictions and interpret model coefficients.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Structure
```text
Task-3-Linear-Regression/
│
├── Dataset/
│   └── House Price Prediction Dataset.csv
│
├── Task3.ipynb
│
├── README.md
```

## Dataset Description
**Dataset:** House Price Prediction Dataset

Selected Features:

| Feature | Description |
|---|---|
| Area | Area of the house |
| Floors | Number of floors |
| Price | Target variable representing house price |

- Independent Variables (X): Area, Floors
- Dependent Variable (Y): Price

## Implementation Steps

1. Imported the required Python libraries.
2. Loaded the house price dataset using Pandas.
3. Explored dataset information and checked missing values.
4. Selected Area and Floors as independent variables.
5. Selected Price as the dependent variable.
6. Split the dataset into training (75%) and testing (25%) sets.
7. Initialized and trained the Multiple Linear Regression model.
8. Generated predictions using testing data.
9. Evaluated model performance using MAE, MSE, and R².
10. Interpreted regression coefficients.
11. Visualized actual versus predicted house prices.

## Model Evaluation

The model is evaluated using the following metrics:

| Metric | Description |
|---|---|
| MAE | Mean Absolute Error |
| MSE | Mean Squared Error |
| R² Score | Measures the proportion of variance in house prices explained by the model |

Actual evaluation results are available in the Jupyter Notebook.

## Visualization
The project includes an Actual vs Predicted House Prices scatter plot to compare the model's predictions against actual values.

## How to Run the Project

**1. Clone the repository**
```bash
git clone https://github.com/Atharv-Vyahalakar/Elevate-Labs-Aiml-Internship-Task-3.git
```

**2. Navigate to the project directory**
```bash
cd Elevate-Labs-Aiml-Internship-Task-3
```

**3. Install dependencies**

**4. Launch Jupyter Notebook**
```bash
jupyter notebook
```

**5. Open and execute the notebook.**

## Key Learnings
- Understanding Multiple Linear Regression.
- Working with independent and dependent variables.
- Training and testing machine learning models.
- Evaluating regression models using performance metrics.
- Interpreting model coefficients.
- Visualizing regression predictions.

## Conclusion
This task provided practical experience in implementing Multiple Linear Regression using Scikit-learn. The project demonstrates how multiple house-related features can be used to predict property prices and how regression metrics help evaluate prediction performance.

---

**Internship:** Elevate Labs AI & ML Internship  
**Task:** Task 3 – Linear Regression
