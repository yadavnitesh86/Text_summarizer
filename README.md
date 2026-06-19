# 📝 Text Summarizer using T5 Transformer

## 📌 Project Overview

This project fine-tunes Google's **T5 (Text-to-Text Transfer Transformer)** model for **abstractive text summarization** using the **SAMSum dialogue dataset**. The model learns to generate concise summaries from lengthy conversations and dialogues.

The project demonstrates the complete NLP workflow, including:

* Data loading and preprocessing
* Text cleaning
* Tokenization using T5 Tokenizer
* Fine-tuning the T5-small model
* Model training with Hugging Face Trainer API
* Summary generation from dialogue text

---

## 🚀 Features

✅ Dialogue summarization using Transformer architecture

✅ Text preprocessing and cleaning

✅ Fine-tuning pre-trained T5 model

✅ Hugging Face Transformers integration

✅ Efficient training pipeline

✅ End-to-end NLP project

---

## 🛠️ Tech Stack

* Python
* Pandas
* Hugging Face Transformers
* T5-small
* PyTorch
* Trainer API
* SAMSum Dataset

---

## 📂 Project Workflow

### 1. Data Loading

* Load SAMSum training and validation datasets.
* Sample a subset of data for faster experimentation.

### 2. Data Preprocessing

* Remove HTML tags
* Remove extra spaces
* Normalize text
* Convert text to lowercase

### 3. Tokenization

* Convert dialogue text into token IDs using T5 Tokenizer.
* Create labels from summary tokens.

### 4. Model Training

* Load pre-trained `t5-small`.
* Configure training arguments.
* Train using Hugging Face Trainer.

### 5. Text Summarization

* Generate concise summaries from unseen dialogues.

---

## 📊 Dataset

**SAMSum Dataset**

The SAMSum dataset contains human-written summaries of messenger-like conversations.

Dataset fields:

* `dialogue`
* `summary`

---

## ⚙️ Installation

```bash
pip install transformers
pip install torch
pip install pandas
```

---

## ▶️ Run the Project

```python
trainer.train()
```

After training, use the model to generate summaries for new dialogues.

---

## 📈 Future Improvements

* Train on the complete dataset
* Use T5-base or FLAN-T5
* Add ROUGE score evaluation
* Deploy with Streamlit
* Create REST API using Flask/FastAPI
* Optimize hyperparameters

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Transformer-based NLP workflows
* Text preprocessing techniques
* Hugging Face ecosystem
* Fine-tuning pre-trained language models
* Sequence-to-sequence learning
* Abstractive text summarization

---

## 👨‍💻 Author

Nitesh Yadav

If you found this project useful, consider giving it a ⭐ on GitHub.
