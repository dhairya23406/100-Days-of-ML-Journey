
# Day 29 - Titanic Survival Prediction using Pipeline

## 📚 Topics Covered
- Pipelines in Scikit-learn
- ColumnTransformer
- Feature Engineering
- Hyperparameter Tuning
- GridSearchCV
- Model Export using Pickle

---

## 📌 Dataset
- Titanic Dataset
- Features:
  - Pclass
  - Sex
  - Age
  - SibSp
  - Parch
  - Fare
  - Embarked

Target:
- Survived

---

## 🛠 Steps Performed

1. Imported Libraries
2. Loaded Dataset
3. Train-Test Split
4. Data Preprocessing
   - Missing Value Imputation
   - One Hot Encoding
   - Scaling
5. Created Pipeline
6. Trained Model
7. Hyperparameter Tuning using GridSearchCV
8. Saved the Pipeline using Pickle

---

## 📦 Files

- day_29_titanic_using_pipeline.ipynb
- day_29_predict_using _pipeline.ipynb
- train.csv
- pipe.pkl

---

## 📖 Key Learnings

- Pipelines make preprocessing and model training easier.
- GridSearchCV helps in finding the best hyperparameters.
- Pickle can save trained models for future use.

---

## 🚀 Next Steps

- Load the saved pipeline.
- Predict on unseen data.
- Deploy the model using Streamlit.
