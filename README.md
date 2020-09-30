# github-upload
MNIST data set of handwritten digits was used for this project.
I have used modAL Framework for Python. This framework is built on top of scikit-learn library of Python.
In my code I have used k-means++ approach for initializing the cluster centres/centroids.
In this approach the first cluster centre is chosen uniformly at random from the data points that are being clustered, after which each subsequent cluster centre is chosen from the remaining data points with probability proportional to its squared distance from the point's closest existing cluster centre.
CONCLUSIONS
• For my dataset, in pool-based learning, margin sampling performed better when additional label data was less than 20% whereas entropy sampling performed better when additional data labelled was more than 40%
• For my dataset, in stream-based learning, entropy uncertainty measure performed better when additional labelled data was 10% whereas margin uncertainty measure gave better results when additional labelled data more than 10%
• Overall, pool-based learning gave better accuracy than stream- based learning
• In QBC, KL divergence sampling performed better than Vote entropy sampling
• Number of points in version space were lesser for KL divergence sampling and decreased on increasing the additional labelled data provided
• All three active learning methods performed better than random labelling scenario.
• Accuracy achieved by K-Means was 76.67% and the resources saved were:1490 hours and Rs.1,49,000
