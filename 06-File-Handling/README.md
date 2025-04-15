# File Handling

This section covers file handling in Bash, including:

- Reading files
- Writing to files
- Appending to files

## Examples

1. **Reading a File**:
   ```bash
   #!/bin/bash
   while read line; do
       echo "$line"
   done < file.txt
   ```

2. **Writing to a File**:
   ```bash
   #!/bin/bash
   echo "Hello, World!" > output.txt
   ```

3. **Appending to a File**:
   ```bash
   #!/bin/bash
   echo "Another line" >> output.txt
   ```

## Exercises

- Write a script that counts the number of lines in a file.
- Write a script that creates a backup of a file by copying it to a new file with a `.bak` extension.