[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Shruti-Vijayvargiya/concrete-strength-prediction/blob/main/ML%20Project.ipynb)
# Concrete Compressive Strength Prediction using Machine Learning 🏗️💻

## Project Overview
In civil engineering, determining concrete compressive strength traditionally requires waiting up to 28 days for the material to cure, followed by destructive physical lab testing. This process is time-consuming and expensive.

This project uses **Machine Learning** to predict the compressive strength of concrete instantly based on its component ingredients and age, eliminating the need for immediate physical testing.

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
I tested and trained the data using machine learning regression algorithms.

* **Model Evaluation Metric:** Achieved a high accuracy score ($R^2$) predicting concrete strength instantly.
* **Key Insight:** The composition of cement, water ratios, and the total curing age were found to be the most critical factors in determining the concrete's ultimate strength.

## How to Run This Project
1. Clone this repository or download the files.
2. Open **Anaconda Navigator** and launch **Jupyter Notebook**.
3. Run the `ML Project.ipynb` file. (Ensure `Concrete_Data.csv` is in the same folder).
