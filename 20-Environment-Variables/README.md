# Environment Variables

This section explains how to work with environment variables in Bash, including:

- Setting and exporting variables
- Accessing system environment variables
- Using `.env` files

## Examples

1. **Setting and Exporting Variables**:
   ```bash
   #!/bin/bash
   export MY_VAR="Hello"
   echo "$MY_VAR"
   ```

2. **Accessing System Variables**:
   ```bash
   #!/bin/bash
   echo "Home directory: $HOME"
   ```

3. **Using .env Files**:
   ```bash
   #!/bin/bash
   source .env
   echo "$MY_VAR"
   ```

## Exercises

- Write a script that sets and exports a variable.
- Write a script that reads variables from a `.env` file.