# AutoMPGPrediction-MachineLearning
 
The 398 car records in the Auto MPG sample data set span the years 1970 to 1982. It includes information about the car's name, MPG, cylinder tally, horsepower, and weight. Here, using deep learning models, I will attempt to predict the miles per gallon (MPG) of a car. I have downloaded the dataset AUTO MPG rom the UCI Machine Learning Repository (http://archive.ics.uci.edu/ml/datasets.php)

Methodology:  
For this particular problem, I'll employ the deep learning work process. I'll begin by importing libraries, obtaining data, preprocessing it by handling categorical features, null values, and normalising the dataset, analysing the data, and creating a baseline model. I'll then build larger models than the baseline model, regularise the model, and adjust the hyperparameters. Review the model, obtain the results, plot the errors, save the model, reload the model for testing, and then draw a conclusion.

Due to the fact that it is a regression issue, I did not use accuracy. We frequently use error in regression problems to evaluate the effectiveness of the model.

Basic libraries like Numpy, Pandas, Matplotlib, Seaborn, and Tensorflow will be imported.
