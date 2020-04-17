# Balance-Scale-data-science-project

# Objective

## This data set was generated to model psychological experimental results. Each example is classified as having the balance scale tip to the right, tip to the left, or be balanced. The attributes are the left weight, the left distance, the right weight, and the right distance.

# Dataset Used

## Balance scale dataset taken from [UCI machine learning repository](http://archive.ics.uci.edu/ml/datasets/Balance+Scale)
1. No. of Instances - 625
2. No. of Attributes - 5
3. No. independent variable  - 4
4. No. dependent variable - 1

# Conclusion

## After applying 5 classification models, it was noted that our initial analysis through a mathematical model still produced the best results (100% accuracy). However, since such a perfect model was obviously impractical through Machine Learning Classification algorithms, and such drastic results can only be attributed to overfitting. Hence, we have tested our dataset on 5 different classification models. It was seen that the SVC model performed best with an accuracy of 91.48%. It can be attributed to the fact that our data is extremely polarised. Next, we saw that the KNN model performed particularly well for k>8 and best for k=20, tying in it’s accuracy with the SVC model for 91.48%. An accuracy of 91.48% is much above the threshold accuracy of 70%, our initial objective. We can conclude that our model satisfactorily classifies the data
