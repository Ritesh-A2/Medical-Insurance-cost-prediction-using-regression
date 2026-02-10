#  Medical Insurance Cost Prediction
### *Custom Regression Suite Built from Scratch*

##  Objective
The goal of this project is to implement, analyze, and compare various **Linear Regression** models to predict medical insurance charges. 

> **Note:** All regression models are implemented **from scratch** using NumPy. No pre-built machine learning libraries (like scikit-learn) were used for the algorithm logic.

---

##  Problem Statement
Predict medical insurance costs (`charges`) based on personal and health-related attributes. We evaluate how different techniques—from simple gradients to L1/L2 regularization—handle the variance in healthcare data.

---

##  Dataset Description
* **Name:** Medical Insurance Dataset (Kaggle)
* **Target Variable:** `charges` (Continuous)
* **Key Features:** `age`, `bmi`, `children`, and encoded categorical variables.
* **Status:** Cleaned; no missing values; manual numerical encoding applied.

---

##  Tools & Technologies
* **Language:** Python 
* **Platform:** Google Colab
* **Libraries:** * `NumPy` (Math & Matrix operations)
    * `Pandas` (Data handling)
    * `Matplotlib` / `Seaborn` (Visualizations)

---

##  Methodology
The project follows a structured lifecycle:

1. **Exploratory Data Analysis (EDA):** Heatmaps and distribution plots.
2. **Simple Linear Regression:** Baseline model using a single feature.
3. **Multiple Linear Regression:** Multi-feature model using **Gradient Descent**.
4. **Polynomial Regression:** Capturing non-linear relationships.
5. **Regularization:** * **Ridge (L2):** Reducing model variance.
    * **Lasso (L1):** Feature importance and shrinkage.
6. **Model Diagnostics:** Residual analysis and assumption validation.

---

##  Evaluation Metrics
All metrics were calculated manually using the following formulas:

| Metric | Purpose |
| :--- | :--- |
| **MSE** | Mean Squared Error |
| **RMSE** | Root Mean Squared Error |
| **R² Score** | Coefficient of Determination |

---

##  Key Observations
* **Age & BMI:** Show the strongest positive correlation with insurance charges.
* **Polynomial Fit:** Significantly improved performance over standard linear paths.
* **Regularization:** Ridge stabilized coefficients while Lasso helped in identifying the most impactful features.

---

##  Repository Contents
*  `insurance_model.ipynb` – Full implementation notebook.
*  `insurance.csv` – Raw dataset.
*  `Plots/` – Visualization outputs.

---

##  How to Run
1. Clone the repository.
2. Upload `insurance_model.ipynb` to **Google Colab**.
3. Ensure `insurance.csv` is in the same directory.
4. Run all cells to see the scratch implementation in action.
