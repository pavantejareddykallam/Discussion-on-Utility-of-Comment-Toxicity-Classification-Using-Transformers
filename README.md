# BERT for Comment Toxicity Classification

This repository contains both theoretical and practical resources related to using BERT (Bidirectional Encoder Representations from Transformers) for classifying toxic comments in online text data.

## 📚 Contents

### 1. `BERT_Toxicity_Report.pdf`
A research-oriented book report covering:
- The background and architecture of BERT
- Its advantages in understanding language context bidirectionally
- A focused case study on **comment toxicity classification**

<img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/2f134e6c-3655-4db4-b6c0-6238d48b060a" />

This document is ideal for readers seeking a conceptual foundation of BERT and its utility in real-world text classification problems.

### 2. `BERT_Toxicity_Classifier.ipynb`
A Jupyter notebook demonstrating the **practical application of BERT** to the comment toxicity classification task. It includes:
- Data preprocessing
- Tokenization using Hugging Face Transformers
- Model setup with pretrained BERT (e.g., `bert-base-uncased`)
- Fine-tuning and training
- Evaluation metrics (accuracy, precision, recall, F1-score)
- Visualization of model performance

This notebook is designed for hands-on learners and practitioners who want to understand how BERT performs in a toxic comment detection pipeline.

## 🔧 Requirements

To run the notebook, make sure you have the following installed:

- Python 3.7+
- `transformers`
- `datasets`
- `scikit-learn`
- `pandas`
- `torch`


Install dependencies via:

```bash
pip install transformers datasets scikit-learn pandas torch matplotlib
