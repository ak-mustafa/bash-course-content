# Advanced File Handling

This section explores advanced file handling techniques in Bash, including:

- Using `find` to locate files
- Using `xargs` for batch processing

## Examples

1. **Finding Files**:
   ```bash
   #!/bin/bash
   find /path/to/directory -name "*.txt"
   ```

2. **Batch Processing**:
   ```bash
   #!/bin/bash
   find . -name "*.txt" | xargs grep "pattern"
   ```

## Exercises

- Write a script that finds all `.log` files and deletes them.
- Write a script that compresses all `.txt` files in a directory.