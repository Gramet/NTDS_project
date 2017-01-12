# NTDS_project
NTDS project : Twitter users gender classification

To do list : 
-

- then (optional) by combining and weighting the features
- Test with external data
- Maybe get other datasets (facebook, multiple tweets of single user,...)

Done : 
-

- find word predictors in text/description, find color predictors in sidebar and link color profile
- (optional) provide image to [google feature extraction](https://cloud.google.com/vision) for example, find features predictors based on text
- display predictors
- create model for prediction, first with separate features


Project insight:
-

The goal  of this project is to predict the gender of twitter users based on various features, especially on the tweets they post. We will try to analyze how well do words in tweets can define the gender of a user, and also see which words are the most important for gender prediction.  

Our project would consist in : 
- The use of a Kaggle data set as a basic training and testing data : 
https://www.kaggle.com/crowdflower/twitter-user-gender-classification
- Creation of another database of twitter users
- Extraction of relevant features
- Maybe apply the same algorithm on Facebook data, in order to observe if the results differ, due to difference of behavior depending on the social network.
- On the basis of gender, maybe we can try to predict other information of the users like hobbies, characteristics, or even shopping preferences and social networks.

TA's comment : 
- Well defined as a Kaggle competition.
- How do you choose which users to collect tweets from ? Be careful of bias in training data. Anyway you should do this at the end. Work on the model first.
- By "extraction of relevant features", you mean hand-crafted features to be fed to a classifier ?
- Which algorithm will you test first for classification ?
- What will you do for data exploration ?
- Would be interesting to see which of text or profile picture has the most predictive power.


