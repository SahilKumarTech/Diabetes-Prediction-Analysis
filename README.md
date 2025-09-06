# Diabetes Prediction Analysis
A machine learning project for predicting diabetes using logistic regression. Includes data preprocessing, exploratory data analysis, and model evaluation.

This project focuses on predicting the onset of diabetes using the Pima Indians Diabetes Dataset. The workflow includes data cleaning, exploratory data analysis (EDA), and building a logistic regression model for classification.

## Dataset
The dataset used is `diabetes.csv`, which contains diagnostic measurements for 768 female patients of Pima Indian heritage. The target variable is `Outcome` (0 = no diabetes, 1 = diabetes).

## Features
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target)

## Project Steps
1. **Data Loading and Inspection**
2. **Handling Missing Values** (replace zeros with mean)
3. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap
   - Descriptive statistics
4. **Model Building**
   - Logistic Regression
5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
Run the Jupyter notebook `diabetes_project.ipynb` to execute the entire pipeline.

## Results
The model's performance is evaluated using accuracy and other classification metrics. Detailed results can be found in the notebook.

## License
This project is open-source and available under the MIT License.
