# Doctor Bot – Chronic Kidney Disease Chatbot

## Overview
Doctor Bot is a simple chatbot that answers questions about Chronic Kidney Disease (CKD). It uses Natural Language Processing (NLP) to analyze a medical article and provide relevant answers based on user input.

## How it works
The project extracts text from a medical article and splits it into sentences. When the user asks a question, the bot compares it with the sentences using TF-IDF (CountVectorizer) and cosine similarity. It then returns the most relevant sentence as the answer.

## Features
- Answers questions about Chronic Kidney Disease
- Uses NLP techniques for text processing
- Finds similarity between user input and article text
- Simple command-line interface

## Technologies Used
- Python
- NLTK
- Scikit-learn
- Newspaper3k

## How to Run
1. Install dependencies:

2. 
2. Download NLTK data:
```python
import nltk
nltk.download('punkt')

python bot.py
