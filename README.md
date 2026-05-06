# 🏠 House Price Prediction with Clustering

## 📌 Overview

This project builds a machine learning system to predict house prices using regression and enhances it with clustering to categorize properties into market segments. The model not only estimates price but also classifies houses as Budget, Mid-range, or Premium.

---

## 🚀 Features

* Predict house prices using Linear Regression
* Segment houses using K-Means Clustering
* Visualize model performance and data insights
* Classify properties into meaningful categories
* Custom input prediction (user-defined house)

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📊 Dataset

The dataset contains structured housing features such as:

* Area
* Number of bedrooms
* Number of bathrooms
* Floors
* Age of the house
* Location score

Target variable:

* Price

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Checked structure and cleaned data

### 2. Clustering (Unsupervised Learning)

* Applied K-Means clustering
* Grouped houses into 3 segments
* Mapped clusters to:

  * Budget
  * Mid-range
  * Premium

### 3. Regression (Supervised Learning)

* Used Linear Regression model
* Split data into training and testing sets
* Trained model on housing features

### 4. Evaluation

* Used Mean Absolute Error (MAE)
* Compared predicted vs actual values

### 5. Visualization

* Scatter plot (Actual vs Predicted)
* Cluster visualization
* Bar graph (Average price by category)

---

## 📈 Results

* The model successfully predicts house prices with reasonable accuracy
* Clustering provides clear segmentation of properties
* Visualization helps interpret model performance and trends

---

## 🔮 Sample Output

* Predicted Price: ₹7,200,000
* Category: Premium

---

## 📌 Future Improvements

* Add more features (location coordinates, amenities)
* Use advanced models (Random Forest, XGBoost)
* Deploy as a web application (Streamlit)
* Improve clustering using more features

---

## 💡 Conclusion

This project demonstrates how supervised and unsupervised learning can be combined to build a more insightful and practical machine learning solution for real-world applications.

---

