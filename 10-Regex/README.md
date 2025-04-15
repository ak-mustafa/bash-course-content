# Regular Expressions

This section introduces regular expressions in Bash, including:

- Using `grep` with regex
- Using regex in conditional statements

## Examples

1. **Using grep with Regex**:
   ```bash
   #!/bin/bash
   grep -E "^[a-z]+@[a-z]+\.[a-z]{2,}$" emails.txt
   ```

2. **Regex in Conditionals**:
   ```bash
   #!/bin/bash
   if [[ $1 =~ ^[0-9]+$ ]]; then
       echo "Input is a number"
   else
       echo "Input is not a number"
   fi
   ```

## Exercises

- Write a script that validates email addresses using regex.
- Write a script that checks if a string contains only alphabets.