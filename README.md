# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to determine if there was any bias positivity towards Amazon reviews that were written as part of the Vine program. One measure of this is how many 5-star reviews paid Vine reviews resulted in vs. unpaid non-Vine reviews.

## Results
- There were 21 total Vine reviews vs. 6,690 total non-Vine reviews.

  ![image1](https://github.com/JFoArlas/Amazon_Vine_Analysis/blob/main/Resources/paid_vs_unpaid_total.png)

- There were 10 5-star Vine reviews vs. 3,448 5-star non-Vine reviews.

  ![image2](https://github.com/JFoArlas/Amazon_Vine_Analysis/blob/main/Resources/paid_vs_unpaid_5star.png)

- 48% of Vine reviews were 5 stars, compared to 52% of non-Vine reviews resulting in 5 stars.

  ![image3](https://github.com/JFoArlas/Amazon_Vine_Analysis/blob/main/Resources/paid_vs_unpaid_%255star.png)

## Summary
The sample size of the Vine reviews (i.e. the reviews that were paid) was very small relative to the non-Vine (i.e. unpaid) reviews. So while there is not a higher percentage of 5-star reviews when the review is paid, we cannot definitively say that paid reviews do not result any positivity bias.

If you were to take the average star rating for both Vine and non-Vine reviews, you find that the average rating is actually higher for paid reviews by almost a half star. So while our review data does not reflect more 5-star ratings for paid reviews, one could suspect that paid reviews could still result in some positivity bias in terms of the average rating. That said, because our sample size is so small for paid reviews, I would not definitively conclude that without more data.

![image4](https://github.com/JFoArlas/Amazon_Vine_Analysis/blob/main/Resources/avg_star_rating.png)
