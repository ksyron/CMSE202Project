# CMSE202Project
Model and Predict the best poker move to make based on simulated/historic games.
Dylan Fear, Wesley Castro, Kyle Syron, Sayeda Tasnim

**Directions**

To run the code:

1.Open the Final_Project.ipynb file and download the poker_ranking.jgp to the same directiory

2. Run all the python packages in the first cell
   
3. Run each cell in order till section 2.3

4. If you want to change the number of n_simulations to see how the number of entries can effect the models
   
5. Run section 3 in order to see models(go back and changed n_simulations if you want)
   
6. Run section 4 to see random hand and the probability that you should check or fold compare the hand rank image to see what hand you have

**ABSTRACT**

The project created is, "Model and Predict Best Poker Move to Make Based on Simulated/Historic Games". It aims to develop a computational model that evaluates poker hands and recommends the optimal move to make based on simulated game data. By leveraging the hierarchical structure of poker hand rankings and analyzing gameplay probabilities, our goal is to provide the best possible move for the player at any given moment in the game. This project implements a simulation-based approach to poker gameplay while focusing on modeling, ranking, and predicting the optimal poker hands. 

 

Python was used as the programming language, utilizing libraries such as Pandas and NumPy for facilitating data handling, Matplotlib for graphing and visualization and Scikit-learn supporting predictive modeling. The model uses random generated data created via a full poker game simulation. Key functionalities include determining hand rankings, calculating win probabilities, and suggesting the best move (check or fold) for any given scenario. 

 

Our methodology integrated rule-based logic and data-driven approaches. The method involves generating and manipulating card objects to create a complete poker game environment, including the drawing of hands, flop, turn, and river cards. The program evaluates hands by assigning a score to identify and rank poker combinations, such as flushes, straights, and full houses, using a systematic analysis of suits and scores.  

 

This project develops a machine-learning model to predict the best poker move (check or fold) based on hand rankings, leveraging simulated data for training and evaluation. The machine learning model uses a logistic regression classifier with the model being trained on poker hand ranking data. The analysis reveals that higher-ranked hands correlate strongly with a higher likelihood of checking, while lower-ranked hands favor folding. 



 

Results demonstrate the model's accuracy in predicting optimal moves across diverse gameplay scenarios. Through rigorous testing on simulated datasets, we validated the model's recommendations, ensuring they align with both probabilistic expectations and expert strategies. These results validate the model's ability to emulate strategic decision-making in poker, laying a foundation for future enhancements with more complex game scenarios and datasets. 

 

The discussion addresses challenges such as computational overhead from extensive simulations and balancing static rule-based logic with dynamic learning from data. We also explored the limitations of our approach, including potential biases in simulated data, not accounting for bluffing/when to raise or call, and proposed future enhancements, such as real-time learning and integration with live game feeds. 

 

In conclusion, this project offers a slightly simplified framework for evaluating poker hands and recommending optimal moves. The model demonstrates a classification accuracy of 95%, with a precision, recall and f-1 score of 0.96 for "fold" decisions and a precision, recall and f-1 score of 0.94 for “check”. Example predictions align with logical poker strategies, showing you should most likely fold with a hand of “10 of Clubs”, “3 of Hearts” and the house being “2 of Hearts”, “King of Spades”, “7 of Diamonds”, “Jack of Hearts” and ”4 of Clubs”. Future work involves game theory, real-time decision-making and expanding the scope to multiplayer dynamics. This model provides a scalable framework for both educational purposes and practical applications in game strategy analysis.

**Contributions**

Contributions toward the project of the team involved Dylan creating the object of the cards,deck and poker game. The next part of the project identifying hands was collaborated on by Sushit and Dylan in order to find out what hand rank you have. Wesley and Kyle helped integrate the logistic regression model  and confusion matrix with the previously defined classes so that we could predict a meaningful result. Kyle also made very helpful visuals of our code which helps the reader understand what is going on. Sayeda created the presentation with Sushit and Wesley creating the Abstract.
