# FIFA-19-Player-Value-Prediciton
## Abstract:
This project focuses on player data from FIFA 19 which is developed by Electronic Arts for the 2019 edition of their FIFA game franchise in which you can play as many club and national soccer teams. The dataset used here is available on Kaggle. It has statistics on attributes such as preferred foot, body type, and skills in passing, shooting, and goalkeeping, that all go into a player’s overall score. 

The aim of our project is to predict the Value of a player with the given attributes. The dataset provides statistics of about 18000 players on about 60 different attributes. For each attribute, we have an integer from 1 to 99 that measures how good a player is at that attribute. These attributes are optimal indicators to determine the performance of a player at a particular playing position. 

## Problem Definition
### Overview 
 
FIFA 19 gives the users an option to play the game by selecting their desired team. It also gives the users an option to customize the team by hiring, upskilling (existing) or creating (new) players. While creating a dream team, the user might spend a major portion of their budget for signing few players which make it difficult to compete and advance in the game. Since the game automatically sets a standard value for each player, the users require a method to determine the value themselves. Our project aims to address these issues.

### Problem Statement    
  
Make a regression model to objectively determine the market value of a player based on the skill set they possess, thus allowing the user to form a team of excellent and undervalued players at minimal cost.

## Result 
The Random Forest regression model is finalized to predict the value of a player with the given attributes. After necessary hyper parameter tuning our model has a MSE value of 0.0218 and a  R- squared value of 0.9884, which is a good score.

## Conclusion

FIFA 19 automatically sets a standard price for each player in the game. It is, therefore, necessary for a user to objectively determine the value of the player to form a team of excellent and undervalued players at minimal cost. For this player market value regression task, we had better results with a Random Forest Regressor. The user can now provide the skill sets of the required player in the website and the model will predict the player’s value. Then the user can determine whether to choose that particular player or create a new player with the same skill sets.

## Website
[FIFA 19 Player Value Prediction](https://tinyurl.com/2p952xv4)
