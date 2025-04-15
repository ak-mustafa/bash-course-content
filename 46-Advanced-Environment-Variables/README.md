# Advanced Environment Variables

This section explores advanced usage of environment variables, including:

- Exporting variables across scripts
- Using `.env` files

## Examples

1. **Exporting Variables**:
   ```bash
   #!/bin/bash
   export MY_VAR="value"
   ./another_script.sh
   ```

2. **Using .env Files**:
   ```bash
   #!/bin/bash
   set -a
   source .env
   set +a
   ```

## Exercises

- Write a script that reads variables from a `.env` file and prints them.
- Write a script that exports a variable and uses it in another script.