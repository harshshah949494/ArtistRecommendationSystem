# ArtistRecommendationSystem
Personalized Top Music Artists Recommendations for Users
This project is built to recommend top Music Artists which the user might be interested in listening to, 
based on his previous listening history.It uses ALS MAtrix Factorization Algorithm and Pyspark to process and recommend top Artists.

About the Dataset:

This data set contains profiles for around 150,000 real people.The dataset lists the artists each person listens to, and a counter
indicating how many times each user played each artist

The dataset is continually growing; at the time of writing. Audioscrobbler is receiving around 2 million song submissions per day

We may produce additional/extended data dumps if anyone is interested in experimenting with the data. 

Please let us know if you do anything useful with this data, we're always up for new ways to visualize it or analyse/cluster it etc :)

License
-------

This data is made available under the following Creative Commons license:
http://creativecommons.org/licenses/by-nc-sa/1.0/


Files
-----

user_artist_data.txt
    3 columns: userid artistid playcount

artist_data.txt
    2 columns: artistid artist_name

artist_alias.txt
    2 columns: badid, goodid
    known incorrectly spelt artists and the correct artist id. 
    you can correct errors in user_artist_data as you read it in using this file
  
