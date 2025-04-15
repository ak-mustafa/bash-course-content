# Cloud Integration

This section explains integrating Bash scripts with cloud services, including:

- Using AWS CLI
- Using Azure CLI
- Automating cloud tasks

## Examples

1. **Using AWS CLI**:
   ```bash
   #!/bin/bash
   aws s3 ls
   ```

2. **Using Azure CLI**:
   ```bash
   #!/bin/bash
   az storage account list
   ```

3. **Automating Cloud Tasks**:
   ```bash
   #!/bin/bash
   aws ec2 start-instances --instance-ids i-1234567890abcdef0
   ```

## Exercises

- Write a script that uploads a file to an S3 bucket.
- Write a script that lists all virtual machines in an Azure subscription.