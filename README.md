# Twitter WordCloud analysis for Trump, Biden & Obama with Python

## Project Intro/Objective
The purpose of this project is to visualise observations made through analysing scraped tweet level data from 2008-2020 for Barack Obama, Joe Biden and Donald Trump.
The 'Exploratory_analysis_twitter_obama_trump_biden.ipynb' details how I was able to generate a WordCloud fitted to the shape of Obama, Trump and Biden

### Blog for detailed writeup
* https://medium.com/@hitennaran

### Methods Used
* Data Visualization
* WordCloud generator
* Web Scraping

### Technologies 
* Python
* GetOldTweets3
* PIL
* json
* wordcloud
* pandas
* numpy
* matplotlib
* seaborn
* glob
* csv
* time
* re
* datetime


## Project Description

The project is broken down into 7 key sections within the "Exploratory_analysis_twitter_obama_trump_biden.ipynb" workbook:

1. Scraping tweet level data from Obama, Trump and Biden's Twitter feeds via the "GetOldTweet3" library. Given the limitations of only being able to obtain up to 3,200 tweets via basic Twitter API access. Working with the 'GetOldTweets3' library is a useful hack for scraping an inifinite amount of tweets as we're able to obtain the neccessary tweet data through web scraping the twitter user feeds versus accessing through an API connection.
2. Assessing the data in order to identify what cleaning steps are required.
3. Cleaning the dataset in order to make it fit for conducting exploratory analysis.
4. Exploratory analysis into the dataset and uncover learnings. This is where I produce a WordCloud fitted to the shape of Obama, Trump and Biden
5. Export cleaned DataFrame to a GoogleSheet.
6. Export DataFrame to csv for DataStudio usage.
7. Export original cleaned Dataset.

## Getting Started

Will need to pip install the following libraries in order to scrape tweets and generate a wordcloud.

1. https://pypi.org/project/GetOldTweets3/
2. https://github.com/amueller/word_cloud

### Relevant files

1. Web scraping, cleaning and exploratory analysis: "Exploratory_analysis_twitter_obama_trump_biden.ipynb"
2. Explanatory analysis (Jupyter Notebook and HTML Slidedeck) : "Explanatory_analysis_twitter_obama _trump_biden.ipynb", "Explanatory_analysis_twitter_obama _trump_biden.slides.html"
3. Clean csv file for Jupyter Notebook usage: "biden_trump_obama_clean_2008_2020_original"
4. Clean csv file for Google Sheets usage: "biden_trump_obama_clean_2008_2020_gspread"
5. Clean csv file for DataStudio usage: "biden_trump_obama_clean_2008_2020_datastudio"

## References

Following blog served extremely useful in providing an overview on how to extrapolate tweet level data working with the 'GetOldTweets3' library

* https://medium.com/@AIY/getoldtweets3-830ebb8b2dab

