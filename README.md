# Text Sentiment Analysis
## Project Title
**"Text Sentiment Analysis"**
## Dataset
*IMDB Reviews Dataset*
## Overview
This project builds a sentiment analysis pipeline that processes and analyzes movie reviews from the IMDB Reviews dataset. The main steps include:
- **Text Preprocessing:**  
  - Tokenization (splitting text into words)  
  - Stopword Removal (filtering out common, non-informative words)  
  - Lemmatization (normalizing words to their base form)
- **Feature Engineering:**  
  Transforming preprocessed text into numerical features using TF-IDF.
- **Model Training & Evaluation:**  
  Training two classifiers—Logistic Regression and Naive Bayes—to predict sentiment and evaluating their performance using metrics such as precision, recall, and F1-score.
## Required Libraries
- **pandas:** For data manipulation  
- **nltk:** For natural language processing tasks  
- **scikit-learn:** For feature extraction, model training, and evaluation
## Conclusion
This project demonstrated a complete pipeline for text sentiment analysis using the IMDB Reviews dataset. We implemented thorough text preprocessing, converted the cleaned text into numerical features using TF-IDF and trained two classifiers—Logistic Regression and Naive Bayes—to predict sentiment. While initial evaluation metrics indicate room for improvement, this project establishes a strong foundation for further optimization and experimentation with advanced techniques.
***