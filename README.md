# VoiceClassification
An advanced Classification model categorizes voice clips to select radio jockeys for the company. It utilizes sophisticated algorithms for precise classification.

## Problem Statement
Motion Studios is the largest production house in ERuope. Its total revenue is $1B+. The company has launched a new reality TV show called "The Star RJ"
The show is aout finding a new radio jockey who will be the star presenter on upcoming shows.
In the first round, participants will have to upload their voice clips online which then will be evaluated by experts for selection to the next round.
There is a seperate team in the first round for evaluation of male and female voices. 
The response to the show is unprecendented, and the company is flooded with voice clips.
As a result, there is a need to classify the voice as either male or female such taht the first level of filtration is quicker.

## Steps Covered 
1. Importing necessary libraries and dataset
2. Checking for missing values in that dataset
3. Checking the distrubution of the dataset
4. Preprocessing the data using label encoders
5. Fitting SVM classifier on the tranformed data
6. Printing the accuracy, confusion matrix, and the classification report
7. Using grid search to optimize results further
8. Printing new accuracy, confustion matrix, and classification report of optimized model
