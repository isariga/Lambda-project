# Lambda-project
Steps of the project
1. Create a S3 bucket where need to uncheck “Block all public access”.
   ![Create S3 bucket](./bucket.png)
2. Create Lambda function and write lambda code.
   ![Create Lambda](./lambda.png)
3. Lambda Trigger.
   ![Trigger Configuration](./lambda_trigger.png)
4. upload html code in object and deploy lambda with S3 bucket.
   ![Trigger bucket](./S3_bucket_trigger.png)
6. Cloud watch metrics to monitor log streams related to S3 file Upload.
   ![cloud watch metrics](./cloudwatch_metrics)
7. Log events.
   ![log events](./log_events.png)
