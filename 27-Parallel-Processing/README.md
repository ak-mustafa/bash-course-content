# Parallel Processing

This section explains how to run tasks in parallel in Bash, including:

- Using `&` to run background tasks
- Using `wait` to synchronize tasks
- Using `xargs` for parallel execution

## Examples

1. **Running Background Tasks**:
   ```bash
   #!/bin/bash
   task1 &
   task2 &
   wait
   ```

2. **Using xargs**:
   ```bash
   #!/bin/bash
   echo -e "task1\ntask2" | xargs -n 1 -P 2 bash -c
   ```

## Exercises

- Write a script that downloads multiple files in parallel.
- Write a script that processes multiple files concurrently.