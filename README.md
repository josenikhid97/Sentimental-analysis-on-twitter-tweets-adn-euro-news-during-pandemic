**Twitter Crawler**

1. Setup Twitterscraper Tool from https://github.com/taspinar/twitterscraper
2. Edit bash file TwitterCrawler.bsh and set start/end date.
3. Run script


**Euronews Crawler**

1. Just update number of pages need to be scraped.
2. Put chrome driver in the same folder of the notebook
3. run the  Webscrapper.ipynb

**Sentiment analysis**

1. Set the input files path for the tweets in IBM tone analyzer.
2. For BERT model, set the paths for training data, testing data and data for predictions.
3. To perform predictions for different sentiments, un-comment the lines for the respective sentiment in the BERT model.

**Topic Modeling**

For getting most trend keywords:
1. Set MALLET_HOME in environment variables
2. SET JAVA_Home in environment variables
3. Update mallet_path in the notebook   Topic_Modeling.ipynb
4. set root_path = '../Euronews/' for euronows excel files
5. Run Topic Modeling/Topic_Modeling.ipynb
6. Dont forget to update the path of all output files


For presenting the results of Topic Modeling:
1. Set path of LDA_Euronews_colab_topics.xlsx file
2. Set path of LDA_Euronews_colab.xlsx file
3. Set path of Euronews_full.xlsx file
4. Run Topic Modeling/Results_Topics_Modeling.ipynb

For presenting the results of Tweets classfication by Topic Modeling:
1. Set path of tweets  root_path="/content/drive/My Drive/Tweets/CSV/"
2. Set path of LDA_Euronews_colab_topics.xlsx file
3. Run Topic Modeling/Twitter_Trending_topics.ipynb

