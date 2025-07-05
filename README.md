# 🩺 Diabetes Prediction using SVM

This machine learning project predicts whether a patient is diabetic based on medical features using a **Support Vector Machine (SVM)** classifier. Implemented entirely in **Google Colab** using Python and Scikit-learn.

---

## ✅ Project Highlights

- ✅ Checked for null values
- ✅ Balanced the dataset using **undersampling**
- ✅ Standardized features using `StandardScaler`
- ✅ Performed **train-test split**
- ✅ Trained using **SVM classifier**
- ✅ Evaluated the model with:
  - **Accuracy score**
  - **Confusion matrix**
- ✅ Achieved:
  - 🎯 **Training Accuracy:** 78%
  - 📈 **Testing Accuracy:** 81%

---

## 📦 Technologies Used

- Python 3 (Google Colab)
- Libraries:
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`, `seaborn`

---

## 📊 Model Evaluation

### 📘 Confusion Matrix:

- **True Negatives (TN):** 25 — Non-diabetic correctly classified  
- **False Positives (FP):** 8 — Non-diabetic misclassified as diabetic  
- **False Negatives (FN):** 2 — Diabetic misclassified as non-diabetic  
- **True Positives (TP):** 19 — Diabetic correctly classified  

---

## 🧪 How to Use

1. Open the `diabetes_prediction.ipynb` notebook in **Google Colab**.
2. Upload your dataset (`diabetes.csv`).
3. Run the notebook step-by-step:
   - Data loading and inspection
   - Class balancing and scaling
   - Model training using `SVC`
   - Accuracy evaluation and confusion matrix visualization

---

## 📁 Files Included

├── DiabetesPrediction.ipynb # Main Colab notebook
└── README.md # Project summary and usage

---

## 📚 Dataset

- **PIMA Indian Diabetes Dataset**

---

## 📌 Note

This notebook was built as part of practical machine learning training to demonstrate end-to-end binary classification — from data preparation to evaluation.

---

## 🧠 Future Work

- Try other models like **Random Forest** or **Logistic Regression**
- Use **cross-validation** for better reliability
- Apply **feature engineering** or **hyperparameter tuning**

---

## 🔐 License

This project is for educational purposes.


