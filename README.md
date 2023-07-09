# Natural Language with Disaster Tweets

This project work with the data set consisting of tweets that are either normal tweets, or tweets reporting a disaster.
The aim of the project is to predict what type a certain tweet is, using different machine learning models

**Preprocessing**
\n
To obtain the best results as possible, we chose to perform some preprocessing to our data before fitting the models.
The chosen preprocessings we did was as follows:

Removing or filling Na-values
Removing duplicates
Converting all letters to lower case
Removing mentions (@) in tweets
Removing URLs
Removing email-addresses
Removing punctuations
Removing digits
Removing emojis
Removing English stopwords
Perform stemming
Perform Lemmatization

**Models**
We chose the following models

Random Forest Classifier Model
Logistic regression model
Decision Tree Classifier

## Findings

**Random Forest Classifier Model**
Accuracy Score: 79.5693%
Precision Score: 88.4058%
Recall Score: 60.0246%
F_1 Score: 71.5018%

**Logistic regression model**
Accuracy Score: 81.0924%
Precision Score: 81.5021%
Recall Score: 72.0787%
F_1 Score: 76.5013%

**Decision Tree Classifier**
score: 0.77549


## Challenges

We had some challenges creating the final submission in the right format. We did a quick fix, which might not meet the required format. At least the code should be right.
