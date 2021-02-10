> This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not a given text information is fake.

> Using this following approach:
1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Defintion

In a statement,

> Dataset Description: Build a system to identify unreliable text information(Fake news).

## 2. Data

The data is available on Kaggle. https://www.kaggle.com/c/fake-news/data

## 3. Evaluation

> If we have zero(0) as the test_label value when predicting whether a text information is fake or not during the proof of concept, we 'll pursue the object
> label feature

    1: unreliable
    0: reliable

## 4. Features

> This is where you 'll get different information about each of the features in the data.



**Create data dictionary**



**Dataset Description: Build a system to identify unreliable text information:**



    * train.csv: A full training dataset with the following attributes:
      - id: unique id
      - title: the title
      - author: author
      - text: the text of the article; could be incomplete
      - label: a label that marks the article as potentially unreliable
        1: unreliable
        0: reliable
    * test.csv: A testing training dataset with all the same attributes at train.csv without the label