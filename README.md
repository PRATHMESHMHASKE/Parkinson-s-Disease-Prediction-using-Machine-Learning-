# Parkinson-s-Disease-Prediction-using-Machine-Learning-
# Parkinson’s Disease Prediction Using Machine Learning

This project aims to predict Parkinson’s disease in individuals using vocal measurements. The dataset used includes biomedical voice measurements from people with and without Parkinson’s disease.

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- **Instances**: 197
- **Features**: 23 (including name, frequency jitter, shimmer, noise-to-harmonics ratio, etc.)
- **Target Variable**: `status`
  - `1` → Parkinson’s
  - `0` → Healthy

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Pandas Profiling
- Pickle (for model saving)

## 📌 Project Steps

1. **Data Exploration & Profiling**
   - Data types, null values, distributions
   - Visualizations: histograms, bar plots, heatmaps

2. **Data Preprocessing**
   - Dropped `name` column
   - Feature/target split
   - Train-test split

3. **Model Training & Evaluation**
   - Logistic Regression
   - Random Forest Classifier
   - Decision Tree Classifier
   - Naïve Bayes
   - K-Nearest Neighbors
   - Support Vector Machine (SVM)
   - Evaluated using Accuracy, Confusion Matrix, Classification Report, and Cohen’s Kappa Score

4. **Model Deployment**
   - Saved the best-performing model (SVM) using `pickle`.

## 🔍 Results

- **SVM** achieved high accuracy and performance.
- **Kappa Score** used to measure model agreement beyond chance.

## 📁 File Structure

