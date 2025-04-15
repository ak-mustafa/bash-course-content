# Advanced Disk Management

This section covers advanced disk management tasks, including:

- Managing partitions
- Monitoring disk health

## Examples

1. **Creating a Partition**:
   ```bash
   #!/bin/bash
   fdisk /dev/sda
   ```

2. **Checking Disk Health**:
   ```bash
   #!/bin/bash
   smartctl -H /dev/sda
   ```

## Exercises

- Write a script that lists all partitions on a disk.
- Write a script that checks the health of all disks.