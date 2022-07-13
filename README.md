# Supervised-and-semi-supervised-analysis-of-seeds

This data set in based on 209 observations of seeds.
The target variable is the category of wheat they belong to. There are 3 categories.
It is a mixture of continuous and categorical variables.
The main question that the dataset helps to answer is what category of wheat do the seeds belong to.
The use of classifiers helped to train and build predictive models. I tried 4 classifiers and the 2 with the best results are in this code.
The accuracies that I received were 90% for SVM and 95% fot Logistic regression.
I used Support Vector Machine and Logistic Regression. The reason is that they both generated the highest accuracies.
I have also used clusteing: K-meand and Hierarchical.
K-means clustering uses “centroids”, K different randomly-initiated points in the data, and assigns every data point to the nearest centroid. 
Hierarchical clustering, also known as hierarchical cluster analysis, is an algorithm that groups similar objects into groups called clusters. 
I realised that both of them showed that 3 clusters were optimum. The elbow curve for the K-means, and the dendogram for Hierarchical clustering supported that claim.
