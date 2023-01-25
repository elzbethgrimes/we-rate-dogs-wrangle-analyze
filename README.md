# we-rate-dogs-wrangle-analyze

## Wrangle and Analyze Data

The purpose of this project is to wrangle and analyze a dataset gathered from the tweet archive of Twitter user @dog_rates, a.k.a WeRateDogs. The wrangling, cleaning, and analysis is contained in the Jupyter Notebook `wrangle_act.ipynb`. The file `act_report.pdf` contains a write up of the findings. 

The steps in this project include the following:
1. Gathering data
2. Assessing data
3. Cleaning data
4. Storing data
5. Analyzing, and visualizing data
6. Reporting
    * data wrangling efforts
    * data analyses and visualizations   

#### Data:
1. `twitter_archive_enhanced.csv` -comma-separated values provided by Udacity and manually downloaded from the Udacity site
2. `image_predictions.tsv` - a tab-separated file downloaded programmatically using the Requests library from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)
3. `tweet_json.txt`- a JSON file gathered by querying Twitter’s API to download the JSON data using Python’s Tweepy library
