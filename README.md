# Avito-Demand-Prediction

##Instructor: Johnston Patrick Hall##

##Team Name:##

*Master GY*

##Team Member:##

* Hsia, Pei-Hsuan
* Liu, Miki
* Xing, Guangyu
* Zeng, Jiwei 

**Finish Date:** June 27th, 2018

## About the Project

##Avito.ru## is the most popular classifieds site in Russia and is the third biggest classifieds site in the world after Craigslist and the Chinese website 58.com. In December 2016, it had more than 35 million unique monthly visitors. On average, Avito.ru's users post more than 500,000 new ads daily and the overall ads are about 30 million active listings.

https://www.kaggle.com/c/avito-demand-prediction

When selling used goods online, a combination of tiny, nuanced details in a product description can make a big difference in drumming up interest. And, even with an optimized product listing, demand for a product may simply not exist–frustrating sellers who may have over-invested in marketing.

##Target:## In this competition, Avito is challenging us to predict demand for an online advertisement based on its full description (title, description, images, etc.), its context (geographically where it was posted, similar ads already posted) and historical demand for similar ads in similar contexts. With this information, Avito can inform sellers on how to best optimize their listing and provide some indication of how much interest they should realistically expect to receive.

About the Notebook

One more exciting competition ahead and this involves both NLP (text data in Russian) and Image data along with numerical. In this notebook, we will take a look at feature extraction, text mining and Gradient Boosting Machine models training.

##Steps:##

1. Import data sets
2. Translate columns in Russian into ones in English or substitute Cylliric Alphabets with Roman Alphabets
3. Split the Training datasets into Training and Validation
4. Fill null values
5. Feature Extraction from active and period tables
5. Feature extraction with text columns
6. Label Encoding
7. TF-IDF 
8. Wordbatch
9. Image Feature extraction with Keras
10. Train model with Light GBM
11. Train model with XGBoost
12. Submit results and select model
