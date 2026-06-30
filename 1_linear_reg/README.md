# Canada Per Capita Income Prediction 🇨🇦📉

A single-variable linear regression model built using Python to analyze historical Canadian economic data and forecast net national income per capita. This project demonstrates foundational concepts in machine learning, data visualization, and matrix dimensionality constraints.

---

##  Key Takeaways & Project Metrics

* **Model Framework:** Scikit-Learn (`linear_model.LinearRegression`)

* **2020 Income Prediction:** **$41,288.69**

---

##  Visualizing the Trend

Real-world economic data is rarely a perfect straight line. As shown in the scatter plot below, the data drops significantly during macro-economic shifts (such as the 2008 global financial crisis). 

The linear regression model cuts through this "noise" by finding a line of best fit—acting as a rigid mathematical compromise to capture the long-term, overarching trajectory.



---

##  Important Core Concepts Explored

### 1. The 2D Requirement for Features ($X$)
A crucial design element of `scikit-learn` is that independent variables ($X$) must always be formatted as a 2-dimensional grid (e.g., `df[['year']]`), even when using only a single feature. This structural standard ensures the data is inherently prepared to scale seamlessly into **Multiple Linear Regression** columns (like adding GDP, population, or employment rates).

### 2. The 1D Target ($y$)
Conversely, the target variable ($y$) representing the predicted outcome remains a simple, flat 1-dimensional list (e.g., `df['per capita income (US$)']`), as the model only maps out a single response per observation row.

---

