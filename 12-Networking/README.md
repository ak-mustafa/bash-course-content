# Networking

This section covers networking in Bash, including:

- Using `ping` and `curl`
- Checking network connectivity

## Examples

1. **Using ping**:
   ```bash
   #!/bin/bash
   ping -c 4 google.com
   ```

2. **Using curl**:
   ```bash
   #!/bin/bash
   curl -I https://example.com
   ```

## Exercises

- Write a script that checks if a website is reachable.
- Write a script that downloads a file from a URL using `curl`.