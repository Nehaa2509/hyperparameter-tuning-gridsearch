# Hyperparameter Tuning using GridSearchCV  
## AI & ML Internship – Task 16

## 📌 Objective
The objective of this task is to optimize a machine learning model using GridSearchCV and compare its performance with a default model.

---

## 📊 Dataset
Breast Cancer Dataset (from sklearn library)

- Binary classification problem  
- Classes: Malignant (0) and Benign (1)  
- 569 samples  
- 30 numerical features  

---

## 🛠 Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 🔍 Workflow
1. Loaded dataset from sklearn  
2. Split data into training and testing sets (80/20 with stratification)  
3. Trained baseline Random Forest model  
4. Defined hyperparameter grid  
5. Applied GridSearchCV with 5-fold cross-validation  
6. Extracted best parameters  
7. Evaluated tuned model  
8. Compared performance  

---

## ⚙ Hyperparameter Grid
```
n_estimators: [50, 100, 200]
max_depth: [None, 10, 20]
min_samples_split: [2, 5, 10]
```

Total combinations tested: 27  
Total models trained with 5-fold CV: 135  

---

## 📈 Results
Default Model Accuracy: XX.XX  

Best Parameters:
```
{
 'n_estimators': ...,
 'max_depth': ...,
 'min_samples_split': ...
}
```

Tuned Model Accuracy: XX.XX  

---

## 🧠 Concepts Covered
- Hyperparameters  
- GridSearchCV  
- Cross-validation  
- Model optimization  
- Avoiding data leakage  
- GridSearch vs RandomSearch  

---

## 📁 Repository Structure
```
hyperparameter-tuning-gridsearch/
│
├── task16_gridsearch.ipynb
└── README.md
```

---

## ✅ Conclusion
This project demonstrates how hyperparameter tuning improves model performance and ensures better generalization using cross-validation.
