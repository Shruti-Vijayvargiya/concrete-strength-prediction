# Concrete Compressive Strength Prediction using Machine Learning 🏗️💻

## Project Overview
In civil engineering, determining concrete compressive strength traditionally requires waiting up to 28 days for the material to cure, followed by destructive physical lab testing. This process is time-consuming and expensive.

This project uses **Machine Learning** to predict the compressive strength of concrete instantly based on its component ingredients and age, eliminating the need for immediate physical testing.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Shruti-Vijayvargiya/concrete-strength-prediction/blob/main/ML%20Project.ipynb)

*Note: If GitHub's built-in notebook viewer shows a "File Not Found" or rendering error, click the "Open In Colab" badge above to view the complete interactive code and charts instantly.*

## Dataset & Properties
The model analyzes the following properties of the concrete mix:
* **Cement** (kg in a m³ mixture)
* **Blast Furnace Slag** (kg in a m³ mixture)
* **Fly Ash** (kg in a m³ mixture)
* **Water** (kg in a m³ mixture)
* **Superplasticizer** (kg in a m³ mixture)
* **Coarse Aggregate** (kg in a m³ mixture)
* **Fine Aggregate** (kg in a m³ mixture)
* **Age** (Number of days cured, e.g., 1 to 365)

## Tech Stack & Tools
* **Environment:** Anaconda (Jupyter Notebook)
* **Language:** Python
* **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## Model & Results
I evaluated and compared three different machine learning regression models to find the most accurate predictor:
1. **Linear Regression** (Baseline model)
2. **Decision Tree Regressor**
3. **Random Forest Regressor**

* **Evaluation Metrics:** The models were trained and benchmarked using Mean Absolute Error (MAE), Mean Squared Error (MSE), and the $R^2$ Score.
* **Key Insight:** The composition of cement, water ratios, and the total curing age were found to be the most critical features in determining the concrete's ultimate strength.

## How to Run This Project
1. Clone this repository or download the files.
2. Open **Anaconda Navigator** and launch **Jupyter Notebook**.
3. Run the `ML Project.ipynb` file. (Ensure your dataset file is in the same folder).
