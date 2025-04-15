# File Permissions

This section explains file permissions in Bash, including:

- Using `chmod` to change permissions
- Using `chown` to change ownership
- Understanding permission symbols

## Examples

1. **Changing Permissions**:
   ```bash
   #!/bin/bash
   chmod 755 script.sh
   ```

2. **Changing Ownership**:
   ```bash
   #!/bin/bash
   chown user:group file.txt
   ```

3. **Viewing Permissions**:
   ```bash
   #!/bin/bash
   ls -l file.txt
   ```

## Exercises

- Write a script that changes the permissions of all `.sh` files in a directory to executable.
- Write a script that changes the ownership of a file to a specific user.