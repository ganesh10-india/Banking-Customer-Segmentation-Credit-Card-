# Banking-Customer-Segmentation-Credit-Card-
Develop a customer segmentation to define marketing strategy. Used PCA to reduce dimensions of the dataset and KMeans++ clustering technique is used for clustering and profiling of clusters.

# Credit Card Customer Segmentation

<p align="center"><img width="70%" src="images/4clustersol.png" /></p>
--------------------------------------------------------------------------------
## Project Summary
* Derived new KPI by using data manipulation methods.
* Checked the multi-collinearity using heatmap.
* Standardized the data and applyied PCA to get optimal number of Pricipal Components.
* KMeans Clustering is used - Silhotte Score and Cluster Inertia Score used to fix the number of clusters.
* Done profiling to draw insights for the clusters.

<p align="center"><img width="60%" src="images/silhottescor.png" /></p>

## Final Clusters and Recommendations
* Based on silhouette_score, i have taken number of clusters to be 4.

<p align="center"><img width="60%" src="images/cluster.png" /></p>

* **Suggested Marketing Strategy for these clusters:**
* Group 0
   - This is performing best among all the clusters are maintaining highest monthly average purchases. Giving any reward points might increase their purchases.
* Group 1
   - This group is doing maximum oneoff payments(may be for bills only). Customers of this group can be offered discount/offer on next transactions upon full payment.  
* Group 2 
   - They are potential target customers who are paying bills and doing purchases and maintaining comparatively good credit score. So we can increase credit limit or can lower down interest rate. Promote premium cards/loyality cars to increase transcations.  
* Group 3
   - These customers are taking maximum cash advance, these customers should be given remainders for payments. Offers can be provided on early payments to improve their payment rate.

## Prerequisites
The following list summarizes the packages/softwares used in this project. These are the softwares/packages you neeed to install before executing the project file.
* Anaconda v – 5.2.0 (py 36_3) 
* Python v – 3.6 + 
