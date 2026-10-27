# Heart Disease Prediction Project 

A comprehensive Machine Learning project aimed at predicting the presence and severity level of heart disease based on patient clinical diagnostic features.


# Project Overview
Heart disease is one of the leading causes of health complications worldwide. Early detection can save lives. 
In this project, I used the **UCI Heart Disease Dataset** to build and evaluate predictive models that classify whether a patient has heart disease and determine the severity level on a scale from `0` (normal/healthy) to `4` (severe disease).


# Machine Learning Workflow

# 1. Data Collection & Preprocessing
* Loaded and thoroughly inspected the dataset using **Pandas**.
* Handled missing values (`NaN`s) and handled numerical vs categorical features properly.
* Cleaned and scaled numerical features to optimize model performance.

# 2. Exploratory Data Analysis (EDA)
* Analyzed feature distributions and correlated key indicators such as age, chest pain type (`cp`), resting blood pressure (`trestbps`), serum cholesterol (`chol`), and maximum heart rate achieved (`thalch`).
* Visualized feature correlations using heatmaps and histograms via **Seaborn** & **Matplotlib**.

# 3. Model Training & Evaluation
* Split data into training and test sets using stratified sampling to maintain class ratios.
* Implemented multiple classification models, including **Random Forest Classifier** and **LightGBM**.
* Applied hyperparameter tuning and cross-validation to maximize classification accuracy and prevent overfitting.


# Results

* **Best Performing Models:** Random Forest & LightGBM
* **Overall Accuracy:** **88.40%** 
* **Target Output:** Predicts disease severity stages (`0` = Absence, `1, 2, 3, 4` = Increasing Severity levels).



# Tech Stack & Tools

* **Programming Language:** Python 
* **Data Processing & EDA:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, LightGBM
* **Environment:** Jupyter Notebook


# Repository Structure

* `heart_disease_prediction.ipynb` : Jupyter notebook containing the step-by-step EDA, data cleaning, model training, and evaluation.
* `heart_disease_uci.csv` : The dataset used for training and testing.


# How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Yasmine52/Heart-Disease-Prediction-Proj.git](https://github.com/Yasmine52/Heart-Disease-Prediction-Proj.git)
