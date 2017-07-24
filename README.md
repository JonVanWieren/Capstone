# Capstone
Capstone project for Data Science Immersive course at General Assembly, Atlanta, GA, July 2017

This capstone project attempts to select the winner of Major League Baseball games, using only data that would be available
to someone wanting to bet on the games. Data was first downloaded from www.retrosheet.com, and then changed so that only 
information from previous games would be used to pick a game. 

Data cleaning and creating was a big part of this project. As an example, if the Los Angeles Dodgers are playing in their 
50th game of the season, and a gambler wants to look at the past 10 games for patterns in the data, information from their
games 40-49 needs to be pulled. I used 3, 5, 8, 13, 21 and 34 day lookback periods and a number of different data points. 

Nine models were introduced and tested, including Logistic Regression, Random Forest, and a Support Vector Classifier. 
