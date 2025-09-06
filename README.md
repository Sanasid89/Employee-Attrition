# Employee-Attrition
# 📊 Employee Attrition Analysis 📊

This notebook analyzes employee attrition and builds predictive models.

## 📝 Table of Contents

1. [Data Loading & Exploration](#data-loading-initial-exploration)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Training & Evaluation](#model-training-and-evaluation)
5. [Saving Model & Data](#saving-the-model-and-processed-data)
6. [Future Scope](#future-scope)

---

## 💾 Data Loading & Exploration <a name="data-loading-initial-exploration"></a>

Loads the dataset and performs initial checks like displaying data, checking for nulls and duplicates, and showing descriptive statistics.

## 📈 Exploratory Data Analysis (EDA) <a name="exploratory-data-analysis-eda"></a>

Visualizes relationships between features and 'Attrition'. Includes plots for Department, Education Field, Job Role, Gender, and a correlation heatmap. Also calculates attrition rates by gender.

## 🔧 Data Preprocessing <a name="data-preprocessing"></a>

Converts categorical data to numerical format using Label Encoding.

## 🤖 Model Training & Evaluation <a name="model-training-and-evaluation"></a>

Trains and evaluates Logistic Regression and Random Forest models. Addresses target variable imbalance using Random OverSampling. Reports accuracy, f1-score, MAE, and confusion matrices.

## 💾 Saving Model & Data <a name="saving-the-model-and-processed-data"></a>

Saves the trained Random Forest model and processed data using pickle.

## ✨ Future Scope ✨ <a name="future-scope"></a>

- Explore other resampling techniques (SMOTE, ADASYN).
- Feature Engineering to create new features.
- Hyperparameter tuning for models.
- Evaluate other models (SVM, Gradient Boosting, Neural Networks).
- Analyze feature importance.
- Improve model interpretability (SHAP, LIME).
- Consider model deployment.
- Collect more data.
- Perform time-series analysis if applicable.
