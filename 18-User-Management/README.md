# User Management

This section covers managing users in Bash, including:

- Adding and deleting users
- Modifying user accounts
- Viewing user information

## Examples

1. **Adding a User**:
   ```bash
   #!/bin/bash
   sudo useradd newuser
   ```

2. **Deleting a User**:
   ```bash
   #!/bin/bash
   sudo userdel newuser
   ```

3. **Viewing User Information**:
   ```bash
   #!/bin/bash
   id username
   ```

## Exercises

- Write a script that creates a new user and sets a default password.
- Write a script that lists all users on the system.