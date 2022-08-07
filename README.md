# Analyses of WeRateDogsData Twitter Archive Data -a Udacity Data Analysis Nanoprogram Project
#### by Chimmuanya Mogbo

## Dataset:

This Project uses 3 datasets related to the the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with and makes funny comments about their dogs.
These included:
1. The WeRateDogs Twitter Archive avaiable as a csv file [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced.csv)
2. An Image Predictions File generated after running the dog pictures through a neural network -avaiable as a tsv file [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)
3. Additional data about the tweets was gotten from a json file following my inability to obtain authentication keys from Twitter for scraping through their site -available as a txt file [here](https://video.udacity-data.com/topher/2018/November/5be5fb7d_tweet-json/tweet-json.txt).

The datasets were assessed and cleaned and merged into a tidy master dataset and this master dataset was analyzed to give the findings of this project.

## Summary of Findings 
In the exploration some of the findings that I made include: 

The golden retriever is by far the most 'owned' dog (count=120) in this list. The rarest dogs in this list include the silky terrier among others.
Breeds that were more commonly owned generally received higher mean ratings. However, many less common breeds like the norfolk terrier, saluki, and toy poodle,etc
were also very highly rated.Dog Pictures from Twitter for Iphone had higher mean ratings compared to those from Twitter Web Client
Within the span of 3 years and from quarter to quarter, mean ratings from WeRateDogs climbed significantly.
Dogs with at least a Dog Family Member had a slightly higher average rating compared to dogs without any Dog Family member.
Dogs with higher ratings had their tweets marked as favorites more times than lower-rated dogs. The same trend was seen with the number of retweets.

### Limitations: 
No statistical tests were done in this project, therefore these findings do not prove causation. However, there are several instances of correlation.
