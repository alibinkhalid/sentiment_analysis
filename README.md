# Sentiment Analysis
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.


# Data includes:
Reviews from Oct 1999 - Oct 2012

* 568,454 reviews
* 256,059 users
* 74,258 products


# About Data
The reviews were read into a pandas dataframe, then visually analysed. Subset of dataset i.e. Review Text and Score/Rating given by the customer was used downstream. 

Ratings were given by the customers ranging from 1 to 5 with 5 being the best. 

# What is this about?
The purpose of this exercise is to identify the sentiment of the customer using their feedback left about the project. To achieve this Vader Lexicon of NLTK is used. Once the sentiment (positive/negative) has been identified then it is compared with the rating provided. Assuming that customer who have given positive reviews would have given a rating of 4 or 5. Negative reviews would come from customers who have given a rating of 1 or 2. 

In the next step topic modeling is done using LDA.


## References
https://www.kaggle.com/snap/amazon-fine-food-reviews/version/2
