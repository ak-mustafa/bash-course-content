# JSON Processing

This section covers working with JSON data in Bash, including:

- Using `jq` to parse JSON
- Extracting specific fields

## Examples

1. **Parsing JSON**:
   ```bash
   #!/bin/bash
   echo '{"name": "John", "age": 30}' | jq '.name'
   ```

2. **Extracting Fields**:
   ```bash
   #!/bin/bash
   jq '.users[0].name' data.json
   ```

## Exercises

- Write a script that extracts all user names from a JSON file.
- Write a script that counts the number of objects in a JSON array.