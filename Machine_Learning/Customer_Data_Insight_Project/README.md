# 🤖 Customer Data Insight Project

This project focuses on analyzing customer behavior data from a supermarket chain to predict customer responses to premium membership campaigns. The pipeline includes comprehensive data cleaning, feature engineering, supervised and unsupervised machine learning techniques, and detailed model evaluation.

---

## 🧭 Project Overview

The primary goal of this project is to develop predictive models that identify customers likely to accept a premium membership offer. The dataset includes demographic details, spending patterns, purchase history, and previous campaign responses.

**Target Variable:**

* `Response`:

  * `1`: Customer accepted the membership offer.
  * `0`: Customer declined the offer.

---

## 🧱 Project Steps

### 🔍 Data Exploration

* Initial data load and inspection (data types, missing values, cardinality).
* Summary statistics to understand distributions and detect anomalies.

### 🧹 Data Cleaning

* Removal of irrelevant features (e.g., customer IDs).
* Standardization of categorical variables (e.g., merging synonyms such as "Single" and "Alone").
* Conversion of date fields (e.g., `Dt_Customer`) to datetime format.
* Group-wise imputation for missing income values based on education levels.

### 📊 Exploratory Data Analysis

* Visualization of feature distributions using histograms and boxplots.
* Identification of skewed variables and outliers.
* Correlation analysis between numeric features to identify multicollinearity.

### 🧪 Feature Engineering

* Creation of customer seniority (months since first purchase).
* Derivation of total spending and spending shares by product category.
* Encoding categorical variables (one-hot encoding and ordinal encoding).
* Outlier management using the IQR method.
* Feature scaling with StandardScaler or RobustScaler.

### ⚖️ Handling Class Imbalance

* Utilization of SMOTENC for oversampling mixed numeric and categorical features.
* Alternative approaches include class weights for algorithms supporting it.

### 🤖 Supervised Learning

* Model training using Random Forest, Decision Tree, KNN, and Gaussian Naive Bayes.
* Cross-validation and hyperparameter tuning with GridSearchCV.
* Evaluation using Accuracy, Precision, Recall, F1 Score, ROC-AUC, and confusion matrices.

### 📈 Unsupervised Learning (Segmentation)

* Application of PCA for dimensionality reduction.
* K-Means clustering to identify distinct customer segments.
* Profiling segments based on spending patterns and response rates.

---

## 🛠️ Tools & Technologies

* **Python:**

  * Data manipulation: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`
  * Machine Learning: `scikit-learn`, `imbalanced-learn`
---

## 🧪 How to Use

- Clone the Repository
- Install dependencies
- Run the Jupiter notebook


---

## 📊 Key Insights & Results

* The Random Forest model typically provides the best balance of predictive performance and interpretability.
* Key predictive features often include total spend, income, seniority, and family size.
* Segmentation identifies distinct customer groups useful for tailored marketing campaigns.

---

## 🎯 Applications

* Enhancing customer targeting and personalization for membership offers.
* Optimizing marketing ROI by prioritizing high-propensity leads.
* Informing strategic marketing initiatives through segment insights.

---

## 👤 Author

**Francesca Tuninetti**
[LinkedIn](https://www.linkedin.com/in/tuninettifrancesca)

---

## 📄 License

This project is released under the **MIT License**. See the LICENSE file for details.

