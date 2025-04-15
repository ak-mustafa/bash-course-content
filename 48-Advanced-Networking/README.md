# Advanced Networking

This section explores advanced networking tasks, including:

- Configuring network interfaces
- Monitoring network traffic

## Examples

1. **Configuring an Interface**:
   ```bash
   #!/bin/bash
   ifconfig eth0 192.168.1.100 netmask 255.255.255.0
   ```

2. **Monitoring Traffic**:
   ```bash
   #!/bin/bash
   tcpdump -i eth0
   ```

## Exercises

- Write a script that configures a static IP address.
- Write a script that captures network traffic for a specific port.