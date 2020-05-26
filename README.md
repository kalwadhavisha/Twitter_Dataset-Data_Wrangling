# Twitter_Dataset-Data_Wrangling

Gathered data from the archives of a twitter account called WeRateDogs which rates owned dogs in their tweets and adds a humorous comment with it. Gathered retweet and like counts for all the tweets from the twitter API using the access library tweepy and read them into a pandas dataframe in the Jupyter Notebook. Downloaded a tsv file about the tweets programmatically using the requests and BeautifulSoup libraries in python. Assessed quality and tidiness issues in the the gathered datasets and cleaned all of them using pandas functions. Analysed the cleaned tables and created visualizations using the matplotlib library.

## Project Files

- twitter-archive-enhanced : Csv file containing data about the tweets like tweet text, dog ratings, dog name, dog type, etc.

- image-predictions : Tsv file containing all the dog breed predictions for all the tweets, computed using a neural network that predicted the breeds by using the dog images in the tweets. Other features include image url and breed_predicted which has two values True and False, True for when a breed was predicted and False if otherwise.

- tweet_json : A text file created which consists of each tweet's json object.

- tweet_counts_clean : A file created from a cleaned dataset consisting of retweet and like counts for all the tweets. These counts were gathered using the twitter API and the python library tweepy.

- image_predictions_clean : Cleaned version of the image-predictions file.

- twitter_archive_master : A master dataset created by joining the cleaned versions of all the three files.

- wrangle_act : Project workbook where all the wrangling, analyzing and visualizing was done.

- wrangle_report : Project report discussing all the activities performed in the workbook.

- act_report : Report communicating the insights drawn from the wrangled datasets with the help of visualizations.

## Software Required

- Need to be able to work in a Jupyter Notebook.

- The following packages (libraries) need to be installed:
  - pandas
  - NumPy
  - requests
  - tweepy
  - json
  
## Points to be noted

Key points to keep in mind when data wrangling for this project:

- The project only need original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.
- Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
- Cleaning includes merging individual pieces of data according to the rules of tidy data.
- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.

## Task

The tasks in this project are as follows:

- Data wrangling, which consists of:
  - Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
  - Assessing data
  - Cleaning data
- Storing, analyzing, and visualizing your wrangled data
- Reporting on
  - Data wrangling efforts
  - Data analyses and visualizations
  
