# 📊 Customer Sentiment Analysis: SVM vs. BERT

This project applies Natural Language Processing (NLP) techniques to classify customer feedback into sentiment categories (negative, neutral, positive). It compares a traditional machine learning model (SVM) with a transformer-based model (BERT) to evaluate performance, scalability, and business suitability.

---

## 🚀 Project Overview
- Performed text preprocessing and TF-IDF feature extraction  
- Built and tuned an **SVM model** for strong baseline performance  
- Fine-tuned a **BERT model** for deep contextual understanding  
- Evaluated models using accuracy, F1-score, and log loss  
- Compared model performance and deployment suitability  

---

## 🛠️ Tools & Technologies
- **Python**  
- **Scikit-learn (SVM, evaluation metrics)**  
- **Hugging Face Transformers (BERT)**  
- **PyTorch / TensorFlow**  
- **Pandas, NumPy**  

---

## 📂 Dataset
- Kaggle Dataset:  
  https://www.kaggle.com/datasets/simaanjali/emotion-analysis-based-on-text/data  

> Note: Dataset exceeds GitHub upload limits (>25MB), so it is hosted externally.

---

## 📈 Key Results
- **SVM achieved near-perfect performance (~99.7% accuracy, F1-score)**  
- **BERT achieved strong performance (~82% accuracy)** but required significantly more computational resources  
- SVM outperformed BERT on this dataset due to its structure and simplicity  

---

## 💼 Business Implications
- Automates large-scale sentiment classification, reducing manual effort and cost  
- Enables faster, data-driven decision-making from customer feedback  
- Scalable solution adaptable to growing data volumes  
- **SVM is more suitable for deployment** due to efficiency and strong performance  
- **BERT is beneficial** when deeper language understanding is required  

---

## ✅ Strengths
- Structured and reusable NLP pipeline  
- Supports both classical (SVM) and deep learning (BERT) approaches  
- Comparative framework helps select the best model for business needs  

---

## ⚠️ Limitations
- Class imbalance affects minority class performance  
- BERT trained on a small subset due to computational constraints  
- BERT lacks interpretability compared to SVM  
- SVM may struggle with highly complex language patterns  

---

## 📊 Recommendations
- Improve class balance by collecting more minority class data  
- Use **SVM for efficiency-focused deployment**  
- Use **BERT for complex text scenarios**  
- Continuously monitor model performance on new data  
- Apply explainability tools (e.g., SHAP, LIME) for BERT predictions  

---

## 🔍 Model Explainability
- **SVM**: More transparent and interpretable  
- **BERT**: More complex (“black box”)  
- Recommended tools: **SHAP** and **LIME** for post-hoc explanations  

---

## 📌 Conclusion
While BERT provides strong contextual understanding, **SVM proves to be the more practical and efficient model for this task**, achieving superior performance with lower computational cost. The choice between models should depend on data complexity and business requirements.


