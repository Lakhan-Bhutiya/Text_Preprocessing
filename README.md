#  Text Preprocessing with NLTK (NLP Basics)

This repository contains a complete **Text Preprocessing Pipeline** built using **NLTK (Natural Language Toolkit)**.  
It demonstrates how to clean and prepare raw text for **NLP** and **Machine Learning** tasks.

---

##  What This Notebook Covers

### 🔹 1. Tokenization  
Splitting text into words and sentences using NLTK tokenizers.

### 🔹 2. Stopword Removal  
Removing common words that add little meaning (e.g., "the", "is", "and").

### 🔹 3. Stemming (Porter Stemmer)  
Reducing words to their root form (e.g., "running" → "run").

### 🔹 4. Lemmatization (WordNet Lemmatizer)  
Converting words to their proper dictionary base form (e.g., "better" → "good").

### 🔹 5. POS Tagging  
Identifying the part of speech of each token (noun, verb, adjective, etc.).

### 🔹 6. Named Entity Recognition (NER)  
Extracting real-world entities like PERSON, LOCATION, and ORGANIZATION.

### 🔹 7. N-grams (Bigrams, Trigrams, N-grams)  
Extracting sequences of words to capture context.

### 🔹 8. Clean Corpus Construction  
Cleaning sentences by removing punctuation, stopwords, and applying stemming.

### 🔹 9. Frequency Distribution  
Finding the most common meaningful words in the text.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Notebook_1_Text_Preprocessing.ipynb` | Main notebook containing all preprocessing steps |
| `README.md` | Documentation file (this file) |

---

##  Why This Notebook Matters

Text preprocessing is the **foundation** of all NLP tasks.  
Before building models like sentiment analysis, document classification, chatbots, or summarizers, we must transform raw text into clean, meaningful features.

This notebook teaches:

- How to clean text  
- How to extract meaningful tokens  
- How to remove noise  
- How to prepare text for machine learning  
- How to build a clean corpus for TF-IDF or ML models  

---

## 📦 Technologies Used

- Python  
- NLTK  
- Regular Expressions (re)  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Lakhan-Bhutiya/Text_Preprocessing
   ```
2. Install required libraries:
   ```
   pip install nltk
   ```
3.Open the notebook:
   ```
   jupyter notebook

   ```
