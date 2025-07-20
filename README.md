# Toxic Comment Classification using Deep Learning

This project focuses on identifying toxic language in user-generated comments using a deep learning model. The model is trained to detect six different categories of toxicity, enabling automated content moderation for safer digital platforms.

## Problem Statement

Online platforms are increasingly vulnerable to harmful comments such as hate speech, threats, and insults. This project uses NLP and deep learning to classify comments into the following categories:

- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

---

## 🛠️ Technologies Used

- Python 3.x  
- TensorFlow / Keras  
- Pandas & NumPy  
- TextVectorization (for tokenization & padding)  
- Bidirectional LSTM  
- Gradio (for real-time model inference)

---

## 📂 Dataset

The dataset used is from the [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge), which includes 150,000+ labeled comments from Wikipedia.

---

## 🧠 Model Architecture

- **Embedding Layer** – Converts tokens into dense vectors  
- **Bidirectional LSTM** – Captures context in both directions  
- **Dense Layers** – Extract deeper patterns  
- **Output Layer (Sigmoid)** – Produces probability for each of the six classes  

Loss Function: `Binary Crossentropy`  
Activation: `Sigmoid` (multi-label output)  
Optimizer: `Adam`  
Input Length: 1800 tokens (vectorized)

---
