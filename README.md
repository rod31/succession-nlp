# Succession NLP – Sarcasm Detection & Character Style Transfer

## 💬 Overview
This project explores natural language processing techniques to classify **sarcasm** in dialogue from the TV series *Succession*, and to generate text in the style of specific characters. Up to this moment, I focused on generating text in the style of Roman Roy, who is known for his sharp wit and snarky remarks.

Sarcasm is a very complex and nuanced language feature. It often depends on context, tone, and shared knowledge, making it especially hard to detect using only text-based models. However, sarcasm detection can potentially present many commercial applications, like analyzing online reviews of products, services (such as restaurants, hotels, and books), and opinions on topics ranging from politics to personal experiences.

It's also possible that sarcasm detection in social media posts can provide insights into mental health issues by identifying shifts in tone, emotional state, or social behavior. Sarcasm can be a form of indirect expression, often masking feelings of frustration, loneliness, or sadness, especially in online environments. When used excessively or in contexts that deviate from typical patterns, it may reflect underlying stress, anxiety, or depressive symptoms. Detecting these nuances through machine learning could contribute to early mental health screening and help researchers understand how people express emotional distress digitally. 

Using transformer-based models (BERT), the project fine-tunes and evaluates multiple architectures for sarcasm detection. It also implements **style-aware text generation**, transforming neutral lines into character-specific phrasing using Generative AI techniques.

## 🧠 Technologies Used
- Python
- Hugging Face Transformers (BERT)
- Scikit-learn
- Google Colab / Jupyter
- Pandas, NumPy, Matplotlib, Seaborn

## 🛠️ Features
- Fine-tuned BERT for binary sarcasm classification on manually labeled Succession dialogue
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
