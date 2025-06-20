# prompt2books
Midterm project for Natural Language Processing - AIGC-5501

# Book Recommender using TF-IDF & N-Gram Matching

This project explores how simple NLP techniques can help recommend books based on natural-language queries like  
> “a funny book for vacation” or “a love story that made me cry”.

## Objective
Help users discover relevant and emotionally aligned books by matching their free-form prompts with book metadata using TF-IDF vectorization.

## Key Features
- **TF-IDF Vectorizer** with Unigram and N-Gram (1,2) support  
- **Cosine Similarity** to compare user input with books  
- Handles vague, emotional, and user-style queries  
- Evaluation across multiple prompts and models  
- Custom plot showing model performance across queries

## Dataset
Sourced from [Books Dataset on Kaggle](https://www.kaggle.com/datasets/elvinagammed/books-dataset):  
- ~103,000 books  
- Fields used: `Title`, `Authors`, `Category`, `Description`  
- Cleaned using lemmatization, stopword filtering, punctuation removal

## System Pipeline

