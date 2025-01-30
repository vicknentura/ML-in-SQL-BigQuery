Google Cloud x MLB Hackathon 
Challenge 5: Prospect Prediction


# **Methodology**

1. Train the regression-based prediction model using the MLB statistics on each player from each team.
  * Test linear regression, LASSO, Ridge, and ensemble methods like DT and RF

2. Find an optimal set of player stats using available performance fields and evaluate model performance using regression metrics (MSE, RMSE, and MAE)
  * Consider feature selection techniques like RFE and feature importnace in the case of DT and RF

3. Use historical league data as layers of training to reinforce the best player rankings potentially using a neural network and re-evaluate the performance
  * Transfer learning

4. Run the players from other leagues through the model and obtain a ranking
  * Consider a validation step for how well the model performs on these players compared to MLB players
