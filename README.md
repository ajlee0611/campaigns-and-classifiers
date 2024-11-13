# Analysis of Banking Campaigns

### Summary of Findings

In this exercise, we utilized data from a Portuguese banking institution that contain the results of multiple marketing campaigns with the goal to get customers to subscribe to a term deposit. As part of the objective we were tasked to find the most impactful features that led to a 'yes' decision from customers. Using a RandomTreeClassifier, we were able to deduce
that the duration of a campaign was much more important than the amount of campaigns themselves.

In the next part of this notebook, we used different classifiers to identify which modeling technique was most accurate and efficient in processing the data. Utilizing logistic regression as a baseline, we compared the KNN algorithm, SVM model, and DecisionTreeClassifier() against each other. While all models had a remarkably similar test and training score, it was
abundantly clear that the DecisionTree had the fastest average training time, while the SVM model had a training time greater than the others by a magnitude of over 100. From this, we can conclude that the SVM model is not efficient compared to the other 3.
