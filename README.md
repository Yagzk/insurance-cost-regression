# insurance-cost-regression
The goal of this project is to build a **regression model** that predicts **insurance costs (charges)** based on individuals’ demographic and physical characteristics.  
The study focuses on comparing **Linear Regression** and **Polynomial Regression** models.

The dataset includes variables such as age, gender, BMI, number of children, smoking status, and region.

---

### Dataset & Features
Main features used in the dataset:

- **Age:** Age of the insured person  
- **Sex:** Gender (male / female)  
- **BMI:** Body Mass Index  
- **Children:** Number of dependents  
- **Smoker:** Smoking status  
- **Region:** Residential area  
- **Charges:** Insurance cost (target variable)

---

### What Was Done

#### 1. Data Loading & Exploration
- Loaded the dataset using pandas  
- Checked data types, dataset shape, and missing values  
- Explored the overall structure of the data  

#### 2. Data Preprocessing
- Converted categorical variables into numerical format  
- Selected relevant features for regression modeling  

#### 3. Modeling
The following models were implemented:

- **Linear Regression**
- **Polynomial Regression**

For polynomial regression:
- Feature expansion was applied using `PolynomialFeatures`

#### 4. Training & Testing
- The dataset was split into training and test sets  
- Models were trained on training data and evaluated on test data  

#### 5. Evaluation Metrics
Model performance was evaluated using:

- **Mean Squared Error (MSE)**
- **R² Score**

Results of linear and polynomial regression models were compared and interpreted.

---

### Conclusion
The results show that polynomial regression can capture **non-linear relationships** better than linear regression in some cases, but it may also lead to **overfitting** when higher-degree polynomials are used.  
This highlights the importance of choosing the right model complexity for regression problems.

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

---

## Notes
This project was developed as part of a machine learning assignment to demonstrate **regression modeling, feature transformation, and model evaluation** techniques.
