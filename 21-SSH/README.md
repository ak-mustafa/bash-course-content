# SSH

This section covers using SSH in Bash scripts, including:

- Connecting to remote servers
- Copying files with `scp`
- Automating SSH tasks

## Examples

1. **Connecting to a Server**:
   ```bash
   #!/bin/bash
   ssh user@server.com
   ```

2. **Copying Files with scp**:
   ```bash
   #!/bin/bash
   scp file.txt user@server.com:/path/to/destination
   ```

3. **Automating Tasks**:
   ```bash
   #!/bin/bash
   ssh user@server.com "ls -l"
   ```

## Exercises

- Write a script that connects to a server and lists files in a directory.
- Write a script that copies multiple files to a remote server.