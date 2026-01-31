# aws-s3-glacier-storage
# Amazon S3 Glacier – Object Storage Exercise

## Overview
This project demonstrates how to store data in Amazon S3 using the Glacier storage class for long-term archival purposes.

## Objective
- Upload an object to Amazon S3
- Store the object using Glacier Flexible Retrieval
- Verify the storage class
- Understand archival storage use cases

## Steps Performed
1. Used an existing S3 bucket in the eu-north-1 (Stockholm) region
2. Uploaded a small text file via the AWS Management Console
3. Selected Glacier Flexible Retrieval as the storage class
4. Verified the object’s storage class after upload

## Key Concepts Learned
- S3 Glacier is a storage class within Amazon S3
- Glacier is designed for long-term, infrequently accessed data
- Retrieval from Glacier is slower and may incur additional cost
- Glacier is commonly used for compliance and archival storage

## Screenshots

### Glacier Object Upload Confirmation
(screenshots/glacier-object-details.png)


### Object Stored in Glacier
(screenshots/glacier-object-details.png)

## Conclusion
This exercise provided hands-on experience with archival storage in AWS and demonstrated how organizations optimize costs using Amazon S3 Glacier.
