# Advanced APIs

This section explores advanced API interactions in Bash, including:

- Using `curl` for POST requests
- Handling API authentication

## Examples

1. **POST Request**:
   ```bash
   #!/bin/bash
   curl -X POST -H "Content-Type: application/json" -d '{"key": "value"}' https://api.example.com/resource
   ```

2. **Authentication**:
   ```bash
   #!/bin/bash
   curl -u username:password https://api.example.com/resource
   ```

## Exercises

- Write a script that sends a POST request to an API and prints the response.
- Write a script that retrieves data from an API using an API key.