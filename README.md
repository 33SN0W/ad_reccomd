# YouTube Ad Recommender

## Overview

This project centers on developing a machine learning-driven YouTube Ad Recommender system to refine advertisement targeting. By analyzing video titles and descriptions, the aim is to predict appropriate categories and offer tailored ad recommendations.


## Data Preprocessing

   - Rectified missing values and standardized text data.
   - Lowercased all text, eliminated numerical values, punctuation, and whitespace.
   - Enhanced textual data quality through lemmatization and stop word removal.
   - Employed label encoding on the target variable for model training.
    
## Text Vectorization and Feature Engineering

   - Implemented TF-IDF vectorization to convert textual features into numerical representations.
   - Leveraged unigram and bigram features for both title and description texts.
   - Conducted in-depth feature analysis, extracting valuable insights for each class.

## Modeling and Training

  -  Segregated the data into training and testing sets to assess model performance.
  -  Trained Naive Bayes and SVM models on combined features extracted from title and description texts.

## Performance Evaluation and Analysis

   - Assessed model performance using precision, recall, and a confusion matrix.
   - Visualized precision-recall curves for Naive Bayes and SVM, providing a holistic view of model performance.
   - Effectively communicated findings through lucid and impactful visualizations.

