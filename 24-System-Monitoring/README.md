# System Monitoring

This section covers monitoring system performance in Bash, including:

- Using `top` and `htop`
- Monitoring CPU and memory usage
- Logging system metrics

## Examples

1. **Using top**:
   ```bash
   #!/bin/bash
   top -n 1
   ```

2. **Monitoring CPU Usage**:
   ```bash
   #!/bin/bash
   mpstat
   ```

3. **Logging Metrics**:
   ```bash
   #!/bin/bash
   echo "$(date): $(free -h)" >> system.log
   ```

## Exercises

- Write a script that logs CPU and memory usage every minute.
- Write a script that alerts if CPU usage exceeds 90%.