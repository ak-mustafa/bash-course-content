# Containers

This section covers working with containers in Bash, including:

- Using Docker CLI
- Building and running containers
- Managing container images

## Examples

1. **Running a Container**:
   ```bash
   #!/bin/bash
   docker run -d nginx
   ```

2. **Building an Image**:
   ```bash
   #!/bin/bash
   docker build -t my-image .
   ```

3. **Listing Images**:
   ```bash
   #!/bin/bash
   docker images
   ```

## Exercises

- Write a script that builds and runs a Docker container.
- Write a script that cleans up unused Docker images.