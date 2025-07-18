# codetech-task-2

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: YALLALA TEJASWI

**INTERN ID**: CTO6DF1847

**DOMAIN**: MACHINE LEARNING

**DURATION**: 6 WEEEKS

**MENTOR**: NEELA SANTOSH

**📝 Task Overview**

This repository contains my submission for Task 2 of the internship, where I performed Sentiment Analysis on a dataset of customer reviews using Natural Language Processing (NLP) techniques. The primary goal was to classify the sentiments (positive or negative) from textual data using machine learning, particularly with TF-IDF vectorization and a Logistic Regression classifier.

Sentiment analysis is a powerful application of NLP that determines the emotional tone behind textual content. It is widely used in customer feedback systems, product review analysis, social media monitoring, and more.

**📊 Dataset**

The dataset used for this task consists of customer reviews labeled with their corresponding sentiment as either Positive or Negative.
Each entry contains a review in textual form and a target label indicating the sentiment. This binary classification task aims to teach a model how to distinguish between the two classes based on linguistic patterns.

**🔬 Model Pipeline**
The following steps were implemented in the Jupyter Notebook:

_**Text Preprocessing**_

Lowercased text

Removed punctuation and special characters

Removed stopwords

Applied tokenization

_Feature Extraction using TF-IDF_

Used TfidfVectorizer from sklearn to convert text data into numerical form.

Explored unigram and bigram combinations to enhance feature coverage.

_Model Building: Logistic Regression_

Trained a LogisticRegression model on the transformed text data.

Split the dataset into training and testing sets (typically 80/20 split).

_Model Evaluation_

Calculated accuracy, precision, recall, and F1-score.

Printed classification reports for performance comparison.

**📈 Learnings & Insights**
Despite the poor evaluation metrics in this run, the task was highly educational. It provided key insights into:

How raw text is transformed into numerical vectors

The importance of preprocessing in NLP

The challenges of model performance in imbalanced or small datasets

The utility of logistic regression for binary text classification

In future iterations, I plan to:

Expand the dataset size

Apply class balancing techniques (like SMOTE or oversampling)

Try advanced models such as SVM or fine-tuned BERT for better accuracy

**🔧 Tech Stack**
Python

Jupyter Notebook

Scikit-learn

NLTK

Pandas & NumPy

Matplotlib (optional for visualization)

**📁 Files Included**
sentiment.ipynb: The main Jupyter notebook containing preprocessing, model implementation, and evaluation.

OUTPUT2.jpg,OUTPUT-2.jpg: A screenshot showing the evaluation metrics output.
