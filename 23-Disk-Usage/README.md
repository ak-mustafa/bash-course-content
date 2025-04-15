# Disk Usage

This section covers monitoring disk usage in Bash, including:

- Using `df` to check disk space
- Using `du` to check directory sizes
- Cleaning up disk space

## Examples

1. **Checking Disk Space**:
   ```bash
   #!/bin/bash
   df -h
   ```

2. **Checking Directory Sizes**:
   ```bash
   #!/bin/bash
   du -sh /path/to/directory
   ```

3. **Cleaning Up Disk Space**:
   ```bash
   #!/bin/bash
   rm -rf /path/to/temp/files
   ```

## Exercises

- Write a script that lists the top 5 largest directories in a path.
- Write a script that checks if disk usage exceeds 80% and sends an alert.