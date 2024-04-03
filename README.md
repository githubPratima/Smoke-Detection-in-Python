Task: A collection of data points on various parameters related to air entities and our task is to realize when there is smoke according to the data passed. This is a binary classification task wherein we have to classify if there is smoke or not.


Introduction: This project is about a smoke detection system that introduces a smoke detector to determine a fire or not. It helps to give a warning to people about the smoke fire, carbon monoxide, or other fire-related or general notification emergencies which are detected in their surroundings. Some of the classifiers that we used in this project are KNeighborsClassifier, SGDClassfier, LogisticRegression, RandomForestClassifeir, GradientBoostingClassifier, AdaBoostClassifier, etc. In this project for getting the result of smoke detection, I have done data exploration, data cleaning, data splitting, and feeding the data to various models, and plot results, and fine-tune model stacking.

Experiments and Results:
The smoke detection dataset contains 16 columns in total which are mentioned below in detail.
Feature Description:
      The project consists of only numerical features; there are no categorical features. For example 
1.	UTC - The time when the experiment was performed.
2.	Raw H2 - The amount of Raw Hydrogen present in the surroundings.
3.	Temperature -Surroundings temperature in Celsius
4.	Humidity - The air humidity during the experiment.
5.	TVOC - Total Volatile Organic Compounds in ppb (parts per billion)
6.	eCo2 - CO2 equivalent concentration in ppm (parts per million)
7.	Raw Ethanol - The amount of Raw Ethanol present in the surroundings.
8.	Pressure - Air pressure. Measured in hPa
9.	PM1.0 - Particulate matter of diameter less than 1.0 micrometer .
10.	PM2.5 - Particulate matter of diameter less than 2.5 micrometers.
11.	NC0.5 - Concentration of particulate matter of diameter less than 0.5 micrometers.
12.	NC1.0 - Concentration of particulate matter of diameter less than 1.0 micrometers.
13.	NC2.5 - Concentration of particulate matter of diameter less than 2.5 micrometers.
14.	CNT - Simple Count.
15.	Fire Alarm - (Reality) If the fire was present then the value is 1 else it is 0.


Conclusion:
To conclude we displayed all the results such as accuracy, f1 score, auc score and classification report. We also did 5-fold cross validation on the trained stacking classifier. 
	Cross-validation is a resampling procedure used to evaluate machine learning models on a limited data sample.
	The procedure has a single parameter called k that refers to the number of groups that a given data sample is to be split into. As such, the procedure is often called k-fold cross-validation. When a specific value for k is chosen, it may be used in place of k in the reference to the model, such as k=10 becoming 10-fold cross-validation.
	Cross-validation is primarily used in applied machine learning to estimate the skill of a machine learning model on unseen data. That is, to use a limited sample in order to estimate how the model is expected to perform in general when used to make predictions on data not used during the training of the model.
	It is a popular method because it is simple to understand and because it generally results in a less biased or less optimistic estimate of the model skill than other methods, such as a simple train/test split.

 **full description in Report*
