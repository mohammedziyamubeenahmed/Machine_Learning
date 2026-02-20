# 🏠 Housing Price Prediction using Regression Techniques

This project develops a machine learning regression pipeline to predict housing prices using the California Housing Dataset from scikit-learn. The objective is to build, evaluate, and optimize regression models through structured preprocessing, feature engineering, model comparison, and hyperparameter tuning.

---

## 📌 Project Objective

To design and evaluate regression models capable of accurately predicting median housing prices based on socioeconomic and geographic features.

The project emphasizes:
- Structured ML workflow
- Feature engineering
- Model evaluation rigor
- Hyperparameter optimization
- Performance comparison

---

## 📊 Dataset

- **Source:** `sklearn.datasets.fetch_california_housing`
- Contains housing data including:
  - Median income
  - House age
  - Average rooms
  - Population
  - Latitude & Longitude
- Target variable: Median house value

---

## 🔎 Data Exploration & Preprocessing

- Loaded and explored dataset using pandas and matplotlib
- Checked for missing values and outliers
- Visualized feature distributions and correlations
- Applied feature scaling where necessary
- Structured dataset split:
  - 70% Training
  - 10% Validation
  - 20% Testing

---

## ⚙️ Feature Engineering

- Created derived features from existing variables
- Applied scaling/normalization (StandardScaler / MinMaxScaler)
- Evaluated feature importance
- Handled potential categorical extensions (if applicable)

---

## 🤖 Model Building & Evaluation

Implemented and compared multiple regression algorithms, including:

- Linear Regression
- Ridge / Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### Evaluation Metrics Used

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Applied **k-fold cross-validation** to estimate generalization performance.

---

## 🎯 Model Tuning & Selection

- Performed hyperparameter tuning using:
  - GridSearchCV
  - RandomizedSearchCV
- Compared validation performance
- Selected best-performing model based on RMSE and R²

---

## 📈 Model Prediction

- Generated predictions on the test dataset
- Compared predicted vs actual values
- Analyzed bias–variance behavior
- Interpreted feature impact on pricing trends

---

## 🚀 Extensions Explored

- Handling categorical features via encoding (if applicable)
- Experimenting with ensemble techniques:
  - Stacking
  - Blending
- Performance comparison across ensemble models

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## 📌 Key Takeaways

- Feature engineering significantly impacts regression performance.
- Regularization helps control overfitting.
- Ensemble models often outperform simple linear models.
- Cross-validation is critical for reliable model comparison.


