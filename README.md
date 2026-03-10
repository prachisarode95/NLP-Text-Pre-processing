# NLP-Text-Pre-processing

This assignment includes the task of taking two paragraphs as a single input and applying a series of cleaning and normalization steps before the text can be used in any NLP or machine learning operation.

---

## Input

Two paragraphs are used as a combined input string. The paragraphs cover the text intentionally include multiple punctuation marks such as periods, commas, colons, semicolons, exclamation marks, and question marks to demonstrate proper punctuation removal.

---

## Pre-processing Techniques Applied

1. Punctuation Removal 

2. Stop Word Removal 

3. Stemming 

4. Lemmatization

---

## Tools and Libraries

- Python 3
- NLTK (Natural Language Toolkit)
- Google Colab (execution environment)

---

## File

- `NLP_Text_Preprocessing_Assignment.ipynb`

---

## Observations

Stemming is faster but may produce non-dictionary word forms. Lemmatization is slower but produces linguistically accurate base forms. Stop word removal and punctuation removal together significantly reduce the token count, leaving only the meaningful content words from the original text.
