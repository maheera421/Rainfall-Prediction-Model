# 🌧️ Rainfall Prediction in Australia

This project uses a historical weather dataset from various locations in Australia to predict whether it will rain tomorrow. By applying multiple classification algorithms and proper data preprocessing techniques, the model aims to provide accurate and actionable weather forecasts.

## 📂 Dataset

- Source: [Kaggle - Rain in Australia Dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- Features include: temperature, humidity, wind direction/speed, pressure, cloud cover, and more.
- Target variable: `RainTomorrow` — a binary label indicating whether it rained the next day.

## 📌 Objectives

- Preprocess raw weather data (handle missing values, encode categorical data, remove outliers)
- Address class imbalance using oversampling
- Perform feature selection and scaling
- Train and evaluate multiple ML models (Logistic Regression, Decision Tree, Neural Network)
- Compare model performance
- Predict rainfall for a new sample based on current weather data

## 🧪 Technologies Used

- Python
- Jupyter Notebook
- pandas, NumPy
- scikit-learn
- seaborn, matplotlib

## 🧰 ML Models Trained

- Logistic Regression
- Decision Tree Classifier
- Neural Network (MLPClassifier)

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC (optional)
- Cohen’s Kappa (optional)
- Time taken for model execution

## 🧼 Data Preprocessing Steps

- Imputation using median values
- Label Encoding for categorical variables
- One-hot encoding for nominal features
- Outlier removal using IQR
- Feature selection using SelectKBest

## 🔮 Making Predictions

Once trained, the model can take a single row of current-day weather data (excluding the label) and predict whether it will rain the next day.

## 📊 Results

- Model comparison visualized with bar and line plots
- Neural Network outperformed other models in accuracy (example only—adjust based on your actual results)

## 📎 Conclusion

This project demonstrates the power of combining traditional machine learning algorithms with thorough data preprocessing to solve real-world binary classification problems. The rainfall prediction system could help in agriculture planning, water resource management, and public safety.


