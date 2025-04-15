# Advanced Networking

This section covers advanced networking tasks in Bash, including:

- Using `netstat` and `ss`
- Configuring network interfaces
- Monitoring network traffic

## Examples

1. **Using netstat**:
   ```bash
   #!/bin/bash
   netstat -tuln
   ```

2. **Monitoring Traffic**:
   ```bash
   #!/bin/bash
   tcpdump -i eth0
   ```

3. **Configuring Interfaces**:
   ```bash
   #!/bin/bash
   ifconfig eth0 up
   ```

## Exercises

- Write a script that lists all open network connections.
- Write a script that captures network traffic for a specific port.