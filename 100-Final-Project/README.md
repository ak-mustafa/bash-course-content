# Final Project

This section provides a final project to apply all the concepts learned in the course.

## Project Description

Create a Bash script that automates the following tasks:

1. Accepts a directory path as input.
2. Counts the number of files and subdirectories in the directory.
3. Searches for a specific word in all `.txt` files in the directory.
4. Creates a backup of all `.txt` files by copying them to a `backup` directory.
5. Logs all actions to a `log.txt` file.

## Requirements

- Use functions to organize the script.
- Handle errors gracefully.
- Use loops and conditionals effectively.

## Example Output

```bash
$ ./final_project.sh /path/to/directory
Files: 10
Directories: 5
Occurrences of 'example': 3
Backup created in /path/to/directory/backup
Log written to /path/to/directory/log.txt
```