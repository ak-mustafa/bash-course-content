# Backup Scripts

This section explains how to create backup scripts in Bash, including:

- Backing up files and directories
- Using timestamps in backups
- Automating backups with cron

## Examples

1. **Backing Up a Directory**:
   ```bash
   #!/bin/bash
   tar -czvf backup.tar.gz /path/to/directory
   ```

2. **Using Timestamps**:
   ```bash
   #!/bin/bash
   tar -czvf backup_$(date +%Y%m%d).tar.gz /path/to/directory
   ```

3. **Automating Backups**:
   ```bash
   #!/bin/bash
   echo "0 2 * * * tar -czvf backup.tar.gz /path/to/directory" | crontab -
   ```

## Exercises

- Write a script that creates a daily backup of a directory.
- Write a script that restores files from a backup.