# Personality-Prediction

#Introduction
The aim of the project is to predict the personality of a specific person. The project incudes building and training of a model capable of predicting a person's MBTI label using only what people post in online forums.
This project uses Natural Language processing (NLP) as the processed data is used to classify and assign MBTI labels to a person’s online forum posts.

#Dataset Used
The dataset contains 8675 rows of data. On each row, there is: 
  • person’s type in the form of 4 letter code
  • The posts made by the person
The four-letter code is the combination of 8 variables (four binary variables).

#Personality types
Each personality type consists of four binary variables i.e the four labels, they are:
  • Mind: Introverted (I) or Extraverted (E)
  • Energy: Sensing (S) or Intuitive (N)
  • Nature: Feeling (F) or Thinking (T)
  • Tactics: Perceiving (P) or Judging (J)

The combination of these eight classes gives the final personality type. The distribution 
of the personality types is shown in the figure below:

#Approach 
-Goals 
  The aim is to classify the personality type of a person on the MBTI labels based upon 
  the posts available to us.
-Tasks 
  • Removing data imbalance
  • Splitting the dataset into test and train set
  • Pre-processing the dataset for further analysis 
  • Trying various models and find the best one for personality prediction
  • Training the model class wise 
  • Prediction made on the test data for each of the four characteristics (classes)
