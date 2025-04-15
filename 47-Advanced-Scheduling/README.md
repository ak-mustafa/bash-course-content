# Advanced Scheduling

This section covers advanced scheduling tasks, including:

- Scheduling with `at` and `cron`
- Automating recurring tasks

## Examples

1. **Using at Command**:
   ```bash
   #!/bin/bash
   echo "echo 'Task executed'" | at now + 1 minute
   ```

2. **Recurring Cron Jobs**:
   ```bash
   #!/bin/bash
   echo "0 0 * * * /path/to/script.sh" | crontab -
   ```

## Exercises

- Write a script that schedules a task to run every hour.
- Write a script that lists all scheduled tasks for the current user.