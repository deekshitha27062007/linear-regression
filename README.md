# linear-regression
 Task 3: Linear Regression - AI & ML Internship

 Objective
To implement and understand **Simple** and **Multiple Linear Regression** using the Housing Price Prediction dataset. The goal is to build models that predict house prices based on various features, evaluate them using regression metrics, and interpret the model coefficients.

---

 Dataset
**Housing Price Prediction Dataset**  
Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

Features include:
- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Furnishing Status (encoded)

---

##  Tools & Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

 What I Did

###  Data Preprocessing
- Loaded CSV dataset using `pandas`.
- Converted categorical column `furnishingstatus` into numerical format.
- Handled basic cleaning if required.

### Model Building
- **Simple Linear Regression:** Predicted house price using only `area`.
- **Multiple Linear Regression:** Used multiple features (`area`, `bedrooms`, `bathrooms`, `stories`, `parking`).

###  Model Evaluation
- Evaluated using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

###  Visualization
- Plotted regression line for **Simple Linear Regression** using `matplotlib`.

###  Coefficient Interpretation
- Displayed and interpreted feature weights (coefficients) in multiple regression.



###  Simple Linear Regression
- **Feature:** Area
- **MAE:** *your_value*
- **MSE:** *your_value*
- **R² Score:** *your_value*

###  Multiple Linear Regression
- **Features:** Area, Bedrooms, Bathrooms, Stories, Parking
- **MAE:** *your_value*
- **MSE:** *your_value*
- **R² Score:** *your_value*

> Replace *your_value* with actual output values from your script.

---

##  Key Learnings
- How linear regression models make predictions.
- When and why to use MAE vs MSE.
- The importance of R² in evaluating regression models.
- How to interpret regression coefficients.
- Visualizing regression lines and actual data points.

---




