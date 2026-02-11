# DecisionTree_iris_dataset
Using DecisionTree to classify the types of flower (DecisionTreeClassifer)
2 types of decision tree in scikit-learn,  DecisionTreeClassifier and DecisionTreeRegressor
Regression trees estimate values of continuous target variables, while classification trees predict outcomes of categorical target variables.
(Gini Impurity measures the likelihood of a random sample being incorrectly labeled if it were classified according to the distribution of labels in a dataset.)

Decision trees are among the most common data mining methods used to partition a set or subset of observations to reach specific decision points based on certain criteria.
We can use the decision tree model to understand the relationship between the target variable and the input variable. In fact, the decision tree handles complex relationships, such as non-linearity and interactions, rather well. 

The value of a leaf node represents the prediction for the target variable for observations classified into that node. If the target variable is categorical, the value of the leaf node is the mode, the most frequent class.  
Every parent node has only two child nodes, meaning the tree is split into two sub-samples at each decision point. 
The homogeneity of each subset reflects the quality of the split from a parent node to its child nodes. In classification trees, homogeneity is measured by Gini and entropy.
Both Gini and entropy measure the impurity of a node, but differ in their theoretical backgrounds. 
By comparing the impurity decrease across all possible splits in all input variables, the split with the highest reduction in impurity will be chosen.

For example, the Gini index of node  in the decision tree can be calculated as: 
Gini(A) = 1−∑mi=1(Pi)^2
where  represents the number of classes in the target variable
Pi denotes the proportion of observations in node that belong to class  
