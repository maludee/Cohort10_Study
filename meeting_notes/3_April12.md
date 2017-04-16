## April 12th, 2017   

### Algorithms:   

_Bayes Review:_    
1. Multinomial Naive Bayes - Designed for text documents. Rather than taking into account the presence of a word as a binomial, word counts are features.   
2. Gaussian Naive Bayes - for continuous features, like temperature or MPH
3. Bernoulli Naive Bayes - for binomial features

Pros: scales well, fast, interpretable in that the output is a probability     
Cons: usually doesn't do as well as other models, and the central assumption that features are independent isn’t always true

_SVMs - Support Vector Machines_   
Classifier. Finds a decision boundary/hyperplane that separates two classes with the greatest possible margin between the classes. 
Can use kernels if the data is not linearly separable.

Pros: works well on small datasets, linear SVM doesn’t overfit, not affected by outliers, interpretable, good with mixed data (combination of continuous and categorical)    
Cons: expensive for large datasets - shouldn’t have too many rows or columns (features)

### Miscellaneous:

Gradient Boosted Trees - read explanation here: http://blog.kaggle.com/2017/01/23/a-kaggle-master-explains-gradient-boosting/ 

Gradient Descent - finds the minimum of the cost function. 
