# 🤖 Recommender Systems Project

This project explores three distinct methodologies to build robust recommender systems: Collaborative Filtering, Content-Based Filtering using TF-IDF, and a Hybrid approach integrating Deep Learning techniques.

## 🧭 Project Overview

This project aims to evaluate and compare the following recommender approaches:

1. **Collaborative Filtering:** Recommendations are generated based on similarities in user-item interactions, identifying patterns across user preferences.
2. **Content-Based Filtering (TF-IDF):** Recommendations leverage textual analysis of item features through Term Frequency-Inverse Document Frequency (TF-IDF).
3. **Hybrid Deep Learning Approach:** Combines collaborative filtering and content-based features using embedding layers within neural network architectures to capture complex patterns and enhance recommendation performance.

## 🧱 Project Structure

### 👥 Collaborative Filtering

* **Data Preparation:** User-item interaction matrices preprocessing.
* **Similarity Measures:** User-based and item-based similarity computations.
* **Recommendations:** Personalized item recommendations based on computed similarities.

### 🧾 Content-Based Filtering (TF-IDF)

* **Data Preprocessing:** Textual feature extraction and cleaning.
* **Feature Engineering:** TF-IDF transformation for item characterization.
* **Recommendation Generation:** Content similarity-based recommendations.

### 🧠 Hybrid Deep Learning Approach

* **Data Preprocessing:** Unified data preparation integrating collaborative and content-based features.
* **Model Development:** Design and training of neural networks using embedding layers and dense architectures.
* **Evaluation and Analysis:** Model performance assessment using metrics such as RMSE, precision, recall, and F1-score.

## 🛠️ Tools and Technologies

* **Python**

  * `pandas` for data manipulation
  * `numpy` for numerical computations
  * `scikit-learn` for collaborative filtering and TF-IDF
  * `TensorFlow/Keras` for deep learning model implementation
  * `matplotlib` and `seaborn` for visualization

## 🔄 How to Use

* Clone or download the repository.
* Install the required Python dependencies.
* Execute the Jupyter notebooks provided to reproduce the recommender models and visualize results.

## 💡 Insights and Results

* Demonstrated the effectiveness of each recommender system approach.
* The hybrid deep learning method showed superior capability by leveraging both collaborative and content-based insights.

## 🎯 Applications

These recommender systems are beneficial for:

* E-commerce platforms seeking personalized product recommendations.
* Media streaming services for targeted content suggestions.
* Any domain where tailored recommendations improve user experience and engagement.

## 👤 Author

* \[Francesca Tuninetti]
* \[www.linkedin.com/in/tuninettifrancesca]

## 	📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
