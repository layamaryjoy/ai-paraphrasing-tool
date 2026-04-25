# 🤖 AI-Powered Paraphrasing Tool

![Python](https://img.shields.io/badge/Python-3.9-blue)
![NLP](https://img.shields.io/badge/NLP-Transformers-orange)
![Model](https://img.shields.io/badge/Model-T5%20%2F%20HuggingFace-green)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-red)

An AI-based Natural Language Processing (NLP) project that generates high-quality paraphrases using deep learning transformer models. The tool rewrites input text while preserving its original meaning, improving clarity, and ensuring originality.

---

## 🚀 Run Project in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KHsHZaDvc1TD52nvCsNXxfwHZV7ranrY)

---

# 📘 Project Overview

This project implements an **AI-powered paraphrasing system** using transformer-based models like **T5 / Hugging Face Transformers**.

The system:

✔ Takes input text  
✔ Generates a paraphrased version  
✔ Maintains semantic meaning  
✔ Improves readability and fluency  
✔ Evaluates output using NLP metrics  

---

# 🎯 Objective

The main objectives of this project are:

- Build an AI-based paraphrasing tool using deep learning  
- Preserve meaning while rewriting text  
- Improve linguistic quality and readability  
- Ensure originality (reduce copying)  
- Evaluate performance using standard NLP metrics  

---

# ⚙️ Methodology

The project follows this pipeline:

- Text Input  
- Tokenization  
- Transformer Model Processing (T5 / Hugging Face)  
- Text Generation (Paraphrased Output)  
- Evaluation Metrics Calculation  

---

# 🧠 Model Used

- Transformer-based model (**T5 / Hugging Face Transformers**)  
- Pretrained on large text corpora  
- Capable of generating human-like paraphrases  

---

# 📊 Sample Result

### 📝 Original Text:
Deep learning models have significantly enhanced the performance of image and speech recognition systems by leveraging large amounts of labeled data.

### 🔁 Paraphrased Output:
The utilization of massive quantities of labeled data by deep learning models has resulted in significant improvements in both image and speech recognition systems.

---

# 📊 Evaluation Metrics

| Metric               | Score  | Description |
|---------------------|--------|------------|
| BLEU Score          | 0.1407 | Measures word overlap (lower = better paraphrasing) |
| ROUGE-1             | 0.6222 | Content retention |
| ROUGE-2             | 0.3721 | Phrase-level similarity |
| ROUGE-L             | 0.3556 | Longest sequence match |
| Semantic Similarity | 0.9113 | Meaning preservation |

---

# 📈 Final Evaluation Report

## 1️⃣ BLEU Score
Indicates how different the paraphrased text is from the original.  
A moderate score shows reduced copying.

## 2️⃣ ROUGE Scores
Measure how much important content is retained.  
Higher scores indicate better content preservation.

## 3️⃣ Semantic Similarity
Measures meaning similarity using embeddings.  
A high score confirms accurate paraphrasing.

## ✅ Overall Conclusion
The model generates fluent, grammatically correct, and meaningful paraphrases.  
It effectively balances originality and semantic accuracy.

---

# 🛠 Tech Stack

| Tool                 | Purpose                      |
|----------------------|------------------------------|
| Python               | Programming language         |
| Hugging Face         | Transformer models           |
| Transformers Library | NLP model implementation     |
| PyTorch / TensorFlow | Model backend                |
| NLTK / spaCy         | Text processing              |
| Google Colab         | Development environment      |

---

# 📁 Repository Structure

ai-paraphrasing-tool/

│  
├── Module_End_Assignment6_GenAI.ipynb

├── Module End Assignmnet6_GenAI.pdf

├── README.md  

---

# 🚀 How to Run the Project

## 1️⃣ Open in Google Colab
Use the link above to run directly.

## 2️⃣ Install Dependencies (if running locally)

```bash
pip install transformers torch nltk spacy
## 3️⃣ Run the Notebook

Execute all cells to generate paraphrased outputs.

---

# ⚠️ Limitations

- Output quality depends on pretrained model  
- May sometimes produce similar sentence structures  
- Limited fine-tuning on domain-specific data  
- Performance varies with input complexity  

---

# 📌 Academic Submission

This project was developed as part of a **Generative AI / NLP assignment** to demonstrate the use of transformer-based models for text paraphrasing, along with evaluation using BLEU, ROUGE, and semantic similarity metrics.

---

# 👤 Author

**Name:** Laya Mary Joy  
**Program:** Generative AI  
**Date:** April 25, 2026

---

# ⭐ Acknowledgment

Thanks to instructors and resources from **Hugging Face** and **Google Colab** for enabling this project.

---

# 🚀 Future Improvements

- Fine-tune model on custom datasets  
- Add grammar correction module  
- Build web app using Streamlit  
- Improve evaluation metrics  
- Support multiple languages  
