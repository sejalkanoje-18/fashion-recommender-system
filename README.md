## 👗 Fashion Recommender System
Personalized product recommendations are the alternative way of navigating through the online shop. More people find products they need. Even if they didn’t think of them. The project is a Website application for fashion recommendation using machine learning with a built-in a recommendation engine which suggests similar products to the given product.

## 💡 RECOMMENDATION SYSTEMS
Recommender systems are one of the most successful and widespread applications of machine learning technologies in business. Recommendation systems help to increase the business revenue and help customers to buy the most suitable product for them. Now, we’ll look towards different types of filtering used by recommendation engines.

## [Content-based filtering](https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd)

This filtering is based on the description or some data provided for that product. The system finds the similarity between products based on its context or description. The user’s previous history is taken into account to find similar products the user may like.

## [Collaborative filtering](https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd)
The recommendations are done based on the user’s behavior. History of the user plays an important role. For example, if the user ‘A’ likes ‘Coldplay’, ‘The Linkin Park’ and ‘Britney Spears’ while the user ‘B’ likes ‘Coldplay’, ‘The Linkin Park’ and ‘Taylor Swift’ then they have similar interests. So, there is a huge probability that the user ‘A’ would like ‘Taylor Swift’ and the user ‘B’ would like ‘Britney Spears’. This is the way collaborative filtering is done.

Two types of collaborative filtering techniques are used ]

[User-User collaborative filtering](https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd)

[Item-Item collaborative filtering](https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd)

Summary :

![Fashion-Recommender-System](https://camo.githubusercontent.com/20993343708ae9ac9184da2f00ed7754a66840226fc986c5a41cefb7d3189490/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3730302f312a6d7a39747a50314c6a5042686d695758654879516b512e706e67)

Note : In the project we will use the approach of Item-Item Collaborative filtering ☣️

## 🚧 Problem Statement 
Given a dataset of 180k apparel images from amazon.com we need to recommend the similar product based on the user choice.

The dataset given contains the following elements :
```bash
 1. asin  ( Amazon standard identification number)

2. brand ( brand to which the product belongs to )

3. color ( Color information of apparel, it can contain many colors) 

4. product_type_name (type of the apperal, ex: SHIRT/TSHIRT )

5. medium_image_url  ( url of the image )

6. title (title of the product.)

7. formatted_price (price of the product)
```
We are going to use a total of 'Four approaches' for recommending the apparel as following.

```bash
1.Bag of words model

2.tf-idf model

3.idf model

4.k nearest neighbors (KNN)
```
## 📂 DATASETS
[Dataset link](https://www.kaggle.com/datasets/ajaysh/women-apparel-recommendation-engine-amazoncom#tops_fashion.json)

## 💻🛠️ Setup and Configuration
# Jupyter Notebook
to play a little bit with/and test models, and to observe Data pre-processing follow these steps :
```bash
* Run the jupyter notebook by jupyter notebook Fashion_recommender_notebook.ipynb
* Start executing the cells by Shift+Enter
```
To run this app, you will need to follow these 3 steps:
1. Requirements
- a Laptop (obviously 😄)

- Text Editor or IDE (eg. vscode, PyCharm)

- Git installed on your Laptop.


















