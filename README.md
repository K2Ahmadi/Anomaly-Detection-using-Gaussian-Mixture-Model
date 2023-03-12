# Anomaly-Detection-using-Gaussian-Mixture-Model
The objective of this project is to construct a Gaussian Mixture model that can detect outliers and identify anomalies, with the aim of preventing credit card fraud activities.

Gaussian Mixture Model (GMM) is a statistical model that can be used for clustering and classification tasks. GMM assumes that the data is generated from a mixture of several Gaussian distributions, each with different means and variances. By estimating the parameters of these distributions, GMM can identify clusters of data points and assign probabilities of belonging to each cluster.


GMM can be used to detect credit card fraud by analyzing transaction data. Fraudulent transactions are typically rare events, and their characteristics may differ from legitimate transactions. GMM can be trained on a dataset of legitimate transactions to learn the typical patterns of transactions, such as time of day, amount, location, and other features.


Once GMM is trained, it can be used to analyze new transactions and assign probabilities of belonging to each cluster. Transactions that have low probabilities of belonging to any cluster can be flagged as potentially fraudulent and further investigated by human analysts.
