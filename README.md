# 💳 Credit Card Fraud Detection

This project demonstrates **Credit Card Fraud Detection** using **Logistic Regression** in **Google Colab**.  
The dataset is highly imbalanced, so under-sampling was applied to balance legitimate and fraudulent transactions.  
The model was trained and evaluated with promising accuracy results.  

---

## 📊 Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Rows:** 284,807 transactions  
- **Features:** 30 (including anonymized PCA features + `Amount`)  
- **Target:** `Class` (0 = Legit, 1 = Fraud)  
- Highly imbalanced (≈ 492 fraud cases vs 284,315 normal)

---

## ⚙️ Methodology
1. Imported libraries (NumPy, Pandas, Matplotlib, Scikit-learn)  
2. Loaded dataset into Pandas DataFrame  
3. Performed exploratory analysis  
4. Balanced dataset using **under-sampling**  
5. Split into training & testing sets (80:20)  
6. Trained **Logistic Regression** model  
7. Evaluated with Accuracy, Precision, Recall, and ROC-AUC  

---

## 📈 Results
- **Training Accuracy:** ~94.6%  
- **Test Accuracy:** ~91.8%  
- ROC-AUC used to evaluate discrimination ability between fraud & legit transactions  

---

## 🚀 How to Run
1. Open the notebook in **Google Colab**  
2. Upload the dataset (`creditcard.csv`)  
3. Run all cells step by step  
4. View results and evaluation metrics  

---

## 🔮 Future Improvements
- Try advanced models (Random Forest, XGBoost, Neural Networks)  
- Use SMOTE for over-sampling instead of under-sampling  
- Deploy the model as a web app (Streamlit/Flask)  

---
