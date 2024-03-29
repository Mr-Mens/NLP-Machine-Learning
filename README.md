# Dr Shaheen Khatoon Tutorial on Basic NLP Techniques with PySpark

## Overview
This tutorial, led by Dr. Shaheen Khatoon, Senior Lecturer in Data Science at the School of Architecture, Computing, and Engineering, University of East London, UK, introduces basic Natural Language Processing (NLP) techniques using PySpark. The focus is on preprocessing text, converting text into numerical form, and applying a regression classifier on a text corpus.

### Instructor:
- **Dr Shaheen Khatoon, Ph.D., PMP, PMI-ACP, ITIL, PgCert TLHE**
- Senior Lecturer in Data Science (Computer Science and Digital Technologies)
- School of Architecture, Computing and Engineering
- University of East London, UK

## Learning Outcomes
By the end of this tutorial, you will learn:
1. Basic NLP techniques to preprocess text.
2. Different techniques to convert text into numerical form (CountVectorizer, HashingTF, and TF-IDF).
3. How to apply a regression classifier on the text corpus.

## Prerequisites
- Basic knowledge of Python and PySpark.
- PySpark environment set up for development.
- An understanding of NLP concepts is beneficial but not mandatory.

## Tutorial Content

### Steps Involved in NLP:
The tutorial covers the following major steps in handling text data for ML modeling:
1. Reading the corpus.
2. Tokenization.
3. Cleaning/stopword removal.
4. Stemming.
5. Converting into numerical form.

### Creating a Corpus
A corpus, an entire collection of text documents such as emails, messages, or user reviews, will be used. We start with basic preprocessing using text.

### Tokenization
We divide text into tokens, removing unnecessary characters like punctuations, and explore how to do this using PySpark.

### Stopword Removal
We remove common words that add little value to the analysis, using PySpark's `StopWordsRemover`.

### Stemming and Lemmatization
We discuss the process of reducing words to their base form, focusing on the use of the nltk library for lemmatization.

### Converting Text into Numerical Form
We explore methods like Bag of Words, CountVectorizer, and TF-IDF to convert text into a form that can be used by ML algorithms.

### Text Classification Using Machine Learning
Finally, we apply what we've learned to perform text classification, predicting the sentiment of movie reviews.

## Setup and Execution
- Ensure PySpark is installed and correctly set up.
- Download the necessary datasets as indicated in the tutorial.
- Follow the step-by-step instructions provided in each section.

## What's Next?
- Experiment with TF-IDF and observe the difference in results compared to using CountVectorizer.
- Try different classification models to identify the best model using various feature engineering techniques.

## Next Lesson
- We will continue with other text representation techniques, such as word2vec, in the upcoming session.

Thank you for participating in this tutorial. Happy Learning!
