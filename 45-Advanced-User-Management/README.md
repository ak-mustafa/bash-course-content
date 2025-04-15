# Advanced User Management

This section covers advanced user management tasks, including:

- Managing user groups
- Automating user creation

## Examples

1. **Adding a User to a Group**:
   ```bash
   #!/bin/bash
   usermod -aG groupname username
   ```

2. **Automating User Creation**:
   ```bash
   #!/bin/bash
   for user in user1 user2 user3; do
       useradd $user
   done
   ```

## Exercises

- Write a script that creates multiple users and assigns them to a group.
- Write a script that lists all users in a specific group.