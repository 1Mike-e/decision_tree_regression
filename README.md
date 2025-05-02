# Decision Tree Regression - Position Salary Prediction

This project demonstrates how to use **Decision Tree Regression** to predict salaries based on position levels using Python and the `scikit-learn` library.

## 📂 Dataset

The dataset used is `Position_Salaries.csv`, which should contain the following columns:

- `Position` (e.g., Business Analyst, Manager, etc.)
- `Level` (numerical representation of position)
- `Salary` (target variable)

The model uses the `Level` column as the feature (`X`) and the `Salary` column as the target (`y`).

## 🧠 Model

A **Decision Tree Regressor** is trained on the entire dataset to learn the relationship between position level and salary.

## 📈 Visualization

A high-resolution plot is generated to visualize:
- The actual data points (in red)
- The predicted salaries by the model (in blue)

## 🚀 Usage

### Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn
