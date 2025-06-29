# elevate_labs-task_4
# Breast Cancer Classification - ML Project

This project uses machine learning to classify breast tumors as **Benign** or **Malignant** using features from a real-world breast cancer dataset. The model is trained with Logistic Regression and deployed using Gradio for an interactive web interface.

---

## 🧠 Dataset
- Source: Breast Cancer Wisconsin (Diagnostic) Dataset
- Target: `diagnosis` (M = malignant, B = benign)
- Total features: 30 numeric features such as `radius_mean`, `texture_mean`, `area_mean`, etc.

---

## 📌 Steps Performed

1. Data cleaning and preprocessing
2. Standardization using `StandardScaler`
3. Train-test split
4. Logistic Regression model
5. Model evaluation using:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Curve
6. Threshold tuning
7. Sigmoid function plot for understanding model behavior
8. Gradio web app interface

---

## 🔍 Model Performance (Logistic Regression)

- Accuracy: **98%**
- Precision (Malignant): 0.98
- Recall (Malignant): 0.98
- ROC-AUC Score: ~0.99

---

## 🚀 How to Run (in Colab)

1. Upload the dataset (`.csv`)
2. Run all cells in order
3. The last cell launches a Gradio app:
   - Use the `share=True` link to access your custom prediction app.

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Gradio
- Google Colab (for development)



