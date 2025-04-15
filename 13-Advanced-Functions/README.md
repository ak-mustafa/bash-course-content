# Advanced Functions

This section covers advanced function techniques in Bash, including:

- Using local variables
- Returning values with `return`

## Examples

1. **Using Local Variables**:
   ```bash
   #!/bin/bash
   my_function() {
       local var="local value"
       echo "$var"
   }
   my_function
   ```

2. **Returning Values**:
   ```bash
   #!/bin/bash
   my_function() {
       return 42
   }
   my_function
   echo "Return value: $?"
   ```

## Exercises

- Write a function that calculates the factorial of a number using recursion.
- Write a function that returns the largest number in an array.