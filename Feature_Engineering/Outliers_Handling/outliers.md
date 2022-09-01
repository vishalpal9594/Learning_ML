
<i><h1>Outlier</h1></i>
An Outlier is a data-item/object that deviates significantly from the rest of the (so-called normal)objects. They can be caused by measurement or execution errors.
<br><br><br>


<h1>How to treat outliers?</h1>
<p>
  <i><b>Trimming:</b></i> It excludes the outlier values from our analysis. <br>By applying this technique our data becomes thin when there are more outliers present in the dataset. Its main advantage is its fastest nature.
  <br><br>  
  <i><b>Capping:</b></i> In this technique, we cap our outliers data and make the limit. 
  <br>i.e, above a particular value or less than that value, all the values will be considered as outliers, and the number of outliers in the dataset gives that capping    number.
  <br><br>
  <i><b>Treat outliers as a missing value:</b></i> 
  <br>By assuming outliers as the missing observations, treat them accordingly i.e, same as those of missing values.
  <br><br>
  <i><b>Discretization:</b></i> by making the groups <br>we include the outliers in a particular group and force them to behave in the same manner as those of other points in that group. This technique is also known as <b><i>Binning</i></b>.
</p>
<br><br><br>

<h1>How to detect outliers?</h1>
<br>
<p>
  <b>For Normal distributions: </b>Use empirical relations of Normal distribution.
  <br>The data points which fall below mean-3*(sigma) or above mean+3*(sigma) are outliers.
  <br>where mean and sigma are the average value and standard deviation of a particular column.
  
  ![image](https://user-images.githubusercontent.com/89294557/187844912-c4767092-5bb8-4f9e-99c9-68a104f0afcf.png)

  <br><br>
  
  <b>For Skewed distributions: </b>Use Inter-Quartile Range (IQR) proximity rule.
  <br>The data points which fall below Q1 – 1.5 IQR or above Q3 + 1.5 IQR are outliers.
  <br>where Q1 and Q3 are the 25th and 75th percentile of the dataset respectively, and IQR represents the inter-quartile range and given by Q3 – Q1.
  
  ![image](https://user-images.githubusercontent.com/89294557/187854807-55b8586d-c486-4e53-9f62-cd259ae82980.png)


   <br><br>
  
  <b>For Other distributions: </b>Use percentile-based approach.
  <br>For Example, Data points that are far from 99% percentile and less than 1 percentile are considered an outlier.
  
  ![image](https://user-images.githubusercontent.com/89294557/187846242-b4d382ba-f2c2-4c2b-a982-efc171e3f298.png)

</p>
