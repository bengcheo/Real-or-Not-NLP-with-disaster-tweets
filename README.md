# Real-or-Not-NLP-with-disaster-tweets
 
## 2020 Kaggle Competition for identifying tweets indicating a disaster.
### Background

Similarly, the full details of the competition can be found on https://www.kaggle.com/theyellowboots/real-or-not-nlp-with-disaster-tweets/notebook
The objective of the project was to find out if a tweet would indicate a disaster or not.

### Methods
Feature engineering was used in order to distinguish the most salient features between disaster and non-disaster tweets. I investigated if there were any differences between the length of words, the number of punctuations, and the number of upper case letters between disaster and non-disaster words.
In the end, the number of punctuations emerged as the feature that could distingish between the two classes of tweets.
A Logistic Regression model was lastly utilized to distinguish between the two classes of tweets.

### Results
Results indicate the following:
1. Training Accuracy: 79% 
2. Test Accuracy:  76%
