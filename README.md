# tenderDemo

Tender is a prototype online platform for building and training personal shopping bots to help users reduce the time, mental load, and annoyance of searching through e-commerce sites for the perfect product.

## Tender helps users:

+ Seamlessly communicate their information through linked social media profiles
+ Quickly and easily setup their ShopBot assistant
+ Train their ShopBot over time with minimal daily prompts about products

## How It Works
ShopBot works by scraping data from user' social media profiles including age, personality, and likes/dislikes to build an initial model of their stated preferences compared to a database of others users. ShopBot then learns user's specific preferences by showing a series of images of different products and asking them to like or dislike them, while also tracking engagement with each product through facial recognition. ShopBot continues to learn preferences daily, sending out a notification asking users' to swipe right to like, or swipe left to dislike a handful of products. All of this information is run through the Tender neural network, constantly retraining and perfecting each ShopBot’s individual purchasing ability.

## Technology Used:
### For Social Media Profile Scraping
+ Facebook API
+ Apply Magic Sauce Datamining API

### For Training the Sockbot
+ Affectiva API for Facial Recognition
+ TensorFlow, Keras, Jupyter for Machine Learning

### User Interface
+ node.js
+ HTML/CSS/Javascript
