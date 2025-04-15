# Conditionals

This section explains how to use conditional statements in Bash, including:

- `if` statements
- `case` statements

## Examples

1. **If Statement**:
   ```bash
   #!/bin/bash
   if [ $1 -gt 10 ]; then
       echo "Greater than 10"
   else
       echo "10 or less"
   fi
   ```

2. **Case Statement**:
   ```bash
   #!/bin/bash
   case $1 in
       start)
           echo "Starting..." ;;
       stop)
           echo "Stopping..." ;;
       *)
           echo "Unknown command" ;;
   esac
   ```

## Exercises

- Write a script that checks if a number is positive, negative, or zero.
- Write a script that takes a command-line argument and prints a message based on its value.