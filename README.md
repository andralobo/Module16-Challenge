# Amazon Vine Analysis

## Overview of the analysis

### Purpose

The purpose is to analyse Amazon reviews written by members written by members of the paid Amazon Vine program.

### Resources

We were given a list of Amazon Review datasets to select one category of products to analyse.  
(https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

We chose grocery as our category and used Pyspart to create an ETL process that extracts the data from amazon, store the data in a dataframe, transform the data, connect to our AWS RDS and load the different dataFrames into our PgAdmin tables that were created.
 

## Results

<img src="https://github.com/andralobo/Module16-Challenge/blob/main/Averages.png?raw=true" width="auto" height="auto">

<b>How many Vine reviews and non-Vine reviews were there?</b>

Vine Reviews: 61
Non-Vine Reviews: 28,287


<b>How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?</b>

Vine 5 Star Reviews: 20
Non-Vine 5 Star Reviews: 15,689


<b>What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?</b>


Vine 5 Star Average: 32.8%
Non-Vine 5 Star Average: 55.5%


## Summary

### Findings

-  The percentage of 5 star reviews from non-Vine members is much higher than the Vine members

-  The number of Vine member reviews was very low compared to the number of Non-Vine reviews

### Conclusion

-  Though these results show that there is no bias, I don't think that there were enough reviews to use for this analysis

-  I would recommend completing this analysis for multiple categories to be able to come to a better conclusion.
