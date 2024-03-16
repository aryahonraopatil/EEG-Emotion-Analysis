# EEG based Emotion Analysis

This study makes use of the DEAP dataset, and machine learning models to perform EEG-based emotion classification. To perform emotion recognition using EEG signals I used machine learning algorithms such as K-nearest neighbor (KNN) and support vector machines (SVM) and used the OpenFace software to collect our ground truth for the machine learning algorithms. 

For EEG based emotion recognition in this project, we used machine learning algorithms such as K-nearest neighbor (KNN) and support vector machines (SVM). The K-nearest neighbor (KNN) algorithm performed better than the support vector machines (SVM) because the the classes (happy, netral, sad) did not have a clear separation and overlapped. KNN makes predictions based on the nearest neighbors, so it can adapt to the local structure of the data even in such situations. Also, the data had a lot of outliers and KNN is robust to noisy data and outliers since it doesn't make any underlying assumptions about the data distribution. For the given dataset, KNN is a better algorithm to build the classification model. 
