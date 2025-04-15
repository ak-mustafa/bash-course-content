# Advanced Security

This section explores advanced security techniques in Bash, including:

- Using `openssl` for encryption
- Generating SSH keys

## Examples

1. **Encrypting a File**:
   ```bash
   #!/bin/bash
   openssl enc -aes-256-cbc -salt -in file.txt -out file.txt.enc
   ```

2. **Generating SSH Keys**:
   ```bash
   #!/bin/bash
   ssh-keygen -t rsa -b 2048
   ```

## Exercises

- Write a script that encrypts a directory.
- Write a script that generates an SSH key pair and prints the public key.