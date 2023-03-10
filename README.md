# Sampling-of-Imbalanced-DataSet

## Introduction
When working with imbalanced data, The minority class is our interest most of the time.So, the machine learning algorithms favor the larger class and sometimes even ignore the smaller class if the data is highly imbalanced.Machine learning algorithms are designed to learn from the training data to minimize the loss and maximize accuracy.
There are many ways through which you can handle an imbalanced dataset. Some require you to have field knowledge others use different algorithms to increase the instances of minority class (Over-sampling) and to decrease the instances of majority class (Under-sampling).

We have applied various other techniques to handle an imbalanced dataset in this notebook and then compare the result with different models.

## Imbalanced Dataset

  
  <p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/82312885/219968300-431c1c29-15de-449c-85b5-6754749b0690.png"> 
   
</p>

   


## Sampling Techniques and Model

### 5 Sampling Techniques have been implemented:

1.  Random Under Sampling
2.  Random Over Sampling
3.  TOMEK links 
4.  Synthetic Minority Oversampling Technique, or SMOTE .
5.  Near Miss



### 5 Machine Learning Models  have been implemented for Comparison:

1.  Support Vector Machine
2.  Decision-Tree -Classifier	
3.  RandomForestClassifier	
4.  KNeighborsClassifier	
5.  GaussianNB	




## Result:

<p align="center">
  <img width="800" height="200" src="https://user-images.githubusercontent.com/82312885/219968860-35c65ab1-ab40-40b3-a7e6-4f8381f3e2ef.png"> 
</p>


## Conclusion:

Accuracy is better with Sampling Techniques with specific Models.

1.  Support Vector Machine with NearMiss
2.  Randon Forest Classifier with Random Over Sampling and TomLinks
3.  KNeighborsClassifier with Random Under Sampling and NearMiss
4.  Gaussian with NearMiss 


