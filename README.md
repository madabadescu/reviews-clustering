# Unsupervised learning - clustering reviews

In this project I will present my approach and my results when applying two unsupervised models on a dataset containing reviews. The dataset that I chose is made of reviews for fine foods from Amazon, together with information about the reviewer, the product and the score that each user gave to each product. For the training of the unsupervised learning algorithms I used the texts' of each review. 

The models that I chose to work with are K-Means clustering and Agglomerative clustering. My approach for finding the best results for the unsupervised learning algorithms was to use the Elbow Method, Grid Search and the Silhouette Coefficient. The models were trained on two types of features: Bag of Words (BoW) and term frequency–inverse document frequency (TF-IDF).

After compiling each algorithm, I made plots in order to better visualize the data and the cluster distribution. I compared all this information and the overall results with random choice and also with a supervised model (SVM). I concluded that both algorithms performed better than the random choice, but worse than the SVM model. 

There are more details in the documentation.
