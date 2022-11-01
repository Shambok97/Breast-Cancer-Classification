# Breast-Cancer-Classification using Machine Learning 

## Overview
 Breast Cancer has been a contributor to high number of deaths a year among women and it has also been classed as the most common type of cancer, based on extensive research. In the medical field, classification of data through data mining and artificial intelligence is an effective way for healthcare professionals to reach a diagnosis. Therefore, the current study aimed to put forward three supervised machine learning algorithms to classify breast cancer based on the cell features in a data set available by the University of California, Irvine Machine Learning repository. The features represent the various characteristics of the cell nuclei which we have implemented through decision tree, random forest and the k-nearest neighbour algorithm (KNN) classifiers and compare their performances in their ability to accurately classify data. The primary challenge of this task was to build all three algorithms without using Python's sklearn and other modules that have  pre-built algorithms. Our results suggest that the mean test accuracy of random forest is higher than the accuracy of KNN and Decision tree. We further propose our future directions based on the limitations we faced with the data set available and algorithms used.

## Algorithms and Results

### Decision Tree

For Decision Tree classifier, we firstly split the data into two parts, 75% for training and 25% for the testing. Next we checked for purity of data to test the homogene- ity of the labels at the specific node. We then calculated 
the entropy of the data set to check for the randomness of the information that we need to process. Following this, we built the Decision Tree algorithm without utilising the scikit machine learning package and ran it for different training and testing iterations. A conditional maximum depth value of 6 was iterated where the training accuracy reached a 100% which is when new branches were not created to prevent overfitting of data. This gave us a testing accuracy of 92.96%. Decision tree is quite easily interpretable but often a single tree lacks the ability in producing effective results. For this reason, we used the Random Forest classifier.

### Random Forest



