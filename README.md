# machine-learning-challenge

In this exercise, two model are used to do classification. As seen in the first model's notebook (model_1), Data structures are examined and appropriate features are selected. 
* *Note: I did label encoding for the output variable, changing from string to numbers.* 

Comparing the two models, SVM is better in classification than logistic regression. The accuracy rate increased from around 60% to 82%. Within the SVM, it's pretty good out of the box, but after the tuning, the accuracy rate increase from 82% to 84%. 

For SVM, people usually to dimension reduction using PCA, however, after checking the scree plot, we can see that all the components accounts for some significant amount of variance, and there is no "elbow" point. Therefore I kept the model as it is. 
