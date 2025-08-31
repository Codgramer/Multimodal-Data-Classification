# Multimodal Data Classification 📝🤖  

This project focuses on building **Multimodal Data Classification pipelines** leveraging feature engineering, deep learning, and ensemble models. The goal was to classify emotions from multimodal datasets (emoticon, text-sequence, and deep-feature embeddings) efficiently and accurately.  

---

## 📌 Project Highlights  
- Engineered preprocessing pipelines for **emoticon, text-sequence, and deep-feature datasets**  
- Applied **PCA** to reduce **10,218 → 300 dimensions** for deep-feature embeddings  
- Trained models including **LightGBM, LSTM (Adam optimizer), and Ensemble frameworks**  
- Optimized pipeline runtime, ensuring reproducibility and scalability  

---

## ⚙️ Features  
- 🔎 **Data Preprocessing**: tokenization, padding, normalization, dimensionality reduction  
- 🧩 **Feature Engineering**: PCA on deep features, embeddings for text sequences  
- ⚡ **Models**: LightGBM, LSTM with Adam optimizer, Ensemble learning  
- 📊 **Automation**: End-to-end training pipeline with modular components  

---

## 📊 Results  
- ✅ **Emoticon Dataset**: **95.91%** accuracy  
- ✅ **Deep-Feature Dataset**: **97.55%** accuracy (PCA + LightGBM)  
- ✅ **Text-Sequence Dataset**: **76.89%** accuracy (LSTM + Adam optimizer)  
- ✅ **Ensemble Model**: **97.75%** accuracy with **40% fewer misclassifications** than individual models  

---

## 🛠️ Tech Stack  
- **Languages**: Python  
- **Libraries**: NumPy, pandas, scikit-learn, LightGBM, TensorFlow/Keras, matplotlib  
- **Approach**: PCA, Feature Fusion, LSTM (Adam optimizer), Ensemble Framework  

---
