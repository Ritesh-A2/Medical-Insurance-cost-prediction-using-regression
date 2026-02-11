#  Medical Insurance Cost Prediction
### *Custom Regression Suite Built using numpy*
## Team Members
*  **Ritesh Chourasia**
* **Pawan Kumar**
*  **Rajdeep Ranjan**

---

##  Dataset Details

The dataset used for this project is the **Medical Insurance Dataset**, sourced from [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance). It consists of 1,338 individual records and provides a real-world look at how demographic and health factors drive insurance costs.

### **Dataset Statistics**
* **Total Samples:** 1,338 records
* **Total Features:** 6 Input features + 1 Target variable
* **Missing Values:** None (Cleaned)

### **Feature Breakdown**
| Feature | Type | Description |
| :--- | :--- | :--- |
| **Age** | Numerical | Age of primary beneficiary. |
| **BMI** | Numerical | Body mass index ($kg/m^2$). |
| **Children** | Numerical | Number of children/dependents covered. |
| **Sex** | Categorical | Gender (Encoded: `0` / `1`). |
| **Smoker** | Categorical | Smoking status (Encoded: `0` / `1`). |
| **Region** | Categorical | US residential area (Encoded: `0`, `1`, `2`, `3`). |
| **Charges** | **Target** | Individual medical costs billed by health insurance. |

---


##  Objective
The goal of this project is to implement, analyze, and compare various **Linear Regression** models to predict medical insurance charges. 

> **Note:** regression models are implemented using NumPy.
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


