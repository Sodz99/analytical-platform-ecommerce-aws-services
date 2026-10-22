# Build an Analytical Platform for eCommerce using AWS Services

Build an Analytical Platform for eCommerce using AWS Services — AWS Data Engineering project.

## Overview
Ecommerce analytics is the process of collecting data from all of the sources that affect a certain shop. Analysts can then utilize this information to deduce changes in customer behavior and online shopping patterns. Ecommerce analytics spans the whole customer journey, from discovery through acquisition, conversion, and eventually retention and support. In this project, we will use an eCommerce dataset to simulate the logs of user purchases, product views, cart history, and the user’s journey on the online platform to create two analytical pipelines, Batch and Real-time. The Batch processing will involve data ingestion, Lake House architecture, processing, visualization using Amazon Kinesis, Glue, S3, and QuickSight to draw insights regarding the following:
- Unique visitors per day
- During a certain time, the users add products to their carts but don’t buy them
- Top categories per hour or weekday (i.e. to promote discounts based on trends)
- To know which brands need more marketin

## Data
This dataset contains user behavioral information from a large multi-category online store along with fields such as event_time, event_type, product_id, price, user_id. Each row in the file represents one of the following event types:
- View
- Cart
- Removed from Cart
- Purchase

_Data is not included in this repository._

## Tech stack
➔ Languages-
- SQL, Python3 ➔ Services -
- AWS S3, AWS Glue, AWS Athena, AWS Cloud9, Apache Flink, Amazon Kinesis, Amazon SNS, AWS Lambda, Amazon CloudWatch, QuickSight, Apache Zepplin, Amazon DynamoDB, AWS Glue DataBrew

Amazon S3 Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance. Users may save and retrieve any quantity of data using Amazon S3 at any time and from any location.

## How to run

## Project structure
```
.gitignore
Code/
  video11 - head N from Zip file.sh
  video12 - stream-data-app-simulation.py
  video17 - lambda_function.py
README.md
```

## Credits
Based on a ProjectPro guided project.
