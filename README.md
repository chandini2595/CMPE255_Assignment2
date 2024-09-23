**AUTOGLUON**

1. It is an open source automated Machine Learning framework developed by AWS.
2. It simplifies the process of building highly accurate machine learning models.
3. It automates model training and optmization.

**Features of AutoML:**
1. Automatically selects best model for the problem.
2. Creates model ensembles and uses staking techniques, combining multiple models to achieve better performance.
3. Powerful for handling tabular/structured data.
4. Supports Natural Language Processing.
5. Combines text, image and tabular data - Multimodal

**Installation of AutoGluon:**
pip install autogluon

It is possible to build powerful machine learning models with 3 lines of code. Here's an example

from autogluon import TabularPredictor

p=predict(label='class').fit(train.csv)

pred=p.predict('test.csv')

Assignments:

1. **Autogluon for Kaggle:** AutoGluon is a powerful tool that can be effectively used to compete in Kaggle competitions, especially for tasks involving tabular data (classification and regression). It automates many of the steps that are typically involved in machine learning competitions, such as model selection, hyperparameter tuning, and ensembling, allowing you to achieve competitive results with minimal effort.

  Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Autogluon_Kaggle_Competitions.ipynb
   
  Youtube Link: https://youtu.be/wq_VjjLTwSU

2. Tabular classification/regression
   
   i. Tabular Quickstart
       
      Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Autogluon_Tabular_QuickStart.ipynb
   
      Youtube Link: https://youtu.be/cCIFGw6AO_c

      Tabular Indepth

      Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Autogluon_Tabular_Indepth.ipynb
   
      Youtube Link: https://youtu.be/akZ5oWrKlF0
   
   ii. Multimodal Tabular

      Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Multimodal_Tabular.ipynb
   
      Youtube Link: https://youtu.be/0NkTNoJ-AWI
   
   iii. Automatic feature engineering

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/AutoGluonTabular_FeatureEngineering.ipynb
   
      Youtube Link: https://youtu.be/bypgwJ5PIys
   
   iv. Multilabel
   
     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/MultiLabel.ipynb
   
      Youtube Link: https://youtu.be/zpQiToOyhm8
   
   v. GPU

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Autogluon_GPU.ipynb

     Youtube Link: https://youtu.be/V7b5tMAfmho
   
