# Arrays

This section covers working with arrays in Bash, including:

- Defining arrays
- Accessing array elements
- Iterating over arrays

## Examples

1. **Defining and Accessing Arrays**:
   ```bash
   #!/bin/bash
   fruits=("apple" "banana" "cherry")
   echo "First fruit: ${fruits[0]}"
   ```

2. **Iterating Over Arrays**:
   ```bash
   #!/bin/bash
   for fruit in "${fruits[@]}"; do
       echo "$fruit"
   done
   ```

## Exercises

- Write a script that stores a list of numbers in an array and calculates their sum.
- Write a script that prints all elements of an array in reverse order.