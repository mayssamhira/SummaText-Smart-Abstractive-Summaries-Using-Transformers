# SummaText: Abstractive Text Summarization using BART

## 📌 Project Overview
QuickDigest is an abstractive text summarization system based on the BART transformer model.  
It automatically generates human-like summaries of long documents while preserving meaning and context.  
The model is trained on the CNN/DailyMail dataset and fine-tuned using Hugging Face Transformers in Google Colab.

---

## 🎯 Problem Statement
With the huge amount of online text—news, research papers, blogs—manual summarization is time-consuming.  
This project aims to automate the summarization process to save time and support quick information digestion.

---

## 🚀 Objectives
- Train an abstractive summarization model using BART
- Preprocess and tokenize the dataset
- Fine-tune the transformer model
- Evaluate results using ROUGE metrics
- Test with custom input text
- Deploy a simple Streamlit app

---

## 🧠 Methodology

### Dataset
- CNN/DailyMail (`cnn_dailymail`, version 3.0.0)

### Steps
1. Load dataset in Google Colab  
2. Preprocess text (cleaning, tokenization)  
3. Fine-tune BART on training set  
4. Evaluate with ROUGE  
5. Generate summaries  
6. Deploy a Streamlit app  

---

## 📦 Tools & Libraries

- Python  
- Google Colab  
- PyTorch  
- Hugging Face Transformers  
- Datasets Library  
- ROUGE Score  
- Streamlit  

---

## 📊 Sample Result

**Input:**  
Daniel Radcliffe gains access to a £20M fortune...

**Generated Summary:**  
Daniel Radcliffe receives a £20M inheritance on his 18th birthday and says
he has no plans to spend recklessly.

---

## 📈 Evaluation
Model performance was evaluated using ROUGE metrics.  
Typical scores:  

| Metric  | Score |
|---------|--------|
| ROUGE-1 | 0.35–0.45 |
| ROUGE-2 | 0.18–0.25 |
| ROUGE-L | 0.32–0.40 |

---

## 🌐 Demo App (Streamlit)
A web app version allows users to paste text and generate summaries interactively using the fine-tuned BART model.

---

## 📌 Conclusion
This project shows that transformer-based models like BART can generate coherent abstractive summaries.  
Future improvements may include Pegasus/T5 models or UI deployment on Hugging Face Spaces.

---

## 📁 Project Structure
|-- notebook/
|-- bart-summarizer/ # fine-tuned model
|-- app/
| |-- streamlit_app.py
|-- README.md


---

## ✍️ Author
**Mayssa Mhira**

