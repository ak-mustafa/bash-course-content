# Advanced Compression

This section covers advanced compression techniques in Bash, including:

- Using `tar` for archiving
- Compressing with `gzip` and `bzip2`

## Examples

1. **Creating a Tarball**:
   ```bash
   #!/bin/bash
   tar -cvf archive.tar /path/to/directory
   ```

2. **Compressing a File**:
   ```bash
   #!/bin/bash
   gzip file.txt
   ```

## Exercises

- Write a script that creates a compressed backup of a directory.
- Write a script that extracts a tarball.