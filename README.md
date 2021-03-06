<div align="center">
  
# Yelp Star Rating Prediction by Natural Language Processing
</div>


<div align="center">
<img src="https://user-images.githubusercontent.com/69224996/96832144-2691c480-13f3-11eb-8e5a-b451a33525d1.png" >
</div>

<br />

<div align="justify">

Yelp is a local business directory service and review site with social networking features. It allows users to give ratings and review businesses. The review is usually short text consisting of few lines with about hundred words. Often, a review describes various dimensions about a business and the experience of user with respect to those dimensions. 

In this notebook we will use Yelp Reviews Dataset. Each observation in this dataset is a review of a particular business by a particular user. The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. In other words, it is the rating of the business by the person who wrote the review, and higher stars is better. The "cool" column is the number of "cool" votes this review received from other Yelp users. The "useful" and "funny" columns are similar to the "cool" column.

The objective of this Natural Language Processing  project is to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews. For this purpose, first we will perform exploratory data analysis. Afterwards, we will build three different models including Random Forest, Naive-Bayes and passive Agressive Classifiers and fit the models and use them with and without text preprocessing and with only removing the stop words. Ultimately, the accuracy scores and the confusion matrices will tell us how well our models perform. 

</div>
