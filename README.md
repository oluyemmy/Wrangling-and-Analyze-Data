# Data Wrangle and Analyze Project
## Introduction 
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.
The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](https://knowyourmeme.com/memes/theyre-good-dogs-brent)." WeRateDogs has over 4 million followers and has received international media coverage.
WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.
## Project Steps Overview
**Step 1**: Gathering data 
**Step 2**: Assessing data 
**Step 3**: Cleaning data 
**Step 4**: Storing data 
**Step 5**: Analyzing, and Visualizing data 
**Step 6**: Reporting 
> * data wrangling efforts
> * data analyses and visualizations
## What sofware Do I need?
* Pandas 
* Numpy 
* requests 
* tweepy
* json
## Project Motivation 
### Context
Your goal: wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.
### The Data
In this project, you will work on the following three datasets.
1. **Enhanced Twitter Archive**

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything

2. **Additional Data via the Twitter API**

Back to the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API

3. **Image Predictions File**

One more cool thing: I ran every image in the WeRateDogs Twitter archive through a [neural network](https://www.youtube.com/watch?v=2-Ol7ZB0MmU) that can classify breeds of dogs*. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

## Project Deliverables
* `wrangle_act.ipynb`: code for gathering, assessing, cleaning, analyzing, and visualizing data
* `wrangle_report`: ocumentation for data wrangling steps: gather, assess, and clean
* `act_report`: documentation of analysis and insights into final data
* `twitter_archive_enhanced.csv`: dataset 
* `image_predictions.tsv`: datast downloadd programmatically 
* `tweet_json.txt`: file constructed via API
* `twitter_archive_master.csv`: combined and cleaned data