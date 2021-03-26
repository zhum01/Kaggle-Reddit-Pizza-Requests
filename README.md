**Problem Description**

The subreddit r/RandomActsOfPizza is an online forum where users can write posts requesting pizza deliveries from other users, who may or may not fulfill the requests.  Each post can have comments and upvotes/downvote from other users, which may influence whether a request is fulfilled or not. Other factors, including the text content of the post, time of the post, online background information about the requester, are also provided in the data set from Kaggle.

**In this project, we aim to use the Kaggle data set to train a model that predicts whether a given pizza-request post will be fulfilled or not.**

**Inference:**

**Input**: is a feature vector describing a post with $n$ number of features, which includes, among others, the text content of the post, and attributes of the requester.

**Output**: binary value indicating whether a requester received pizza or not (0=did not receive pizza, 1=received pizza).

**Models:**

* Logistic Regression
* Boosted Trees

**Training:**

Data from Kaggle split train(75%) and validation(25%), and models will be fit only to the training set and predictions will be made using the validation set.

**Scoring Metric:**

AUCROC
