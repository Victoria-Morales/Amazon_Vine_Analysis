# Amazon Vine Analysis 

## Overview of the Project

#### For this project, we used PySpark to analyze Amazon review data.  The data is comprised of paid (Amazon Vine program) and unpaid reviews.  The dataset that I chose to analyze is the “Outdoors” items. The analysis was done to uncover whether there was bias toward more favorable reviews for the paid Vine program.


## Results

![paid1](/Resources/paid1.png)

![unpaid1](/Resources/unpaid1.png)


* How many Vine reviews and non-Vine reviews were there?
	* 107 paid reviews
	* 39869 unpaid reviews

![paidvsunpaid](/Resources/paidvsunpaid1.png)


* How many Vine reviews were 5-star?  How many non-Vine reviews were 5-star?
	* 56 paid 5-star reviews
	* 21,005 unpaid 5-star reviews

![paidvsunpaid2](/Resources/paidvsunpaid2.png)


* What percentage of Vine reviews were 5-star?  What percentage of non-Vine reviews were 5-star?
	* 52.3% of paid reviews were 5-star
	* 52.7% of unpaid reviews were 5-star


![paidvsunpaid3](/Resources/paidvsunpaid3.png)



## Summary 


#### Based on the analysis done for this specific data set, there is not a positivity bias for the Vine (paid) reviews.  For the “Outdoors” dataset, the percentage of 5-star reviews for both the paid and unpaid reviews are right around 52% and in fact the unpaid reviews are slightly more favorable. Additional analysis that would help to bolster this would be to compare 4-star ratings, to see if this similarly follows the trend.  Conversely, I would be interested at looking at 1-star revies to see if paid reviews would diminish the worst reviews.

#### This analysis seems limited by the relatively small number of Vine reviews in this dataset.  It may not be adequate to perform this analysis. Of all the reviews for this category, 99.73% were unpaid reviews and only 0.27% were paid Vine reviews.  A larger sampling would give me more confidence is the analysis.  Also, analyzing 1 or 2 of the other datasets would strengthen the analysis.
