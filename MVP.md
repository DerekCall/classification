# Classifying All-NBA Selections

 My goal is to classify NBA players that will be selected to an All-NBA team at the end of a season. I am using NBA player statistics for the past 70 years to determine which players will be classified as All-NBA after inputting season statistics in many different categories.
 
A simple random forest model, along with a decision tree and Logistic regression model have been fitted to the data. Each model had high accuracy scores. The dataset is very imbalanced, with only about three percent of NBA players being selected to All-NBA teams each year.

 ![](https://github.com/DerekCall/classification/blob/master/Screen%20Shot%202021-10-25%20at%205.36.48%20PM.png?raw=true)

This preliminary analysis has provided the important features when using a random forest classification model. I will continue to use different metrics to rate the efficacy of the chosen model, as accuracy is not the most appropriate method considering the imbalance in the dataset. Using different threshold levels along with undersampling will hopefully provide a more appropriate end model for classification. 


