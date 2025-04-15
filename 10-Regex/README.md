# Regular Expressions

This section introduces regular expressions in Bash, including:

- Using `grep` with regex
- Pattern matching in scripts

## Examples

1. **Using grep with Regex**:
   ```bash
   #!/bin/bash
   grep -E "^[a-z]+@[a-z]+\.[a-z]{2,}$" emails.txt
   ```

2. **Pattern Matching**:
   ```bash
   #!/bin/bash
   if [[ "hello123" =~ ^[a-z]+[0-9]+$ ]]; then
       echo "Pattern matched!"
   fi
   ```

## Exercises

- Write a script that validates email addresses using regex.
- Write a script that checks if a string contains only digits.