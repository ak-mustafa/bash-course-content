# Functions

This section explains how to write and use functions in Bash scripts, including:

- Defining functions
- Passing arguments to functions
- Returning values from functions

## Examples

1. **Defining a Function**:
   ```bash
   #!/bin/bash
   greet() {
       echo "Hello, $1!"
   }

   greet "World"
   ```

2. **Returning Values**:
   ```bash
   #!/bin/bash
   add() {
       echo $(($1 + $2))
   }

   result=$(add 3 5)
   echo "Result: $result"
   ```

## Exercises

- Write a function that calculates the factorial of a number.
- Write a function that checks if a number is even or odd.