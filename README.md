# Logistic Regression on Chronic Kidney Disease Dataset

## Overview  
This repository implements a **logistic regression** model to predict Chronic Kidney Disease (CKD) using a publicly available dataset. The project includes:

- **kidney_disease.csv**: Raw dataset containing patient attributes and CKD status.  
- **Kidney_disease_classification_problem_Rishi.ipynb**: Jupyter notebook demonstrating data processing, exploratory analysis, model training, evaluation, and visualization steps.

---

## Dataset  
The `kidney_disease.csv` file includes features such as:
- Numerical: age, blood pressure, RBC count, WBC count, albumin, sugar levels, etc.
- Categorical: presence of hypertension, diabetes mellitus, coronary artery disease, edema, etc.
- Target label: whether the patient has CKD.

*(Add details about dataset source, number of records, missing values, and attribute descriptions.)*

---

## Installation

Clone this repository and set up your Python environment:

```bash
git clone https://github.com/Rishhi1/Logistic-Regression-on-Chronic-Kidney-Disease-Dataset.git
cd Logistic-Regression-on-Chronic-Kidney-Disease-Dataset
pip install numpy pandas matplotlib seaborn scikit-learn jupyter



Usage
Launch the notebook to explore and replicate the analysis:
jupyter notebook Kidney_disease_classification_problem_Rishi.ipynb
Inside, you'll find sections covering:
Importing libraries (NumPy, pandas, matplotlib, seaborn, scikit-learn)
Loading and inspecting dataset
Handling missing values (drop, imputation, forward/backward fill)
Exploratory Data Analysis (e.g., correlation heatmap)
Data preprocessing (encoding, feature scaling)
Splitting data into train/test sets
Training logistic regression
Evaluating model performance (accuracy, precision, recall, F1-score)
Visualizing results (confusion matrix, ROC curve)



Results
(Highlight key outcomes here, for example:)
Achieved XX % accuracy, with YY % precision and ZZ % recall.
The correlation heatmap identified strongest predictors like blood pressure, albumin levels, RBC count, etc.
(Adjust according to your actual results.)
