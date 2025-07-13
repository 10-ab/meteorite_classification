
# ☄️ Meteorite Landing Classification using Machine Learning

A machine learning project that classifies meteorites based on physical and geospatial features using NASA's meteorite landings dataset available on Kaggle.

---

## 📌 Project Overview

This project builds a supervised machine learning pipeline to classify meteorites (`recclass`) based on their mass, year, and landing coordinates. It includes data preprocessing, feature engineering, model training, and evaluation using scikit-learn.

---

## 📊 Dataset

- **Source:** [NASA Meteorite Landings on Kaggle](https://www.kaggle.com/datasets/nasa/meteorite-landings)
- **Features used:**
  - `mass (g)`
  - `year`
  - `reclat` (latitude)
  - `reclong` (longitude)
  - `recclass` (target)

---

## 🧠 Tech Stack

- **Python**
- **Pandas, NumPy** – for data preprocessing
- **Matplotlib, Seaborn** – for exploratory data analysis (EDA)
- **scikit-learn** – for model building (Random Forest, Logistic Regression)

---

## ⚙️ Workflow

1. **Data Cleaning:**
   - Removed entries with missing or invalid values (e.g., null years, locations)
   - Parsed year from date field, filtered outliers

2. **Feature Engineering:**
   - Normalized mass, encoded class labels, filtered rare classes

3. **Model Training & Evaluation:**
   - Trained Random Forest and Logistic Regression models
   - Evaluated using accuracy, confusion matrix, and classification report

---

## 📈 Results

- Achieved **~85% accuracy** using Random Forest on cleaned dataset
- Identified most common and high-mass meteorite classes

---

## 🚀 How to Run

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/meteorite-classification.git
cd meteorite-classification
