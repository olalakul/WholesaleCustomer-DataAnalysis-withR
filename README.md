# Wholesale Customer - Multivariate Analysis


This project is about analysis of the [Wholesale Customer Dataset](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) from UCI repository.

## Part 1 - [Multivariate Analysis](http://wholesalecustomer-multivariateanalysis.s3-website.us-east-2.amazonaws.com/) includes

* ANOVA

* Discriminant analysis

<img src="1-WholesaleCustomer-MultivariateAnalysis/wholesale-multivariate_files/figure-html/lda_qda_roc-1.png"  alt="ROC curve for LDA and QDA"  width=600 />


* Factor analysis

* Clustering

<img src="1-WholesaleCustomer-MultivariateAnalysis/wholesale-multivariate_files/figure-html/pam3_clusters_nonintera-1.png"  alt="3 clusters from PAM"  width=700 />

<img src="1-WholesaleCustomer-MultivariateAnalysis/wholesale-multivariate_files/figure-html/pam3_silhouete-1.png"  alt="silhouette diagram for PAM"  width=600 />


* Customer segmentation

<img src="1-WholesaleCustomer-MultivariateAnalysis/wholesale-multivariate_files/figure-html/segments25-1.png"  alt="segments of customers"  width=900 />

Some segments are pretty interesting.

5) Customers in segment 5 are buying very little (in comparison to average values) Fresh, Frozen and Delicassen.
Shouldn't you (as a careful businessmen) check why and what is going on?

6) Customers in segment 6 are buying very little Milk, Grocery, Detergent. Are you sure that you are a careful businessmen?

15) Customers in segment 15 need everything except Frozen. Why? Can it be that donating a refrigerator to them will boost their Frozen revenue to the level of other products (which are not small, by the way)? Is there a practice of such donations in the industry? 

23) Customers in segment 23 look like really large Cafes. Why do they want so little Detergents? Do they stick to  some specific brand that you do not have?


## Part 2 - [Similar Customers](http://wholesalecustomer-similarcustomers.s3-website.us-east-2.amazonaws.com/) includes

* customer similarity by their annual revenue on various categories of products

* interactive visualization for finding similar customers

![annotatedSimilarCustomers](2-WholesaleCustomer-SimilarCustomers/images/SimilarCustomers-total.png)

## Part 3 - [Whom do I sell more frozen products](http://wholesalecustomer-whomsellmorefrozenproducts.s3-website.us-east-2.amazonaws.com/)

demonstates how customer similarity is applied to answer a specific business question - whom of the customers could I offer more frozen products

To improve the segmentation in such a way, that it is tailored to predicting frozen products revenue,
further improvement with Bayesian net is considered

<img src="3-WholesaleCustomer-WhomSellMoreFrozenProducts/wholesale-moreFrozen_files/figure-html/network_all-1.png"  alt="networkForAllColumns"  width=500 />






