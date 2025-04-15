# Package Management

This section explains managing packages in Bash, including:

- Installing and removing packages
- Updating and upgrading packages
- Searching for packages

## Examples

1. **Installing a Package**:
   ```bash
   #!/bin/bash
   sudo apt-get install -y package_name
   ```

2. **Removing a Package**:
   ```bash
   #!/bin/bash
   sudo apt-get remove -y package_name
   ```

3. **Updating Packages**:
   ```bash
   #!/bin/bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

## Exercises

- Write a script that installs a list of packages from a file.
- Write a script that checks for outdated packages and updates them.