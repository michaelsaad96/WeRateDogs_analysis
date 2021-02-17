# Wrangling and Analyzing WeRateDogs Tweet Data
This project gathers data from a variety of sources and in a variety of formats, assesses its quality and tidiness, then cleans it.
We showcase our wrangling efforts through analyses and visualizations.
## How to Run this Project
* The whole data analysis process, consisting of gathering, assessing, cleaning, storing, analyzing, and visualizing, can be viewed in `wrangle_act.ipynb`. This file can be viewed directly in GitHub by simply left clicking.
* Similarly, the wrangling efforts, as well as the analysis and visualization results, can be viewed in `wrangle_report.ipynb` and `act_report.ipynb`, respectively.
* `twitter-archive-enhanced.csv` contains tweets from WeRateDogs account, along with their tweet IDs and timestamps. Dog ratings out of 10, dog names, and dog ranks have been extracted from each tweet and placed into their respective columns.
* `tweet_json.txt` contains additional data about each tweet, like the number of retweets and likes.
* `image_predictions.tsv` contains predictions about each dog's breed, which were determined by a neural network based on the dog's picture.
* `twitter_archive_master.csv` and `dog_table_master.csv` contain the cleaned dataset.
