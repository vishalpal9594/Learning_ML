<h1> Standardization </h1>
<p>
Standardization comes into picture when features of the <b>input data set have large differences between their ranges</b>, or simply when they are measured in different measurement units (e.g., Pounds, Meters, Miles … etc).
  
These differences in the ranges of initial features cause trouble for many machine learning models. For example, for the models that are based on distance computation, if one of the features has a broad range of values, the distance will be governed by this particular feature.

To illustrate this with an example : say we have a 2-dimensional data set with two features, Height in Meters and Weight in Pounds, that range respectively from [1 to 2] Meters and [10 to 200] Pounds. No matter what distance based model you perform on this data set, the Weight feature will dominate over the Height feature and will have more contribution to the distance computation, just because it has bigger values compared to the Height. So, to prevent this problem, transforming features to comparable scales using standardization is the solution.

Any machine learning algorithm that computes the distance between the data points needs Feature Scaling (Standardization and Normalization). 

</p>
<br>

<h3>Z-SCORE</h3>
<p> 
Z-score is one of the most popular methods to standardize data, and can be done by subtracting the mean and dividing by the standard deviation for each value of each feature.

![image](https://user-images.githubusercontent.com/89294557/185532997-52d8a898-92d5-4894-a5d2-a504eda01e73.png)
  
Once the standardization is done, all the features will have a mean of zero, a standard deviation of one, and thus, the same scale.  
</p>
<br>

<h4> Standardization does not get affected by outliers because there is no predefined range of transformed features.</h4>
<h2>which machine learning algorithum need feature scaling <h2>

![image](https://user-images.githubusercontent.com/89294557/185535648-81326636-5b81-4aaf-a377-71fb88876edd.png)
