# AWS-Cost-Optimization--python-boto3
 AWS Cost Optimization project using lambda function followed by Python-Boto3.

AWS Lambda/Serverless:
As a devops engineer we use lambda function for cost optimization , you can trigger lambda function with wide range of services such as s3, cloudwatch and we can also perform event driven activities.

AWS Cost Optimization:
AWS Cost Optimization involves techniques and strategies to minimize the cost of running workloads in Amazon Web Services (AWS) without sacrificing performance or scalability. AWS provides a wide range of services and pricing models, so managing and optimizing costs is essential to avoid overpaying for unused or underutilized resources.

Project:
AWS Cloud Cost Optimization - Identifying Stale Resources

Identifying Stale EBS Snapshots

In this example, we'll create a Lambda function that identifies EBS snapshots that are no longer associated with any active EC2 instance and deletes them to save on storage costs.

Description:

The Lambda function fetches all EBS snapshots owned by the same account ('self') and also retrieves a list of active EC2 instances (running and stopped). For each snapshot, it checks if the associated volume (if exists) is not associated with any active instance. If it finds a stale snapshot, it deletes it, effectively optimizing storage costs.


 ![11](https://github.com/user-attachments/assets/55b6623d-96fd-406f-abb1-b4e24bd300ff)

 

![12](https://github.com/user-attachments/assets/7bf590b8-7876-4106-a0a4-57e35b5f93dd)


![13](https://github.com/user-attachments/assets/a767837f-f3f5-41e0-b921-3a83ce6c4718)


![14](https://github.com/user-attachments/assets/d6cf1656-da11-4149-8408-093d87d5893d)

![15](https://github.com/user-attachments/assets/5fd5de09-b8c3-45e8-a52d-c9e880754765)


![16](https://github.com/user-attachments/assets/64aa9453-221b-4db1-ba67-58e76d2ec552)

![17](https://github.com/user-attachments/assets/cfa3b680-8a9f-42a1-aafc-c4ad38d00b51)


