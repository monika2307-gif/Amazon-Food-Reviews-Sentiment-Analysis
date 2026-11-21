# Amazon Fine Food Reviews Sentiment Analysis

## Project Overview
This project focuses on analyzing Amazon Fine Food customer reviews using Natural Language Processing (NLP), Machine Learning, and Deep Learning techniques.

The objective is to classify customer reviews into three sentiment categories:
- Negative
- Neutral
- Positive

## Business Problem
Customer reviews contain valuable feedback, but analyzing thousands of unstructured reviews manually is time-consuming. This project aims to automate sentiment classification and help understand customer opinions.

## Dataset
- Dataset: Amazon Fine Food Reviews
- Records: 568,454
- Features used: Review Text and Score
- Target: Three sentiment classes

## Technologies Used
- Python
- Pandas and NumPy
- NLTK
- Scikit-learn
- TensorFlow and Keras
- Matplotlib and Seaborn

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Text processing using NLTK
4. Feature extraction using CountVectorizer
5. Tokenization and sequence padding
6. Machine Learning and Deep Learning model building
7. Model evaluation and comparison

## Models Implemented
- Logistic Regression
- Dense Neural Network
- Simple RNN
- LSTM
- Bidirectional LSTM

## Initial Experimental Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 88.00% |
| Dense Neural Network | 89.73% |
| Simple RNN | 81.60% |
| LSTM | 90.52% |
| Bidirectional LSTM | 90.42% |

*These are the results recorded in the original notebook. The preprocessing and evaluation pipeline should be corrected and rerun before treating them as final validated results.*

## Key Learnings
- Understanding text preprocessing and NLP workflows
- Working with large text datasets
- Understanding the differences between RNN, LSTM and Bidirectional LSTM
- Comparing traditional Machine Learning with Deep Learning
- Evaluating classification models using multiple metrics

## Conclusion
This project provided practical experience in building an end-to-end sentiment analysis workflow and understanding how different Machine Learning and Deep Learning architectures perform on text classification tasks.
