#Data

Data can be downloaded form the AWS S3 bucket here: s3://uw-geohack/trees/

If you have an AWS account already, you can use `awscli` to download the data into this directory directly via this command:

```
aws s3 cp s3://uw-geohack/trees/ . --recursive
```

Python pickle files for the processed DataFrames and Random Forest Model object can be downloaded from here:

https://drive.google.com/open?id=1eYl3iXFZHlEvhM4MNcdcnIqSbecCpveF