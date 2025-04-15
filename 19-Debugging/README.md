# Debugging

This section covers debugging Bash scripts, including:

- Using `set` options for debugging
- Using `trap` for error handling
- Debugging with `bash -x`

## Examples

1. **Using set -x**:
   ```bash
   #!/bin/bash
   set -x
   echo "Debugging..."
   set +x
   ```

2. **Using trap**:
   ```bash
   #!/bin/bash
   trap "echo 'An error occurred!'" ERR
   false
   ```

3. **Debugging with bash -x**:
   ```bash
   bash -x script.sh
   ```

## Exercises

- Write a script that uses `trap` to handle errors.
- Debug a script with syntax errors using `bash -x`.