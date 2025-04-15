# Process Management

This section covers managing processes in Bash, including:

- Using `ps` to list processes
- Using `kill` to terminate processes
- Using `jobs` and `bg/fg` for background/foreground processes

## Examples

1. **Listing Processes**:
   ```bash
   #!/bin/bash
   ps aux
   ```

2. **Killing a Process**:
   ```bash
   #!/bin/bash
   kill -9 <PID>
   ```

3. **Background and Foreground**:
   ```bash
   #!/bin/bash
   sleep 100 &
   jobs
   fg %1
   ```

## Exercises

- Write a script that lists all running processes and their memory usage.
- Write a script that starts a background process and brings it to the foreground.