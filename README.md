# Cyber-Bullying-Classification
Problem Statement:- 
  One of the major challenges in identifying cyberbullying or cyber-aggressive comments is to detect a sender’s tone in particular text 
message, email or comments on social media, since what a person may consider to be a joke, may act as a hurting insult to another.

Objective:-
  To Predict if the given tweet is Cyber-Aggressive or Non Cyber-Aggressive. Using various ML algorithms to build prediction models,
evaluate the accuracy and performance of these models. 

Data Describtion:-
The dataset has 20001 items and all have been manually labeled.
The labels are divided into following 2 categories:
1 (Cyber-Aggressive)
0 (Non Cyber-Aggressive)
 
Data Pre Processing:-

This is a process to remove the unwanted words from tweets that does not amount to any emotions.
1. URLs- Doesn’t signify any sentiment, replace it with blank space.
2. Stop words- Words such as “a”, “is”, “the”,etc. Doesn’t  indicate any sentiment.
3. UserNames and HashTags- @ symbol before the username and # for topic; both replaced with space. 
4. Stemming - Removing prefix and suffix from the word 
5. Converting all the letters to lowercase.

