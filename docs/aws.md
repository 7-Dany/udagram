# AWS Cycle

![AWS Cycle](./images/udagram.png)

in AWS, we will deploy our project nn different services and make connection between them

1. By Creating Database instance on RDS Service

__Here I created database instance called database-1__

![Database instance](images/All%20databases.png)
![Database instance](images/RDS-Instance.png)

2. Creating a Bucket in S3 Service to store the frontend for our app in it

__Here I created Bucket called dany-udagram__

![S3 Bucket](images/All%20Buckets.png)
![S3 Bucket](images/my%20bucket.png)

3. Creating A New Environment on elastic beanstalk to save our app's back-end

__Here I created new environment which will run node for my server__

![Elastic Beanstalk](images/EB.png)
![Elastic Beanstalk](images/EB%20config.png)

4. After That i updated Elastic Beanstalk environment variables to connect my database to my backend