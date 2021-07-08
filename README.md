# Data Wrangle Project

## Overview
Real-world data rarely comes clean. Using Python and its libraries, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling.

The dataset to be wrangled (and analyzed and visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

## Outline

Tasks in this project are as follows:

Data wrangling, which consists of:

>1. ##### Gathering data
>2. ##### Assessing data
>3. ##### Cleaning data
>4. ##### Storing, analyzing, and visualizing your wrangled data

## Data Gathering

Gather each of the three pieces of data as described below in a Jupyter Notebook titled ```wrangle_act.ipynb```:
>1. The WeRateDogs Twitter archive.
>2. The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. 
>3. Each tweet's retweet count and favorite ("like") count at minimum, and any additional interesting data. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called ```tweet_json.txt``` file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.

## Assessing Data

After gathering each of the above pieces of data, we will assess them visually and programmatically for quality and tidiness issues. we will detect and document at least eight quality issues and two tidiness issues in ```wrangle_act.ipynb``` Jupyter Notebook. 

## Cleaning Data

We will clean each of the documented issues while assessing, and perform this cleaning in ```wrangle_act.ipynb```.

## Store, Analyze and Visualize

We will store the clean DataFrame(s) in a CSV file with the main one named ```twitter_archive_master.csv```, then analyze and visualize the wrangled data in ```wrangle_act.ipynb``` Jupyter Notebook. At least three (3) insights and one (1) visualization produced.
