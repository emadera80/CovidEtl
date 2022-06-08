# ETL of Covid Data

1) Create Source s3 bucket where the covid data will land.  
2) create destination s3 bucket where parquet files will will be written 
3) create role for AWS Lambda with cloud-watch, s3, glue permission 
4) create lambda function which will trigger by s3 object create event and will trigger glue job the lambda will have the role specified in step3. 
5) create glue job with role.   