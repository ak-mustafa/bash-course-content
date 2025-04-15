# Text Processing

This section covers text processing in Bash, including:

- Using `grep` to search text
- Using `awk` for text manipulation
- Using `sed` for text substitution

## Examples

1. **Using grep**:
   ```bash
   #!/bin/bash
   grep "pattern" file.txt
   ```

2. **Using awk**:
   ```bash
   #!/bin/bash
   awk '{print $1}' file.txt
   ```

3. **Using sed**:
   ```bash
   #!/bin/bash
   sed 's/old/new/g' file.txt
   ```

## Exercises

- Write a script that counts the number of lines containing a specific word in a file.
- Write a script that replaces all occurrences of a word in a file with another word.