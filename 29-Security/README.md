# Security

This section covers security practices in Bash scripting, including:

- Using `chmod` for secure permissions
- Avoiding command injection
- Encrypting files with `gpg`

## Examples

1. **Setting Secure Permissions**:
   ```bash
   #!/bin/bash
   chmod 600 sensitive_file.txt
   ```

2. **Avoiding Command Injection**:
   ```bash
   #!/bin/bash
   user_input="$(echo $1 | sed 's/[^a-zA-Z0-9]//g')"
   echo "Safe input: $user_input"
   ```

3. **Encrypting Files**:
   ```bash
   #!/bin/bash
   gpg -c file.txt
   ```

## Exercises

- Write a script that encrypts a file and decrypts it on demand.
- Write a script that validates user input to prevent command injection.