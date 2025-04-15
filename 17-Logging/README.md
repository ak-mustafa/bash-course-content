# Logging

This section explains how to implement logging in Bash scripts, including:

- Writing logs to a file
- Using timestamps in logs
- Rotating logs

## Examples

1. **Writing Logs**:
   ```bash
   #!/bin/bash
   echo "Log entry" >> script.log
   ```

2. **Using Timestamps**:
   ```bash
   #!/bin/bash
   echo "$(date): Log entry" >> script.log
   ```

3. **Rotating Logs**:
   ```bash
   #!/bin/bash
   mv script.log script.log.bak
   ```

## Exercises

- Write a script that logs the output of a command to a file.
- Write a script that rotates logs daily.