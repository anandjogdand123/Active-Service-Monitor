**AWS Resource Lister**

A shell script to automate the process of listing resources in an AWS account across various services. This script helps in quickly retrieving information about your AWS infrastructure based on the specified region and service.

**Supported Services**
EC2,
RDS,
S3,
CloudFront,
VPC,
IAM,
Route53,
CloudWatch,
CloudFormation,
Lambda,
SNS,
SQS,
DynamoDB,
EBS.

**Usage**
Ensure AWS CLI is installed and configured.

**Run the script with the AWS region and service as arguments:**
./aws_resource_list.sh <aws_region> <aws_service>
**Example:**
./aws_resource_list.sh us-east-1 ec2
**Prerequisites**
AWS CLI installed and configured with valid credentials.
**Author**
Script by Anand Jogdand


AWS CLI installed and configured with valid credentials.
Author
Script by Abhishek Veeramalla.
