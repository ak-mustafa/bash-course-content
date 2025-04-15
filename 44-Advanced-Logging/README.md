# Advanced Logging

This section explores advanced logging techniques in Bash, including:

- Rotating log files
- Centralized logging with syslog

## Examples

1. **Log Rotation**:
   ```bash
   #!/bin/bash
   logrotate /etc/logrotate.conf
   ```

2. **Syslog Logging**:
   ```bash
   #!/bin/bash
   logger -p local0.info "This is a log message"
   ```

## Exercises

- Write a script that rotates logs daily.
- Write a script that sends logs to a remote syslog server.