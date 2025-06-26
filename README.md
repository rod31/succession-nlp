# Succession NLP – Sarcasm Detection & Character Style Transfer

## 💬 Overview
This project explores natural language processing techniques to classify **sarcasm** in dialogue from the TV series *Succession*, and to generate text in the style of specific characters.

Using transformer-based models (BERT), the project fine-tunes and evaluates multiple architectures for sarcasm detection. It also implements **style-aware text generation**, transforming neutral lines into character-specific phrasing using Generative AI techniques.

## 🧠 Technologies Used
- Python
- Hugging Face Transformers (BERT)
- Scikit-learn
- Google Colab / Jupyter
- Pandas, NumPy, Matplotlib, Seaborn

## 🛠️ Features
- Fine-tuned BERT for binary sarcasm classification on labeled Succession dialogue
- Preprocessing pipeline including tokenization, attention masks, and padding
- Evaluation using precision, recall, F1-score, and confusion matrix
- Lexical diversity analysis and sentiment modeling of key characters
- Style transfer using fine-tuned generation models

## 📊 Results
- Achieved >90% test accuracy on sarcasm classification
- Visualizations of character speech patterns (e.g., sentiment, topic models)
- Generated character-specific versions of sample sentences

## 🚀 How to Run
1. Open the Colab notebook (`succession_nlp.ipynb`)  
2. Install dependencies:
```python
!pip install transformers datasets seaborn
