# DecisionTree_iris_dataset - Machine Learning
A Decision Tree Classifier is a highly versatile and intuitive machine learning tool useful for both technical analysis and high-level decision-making

# Real-World Applications
Beyond the Iris dataset, decision trees are used across many critical industries:
- Finance: Assessing loan approval risks by branching through credit scores, income, and debt history.
- Healthcare: Helping doctors diagnose diseases (like diabetes or COVID-19) by weighing symptoms and test results.
- Marketing: Segmenting customers into groups based on demographics or behavior to deliver personalized offers.
- Fraud Detection: Identifying suspicious credit card transactions by analyzing purchase patterns. 

## Overview
The dataset contains information on Three Species of flowers, where i use a decision tree to classify them. 

## Tools Used
- Data loading
- pandas
- matplotlib
- DecisionTree

## Notes
This project was created as a learning exercise to understand decision tree classifer

## Key Insights
- The most critical takeaway is that petal measurements are the primary predictors of iris species.
- petal length (cm) <= 2.45 as the very first split (the root), which perfectly separates Setosa from the other two species.
- Setosa is Linearly Separable: Setosa can be identified with 100% accuracy using just one simple rule (petal length)
- Versicolor vs. Virginica Overlap: These two species are much more similar, must go several levels deep, using multiple features, to distinguish them because their physical measurements often overlap.
- By calculating Gini Impurity, the algorithm automatically ranked the features. (automatic feature)
📘 View the original notebook on Kaggle: [https://www.kaggle.com/code/sebastianngjingpei/notebookb70e17d324](https://www.kaggle.com/code/sebastianngjingpei/notebookad2b85d0f4/edit)
