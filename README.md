**Work Problem**

The task is to develop a machine learning model for predicting whether individuals have diabetes based on specified characteristics. Before building the model, various data analysis and feature engineering steps need to be undertaken.

**Dataset Story**

The dataset is derived from a larger collection held at the National Institutes of Diabetes-Digestive-Kidney Diseases in the USA. It focuses on a diabetes study involving Pima Indian women aged 21 and older in Phoenix, Arizona. The target variable, "outcome," denotes 1 for a positive diabetes test and 0 for a negative result.

- **Pregnancies:** Number of pregnancies
- **Glucose:** 2-hour plasma glucose concentration in oral glucose tolerance test
- **Blood Pressure:** Blood pressure (mm Hg)
- **Skin Thickness:** Thickness of skin
- **Insulin:** 2-hour serum insulin (mu U/ml)
- **Diabetes Pedigree Function:** Function related to glucose concentration
- **BMI:** Body mass index
- **Age:** Age in years
- **Outcome:** Presence (1) or absence (0) of the disease

**Project Tasks**

**TASK 1: EXPLORATORY DATA ANALYSIS**

* **Step 1:** Examine the overall dataset.

* **Step 2:** Identify numerical and categorical variables.

* **Step 3:** Analyze numerical and categorical variables.

* **Step 4:** Analyze the target variable (mean of outcome according to categorical variables, mean of outcome according to the target variable, average of numeric variables).

* **Step 5:** Identify and analyze outlier observations.

* **Step 6:** Perform missing observation analysis.

* **Step 7:** Conduct correlation analysis.

**TASK 2: FEATURE ENGINEERING**

* **Step 1:** Address missing and outlier values. Treat observations with 0 values in variables like Glucose and Insulin as NaN, considering these cannot be valid.

* **Step 2:** Introduce new variables if needed.

* **Step 3:** Implement encoding operations.

* **Step 4:** Standardize numeric variables.

* **Step 5:** Create a machine learning model.
