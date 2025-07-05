# 📱 Google Playstore App Rating Prediction

This project is focused on analyzing and predicting app ratings on the Google Play Store using Exploratory Data Analysis (EDA) and a Machine Learning model (Random Forest Regressor). The dataset includes various attributes of apps such as category, size, installs, reviews, type, and more.

---

## 🎯 Objective

To clean, explore, and analyze Google Play Store data and build a machine learning model that predicts an app's rating based on features like installs, reviews, type, size, category, and price.

---

## 🧾 Dataset

- **Source:** [Kaggle - Google Play Store Apps Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Features:**
  - `App`: App name  
  - `Category`: App category  
  - `Rating`: User rating  
  - `Reviews`: Number of reviews  
  - `Size`: App size (MB/kB)  
  - `Installs`: Number of installs  
  - `Type`: Free or Paid  
  - `Price`: Price of the app  
  - `Content Rating`: Target audience  
  - `Genres`: App genres  
  - `Last Updated`, `Current Ver`, `Android Ver`: Metadata

---

## 📌 Technologies Used

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest)
- Label Encoding

---

## 📊 Steps Performed

### 🔹 1. Data Cleaning
- Removed missing and invalid rows
- Converted data types (Reviews, Size, Price, Installs)
- Encoded categorical variables

### 🔹 2. Exploratory Data Analysis (EDA)
- Distribution of ratings
- Free vs Paid apps
- Most popular categories
- Content rating breakdown
- Correlation between installs, reviews, and ratings

### 🔹 3. Machine Learning
- Feature selection
- Label encoding
- Trained **Random Forest Regressor**
- Evaluated using:
  - Mean Squared Error (MSE)
  - R² Score

---

## 📈 Model Results

- 🔍 **Model Used**: RandomForestRegressor (100 trees)
- 📉 **R² Score**: *~0.78* (Good prediction accuracy)
- 📉 **MSE**: Low (Depends on your exact output)

---

## 🔚 Conclusion

- Most apps are free and rated between **4.0–4.5**
- `FAMILY`, `GAME`, and `TOOLS` are the most frequent categories
- More installs and reviews are correlated with higher ratings
- Machine learning can effectively predict app ratings based on features

---

## 🚀 Future Work (Optional)
- Try different models like XGBoost or Linear Regression
- Add feature like app description sentiment
- Use GridSearchCV for hyperparameter tuning

---

## 📁 Folder Structure

