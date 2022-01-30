Is it mandatory to scales features in any machine learning algorithms?

In general, For  any algorithm that computes distance (like unsupervised algorihms) or assumes normality, scale your features !!!

Above are examples of algorithm:

	+ In KNN,  features should be scaled because this algorithms with an Euclidean distance measure is sensitive to magnitudes  in order to have the same weights.
   
  + Scaling is critical while performing Principal Component Analysis(PCA). PCA tries to get the features with maximum variance and the variance is high for high magnitude features. This skews the PCA towards high magnitude features.
	
  + To make gradient descnt more speed, scaling is a good idea. θ will descend quickly on small ranges and slowly on large ranges, and will therefore oscillate inefficiently at the optimum when the variables are very unequal.
	
  + Tree based models don't use distance and can handle varying ranges of features. So, Scaling is not required.
	
  + Scale features in Linear Discriminant Analysis and Naive Bayes may not have much effect and   because they are equipped to handle the manignitude of each features.
