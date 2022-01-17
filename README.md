# Amazon Vine Analysis:credit_card::bar_chart:

## Overview of the analysis:squirrel:
The purpose of this challenge was to help BigMarket contribute their big data analysis to a client by the name of $ellby. The client is about to release a large amount of catalogs for his clients, and the credibility of the prices is going to be set by the reviews of the clients that have bought those items of the catalogs. Nevertheless, the reviews are in words not numbers, that is what differenciates this challenge to the others, by the help of NLP and Machine Learning the reviews were counted and filtered successfully. 

Now for this challenge, the services of BigMarket was now hired by Amazon to analyse their reviews. A random set of data was chosen and an exhaustive analysis was performed with the dataset to carry on the task. The results were as follows.

## Results:chart_with_upwards_trend:
For the challenge, the next dataset of Amazon was chosen to perfom the analysis:
- https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Games_v1_00.tsv.gz

During the results of the analysis, the following questions can be answered:

- How many Vine reviews and non-Vine reviews were there?
![](https://github.com/Frankdiazw/Amazon_Vine_Analysis/blob/main/Resources/vine_nonvine_reviews.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![](https://github.com/Frankdiazw/Amazon_Vine_Analysis/blob/main/Resources/filtered_count_vine_and_nonvine_reviews.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![](https://github.com/Frankdiazw/Amazon_Vine_Analysis/blob/main/Resources/percentage.png)

## Summary:memo:
As we can see from the results, there were more than a million reviews that was processed through Natural Language Processing and filtered to be able to get the results. In which, from all the paid reviews Amazon did, only 1,607 reviews were 5 stars; while 1,025,317 were 5 star reviews that were not paid. We can tell that more people enjoy giving reviews by own choice, but the reviews that matter the most are the paid ones because people get more motivated and write a more sincere and official statement on the product, which this time was a video-game.

Now, as for the percentage, only 0.15% of all the votes that were 5 star were paid and 99.85% of the votes that were 5 star were unpaid. This is a massive difference from the big dataset provided by Amazon, but we can make a statement here: from all the votes, not even 1% from them are official reviews from people that were paid to make an extensive statement about the product, while unpaid reviews can also be very sincere and well developed, the difference of reviews between these two is absurd. However, the clients who paid for these reviews should take a more extensive look at the paid vine reviews than the unpaid ones.
