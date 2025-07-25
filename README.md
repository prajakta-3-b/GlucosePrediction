# Glucose Level Prediction using Machine Learning

This project aims to predict abnormal glucose levels using various health indicators from the **Framingham Heart Study** dataset. It involves data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and result visualization.


## Dataset

* **Source**: `framingham.csv`
* **Description**: Contains patient records with features like age, BMI, blood pressure, cholesterol, smoking status, and glucose levels.

## Project Workflow

1. **Data Import and Exploration**
    * Loaded the Framingham dataset
   * Explored distributions and correlations

2. **Data Cleaning**

   * Handled missing/null values
   * Corrected data formats

3. **Exploratory Data Analysis (EDA)**

   * Visualized glucose distribution
   * Analyzed health factors affecting glucose levels (e.g., BMI, age)

4. **Feature Selection & Engineering**

   * Removed irrelevant features
   * Created and scaled important features

5. **Model Training**

   * Trained classification models:

     * Logistic Regression
     * Decision Tree
     * Random Forest

6. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-Score
   * Confusion Matrix & ROC-AUC curve

7. **Prediction & Insights**

   * Predicted abnormal glucose levels
   * Identified important health indicators

8. **Visualization**

   * Plotted feature importance
   * Compared model performances

## Technologies Used

* Python (Pandas, NumPy)
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

## Results

* Achieved competitive performance across models
* Random Forest showed the highest accuracy
* Key indicators: BMI, Age, Cholesterol, Blood Pressure

