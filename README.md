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

  Code: https://colab.research.google.com/drive/1UMKIBuF0TvS8R2Jl21IGvZJQsBQa2_EA?usp=sharing
   
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

   vi. Text Classification

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Autogluon_Text_Classification.ipynb

     Youtube Link: https://youtu.be/bbwMrnXWvWA

   vii. Sentiment Analysis and Sentence Similarity

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Sentiment_Analysis_And_Sentence_Similarity.ipynb

     Youtube Link: https://youtu.be/L5Wrrr8bEfU

   viii. Finetune foundation models

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Finetune_Models.ipynb

     Youtube Link: https://youtu.be/KPKTk_-j45M

   ix. Named Entity Recognition

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Named_Entity_Recognition.ipynb
   
     Youtube Link: https://youtu.be/NIyrXiEDYtU
   
   x. Text Similarity Matching

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Text_Similarity_Matching.ipynb
   
     Youtube Link: https://youtu.be/Z1GVs3kcMI8

   xi. Image Classifier

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Image_classifier.ipynb
   
     Youtube Link: https://youtu.be/GMOsakiSy-E

   xii. Zero shot classification

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Zero_Shot_Image_Classification_with_CLIP.ipynb
   
     Youtube Link: https://youtu.be/OAkCOfg_ze4

   xiii. Image Object Detection

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Image_Object_Detection.ipynb
   
     Youtube Link: https://youtu.be/E6SA3x8Wovo

   xiv. Image Segmentation

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Image_Segmentation.ipynb
   
     Youtube Link: https://youtu.be/E6SA3x8Wovo

   xv. Document classification

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Document_Classification.ipynb
   
     Youtube Link: https://youtu.be/yfu2vKBZTvc

   xvi. PDF classification

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/PDF_Classification.ipynb
   
     Youtube Link: https://youtu.be/CXgcMsjc5h4

   xv. Image to Image

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Image_to_Image.ipynb
   
     Youtube Link: https://youtu.be/9TdAgWndCqk

   xvi. Text to Text

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Text_to_Text.ipynb
   
     Youtube Link: https://youtu.be/gZrfWNOrNfQ

   xvii. Image Text

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Image_Text_Matching.ipynb
   
     Youtube Link: https://youtu.be/4VZTA2I8quk

   xviii. Image Text Zero shot

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Zero_Shot_Image_Text_Matching.ipynb

     Youtube Link: https://www.youtube.com/watch?v=pe7T5Jsu4mM

   xix. Text Semantic Search

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Text_Semantic_Search.ipynb

     Youtube Link: https://www.youtube.com/watch?v=stA_YC-kcPM&t=2s

   xx. Multi Modal Mixed Types Text Columns
   
     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Multi_modal_mixed_types_text_columns.ipynb

     Youtube Link: https://www.youtube.com/watch?v=h92R8msR_4M

   xxi. Images + text in table

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Autogluon_Image_Text_G2.ipynb

     Youtube Link: https://www.youtube.com/watch?v=ERuLJQitaV8

   xxii. Entity extraction in multi modal

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Entity_Extraction_in_Multimodal.ipynb

     Youtube Link: https://www.youtube.com/watch?v=4_9dMiha078

   xxiii. Time series forecasting with autogluon and also zero shot chronos

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Time_series_forecasting_with_autogluon.ipynb

     Youtube Link: https://www.youtube.com/watch?v=ZYr_oUBaeF4

   xxiv. Multi Modal image+text+tabular prediction

     Code: https://github.com/chandini2595/CMPE255_Assignment2/blob/main/Multi_Modal_image%2Btext%2Btabular_prediction.ipynb

     Youtube Link: https://www.youtube.com/watch?v=0ewSYbtmN14

   
   

     
   
