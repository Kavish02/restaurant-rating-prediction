# 🍽️ Restaurant Rating Prediction (Machine Learning)

## 📌 Overview

This project aims to predict the aggregate rating of restaurants using machine learning techniques based on features such as cost, location, votes, and services.

---

## 🎯 Objective

To build and evaluate regression models that can accurately predict restaurant ratings and identify the most influential factors affecting them.

---

## 📊 Dataset

The dataset contains restaurant-related information such as:

* Votes
* Average Cost for Two
* Price Range
* City
* Online Delivery Availability
* Table Booking Availability
* Aggregate Rating (Target Variable)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed unnecessary columns (Restaurant Name, Address, etc.)
* Handled missing values
* Converted categorical data into numerical format
* Encoded Yes/No values into binary (1/0)

---

### 2️⃣ Exploratory Data Analysis (EDA)

* Visualized rating distribution
* Analyzed relationship between votes and ratings
* Generated correlation heatmap

---

### 3️⃣ Model Building

Implemented the following models:

* Linear Regression
* Decision Tree Regressor

---

### 4️⃣ Model Evaluation

Used the following metrics:

* Mean Squared Error (MSE)
* R² Score

---

### 5️⃣ Key Insights

* Votes have a strong influence on restaurant ratings
* Decision Tree performed better than Linear Regression
* Price range has moderate impact on ratings

---

## 📈 Results

The Decision Tree model achieved better performance compared to Linear Regression, indicating the presence of non-linear relationships in the dataset.

---

## 🚀 Future Improvements

* Implement Random Forest for better accuracy
* Perform hyperparameter tuning
* Deploy the model using Streamlit

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📂 Project Structure

restaurant-rating-prediction/
│── restaurant-rating-prediction.ipynb
│── dataset.csv
│── README.md

---

## 👨‍💻 Author

Kavish Vijan

---

## ⭐ If you found this useful, consider giving it a star!
