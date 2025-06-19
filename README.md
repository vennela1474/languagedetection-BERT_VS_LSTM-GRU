# 🌐 Comparative Study: BERT vs. Hybrid LSTM-GRU for Language Detection

## 📄 Paper Title
**Comparative Study of BERT and Hybrid Model (LSTM+GRU) for Language Detection using NLP**

## 👩‍💻 Authors
- **Kola Vennela** – SR University  


## 📌 Abstract

This study investigates two deep learning approaches for **multilingual language detection**:
- **HybridBERT**: A fine-tuned Multilingual BERT model  
- **Hybrid LSTM-GRU**: A combination of bidirectional recurrent networks

Both models were trained on a multilingual dataset spanning 17 languages.  
📈 **Results:**
- **HybridBERT** achieved **99% accuracy**
- **LSTM-GRU Hybrid** achieved **95.6% accuracy**

This paper demonstrates the robustness of transformer-based models and the efficiency of hybrid RNNs in real-world, multilingual NLP tasks.


## 🎯 Objectives

- To compare BERT and LSTM-GRU architectures for language detection.
- To evaluate their accuracy, F1-score, recall, and precision.
- To assess each model's computational efficiency and deployment feasibility.


## 📊 Results Summary

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| HybridBERT        | 99%      | 99%       | 99%    | 99%      |
| LSTM-GRU Hybrid   | 95.6%    | 96%       | 95%    | 95%      |


## 🧠 Key Features

- 🔠 Multilingual dataset with 17 languages
- 🧪 Fine-tuned `bert-base-multilingual-cased` using HuggingFace Transformers
- 🔁 Custom hybrid model built with BiLSTM and BiGRU layers
- 📉 Precision-recall curves and confusion matrix visualizations
- 💡 Lightweight alternative with LSTM-GRU for low-resource deployments


## 🛠️ Tools & Frameworks

- Python
- TensorFlow / Keras
- HuggingFace Transformers
- Scikit-learn
- Matplotlib & Seaborn

