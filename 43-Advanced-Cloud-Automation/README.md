# Advanced Cloud Automation

This section covers advanced cloud automation tasks, including:

- Automating multi-region deployments
- Managing cloud resources with Bash scripts

## Examples

1. **Multi-Region Deployment**:
   ```bash
   #!/bin/bash
   regions=("us-east-1" "us-west-2")
   for region in "${regions[@]}"; do
       aws ec2 describe-instances --region $region
   done
   ```

2. **Resource Cleanup**:
   ```bash
   #!/bin/bash
   aws s3 rm s3://my-bucket --recursive
   ```

## Exercises

- Write a script that lists all EC2 instances across multiple regions.
- Write a script that deletes unused cloud resources.