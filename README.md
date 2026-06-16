# MajorProject_ML

# Heart Disease Prediction Using Machine Learning Classification Models

## 🎯 Objectives:-
-To develop a supervised classification model predicting heart disease presence (Target: 0 or 1)
-To implement, optimize, and compare multiple classification models: Logistic Regression, Decision Tree, Random Forest, and a Feedforward Neural Network (AI Model)
-To evaluate model performance using comprehensive metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC
-To analyze clinical feature distributions and understand key factors contributing to heart disease.

## ⚙️ ML Pipeline Architecture
1. **Data Understanding & Cleaning:** Handled explicit missing values and corrected clinical anomalies (such as invalid zero values in blood pressure and cholesterol)
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions, calculated target variable balance, and generated a correlation matrix heatmap
3. **Feature Engineering:** Standardized numerical columns using `StandardScaler` and encoded categorical features via `OneHotEncoder`
4.**Model Building & Tuning:** Leveraged `GridSearchCV` for hyperparameter optimization across traditional ML models
5. **Deep Learning Framework:** Designed and trained a Feedforward Neural Network utilizing the Keras Functional API with Dropout layers to mitigate overfitting
6. **Evaluation:** Generated comprehensive performance metrics matrices alongside model confusion matrices

## 📊 Tech Stack
**Language:** Python
**Libraries:** Pandas, NumPy, Scikit-Learn, TensorFlow/Keras, Matplotlib, Seaborn
**Environment:** Google Colab
