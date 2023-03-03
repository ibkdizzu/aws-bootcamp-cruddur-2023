# Week 0 — Billing and Architecture

## Billing
Billing console provides a general overview of your spending and other billing related matters

### Important Information in Billing

- Some services vary in pricing based on region
- Billing provides a breakdown of services and charges the they attract
- It provides a way to track free-tier utilization
Amazon Web Service Free tier account has 3 offers
* Free trials: These are services that can be used on for short period throughout the lifetime of the account, unless otherwise payed for. Examples are Amazon Redshift, Amazon SageMaker, Amazon Inspector

* 12 months Free: These are services that are free for up to 12 months and then charges begin to apply
Examples are: Amazon EC2, Amazon S3, Amazon Route 53, Amazon RDS
> **Note** : Caveat of this that some of these services e.e Amazon EC2 and Amazon S3 have actual usage hours **750hrs** attached to them, that adds up to a full month in hours.
However these hours can be spent simultenously e.g running multiple AWS EC2 instances at the same time or multiple S3 buckets.
This means the 750 hrs can be used up before the end of a month and for these extra usage, charges will apply

* Always free: As the name suggests, these services are not charged for any usage and are available for all customers. Example: AWS Lambda, Dynamo DB, Amazon Cloudwatch, Amazon SNS

To ensure that you are running within the free tier scope, especially  for the 12 months free services that can potentially be exhausted before the end 0of month, ensure to track your usage with the free tier option in Billing

![Free tier](0-asset/1.Freetier.PNG)

In the diagram above, no data is populated yet on this free account, however, ensure to check back at intervals to monitor your free tier usage




