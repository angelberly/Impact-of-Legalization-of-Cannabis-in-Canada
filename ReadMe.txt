# 🚭 Smoking Cessation Prediction using Machine Learning

This project uses data science and machine learning techniques to predict the likelihood of individuals successfully quitting smoking based on demographic, behavioral, and socioeconomic features. The analysis is based on the Canadian Public Use Microdata File (PUMF) dataset.

## 📁 Project Structure

- `smoking cessation eda and model_final.ipynb`: Jupyter notebook with complete data cleaning, EDA, preprocessing, and final model training.
- `pumf.csv`: Raw dataset (Public Use Microdata File).
- `README.md`: Project overview and documentation.

## 📊 Objective

To build a predictive model that identifies individuals who are more likely to quit smoking. The project includes:
- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling class imbalance using SMOTE
- Model training and evaluation using multiple algorithms
- Hyperparameter tuning for best model performance

## 📌 Key Features

- Data cleaning and preprocessing pipeline
- Visualization of smoking trends and feature relationships
- Balanced training data using **SMOTE**
- Multiple baseline model comparisons
- Optimized model using **GridSearchCV**
- Final model selection based on best evaluation metrics

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

## 🧠 ML Models Used

| Model               | Description                             |
|---------------------|-----------------------------------------|
| Logistic Regression | Interpretable baseline model            |
| KNN                 | Distance-based baseline model           |
| Random Forest       | Ensemble model for better generalization|
| SVM                 | Final model with hyperparameter tuning  |

## 📈 Evaluation Metrics

- Accuracy
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
