# Error Handling

This section explains how to handle errors in Bash scripts, including:

- Using exit codes
- Using `trap` for cleanup
- Debugging with `set` options

## Examples

1. **Using Exit Codes**:
   ```bash
   #!/bin/bash
   if [ ! -f file.txt ]; then
       echo "File not found!"
       exit 1
   fi
   ```

2. **Using trap**:
   ```bash
   #!/bin/bash
   trap "echo 'Cleaning up...'; rm -f temp.txt" EXIT
   touch temp.txt
   ```

3. **Debugging with set**:
   ```bash
   #!/bin/bash
   set -x
   echo "Debugging..."
   set +x
   ```

## Exercises

- Write a script that exits with an error code if a required file is missing.
- Write a script that cleans up temporary files on exit.