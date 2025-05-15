# News_Data_Analysis
Analysis of data from the UCI Machine Learning Repository

The source of the data in this analysis can be found here: https://archive.ics.uci.edu/dataset/332/online+news+popularity


This analysis was done as part of the coursework for the data science program at Bellevue University. The task was to demonstrate proper modeling techique while using mutliple visualizations. I chose to use a linear regression with principle component analysis to find the most relevant vectors and to eliminate any multicollinearity. 

This was done early in my program and while the model was done correctly there are multiple opportunities for optimization. First, rather than use all variables it would be benifiecal to eliminate a number of them. An assumption of the linear regression is that the features be normal. I can readily eliminate a number of the features that were modeled which would have improved model performance. Additionally, the project would have benefitted from comparing the linear regression to another model such as a Random Forest.

