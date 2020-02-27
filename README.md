# Cloud formation script

## Setup

### Create
sh create_stack

### Delete
aws s3 rm s3://<s3bucket_name> --recursive

aws cloudformation delete-stack --stack-name <stack_name> --region <region_name> --profile <profile_name>

