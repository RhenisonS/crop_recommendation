# 🌱 AI Crop Recommendation System

An AI-powered machine learning project that recommends the most suitable crop based on soil nutrients and environmental conditions.

---

## 📌 Project Overview

This project uses machine learning algorithms to predict the best crop for cultivation using agricultural parameters such as:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH value
- Rainfall

The goal of this project is to help farmers make smarter crop selection decisions using AI and data science.

---

## 🚀 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Label Encoding
- Machine Learning model training
- Hyperparameter tuning using GridSearchCV
- Model evaluation and comparison
- Model saving using Joblib

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

---

## 📂 Dataset Features

| Feature | Description |
|---|---|
| N | Nitrogen content in soil |
| P | Phosphorus content in soil |
| K | Potassium content in soil |
| temperature | Temperature in °C |
| humidity | Humidity percentage |
| ph | Soil pH value |
| rainfall | Rainfall in mm |
| label | Recommended crop |

---

## 🤖 Machine Learning Models Used

1. Decision Tree Classifier
2. Random Forest Classifier
3. K-Nearest Neighbors (KNN)
4. XGBoost Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|---|---|
| Decision Tree | 97.95% |
| Random Forest | 99.54% |
| KNN | 98.18% |
| XGBoost | High Accuracy Achieved |

✅ Random Forest performed best in this project.

---

## 📈 Project Workflow

1. Import Dataset
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Save Model

---

## 💾 Save Model

```python
joblib.dump(best_rf, 'best_rf.pkl')
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook
```

---

## 📸 Example Prediction

```python
Input:
N = 90
P = 42
K = 43
Temperature = 20.8
Humidity = 82
pH = 6.5
Rainfall = 202

Output:
Rice
```

---

## 🎯 Future Improvements

- Web application deployment
- Mobile app integration
- Real-time weather API integration
- Fertilizer recommendation system
- Deep learning implementation

---

