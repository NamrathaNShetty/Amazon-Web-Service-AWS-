# Working With S3 Buckets:
Step 1:
First We have to install S3FS and boto3

$ pip3 install s3fs
$ pip3 install boto3

To connect to the low-level client interface, we must use Boto3’s client(). Then pass in the name of the service you want to connect to, in this case, s3.

Step 2:

To make this  run against our AWS account, we need to provide some valid credentials(access key and their secret access key) . If you already have an IAM user that has full permissions to S3, you can use those user’s credentials .
Now We have to configure our access_key, Secret key in the .env file and load that into our python file.

Step 3:
In this step we have to write code for.
1.Creating a Bucket.
2.Listing Buckets.
3.Create a Dataframe and load that into a bucket. 
4.Read Csv file from s3 bucket directly into python.
5.Download file from S3 and read
6.Delete objects from bucket
7.Delete bucket from S3
