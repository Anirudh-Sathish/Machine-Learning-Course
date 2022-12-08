# Day 3 
_Anirudh Sathish_

## Tasks
1. Perform the KNN on Sonar dataset with and without in-built functions for K=1, 3, 5, 7.
2. Break the 60 features into 6 subsets having 10 features each. Perform the KNN and then compare the performance.
3. Divide them into 6 subsets and perform the classification on each subset. Then perform the majority voting for classification.
4. Also, perform the same tasks for 5 subsets..

## Extra Notes on the Solution 
- For the in built functions of Question 1 , KNN Classifier from sklearn is used 
- For the case without the inbuilt function in Question1 ,I have created a class called as _handmadeknnClassifier_ , which is a KNN classifier for which i have written code from scratch 
- Further for the 2nd Question , I broke down the features into 6 subsets and then independetly performed knn classification for the _k values : 1,3,5,7_ and computed the accuracy
- For the third Question , the same subsets from above were used and then knn Classification was performed simmilary , except in the case a polling function was created and used so as to combine the predictions of the subsets 
- For the 4th Question , the computation is simmilar to the 2nd and third , the only difference being the features are divided into 12 subsets  