# Abed Alrhman - Data Science Portfolio
Welcome to my data science portfolio! This site hosts my journey, skills, and projects developed throughout the Data Science course.

---

## Final Project: Ford Focus Price Prediction System

### 1. Project Description
The automotive secondary market experiences significant price volatility influenced by factors such as vehicle age, continuous mileage degradation, trim levels, and transmission configurations. This project aims to build a robust predictive regression model that helps dealerships and private buyers determine the fair market value of used Ford Focus cars. By accurately mapping these variables, the system minimizes pricing errors and optimizes inventory turnover.

### 2. Dataset Information
The project utilizes a verified historical dataset consisting of real-world transactions of used vehicles. 
* **Key Features Evaluated:** `year`,`model`,`mileage`, `color`,`transmission`.
* **Target Variable:** `price`.

### 3. Tools & Methods Used
* **Programming Language:** Python 3.13
* **Data Manipulation & Visualization:** Pandas, Matplotlib, Seaborn
* **Machine Learning Framework:** Scikit-Learn
* **Architecture:** Institutional-grade Machine Learning **Pipeline** (integrating text processing via `OneHotEncoder` and predictive modeling via `LinearRegression`) to prevent data leakage during scaling and testing.

### 4. Current Progress & Validation Results (Week 2)
* **Exploratory Data Analysis:** Conducted full statistical profiling (`info()` and `describe()`) showing zero missing values across the 150 unique records.
* **Key Inferences:** Visual plotting confirmed a strong inverse correlation between mileage accumulation and market value, heavily adjusted by the production year factor.
* **Model Validation:** The data was partitioned into an 80% training set and a 20% test set.
* **Evaluation Metric:** The model achieved a highly accurate **Mean Absolute Error (MAE) of $1,098.13**, indicating that the average prediction deviates by only around $1,100 from the true vehicle valuation.

---
*Developed as part of the Final Project requirements.*
