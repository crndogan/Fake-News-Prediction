# Fake vs. Real News Detection

## Overview
This project focuses on detecting fake vs. real news headlines using web scraping, natural language processing (NLP), and machine learning.  
The workflow is divided into three parts:
1. Data collection via web scraping
2. Text analysis with NLP methods
3. Machine learning model training and evaluation

## Project Structure
- FakeNewsScraping.ipynb  
  Scrapes and cleans fake news articles.
- RealNewsScraping.ipynb  
  Scrapes and cleans real news articles.
- FakeNews_WordAnalysis.ipynb  
  Preprocesses and analyzes fake news text (word frequency, word clouds).
  RealNews_WordAnalysis.ipynb  
  Preprocesses and analyzes real news text.
- ML_FakeNewsPrediction.ipynb  
  Builds and evaluates classification models.

## Tech Stack
- Web Scraping: BeautifulSoup, requests  
- NLP: NLTK, scikit-learn (TF-IDF, stopwords, lemmatization)  
- Machine Learning: Logistic Regression, Random Forest, SVM  
- Visualization: Matplotlib, WordCloud  

## Workflow
1. Scrape fake and real news data.  
2. Clean and preprocess text (tokenization, stopword removal, lemmatization).  
3. Perform exploratory word analysis (frequency, visualizations).  
4. Convert text to numerical features using TF-IDF.  
5. Train machine learning models and compare performance with accuracy, precision, recall, and F1-score.

## Results
- Highlighted language differences between fake and real news.  
- Built ML models that classify news authenticity with measurable accuracy.  
- Demonstrated how unstructured text can be transformed into structured features for predictive modeling.
