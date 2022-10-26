# WeRateDogs-tweets-analysis

## Dataset Overview
There are 3 datasets in stored in different formats used for this analysis. The tweet archive of WeRateDogs contains basic tweet data for all 5000+ as it 
stood on the 1st of August, 2017. The image prediction dataset stored in a url as a .tsv file and the json.txt dataset holding additional data pulled from tweeter API.

## Data Gathering
The datasets required for the analysis of the are located in 3 different modes;

1.  csv dataset already downloaded
2.  image prediction dataset stored in a url as a .tsv file
3.  A json.txt dataset holding additional data pulled from tweeter API

- The csv file (tweeter-archive-enhanced.csv) was read direcltly into a dataframe using pd.read_csv('tweeter-archive-enhanced.csv')
- The image_prediction was requested and pulled into dataframe using and
- The tweet_json.txt was requested, read, and stored in a separate dataframe.

## Assessing the Data
The data sets were assessed visually using microsoft excel to check for tidiness issues and programatically to check for quality issues.

## Data Cleaning
The assessed issues were cleaned and insights were derived to answer the following questions:
1.  Which type of dogs is the most liked type of dogs?,
2.  What are the average ratings based on the dog types?,
3.  What are the type of dogs that are most tweeted about?
