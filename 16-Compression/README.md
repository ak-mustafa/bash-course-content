# Compression and Archiving

This section covers compressing and archiving files in Bash, including:

- Using `tar` to create archives
- Using `gzip` and `gunzip` for compression
- Using `zip` and `unzip`

## Examples

1. **Creating a Tar Archive**:
   ```bash
   #!/bin/bash
   tar -cvf archive.tar file1 file2
   ```

2. **Compressing with gzip**:
   ```bash
   #!/bin/bash
   gzip file.txt
   ```

3. **Unzipping a File**:
   ```bash
   #!/bin/bash
   unzip archive.zip
   ```

## Exercises

- Write a script that creates a compressed archive of a directory.
- Write a script that extracts all `.tar.gz` files in a directory.