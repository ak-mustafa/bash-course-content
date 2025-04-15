# Data Processing

This section explains processing data in Bash, including:

- Sorting and filtering data
- Using `cut` and `uniq`
- Combining tools for data pipelines

## Examples

1. **Sorting Data**:
   ```bash
   #!/bin/bash
   sort file.txt
   ```

2. **Filtering Unique Lines**:
   ```bash
   #!/bin/bash
   uniq file.txt
   ```

3. **Using cut**:
   ```bash
   #!/bin/bash
   cut -d',' -f1 file.csv
   ```

## Exercises

- Write a script that extracts unique email addresses from a file.
- Write a script that sorts a CSV file by a specific column.