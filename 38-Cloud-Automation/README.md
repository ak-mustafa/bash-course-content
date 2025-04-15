# Cloud Automation

This section covers automating cloud tasks with Bash, including:

- Using AWS CLI
- Automating resource creation

## Examples

1. **Listing S3 Buckets**:
   ```bash
   #!/bin/bash
   aws s3 ls
   ```

2. **Creating an EC2 Instance**:
   ```bash
   #!/bin/bash
   aws ec2 run-instances --image-id ami-12345678 --count 1 --instance-type t2.micro
   ```

## Exercises

- Write a script that lists all EC2 instances in a region.
- Write a script that creates an S3 bucket.