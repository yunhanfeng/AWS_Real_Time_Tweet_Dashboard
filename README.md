# AWS_Real_Time_Tweet_Dashboard
Programmed tweets streaming ETL pipeline with S3, Kinesis, and QuickSight to visualize reviews sentiment for 3 leading smartphone brands (iPhone, Samsung, OnePlus) across different regions

This repo is for our Trends Marketplace project. We analyzed the sentiments of tweets for Google Pixel3 and compared them with iPhoneXS and oneplus6T as these phones were launched at almost same point of time.

We used AWS kinesis to stream twitter data in real time and stored it in AWS S3. After that we used AWS Lambda which helps in serverless cimputing and called AWS comprehend to analyze the tweets and provide a sentiment score to it. This output data along with raw data is queried using AWS Athena and visualized using AWS QuickSight.

Below is the snapshot of the entire processflow:

## Process Flow
![alt text](https://github.com/yunhanfeng/AWS_Real_Time_Tweet_Dashboard/blob/master/Images/Process%20flow.JPG)

And here is the sanpshot of what QuickSight dashboard looks like.

## Dashboard Layout
![alt text](https://github.com/yunhanfeng/AWS_Real_Time_Tweet_Dashboard/blob/master/Images/Dashboard.JPG)
