# Loops

This section covers loops in Bash scripting, including:

- `for` loops
- `while` loops
- `until` loops

## Examples

1. **For Loop**:
   ```bash
   #!/bin/bash
   for i in {1..5}; do
       echo "Number: $i"
   done
   ```

2. **While Loop**:
   ```bash
   #!/bin/bash
   count=1
   while [ $count -le 5 ]; do
       echo "Count: $count"
       ((count++))
   done
   ```

3. **Until Loop**:
   ```bash
   #!/bin/bash
   count=1
   until [ $count -gt 5 ]; do
       echo "Count: $count"
       ((count++))
   done
   ```

## Exercises

- Write a script that prints numbers from 1 to 10 using a `for` loop.
- Write a script that keeps asking for user input until they type "exit".