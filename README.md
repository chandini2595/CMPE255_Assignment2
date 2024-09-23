#AUTOGLUON

1. It is an open source automated Machine Learning framework developed by AWS.
2. It simplifies the process of building highly accurate machine learning models.
3. It automates model training and optmization.

Features of AutoML:
1. Automatically selects best model for the problem.
2. Creates model ensembles and uses staking techniques, combining multiple models to achieve better performance.
3. Powerful for handling tabular/structured data.
4. Supports Natural Language Processing.
5. Combines text, image and tabular data - Multimodal

Installation of AutoGluon:
pip install autogluon

It is possible to build powerful machine learning models with 3 lines of code. Here's an example

from autogluon import TabularPredictor

p=predict(label='class').fit(train.csv)

pred=p.predict('test.csv')
