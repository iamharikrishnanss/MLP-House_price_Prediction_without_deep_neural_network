# MLP-House_price_Prediction_without_deep_neural_network
 It performs machine learning using MLP (Multi-Layer Perceptron) regression on a housing dataset.
 ## Before tuning
 Calculates and prints the Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE) between the predicted and actual target values.
 ## Performs tuning
 Performs tuning of the MLP model by changing various parameters such as the number of hidden layer nodes, learning rate, learning rate initialization, max iterations, shuffle, and alpha. The tuning process involves creating multiple MLP models with different parameter values and evaluating their performance on a tuning (validation) set.Trains the MLP model with the best-tuned parameters on the training set.
 
 The tuning process involves training multiple MLP models with different parameter combinations and evaluating their performance on the tuning (validation) set. The models' performance is measured using the root mean squared error (RSME).

After the tuning process, the best-performing MLP model is selected based on the RSME value. The selected model is then evaluated on the testing set (`X_test` and `y_test`), and its performance is reported using various metrics.
 
 Then again calculating MSE, RMSE, MAE and MAPE.
 The code demonstrates how to preprocess a housing dataset, train an MLP regression model, and tune its parameters for optimal performance. The final trained model can be used to predict house prices based on the provided input variables.
