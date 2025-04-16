# Home_Assignment-4_CNN
# 🤖 NLP & Deep Learning Mini Projects

This repository contains four mini-projects that demonstrate foundational concepts in Natural Language Processing (NLP) and deep learning using Python libraries like NLTK, spaCy, NumPy, and HuggingFace Transformers. These scripts are suitable for students, educators, and developers seeking to understand core NLP workflows and mechanisms.

---

## 📄 Project Overview

The following four scripts are included in this repository:

1. **NLP Preprocessing with NLTK**  
   This script tokenizes a sentence into individual words, removes English stopwords (such as "the", "are", "in"), and applies stemming using the PorterStemmer to reduce words to their base forms. It uses the sentence:  
   `"NLP techniques are used in virtual assistants like Alexa and Siri."`  
   The script prints:
   - Original tokens
   - Tokens without stopwords
   - Stemmed words

2. **Named Entity Recognition with spaCy**  
   This script loads the `en_core_web_sm` model and identifies named entities (such as PERSON, GPE, DATE, etc.) in a sentence. For each entity, it displays:
   - The entity text (e.g., Barack Obama)
   - The entity label (e.g., PERSON)
   - Start and end character positions  
   Example sentence used:  
   `"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."`

3. **Scaled Dot-Product Attention using NumPy**  
   This script manually implements the scaled dot-product attention mechanism, which is commonly used in transformer models. It:
   - Calculates dot products between query (Q) and key (K) matrices
   - Scales the results by √d
   - Applies the softmax function to compute attention weights
   - Multiplies weights with value (V) matrix to get the final output  
   Test matrices Q, K, and V are hardcoded, and attention weights and final output are printed.

4. **Sentiment Analysis using HuggingFace Transformers**  
   This script uses a pre-trained pipeline from HuggingFace (`distilbert-base-uncased-finetuned-sst-2-english`) to classify the sentiment of a sentence. It prints:
   - The predicted sentiment label (e.g., POSITIVE)
   - The model's confidence score (e.g., 0.9998)  
   The example sentence analyzed is:  
   `"Despite the high price, the performance of the new MacBook is outstanding."`

---

## 🛠️ Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/NLP-Mini-Projects.git
cd NLP-Mini-Projects

