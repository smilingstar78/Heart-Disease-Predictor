# Heart Disease Prediction using Logistic Regression

This project uses **Logistic Regression** to predict whether a person is likely to have heart disease, based on several medical features. It was built while learning and practicing machine learning techniques, especially focusing on classification models and evaluation metrics like **recall** and **F1 score**.

---

## 🔍 What I Did:
- Explored and cleaned the **Heart Disease UCI dataset** (Kaggle)
- Applied **Logistic Regression** for binary classification (Disease / No Disease)
- Prioritized **Recall** to avoid false negatives (missing actual patients with heart disease)
- Evaluated model performance using:
  - Confusion Matrix
  - ROC Curve
  - F1 Score
- Visualized predictions using **Matplotlib**

---

## 📊 What I Learned:
- How **logistic regression** handles binary classification
- Why **recall is crucial** in medical diagnosis models
- How to **tune classification thresholds**
- The importance of metrics beyond accuracy (like F1 score and ROC-AUC)
- Basics of **data preprocessing**, **model evaluation**, and **visualization**

---

## 📁 Dataset
- **Source:** [Heart Disease UCI Dataset on Kaggle](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- Features include: age, cholesterol, chest pain type, fasting blood sugar, max heart rate, etc.

---

## 📈 Results
- **Recall:** `0.9655` – model successfully identified most true cases of heart disease
- **F1 Score:** `0.8888`
- **Confusion Matrix:**  
  `[[26  6]`  
   `[ 1 28]]`

> The model was tuned to catch as many heart disease cases as possible — even at the cost of some false positives.

---

## 🔧 Tools Used:
- Python 🐍
- pandas, numpy
- matplotlib
- scikit-learn

---

## 💡 Future Improvements
- Try other models (Random Forest, XGBoost)
- Explore feature selection techniques
- Add Streamlit UI for doctor-friendly app version
- Fine-tune threshold to eliminate even the last false negative

---

## 💬 Contact Me
Made with ❤️ while learning ML!  
Feel free to connect on:
- 🔗 [LinkedIn](https://www.linkedin.com/in/muskan-tariq-095a50282)
- 📷 [Instagram](https://www.instagram.com/ai_enthusiast86)
- 🧠 [YouTube](https://www.youtube.com/@ai_enthusiast86?si=bYV1AgkBoCMVUBiK)

---

> ⭐ Star this repo if it helped you or inspired you to learn more about machine learning in healthcare!
