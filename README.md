# Amazon_Vine_Analysis
Amazon Vine Analysis

Overview
With this SellBy project, we have been tasked with analyzing the paid Amazon Vine program. Amazon Vine is a program where vendors pay a fee to Amazon and send their products to Vine members who in turn will publish a review.
For this project, we have analyzed a dataset of reviews for pet products. This is a very popular category for Amazon with a vocal consumer base as pet owners want to ensure that they are buying good, quality products for their pets. Utilizing PySpark, pgAdmin and Amazon Web Services, we performed ETL on the Amazon pet product reviews then determined the bias of Vine reviews vs non-Vine reviews.

Results
-There were a total of 170 Vine reviews and 37,840 non-Vine reviews. 
-There were 65 Vine reviews that were 5-stars and 20,612 non-Vine reviews that were 5-stars. 
￼-38.2% of Vine reviews were 5-stars and 54.5% of non-Vine reviews were 5-stars. 

Summary
There is no positivity bias for reviews in the Vine program since only 38.2% of Vine reviews came back with 5-star ratings whereas 54.5% of non-Vine reviews were 5-stars.Another analysis should be conducted on 4 star reviews to see if it can further support the statement above is true. If the results still show that the percentage of Vine reviews is much less than the non-Vine reviews, then the statement that there does not seem to be a positivity bias for reviews in the Vine program is supported.
