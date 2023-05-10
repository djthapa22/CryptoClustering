## CryptoClustering

Within this module, I learned how to cluster crytp currency using two methods of unsupervised learning. These methods and techniques are demonstrated below:

* Prepare the data, using Standard Scaler to normalize the numeric data within price change fields
* Find the Best Value for k Using the Original Scaled DataFrame
* Cluster Cryptocurrencies with K-means Using the Original Scaled Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for k Using the PCA Data
* Cluster Cryptocurrencies with K-means Using the PCA Data

**<ins>Findings</ins>**
* **Question 1 :** What is the best value for `k`?
  * **Answer:** Although it can be debated between 3 or 4 as the value of K. The greatest decrease in change in inertia looks be at a value of **4**. <br>
* **Question 2:** What is the total explained variance of the three principal components?<br>
  * **Answer:** The total explained variance using the three principal components is **89.5%** <br>
* **Question 3:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
  * **Answer:** Although the data shape does not follow a similar shape to the original data. Knowing that PCA models are comparing multiple fields/ metrics, it would enable a better seperation amongst the clustering of the data
