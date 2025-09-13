Predicting Student Participation Likelihood

Project Overview:-
This project predicts the likelihood that a student will actively participate in class discussions based on selected behavioral and activity features. The prediction uses Logistic Regression to estimate probabilities for a binary outcome: likely to participate or not.

Dataset:-
Collected via a student survey.

Features:-
  Reads Books – whether a student reads books regularly.
  Risk taking – self-reported risk-taking behavior.
  Club top1 – primary club or group the student is part of.

Target variable:-
  Introversion extraversion – converted into a binary variable participates (1 = likely to participate, 0 = less likely).
  Code Workflow
  Data Preprocessing
  Load the dataset using pandas.
  Clean column names and handle missing values.
  Encode categorical features (Reads Books, Club top1) using LabelEncoder.
  Convert the target into a binary variable for classification.

Model Training:-
  Split the data into training and testing sets (80-20).
  Train a Logistic Regression model to predict participation probability.

Prediction and Visualization:-
  Predict participation probabilities for the test set.
  Visualize results as a bar graph showing each student’s likelihood to participate.

Output:-
  A bar graph displaying predicted probabilities of participation for each student in the test set.
  Higher bars indicate higher likelihood of participation, making it easy to identify engaged students visually.
