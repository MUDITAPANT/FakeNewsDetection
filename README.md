# Fake News Detection Using Deep Learning
Acadmic Project 2024
## Overview
This project explores the application of **deep learning algorithms** for detecting fake news articles.  
We implemented a **Long Short-Term Memory (LSTM)** model to classify news as real or fake, leveraging sequential text analysis to capture context and long-term dependencies.

---

## Tools & Environment
- **Language:** Python  
- **Libraries:** TensorFlow/Keras, NumPy, Pandas, Matplotlib, Scikit-learn  
- **Platform:** Google Colab  
- **Dataset Sources:** Kaggle (Fake News dataset), FakeNewsNet  

---

## Dataset
- **Legitimate News:** Articles from reputable sources  
- **Fake News:** Verified false articles from fact-checking organizations  
- Includes contextual information such as user and social metadata (in extended datasets).  

---

## Methodology
1. **Data Collection** – Gathered labeled fake and real news articles.  
2. **Preprocessing** – Tokenization, lowercasing, stop-word removal, stemming/lemmatization.  
3. **Feature Extraction** – Word embeddings for textual representation.  
4. **Model Selection** – LSTM chosen for sequential text analysis.  
5. **Model Training** – Trained using accuracy, precision, recall, and F1-score metrics.  
6. **Evaluation** – Cross-validation applied to ensure generalization.  

---

## 🧠 Model Architecture
- **Embedding Layer** – Converts words into dense vector representations.  
- **LSTM Layers** – Capture sequential dependencies and context.  
- **Dense Layers** – Fully connected layers for classification.  
- **Output Layer** – Binary classification (Real vs Fake).  

---

## Results & Discussion
- **Model Used:** LSTM  
- **Accuracy:** 92%  
- **Precision:** 92%  

### Insights
- LSTMs effectively captured sequential dependencies, improving detection accuracy.  
- Computationally intensive training required more resources and time.  
- Demonstrated robustness in distinguishing fake from real news articles.  

---

## Future Work
- Enhance model robustness against adversarial attacks.  
- Curate larger, multilingual datasets for better generalization.  
- Explore transformer-based architectures (e.g., BERT, RoBERTa).  
- Optimize models for **real-time deployment** in social media platforms.  

---

## 👩‍💻 Author
- **Mudita Pant**  
- B.Tech in Computer Science & Engineering (2025)

