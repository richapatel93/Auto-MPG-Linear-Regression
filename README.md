# Auto-MPG-Linear-Regression
This project demonstrates the implementation of Linear Regression to predict the Miles Per Gallon (MPG) of vehicles using the Auto MPG dataset.
# Linear Regression for Predicting MPG

## Overview
This project demonstrates the implementation of **Linear Regression** to predict the **Miles Per Gallon (MPG)** of vehicles using the **Auto MPG dataset**. The dataset contains features such as weight, horsepower, cylinders, and model year, which are used to build and evaluate the model. The project covers data preprocessing, model training, evaluation, and visualization, providing a comprehensive understanding of Linear Regression in a real-world context.

---

## Key Features
1. **Data Preprocessing**:
   - Handling missing values.
   - Splitting the dataset into training and testing sets.
   - Feature selection and normalization.

2. **Model Training**:
   - Implementation of Linear Regression using `scikit-learn`.
   - Training the model on the Auto MPG dataset.

3. **Model Evaluation**:
   - Calculation of R² score to evaluate model performance.
   - Comparison of predictions with actual values.

4. **Visualization**:
   - Scatter plots to visualize relationships between features and MPG.
   - Error analysis using absolute error plots.

5. **Experimentation**:
   - Impact of train-test split ratios on model performance.
   - Effect of reducing the number of features on prediction accuracy.
   - Comparison of model performance with and without feature normalization.

---

## Technologies Used
- **Python**: Primary programming language.
- **Jupyter Notebook**: Interactive environment for code execution and documentation.
- **Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `numpy`: Numerical computations.
  - `scikit-learn`: Machine learning model implementation.
  - `matplotlib` and `seaborn`: Data visualization.

---

## Dataset
The **Auto MPG dataset** is used for this project. It contains the following features:
- **MPG**: Miles per gallon (target variable).
- **Cylinders**: Number of cylinders in the engine.
- **Displacement**: Engine displacement (size).
- **Horsepower**: Engine power.
- **Weight**: Weight of the car.
- **Acceleration**: Time to accelerate from 0 to 60 mph.
- **Model Year**: Year the car was made.
- **Origin**: Country of origin (1: USA, 2: Europe, 3: Japan).

---

## Key Findings
1. **Feature Importance**:
   - Features like **Weight** and **Horsepower** have a strong negative correlation with MPG, while **Model Year** has a positive correlation.
2. **Impact of Train-Test Split**:
   - Reducing the training set size (e.g., 20% train / 80% test) leads to poorer model performance due to insufficient data for training.
3. **Effect of Normalization**:
   - Normalizing features improves model performance by ensuring all features contribute equally to the model.
4. **Prediction Accuracy**:
   - The model achieves reasonable accuracy but struggles with extreme values (e.g., very heavy cars).

---

## How to Use This Repository
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/Linear-Regression-Homework.git
