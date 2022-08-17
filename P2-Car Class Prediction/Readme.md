# Aim Overview # 
	*the aim of this project is to implement a car class prediction KNN-based Model based on certain 
	car	features and attributes
# Implementation Sequannce #
	-Data Featching 
	-Data Shuffling & Splitting
	-string label encoding
	-KNN Implementation
	-Performance Study on a trained models on different portions of the training dataset
	-KNN Tunning for best Hyper parameter Tuning
	### KNN Tuning Description ###
	A function was coded for tuning that takes the k value, training percentage, training data, testing data,
	validation data, metric for calculating the distance. The function returns a list containing accuracy scores
	for testing and validation, time used for training and time spent in prediction for different cases. 
	
# Performance Indicators #
	-Bar Charts
	-Line Charts
	
# Conclusion #
	* Increasing the amount of data to train the model with increases the accuracy score.
	* Different shuffles of data result in different results
	* Using Different metrics for calculating the distance may result in slight changes in the output
	* The best k value is dependent on the data
	* "If for example brute force was used as the searching algorithm, during the training stage, 
		KNN classifier just remembers all the training samples. During the testing stage,
		each test sample need to find its nearest K neighbour, meaning that the classifier 
		needs to calcuate the distance between the test sample to all the training samples.
		So, changing the number of K would not lead to significant time difference during 
		the training. During the testing, using larger dataset usually needs to more time."
