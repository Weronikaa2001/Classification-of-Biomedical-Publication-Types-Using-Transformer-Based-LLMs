# Classification of Biomedical Publication Types Using Transformer-Based LLMs

![Library](https://img.shields.io/badge/Library-Pandas-purple)
![Library](https://img.shields.io/badge/Library-NumPy-lightgrey)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-green)
![Library](https://img.shields.io/badge/Library-PyTorch-red)
![Library](https://img.shields.io/badge/Library-Hugging%20Face%20Transformers-yellow)
![Library](https://img.shields.io/badge/Library-SciPy-blue)
![Library](https://img.shields.io/badge/Library-Matplotlib-blue)
![Library](https://img.shields.io/badge/Library-Seaborn-teal)

### 📌 Project Overview
This project focuses on the classification of biomedical publications into predefined publication types using
transformer-based large language models (LLMs). The goal is to evaluate how modern NLP models perform on
domain-specific text classification tasks in the biomedical field. 

### 📂 Project Structure
├── Classification-of-Biomedical-Publication-Types-Using-Transformer-Based-LLMs.ipynb  
├── README.md

### 🧪 Methodology

#### Data Collection
- Retrieval of biomedical publication metadata using external APIs
- Parsing and structuring of textual data from XML sources
- Construction of a labeled dataset for supervised learning

#### Exploratory Data Analysis
- Analysis of text length distributions
- Examination of class distribution across publication types
- Identification of class imbalance in the target variable

#### Data Preprocessing
- Text cleaning and normalization
- Tokenization using transformer-based tokenizers
- Handling class imbalance through class weighting
- Train–validation–test splitting

### 🤖 Models and Evaluation

Models evaluated:
- PubMed BERT
- BioClinical BERT
- Baseline BERT
- TinyBERT
- Decision Tree 

Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-macro score
- ROC–AUC

### 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
2. Open the notebook:
   ```bash
   jupyter notebook Classification-of-Biomedical-Publication-Types-Using-Transformer-Based-LLMs.ipynb

### 👤 Author

Weronika Mądro - Data Science and Businnes Analytics student, for the purpose of Machine Learning 1 course at University of Warsaw
