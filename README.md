 Multiple Linear Regression - Toyota Corolla Dataset

 📌 Objective
The objective of this project is to build a Multiple Linear Regression (MLR) model to predict the price of Toyota Corolla cars based on various features.

---

 📊 Dataset Description
The dataset contains the following features:

- Age: Age of the car in years  
- KM: Kilometers driven  
- FuelType: Type of fuel (Petrol, Diesel, CNG)  
- HP: Horsepower  
- Automatic: Transmission type (1 = Yes, 0 = No)  
- CC: Engine capacity  
- Doors: Number of doors  
- Weight: Weight of the car  
- Quarterly_Tax  
- Price: Target variable (Car Price in Euros)  

---

🔍 Steps Performed

 1. Data Preprocessing
- Handled categorical variables using Label Encoding  
- Checked for missing values  
- Defined independent (X) and dependent (y) variables  

---

2. Exploratory Data Analysis (EDA)
- Used heatmap to analyze correlation  
- Used pairplot to understand relationships  
- Plotted distributions using histograms  
- Detected outliers using boxplots  
- Visualized categorical data using countplots  
- Analyzed feature relationships using scatter plots  

 Key Insights:
- Age and KM have a negative impact on price  
- HP and Weight have a positive impact on price  
- Diesel cars tend to have slightly higher prices  

---

 3. Model Building
- Applied Multiple Linear Regression  
- Built additional models:
  - Ridge Regression  
  - Lasso Regression  

---

 4. Model Evaluation
- Evaluated models using:
  - R² Score  
  - RMSE (Root Mean Squared Error)  

---

 5. Coefficient Interpretation
- Age: Negative impact → older cars have lower price  
- KM: Negative impact → more driven cars reduce price  
- HP: Positive impact → higher horsepower increases price  
- Weight: Positive impact → heavier cars have higher price  

---

 6. Interview Questions

 What is Normalization & Standardization?
- Normalization scales data between 0 and 1  
- Standardization transforms data to mean = 0 and std = 1  

 How to handle multicollinearity?
- Remove correlated features  
- Use VIF  
- Apply Ridge/Lasso  
- Use PCA  

---

 📈 Models Used
- Linear Regression  
- Ridge Regression  
- Lasso Regression  

---

 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

🚀 Conclusion
The model successfully predicts car prices based on multiple features. Regularization techniques like Ridge and Lasso help improve performance and handle multicollinearity.

---

👨‍💻 Author
Mahesh Kale  
Data Science Student
