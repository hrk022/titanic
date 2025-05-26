# Titanic Survival Prediction 🚢

A data science project using the Titanic dataset to predict passenger survival using classification models. This notebook includes all essential steps in a standard machine learning pipeline, from data cleaning to preprocessing and visualization.

---

## 📁 Dataset

The dataset used is the classic **Titanic** dataset, available from [Kaggle's Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

---

## ✅ Steps Performed

### 1. 📥 Import Dataset & Explore
- Loaded the dataset using `pandas`.
- Explored the dataset shape, column names, data types, and missing values.
- Basic visualizations of distributions using `seaborn` and `matplotlib`.

### 2. 🔧 Handle Missing Values
- Imputed missing values in numerical columns using **mean** or **median**.
- Imputed categorical columns (like `Embarked`) using **mode** or forward-fill as appropriate.

### 3. 🧠 Encode Categorical Variables
- Converted categorical features like `Sex`, `Embarked`, and `Pclass` into numerical values using:
  - **Label Encoding** or
  - **One-Hot Encoding**

### 4. ⚖️ Normalize & Standardize
- Applied **StandardScaler** to scale numerical features like `Age` and `Fare` to bring them to a similar scale for better model performance.

### 5. 📊 Visualize & Remove Outliers
- Plotted **boxplots** for `Age` and `Fare` to detect outliers.
- Removed outliers using the **IQR method** to improve model robustness.
