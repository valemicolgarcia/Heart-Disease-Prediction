# Heart-Disease-Prediction Project

This repository contains a machine learning project focused on predicting the risk of heart disease based on medical data. Various data analysis techniques and classification algorithms are implemented to identify the most influential factors contributing to the development of heart disease.

### Project Overview
The main objective of this project is to build predictive models that detect the risk of heart disease using data that includes medical indicators and lifestyle habits. Through different stages, such as data cleaning, exploratory analysis, and model training, the goal is to develop a tool that can help predict health risks.

# Project Structure


### 1.  Hypothesis and Objective
We hypothesize that lifestyle and medical factors (age, blood pressure, cholesterol, etc.) influence heart disease risk. The aim is to build a model identifying high-risk individuals.

### 2. Data Acquisition and Preparation
Medical data was cleaned, handling missing values and duplicates. Categorical variables were transformed for model compatibility.

### 3. Data Analysis
- **Univariate Analysis:** Understanding each variable's distribution.
- **Bivariate Analysis:** Exploring key relationships like blood pressure and heart disease risk.

### 4. Pre-training Steps
- **Class Balancing:** Applied oversampling to balance the dataset.
- **PCA Analysis:** Reduced dimensionality to improve model efficiency.

### 5. Model Training
Several classification models were trained to predict risk:

- **Decision Tree**
- **Logistic Regression**
- **Random Forest**
- **XGBoost**
  
  
### 6. Validation and Optimization
- **Cross-Validation:** Stratified KFold was used to perform cross-validation and ensure robust model evaluation.
- **Hyperparameter Optimization:** Fine-tuning of each model's hyperparameters to maximize performance.

### 7. Model Comparison
After training and validating the models, results were compared using metrics like accuracy, recall, and F1-score. The best-performing model was selected for heart disease risk prediction.


### Technologies Used
- Python for all processing and analysis.

Libraries:
- `Pandas` and `NumPy` for data manipulation.
- `Matplotlib` and `Seaborn` for visualization.
- `Scikit-learn` for machine learning algorithms.
- `XGBoost` for boosting models.

### How to Run the Project

1. Clone the repository:
```
git clone https://github.com/user/heart-disease-prediction.git
```
3. Install dependencies:
```
pip install -r requirements.txt

```
5. Run the Jupyter notebook to explore the analysis and results


