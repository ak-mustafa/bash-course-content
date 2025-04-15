# Scheduling Tasks

This section covers scheduling tasks in Bash, including:

- Using `cron` jobs
- Using `at` command

## Examples

1. **Creating a Cron Job**:
   ```bash
   # Edit crontab
   crontab -e
   # Add a job to run a script every day at 8 AM
   0 8 * * * /path/to/script.sh
   ```

2. **Using at Command**:
   ```bash
   # Schedule a script to run at a specific time
   echo "/path/to/script.sh" | at 10:00
   ```

## Exercises

- Write a script that creates a cron job to back up a directory daily.
- Write a script that schedules a one-time task using the `at` command.