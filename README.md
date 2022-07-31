# Natural-Language-Processing-with-Disaster-Tweets

## Problem description
Kaggle NLP competition 'Natural Language Processing with Disaster Tweets'. The main problem is to predict if tweets describe disaster really, yes is 1 and no is 0, so it is binary classification problem. Original dataset is balanced, and the ratio of 0 and 1 is 4:3. However, according to real-world situation, I change the dataset to be imbalanced. And the final ratio of 0 and 1 is 10:1.

## Process of data analysis:
1. Text data processing.
2. Build model for balanced data first, and choose best one with F1-score.
3. Create imbalanced data with removing some data with label 1.
4. Use data augmentation to create more samples in imbalanced data.
5. Use the best model in step 2 for training.
6. F1-score for model evaluation.


## Methodology-model
+ TF-IDF + Naive Bayes
+ GloVe + LSTM
+ GloVe + GRU
+ BERT

## Methodology-data augmentation
+ Back translation (English to Spanish/German to English)
+ Random Insertion
+ Text generation

