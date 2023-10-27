# Assignment 2: Machine Learning

About code and algorithm: The data, sourced from the TSLA.csv file, undergoes preprocessing where the 'Date' column is converted into a numerical format, called 'Date_ordinal'. After splitting the data into training and testing subsets, a Linear Regression model from the scikit-learn library is trained on the training data. The modelels accuracy is evaluated on the test data by calculating the Mean Squared Error and R^2 score. A function, predict_price, is implemented to forecast TESLAs stock price on any given future date based on this trained model. 

Why we chose this algorithm: The task is to predict the stock price of TESLA for a specific date. Since stock prices are continuous values, it is a regression problem. Regression algorithms predict continuous outputs, unlike classification algorithms which predict discrete categories. So given the nature of stock prices as continuous values, a regression algorithm, and particularly Linear Regression, is appropriate for this task. 

Brage Eilertsen (s364742), Trym Antonsen (s364596), Theodor Flatebø Jaarvik (s365337), Tobias Rønningen (s374947)
