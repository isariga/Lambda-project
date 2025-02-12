# Lambda-project
Steps of the project
1. Create a S3 bucket where need to uncheck “Block all public access”.
   [Create S3 bucket](./bucket.png)
2. Create Lambda function and write lambda code.
   [Create Lambda](./lambda.png)
3. Lambda Trigger.
   [Trigger Configuration](./lambdatrigger.png)
4. upload html code in object and deploy lambda with S3 bucket.
   [Trigger bucket](./S3buckettrigger.png)
6. Cloud watch metrics to monitor log streams related to S3 file Upload.
   [cloud watch metrics](./cloudwatchmetrics)
7. Log events.
   [log events](./logevents.png)
