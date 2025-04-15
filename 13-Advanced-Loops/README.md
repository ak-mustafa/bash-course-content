# Advanced Loops

This section explores advanced looping techniques in Bash, including:

- Nested loops
- Looping over files

## Examples

1. **Nested Loops**:
   ```bash
   #!/bin/bash
   for i in {1..3}; do
       for j in {1..3}; do
           echo "$i, $j"
       done
   done
   ```

2. **Looping Over Files**:
   ```bash
   #!/bin/bash
   for file in *.txt; do
       echo "Processing $file"
   done
   ```

## Exercises

- Write a script that prints a multiplication table using nested loops.
- Write a script that renames all `.txt` files in a directory to `.bak`.