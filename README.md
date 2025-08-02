# AI/ML Internship Tasks – DevelopersHub Corporation

This repository contains the completed code and documentation for the first three tasks assigned during the AI/ML Engineering Internship at DevelopersHub Corporation. Each task demonstrates the practical application of AI/ML techniques using Python, PyTorch, HuggingFace, and Scikit-Learn.

---

## ✅ Task 1: News Classification with Transformers

### 📌 Objective:
Build a 4-class news text classification system using a pre-trained transformer (DistilBERT) from HuggingFace.

### ⚙️ Tools & Libraries:
- HuggingFace Transformers
- Datasets
- PyTorch
- Scikit-Learn

### 🧪 Key Steps:
- Load a CSV dataset with news texts and labels
- Tokenize using `DistilBERT tokenizer`
- Fine-tune the model on text classification task
- Evaluate using accuracy, classification report

### 🚀 How to Run:
```bash
# Upload dataset.csv file (with 'text' and 'label' columns)
# Then run: 
python task1_news_classification.py
