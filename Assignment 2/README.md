# Linear Regression from Scratch - Medical Price Dataset

This project demonstrates how to implement Linear Regression from scratch using only NumPy, Pandas, and Matplotlib.

---

-> Dataset

- File: Medical Price Dataset.csv
- Target Variable: charges
- Features:
  - age: Age of the primary beneficiary
  - sex: Gender (male, female)
  - bmi: Body Mass Index
  - children: Number of dependents covered
  - smoker: Smoking status (yes, no)
  - region: Residential area in the US (northeast, northwest, southeast, southwest)

---

-> Project Highlights

Supervised Learning Objective  
- Predict medical charges using Linear Regression

Implementation Details  
- Linear regression algorithm built from scratch (no scikit-learn)  
- Encoding for categorical variables  
- Feature normalization (mean = 0, std = 1)

---

-> Workflow

1. Data Loading  
   - Load the dataset using Pandas

2. Exploratory Data Analysis  
   - Check structure, data types, and missing values

3. Data Preprocessing  
   - One-hot encode categorical features (sex, smoker, region)  
   - Normalize numerical features using z-score scaling

4. Model Implementation  
   - Custom functions for:
     - linear_regression_fit: Gradient descent  
     - linear_regression_predict: Prediction

5. Training  
   - Train using 1000 epochs with a learning rate of 0.01

6. Evaluation  
   - Calculate:
     - Mean Squared Error (MSE)  
     - R-squared score (R²)

7. Visualizations  
   - Cost vs Epochs  
   - Charges vs Age (colored by smoker)  
   - BMI vs Charges  
   - Histogram of charges  
   - Actual vs Predicted charges

---

-> Sample Plots

- Cost Function Over Time  
- Age vs Charges (Red = Smokers, Green = Non-Smokers)  
- BMI vs Charges  
- Distribution of Charges

