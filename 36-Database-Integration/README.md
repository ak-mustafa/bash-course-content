# Database Integration

This section covers integrating Bash scripts with databases, including:

- Using `mysql` CLI
- Querying a database

## Examples

1. **Connecting to MySQL**:
   ```bash
   #!/bin/bash
   mysql -u username -p -e "SHOW DATABASES;"
   ```

2. **Running a Query**:
   ```bash
   #!/bin/bash
   mysql -u username -p -e "SELECT * FROM table_name;"
   ```

## Exercises

- Write a script that lists all tables in a database.
- Write a script that inserts a new record into a table.