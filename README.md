# Challenge 16: Amazon Vine Analysis

## Chandrashekhar G. Ranade

This report has two components. The first relates to the summary tables based on the sales of electronics during 2015. This dataset we got from Amazon Webservices. The second component relates to the vine reviews of Amazon.

### Deliverable 1

The detail tables related to the sale of electronics are presented in the git-hub repository submitted along with this write up. The code gives the expected result for Challenge 16. Full review_id and product_id tables were imported in pgAdmin as shown in the following charts.

![Chart](https://i.imgur.com/J0usqqi.png)


![Chart](https://i.imgur.com/DuzU1Qn.png)


### Deliverable 2

Using PySpark package a new google Colab Notebook codes were run and the vine review tables were prepared. The full code is given in the git-hub repository submitted along with this write up, including the related tables.

### Deliverable 3

#### Analysis of Vine Reviews

There were a total of 1080 paid reviews. Out of which 454 paid reviews gave a rating of 5, that is 42% of the total paid reviews. In contrast out of 49673 unpaid reviews, 23043 reviews gave a rating of 5, that is about 46% of the unpaid reviews. Thus there is no significant difference between the 5 star rating given by the paid versus unpaid reviews.

We conclude that, at least for the electronics, the vine reviews were fair in 2015. This conclusion is based on our experience of the analysis of other reviews from the Amazon where we found that when the number of reviews is small the share of 5 start rating is usually high, meaning that there could be a conflict of interest among those who review the products (our claim is that the known parties give Reviews). However, when the number of reviews is large, like in this case of electronics, the reviews for 2015 appear to be unbiased.
