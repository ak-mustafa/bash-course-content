# Advanced Text Processing

This section covers advanced text processing techniques in Bash, including:

- Using `awk` for complex data manipulation
- Using `sed` for advanced text substitution
- Combining tools for pipelines

## Examples

1. **Using awk for Data Manipulation**:
   ```bash
   #!/bin/bash
   awk '{if ($3 > 50) print $1}' data.txt
   ```

2. **Using sed for Substitution**:
   ```bash
   #!/bin/bash
   sed -n 's/old/new/p' file.txt
   ```

3. **Combining Tools**:
   ```bash
   #!/bin/bash
   cat file.txt | grep "pattern" | awk '{print $1}'
   ```

## Exercises

- Write a script that extracts specific columns from a CSV file.
- Write a script that replaces all occurrences of a word in multiple files.