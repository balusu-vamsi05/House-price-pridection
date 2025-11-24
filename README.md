# 🏡 House Price Prediction (ML Project)

A complete **Machine Learning end-to-end project** that predicts house prices using regression algorithms. This project covers data preprocessing, feature engineering, model training, evaluation, and deployment-ready structure. It is simple, clean, and perfect for resumes.

---

## 🚀 Project Overview

This project aims to build a reliable **House Price Prediction Model** using machine learning. It helps understand how different features affect the price of a house and predicts the approximate cost using regression models.

The project includes:

* Data loading & preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training (Linear Regression / Random Forest / XGBoost)
* Hyperparameter tuning
* Model Evaluation
* Final predicted output
* Clean and modular code structure

---

## 📂 Folder Structure

```
House-price-prediction/
│── data/
│   └── housing.csv
│── notebooks/
│   └── eda_and_training.ipynb
│── src/
│   ├── data_preprocessing.py
│   ├── train_model.py
│   └── predict.py
│── models/
│   └── model.pkl
│── README.md
│── requirements.txt
│── app.py (optional for deployment)
```

---

## 🧠 ML Workflow

### 1️⃣ Data Preprocessing

* Handling Missing Values
* Removing Outliers
* Categorical Encoding (Label/OneHot)
* Feature Scaling (Standardization/Normalization)

### 2️⃣ Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Price Distribution
* Impact of features on price

### 3️⃣ Model Training

Models included:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### 4️⃣ Model Evaluation Metrics

* R² Score
* MAE – Mean Absolute Error
* RMSE – Root Mean Squared Error

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```
git clone https://github.com/balusu-vamsi05/House-price-pridection.git
cd House-price-pridection
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook (for EDA & training)

```
jupyter notebook
```

### 4. Run Prediction Script

```
python src/predict.py
```

---

## 📊 Example Prediction

```
Input:
Bedrooms: 3
Bathrooms: 2
Area: 1200 sq ft
Location: Bangalore

Model Output:
Predicted Price: ₹ 72,45,000
```

---

## 🌐 Deployment (Optional)

You can deploy using:

* **Streamlit**
* **Flask API**
* **Render / Vercel / AWS**

Example:

```
streamlit run app.py
```

---

## 📝 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
pickle
```

---

## 🙌 Author

**Vamsi Krishna**
Machine Learning Engineer / AI Developer

If you like this project, ⭐ star the repo!
