# Aim Overview # 
	*the aim of this project is to implement classification models that classify students according to their knowledge level. The Models were trained through a supervised
		learning process to extract a relation between different attributes and each class.
# Implementation Sequannce #
	-Data Featching 
	-Anova Based Feature Selction
	-string label encoding
	-Implementing SVM and Perceptron to get a baseline performance
	-OVR Implementation for each class
	-OVR Aggregation using argmax
	-Classes OVO to get "n*(n-1)/2" models which in our case si models
	-OVO Aggregation
	
# Performance Indicators #
	-Confusion Matrices
	-Desicion Boundries
	
# Result #
	*SVM-based OVO and SVM-based OVR both achieved accuracy=0.9875
	*Linear Perceptron Barley Achieved Accuracy=0.8
