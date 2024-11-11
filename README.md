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
       
      Code: https://colab.research.google.com/drive/1G0jUmMOv2sa_FkYdwta--RZlAh9_U84v?usp=sharing
   
      Youtube Link: https://youtu.be/cCIFGw6AO_c

      Tabular Indepth

      Code: https://colab.research.google.com/drive/10JcC8f35GbrccD_4ikmfjgxA2D1O21sP?usp=sharing
   
      Youtube Link: https://youtu.be/akZ5oWrKlF0
   
   ii. Multimodal Tabular

      Code: https://colab.research.google.com/drive/1WhSBNDpFkirfM7U6n2iJwP66ibXLQR9h?usp=sharing
   
      Youtube Link: https://youtu.be/0NkTNoJ-AWI
   
   iii. Automatic feature engineering

     Code: https://colab.research.google.com/drive/1IISk9cIq9yFRh5z4dvKYdCAPz1kPEs6x?usp=sharing
   
      Youtube Link: https://youtu.be/bypgwJ5PIys
   
   iv. Multilabel
   
     Code: https://colab.research.google.com/drive/11lERr7nIZVQp6VaR8yA-ZEFVOUZVCQEQ?usp=sharing
   
      Youtube Link: https://youtu.be/zpQiToOyhm8
   
   v. GPU

     Code: https://colab.research.google.com/drive/114UPooCLWjkcI9wjCOLQdobacQ4AbRMe?usp=sharing

     Youtube Link: https://youtu.be/V7b5tMAfmho

   vi. Text Classification

     Code: https://colab.research.google.com/drive/1ir19c23_1-LxaGgQqVJTP4d3cLWJDVWS?usp=sharing

     Youtube Link: https://youtu.be/bbwMrnXWvWA

   vii. Sentiment Analysis and Sentence Similarity

     Code: https://colab.research.google.com/drive/1a5eyQhZwlZiAF63rQ8zoReXZjoIFiriB?usp=sharing
   
     Youtube Link: https://youtu.be/L5Wrrr8bEfU

   viii. Finetune foundation models

     Code: https://colab.research.google.com/drive/1IATS-BrlKaFEiDnldnlZJa3GF3Iq9-P0?usp=sharing

     Youtube Link: https://youtu.be/KPKTk_-j45M

   ix. Named Entity Recognition

     Code: https://colab.research.google.com/drive/1GTUB_KfPV9Juis0AemYPOSOq9APl7RVr?usp=sharing
   
     Youtube Link: https://youtu.be/NIyrXiEDYtU
   
   x. Text Similarity Matching

     Code: https://colab.research.google.com/drive/1E_g68ecrWUk7nNxymzIYVMMCZ6RSWCUp?usp=sharing
   
     Youtube Link: https://youtu.be/Z1GVs3kcMI8

   xi. Image Classifier

     Code: https://colab.research.google.com/drive/1GjHuHeDfMfv72RFPVbEB7mq3uY06n6p4?usp=sharing
   
     Youtube Link: https://youtu.be/GMOsakiSy-E

   xii. Zero shot classification

     Code: https://colab.research.google.com/drive/16_ESdEEm8zlRq70qGv-HGZl44Tl4oMaD?usp=sharing
   
     Youtube Link: https://youtu.be/OAkCOfg_ze4

   xiii. Image Object Detection

     Code: https://colab.research.google.com/drive/1hr0-Uh8by0mR4ubXYI4m07rNeFA2h-na?usp=sharing
   
     Youtube Link: https://youtu.be/E6SA3x8Wovo

   xiv. Image Segmentation

     Code: https://colab.research.google.com/drive/1yihg6CvmJ-vFdbn8T1cj64f3d1CilWeq?usp=sharing
   
     Youtube Link: https://youtu.be/E6SA3x8Wovo

   xv. Document classification

     Code: https://colab.research.google.com/drive/1b4xxuOnpBb679zyKxGOKkXfqzLIBTAQa?usp=sharing
   
     Youtube Link: https://youtu.be/yfu2vKBZTvc

   xvi. PDF classification

     Code: https://colab.research.google.com/drive/1-kQ188qdW7LxerV7LxUUMGzXuOBgpszD?usp=sharing
   
     Youtube Link: https://youtu.be/CXgcMsjc5h4

   xv. Image to Image

     Code: https://colab.research.google.com/drive/1oSlAkeKp4xxvdBpoDa51TPoNYvF4zHfd?usp=sharing
   
     Youtube Link: https://youtu.be/9TdAgWndCqk

   xvi. Text to Text

     Code: https://colab.research.google.com/drive/1SEW6th-a5IuLl-D9OZmZI_ZPWxaiL5hd?usp=sharing
   
     Youtube Link: https://youtu.be/gZrfWNOrNfQ

   xvii. Image Text

     Code: https://colab.research.google.com/drive/1RbxPctl6IkzdLHGHfGO_lsS_6A-XnXYK?usp=sharing
   
     Youtube Link: https://youtu.be/4VZTA2I8quk

   xviii. Image Text Zero shot

     Code: https://colab.research.google.com/drive/1q3ddq8Mmh3-lspQ-5v_gCuTYuaHRIIH1?usp=sharing

     Youtube Link: https://www.youtube.com/watch?v=pe7T5Jsu4mM

   xix. Text Semantic Search

     Code: https://colab.research.google.com/drive/19DOky3MNTYeSl4cKywfJ3wdaj_ts4p_e?usp=sharing

     Youtube Link: https://www.youtube.com/watch?v=stA_YC-kcPM&t=2s

   xx. Multi Modal Mixed Types Text Columns
   
     Code: https://colab.research.google.com/drive/1evd-WgYjUoJ_NXlHCkNaJFkmbHM5Og0j?usp=sharing
   
     Youtube Link: https://www.youtube.com/watch?v=h92R8msR_4M

   xxi. Images + text in table

     Code: https://colab.research.google.com/drive/1m_lmN77rMcMq5ZqIaOdKgFpUvsmZ5UNv?usp=sharing

     Youtube Link: https://www.youtube.com/watch?v=ERuLJQitaV8

   xxii. Entity extraction in multi modal

     Code: https://colab.research.google.com/drive/1hm0rhAZ60LM-MZQU9Y1V2sizhqg9oHdd?usp=sharing
   
     Youtube Link: https://www.youtube.com/watch?v=4_9dMiha078

   xxiii. Time series forecasting with autogluon and also zero shot chronos

     Code: https://colab.research.google.com/drive/1nQJZ-NGW_rbn_GLhQ6ZcqFuiixMNcC5B?usp=sharing

     Youtube Link: https://www.youtube.com/watch?v=ZYr_oUBaeF4

   xxiv. Multi Modal image+text+tabular prediction

     Code: https://colab.research.google.com/drive/1QkkryuCGxg5Fqwrwqb_m7kqPLRrsO6FF?usp=sharing

     Youtube Link: https://www.youtube.com/watch?v=0ewSYbtmN14

   
   

     
   
