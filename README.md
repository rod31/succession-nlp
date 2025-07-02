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
- Achieved decent test accuracy on sarcasm classification (Work in Progress)
- Visualizations of character speech patterns (e.g., sentiment, topic models)
- Generated character-specific versions of sample sentences

## 📁 Repo Structure
- `succession_nlp.ipynb` — full Colab notebook
- `succession_nlp.py` - python file
- `data/` — dialogue CSVs or sample inputs
- `style_transfer_demo.txt` — generated examples
- `README.md` — this file

## 🧪 Project Background
Built as a passion project during my final year at Drexel University, this project merges media, language, and machine learning to study the nuances of sarcastic dialogue and personality stylization in modern television.

## 📫 Contact
📧 rodrigo01.aragao@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rb-aragao)
