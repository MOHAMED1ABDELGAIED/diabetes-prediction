
# Diabetes Prediction using Logistic Regression

This project uses machine learning to predict whether a patient is diabetic based on medical diagnostic data. The model is built using **Logistic Regression** in Python.

---

## 📊 Dataset

- The dataset contains health-related attributes such as:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0: Non-diabetic, 1: Diabetic)

- Dataset used: `diabetes.csv`  
  *(Make sure the dataset is in the same directory when running the code)*

---

## ⚙️ Technologies Used

- Python
- pandas
- scikit-learn
- Jupyter Notebook

---

## 🧠 Model

- **Algorithm**: Logistic Regression (Binary Classification)
- **Target Variable**: `Outcome`
- **Features Used**: All other columns
- **Train/Test Split**: 80/20

---

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Make sure you have the required libraries:
    ```bash
    pip install pandas scikit-learn
    ```
3. Run the notebook `Logistic Regression.ipynb`.
4. Ensure `diabetes.csv` is in the same folder as the notebook.

---

## 📈 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## 📌 Example Output

```
Accuracy: 0.79

Confusion Matrix:
[[90 10]
 [19 35]]

Classification Report:
              precision    recall  f1-score   support
           0       0.83      0.90      0.86        100
           1       0.78      0.65      0.71         54
```

---

## ✍️ Author

- Mohamed Abdelgaied
  