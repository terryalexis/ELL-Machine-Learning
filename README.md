# ELL-Machine-Learning

[Jump to poster summary](#code-and-results)

## Overview

This was the final project for my Machine Learning class.  I worked with one other person to compete in the [Feedback Prize - English Language Learning](https://www.kaggle.com/competitions/feedback-prize-english-language-learning) competition on [Kaggle](https://www.kaggle.com).  The competition was hosted by Vanderbilt University and The Learning Agency Lab.

### Goals

<ul>
  <li>Improve automated language assessment tools for English Language Learners (ELLs)</li>
  <li>Train a model to accurately assess the language proficiency of English Language Learners (ELLs) in 8th-12th grade using their essays</li>
</ul>

### Training Dataset

There were roughly 3,900 argumentative essays in the provided training dataset with a median word count of about 400 words. Each essay had six scores on a scale of 1.0 to 5.0 in the following categories: cohesion, syntax, vocabulary, phraseology, grammar, and conventions.  We had to train a model to predict the score of each of those categories for a given essay.

### Data Pre-Processing

We removed stop words (i.e. words that don't provide much information such as "a", "are", or "the"), downcased and cleaned whitespace, and implemented word embedding (i.e. represented words with numerical vectors).

### Models Tried

<ul>
  <li>Ridge Regression</li>
  <li>ElasticNet</li>
  <li>Lasso</li>
  <li>Random Forest Regressor</li>
  <li>Gradient Boosing Regressor</li>
  <li>Pytorch Neural Network</li>
</ul>

**Looking back, we would try more models with word embedding such as a Recurrent Neural Network (RNN) and Long Short-Term Memory Network (LSTM), we just hadn't learned about those models yet at that point in time.

## Code and Results

The final code submission can be found at https://www.kaggle.com/code/alexisterry/english/notebook </br>

Of all models tried, the best-scoring model was the Gradient Boosing Regressor with a score of 0.56. (For reference, the winning score in the competition was 0.43)<br>

The following is a poster summarizing the competition and results of the models tried: </br>

![English Language Learning (2)](https://github.com/terryalexis/ESL-Machine-Learning/assets/70789551/838c7ddd-1223-4110-8f8f-c45fb68dda69)
