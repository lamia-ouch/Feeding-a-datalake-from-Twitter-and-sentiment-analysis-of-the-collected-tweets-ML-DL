# Feeding-a-datalake-from-Twitter-and-sentiment-analysis-of-the-collected-tweets
in this project, I went through 3 Steps:
      1-Listenning on tweets about Covid-19 in both languages arabic and french, and saving them in a csv file;
      2-Stocking file in Azure Datalake;
      3-Preprocessing and cleaning data for sentiment analysis
      
      
   
 #1st Step:
 We Used Twitter Api for listening on topic that we want (Coronavirus, Corana, Covid-19) with condition searching in arabic and french language, 
 taking tweets from accounts who have more than 500 followers
 and Saving them in csv file 

#2nd Step:
We programmed a timer who can upload the csv file to Azure Datalake every 5 min

#3rd Step
Preprocessing by 
  -Deleting stop words 
  -Normalizing spaces 
  -For arabic words removing "TACHKIL"
  -Removing hyperlinks
  -Removing Hashtags # and quote @
  -Removing Retweets RT
after this step we apply stemming

Finally we analyze sentiment using Deep Learning algorithms and Maching learning algorithms using scikit learn and tansorflow

 
