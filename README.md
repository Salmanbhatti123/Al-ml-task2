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
✅ Task 2: Churn Prediction Using ML Pipeline
Objective:
Use traditional ML to predict customer churn based on the Telco dataset.

Tools:

Pandas, NumPy

Scikit-learn

Steps:

Load data from IBM’s Telco dataset.

Drop customerID, handle missing values.

Encode categorical columns with OneHotEncoder.

Scale numeric features.

Train RandomForestClassifier inside a pipeline.

Evaluate with confusion matrix and accuracy.

✅ Task 3: Multimodal Classification (Image + Tabular)
Objective:
Train a model that uses both image features and tabular data for binary classification.

Tools:

PyTorch

Torchvision (ResNet18)

Pandas, PIL

Steps:

Generate synthetic images and tabular CSV.

Use ResNet18 to extract image features.

Combine image + tabular features.

Define a neural network model.

Train the model and evaluate on dummy data.
