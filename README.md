# Recommendations-With-IBM-Project

### Building A Recommendation Engine With IBM!

##### This project is a part of the Data Scientist Nanodegree by Udacity. It involves a significant partnership with IBM, the provider of the dataset. The goal is to create a recommendation engine that can propose new articles to users of the IBM Watson Community.

##### Libraries Used:

* Pandas
* Numpy
* Matplotlib
* pickle
* RE
* NLTK
* Seaborn
* os
* sklearn.feature_extraction.text
* sklearn.metrics
* nltk.corpus
* nltk.stem.wordnet
* nltk.tokenize

## Overview
### I. Exploratory Data Analysis
Prior to making any recommendations, it's crucial to delve into the dataset we'll be utilizing for this project. We must answer some fundamental questions about the data, which will serve as our guide throughout the remainder of the notebook.

### II. Rank Based Recommendations
To kickstart the recommendation process, our initial step is to identify the most popular articles based solely on the number of interactions they've received. Since there are no ratings provided for the articles, we can assume that those with the highest number of interactions are the most popular. These articles are prime candidates for recommendation to new users or anyone, depending on the available information about them.

### III. User-User Based Collaborative Filtering
To enhance recommendations for IBM's platform users, we can analyze users who exhibit similar interaction patterns with items. By identifying these similarities, we can suggest relevant items to users who share comparable preferences. This approach represents a positive stride towards delivering more personalized recommendations to our users.

### IV. Content Based Recommendations
Considering the abundance of content available for each article, there exist various methods for implementing a content-based recommendation system.. 

### V. Matrix Factorization
Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with. We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.
