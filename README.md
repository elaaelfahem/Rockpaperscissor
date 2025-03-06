# Rockpaperscissor
Utilized ML techniques to predict and make decisions in the classic game.
This machine learning model predicts the next move in a Rock-Paper-Scissors game based on the previous three moves made by the player. Using K-Nearest Neighbors (KNN), the model learns patterns from historical game data and predicts the most likely next move, whether it’s Rock (0), Paper (1), or Scissors (2).

Key Features:
Dataset: The model is trained on a dataset containing sequences of moves made by the player. Each sequence includes the last three moves and the corresponding next move.
Algorithm: The model uses K-Nearest Neighbors (KNN), a simple yet powerful algorithm, to classify the next move based on the input sequence.
Evaluation: The model is evaluated using accuracy to determine how well it can predict the next move based on past data.
Key Technologies:
Python for implementation.
scikit-learn for machine learning and model evaluation.
pandas for data handling and preprocessing.
NumPy for numerical computations.
Model Workflow:
Data Collection: The dataset includes sequences of moves from previous games.
Feature Engineering: The last three moves (Move1, Move2, Move3) are used as input features, and the NextMove is the target variable.
Model Training: Using KNN, the model is trained to predict the next move based on the features of previous moves.
Prediction: Once trained, the model can predict the next move for a new set of inputs.
Accuracy: The model's performance is evaluated using accuracy metrics.
This project showcases how machine learning can be applied to games to predict behavior based on historical data. It demonstrates the power of simple algorithms in solving fun yet insightful problems like predicting a player's next move in Rock-Paper-Scissors.
