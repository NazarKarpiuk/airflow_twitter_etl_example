# airflow_twitter_etl_example

An example airflow DAG which collects information from a specific twitter account using the appropriate development API. 

Airflow were hosted on EC2 machine in AWS Cloud and a results stored in S3 Bucket.

**There is an example of fist 20 lines of the resulting file**<br/>
![twitter](https://user-images.githubusercontent.com/72578348/193913828-ec846f50-3acc-4acc-98ff-a07375f622ee.png)

DAG parses the name of the user, the text of tweet, the number of likes, retweets and the date of creation.