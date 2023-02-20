Comparing Sampling Techniques for 5 Machine Learning Models
Introduction
This project explores the effectiveness of different sampling techniques for creating a balanced dataset for a machine learning model. The dataset used is initially unbalanced, so random over-sampling and under-sampling techniques are used to create a balanced dataset. Five different sampling techniques are then applied to this balanced dataset, and the accuracies of the resulting samples are compared using five different machine learning models.

Sampling Techniques
The following five sampling techniques were used in this project:

Simple Random Sampling: A basic sampling technique where each data point in the dataset has an equal probability of being selected in the sample.

Stratified Sampling: A sampling technique where the population is divided into subgroups (strata) based on a specific characteristic, and samples are taken from each stratum in proportion to the population.

Systematic Sampling: A sampling technique where every nth element in the population is selected for the sample, with n being a fixed interval.

Cluster Sampling: A sampling technique where the population is divided into clusters, and a sample of clusters is randomly selected. Then, all members of the selected clusters are included in the sample.

Multi-Stage Sampling: In this method we have used a combination of sampling technique, i.e. cluster and simple random. The dataset is divided into clusters and then random samples are chosen from those clusters.

Final Result Table
Simple Random	Stratified	Systematic	Cluster	Multi-Satge
Logistic Regression	91.01	91.32	79.22	91.30	94.00
Decision Tree	99.62	96.42	92.20	95.65	92.00
Support Vector Machine	69.66	63.26	70.12	72.17	70.00
Gaussian Naive Bayes	76.02	75.00	77.92	66.95	58.00
K-Nearest Neighbors	98.12	95.91	92.20	88.69	86.00

Conclusion
It is recommended to use Decision Tree Algorithm upon taking samples using the Simple Random Sampling technique. We get an accuracy of 99.62%.

Submitted By:
Sehajbir Singh Mann
102003478
