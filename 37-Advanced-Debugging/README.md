# Advanced Debugging

This section explores advanced debugging techniques in Bash, including:

- Using `trap` for debugging
- Logging debug information

## Examples

1. **Using trap**:
   ```bash
   #!/bin/bash
   trap 'echo "Error on line $LINENO"' ERR
   ```

2. **Logging Debug Info**:
   ```bash
   #!/bin/bash
   set -x
   echo "Debugging..."
   set +x
   ```

## Exercises

- Write a script that logs all executed commands to a file.
- Write a script that traps errors and prints the line number.