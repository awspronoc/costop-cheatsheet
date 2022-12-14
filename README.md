# Life-changing habits to reduce your cloud costs
This is a cheat-sheet that goes with STP203 "Life-Changing Habits To Reduce Your Cloud Costs"


## Resources & Links

### Things you should absolutely be doing
* [Enable MFA on all your root accounts](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html)
* [Rotate your IAM keys automtically every 90 days](https://github.com/aws-samples/aws-iam-access-key-auto-rotation)
* [Explore AWS IAM Identity Center instead of logging in using IAM](https://docs.aws.amazon.com/singlesignon/latest/userguide/step1.html)
* [Block public access to unnecessary S3 buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/access-control-block-public-access.html)
* [Explore Amazon Macie for more advanced S3 checks](https://docs.aws.amazon.com/macie/latest/user/monitoring-s3.html)
* [Use Amazon CloudFront for egress cacheable data](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/distribution-overview.html)
* [Create billing alarms to monitor estimated AWS charges](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)
* [Take actions on alarms through Amazon EventBridge](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/cloudwatch-and-eventbridge.html)
* [Understand your AWS Bill breakdown - try out the new interface!](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/invoice.html)
* [Plan your workload using draw.io, cost calculator and spreadsheets](https://calculator.aws/#/)
* [Keep track of various metrics and KPIs](#metrics--kpis)
* [AWS Cost explorer for charts and graphs on usage](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-exploring-data.html)
* [Explore savings plans for well-developed architectures](https://aws.amazon.com/savingsplans/compute-pricing/)


### Things that are a good way of life
* [Conduct an AWS Well Architected Framework Review](https://docs.aws.amazon.com/wellarchitected/latest/framework/the-pillars-of-the-framework.html)
* [Explore the Well Architected Labs](https://wellarchitectedlabs.com/)
* [The right compute for the right job](https://aws.amazon.com/products/compute/)
* [The right database for the right job - compare technology and use-case](https://aws.amazon.com/products/databases/)

#### Quick Wins

* [Go Serverless!](https://serverlessland.com/)
* [Switch to GP3 EBS volumes](https://aws.amazon.com/blogs/storage/migrate-your-amazon-ebs-volumes-from-gp2-to-gp3-and-save-up-to-20-on-costs/)
* [Rely on spot instances for a discount of upto 90% compared to on-demand instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/how-spot-instances-work.html)
* [Understand Amazon S3 storage classes](https://aws.amazon.com/s3/storage-classes/)
* [Rely on intelligent-tiering for automatic transitioning to different storage classes](https://aws.amazon.com/s3/storage-classes/intelligent-tiering/)
* [Automate control over services through AWS Budget actions and service control policies](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-controls.html)


### Things to help you as you grow
* [AWS Cost Anomaly Detection - get alerted on anomalous spend](https://docs.aws.amazon.com/cost-management/latest/userguide/manage-ad.html)
* [Schedule your resources per your need](https://aws.amazon.com/solutions/implementations/instance-scheduler/)
* [CUDOS Workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/fd889151-38aa-4fe2-a29d-d5fa557197bb/en-US)



## Metrics & KPIs

* Create your own metrics and then finalize and track monthly and yearly


| Workload Specific  | KPIs | Cumulative | 
| ------------- | ------------- | ------------- |
| Cost per unit of work (e.g., cost per page of OCR) | Revenue run-rate  | AWS Run Rate |
| Cost for a unit of work that generates revenue | Margin  | Cost breakdown per workload/project | 
| Cost for increased use (verified against calculator) | Monthly Active Users | Increased cost for more users per workload/project | 


