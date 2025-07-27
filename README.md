# file-handling-mini-project
file handle using python
# File Handling Mini Project

This mini project processes student marks from a CSV file, determines the top student for each subject, and identifies the overall top student. The results are printed to the console and saved to an output file.

## How It Works

1. **Input Data**:  
   The project reads student marks from [`mini_project_data.txt`](mini_project_data.txt), which contains lines in the format:
   ```
   Name, Subject, Marks
   Amal, Sceince, 69
   Kamal, Maths, 72
   ...
   ```

2. **Processing**:  
   - For each subject, the student with the highest marks is determined.
   - The total marks for each student across all subjects are calculated.
   - The student with the highest total marks is identified as the overall top student.

3. **Output**:  
   - The results are printed to the console.
   - The same results are written to [`output.txt`](output.txt).

## How to Run

1. Ensure [`mini_project_data.txt`](mini_project_data.txt) is present in the same directory as [`mini_project_file_handling.py`](mini_project_file_handling.py).
2. Run the script:
   ```sh
   python mini_project_file_handling.py
   ```
3. Check the results in the console and in [`output.txt`](output.txt).

## Files

- [`mini_project_file_handling.py`](mini_project_file_handling.py): Main script for processing the data.
- [`mini_project_data.txt`](mini_project_data.txt): Input data file with student marks.
- [`output.txt`](output.txt): Output file with the results.

## Example Output

```
Top student for Sceince is Savindu with 73 marks.
Top student for Maths is Kavindu with 89 marks.
Top student for Sinhala is Ravindu with 46 marks.
Top student for History is Kavindu with 94 marks.
Top student for English is Savindu with 76 marks.
Top student is Kavindu with 251
