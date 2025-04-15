# APIs

This section covers interacting with APIs in Bash, including:

- Using `curl` for API requests
- Parsing JSON responses with `jq`
- Automating API tasks

## Examples

1. **Making a GET Request**:
   ```bash
   #!/bin/bash
   curl -X GET https://api.example.com/data
   ```

2. **Parsing JSON**:
   ```bash
   #!/bin/bash
   curl -s https://api.example.com/data | jq '.key'
   ```

3. **Automating API Tasks**:
   ```bash
   #!/bin/bash
   curl -X POST -H "Content-Type: application/json" -d '{"key":"value"}' https://api.example.com/data
   ```

## Exercises

- Write a script that fetches weather data from an API and displays it.
- Write a script that sends data to an API and logs the response.