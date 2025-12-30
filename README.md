# AWS-ETL-Pipeline
Create a end to end pipeline.

1. The source data is stored in a S3 bucket.
2. The data format stored in S3 bucket is in CSV.
3. We create another S3 bucket and will store the transformed data in avro format.
4. We utilize AWS Glue for crawler to gather the metadata of the source data.
5. After that we jump into ETL pipeline (Visual) under AWS Glue.
6. We select whcih columns we will add from original source.
7. We create a Lamda trigger function.
8. Before running the job we provide all the policies related to AWS Glue and AWS Lamda for the IAM user to run the job and won't be denied permission.
9. Job is successfully run.
<img width="1871" height="155" alt="image" src="https://github.com/user-attachments/assets/40ec26e1-366a-4b45-ba60-cc409bfa0821" />
