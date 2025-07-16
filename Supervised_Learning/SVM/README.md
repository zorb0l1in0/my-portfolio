# 🤖 Classification with Support Vector Machines (SVM)

This project applies Support Vector Machine (SVM) classification techniques to predict customer responses to a "gold" membership offer made via phone calls. The goal is to build a predictive model based on customer demographic and behavioral data.


## 🧭 Project Overview

The dataset comes from a supermarket planning to offer a 20% discount through a $499 membership to **active** customers only.  
The **target variable** is `"Respuesta"`:  
- `1` = accepted the offer  
- `0` = declined the offer



## 🧱 Project Structure

### 🧹 Preprocessing and Cleaning

- Analysis of numerical and categorical variables (types, cardinality, missing values).
- Removal of irrelevant variables (e.g., `ID`).
- Conversion of `Dt_Customer` column from object to datetime.
- Imputation of missing `Income` values grouped by education level.
- Correction of inconsistent categorical values (e.g., "Alone" replaced with "Single" in `Marital_Status`).

### 📊 Exploratory Data Analysis

- Visualization of distributions using histograms and boxplots.
- Detection of **outliers** and variable skewness.
- Standardization of numerical features (important for SVM performance).

### 🧪 Feature Engineering

- One-hot encoding for categorical variables.
- Creation of new features based on age, total spending, and customer habits.

### 🤖 SVM Model Training

- Splitting the dataset into training and test sets.
- Training an SVM model (`SVC`) with different kernels (linear, RBF, polynomial).
- Hyperparameter tuning using `GridSearchCV`.

### 📈 Performance Evaluation

- Evaluation on both training and test sets using metrics such as:
  - **Accuracy**
  - **Confusion Matrix**
  - **Classification Report**
- Visualizations: ROC curve and confusion matrix heatmap.


## 🛠️ Tools and Technologies

- **Python**
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Preprocessing, SVM, metrics, model tuning


## 🧪 How to Use

1. Clone the repository
2. Install the dependencies
3. Run the notebook
   

## 💡 Insights and Results
- Best accuracy was achieved using the RBF kernel with tuned C and gamma values.
- Key predictive features included income, purchase frequency, and age.
- Preprocessing (especially handling outliers and scaling) had a strong impact on performance.


## 🎯 Applications
This classification approach is useful for:
- Targeted marketing campaigns
- Customer segmentation
- Optimizing promotional strategies

## 👤 Author
Francesca Tuninetti
www.linkedin.com/in/tuninettifrancesca



## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
