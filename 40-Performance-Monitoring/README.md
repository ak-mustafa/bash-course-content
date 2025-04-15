# Performance Monitoring

This section covers monitoring system performance with Bash, including:

- Using `top` and `htop`
- Monitoring disk usage

## Examples

1. **Monitoring CPU Usage**:
   ```bash
   #!/bin/bash
   top -b -n 1 | head -n 10
   ```

2. **Checking Disk Usage**:
   ```bash
   #!/bin/bash
   df -h
   ```

## Exercises

- Write a script that logs CPU usage every minute.
- Write a script that checks if disk usage exceeds 80%.