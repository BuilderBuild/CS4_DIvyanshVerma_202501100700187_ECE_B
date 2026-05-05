# CS4_DIvyanshVerma_202501100700187_ECE_B
PYTHON CASE STUDY 4 

# CS4 Submission

## Project Overview

This repository contains a Python script that demonstrates basic text file handling and log processing operations. The script reads a log file (`CS4.txt`), performs classification of log lines, writes filtered logs to separate files, and includes a simple search feature.

## Files

- `answers.py` - Main Python script performing the tasks.
- `CS4.txt` - Sample log file used by the script.
- `info_logs.txt` - Generated file containing only `INFO` log entries.
- `warning_logs.txt` - Generated file containing only `WARNING` log entries.
- `error_logs.txt` - Generated file containing only `ERROR` log entries.
- `search_result.txt` - Generated file containing lines matching the search keyword.
- `readm.md` - Existing project notes file.

## What the Script Does

1. Reads the contents of `CS4.txt` using `read()`, `readline()`, and `readlines()`.
2. Counts the number of `INFO`, `WARNING`, and `ERROR` log lines.
3. Writes filtered log entries to separate output files.
4. Performs a search for a predefined keyword (`ERROR`) and writes matching lines to `search_result.txt`.
5. Demonstrates file pointer operations using `seek()` to read specific sections of the file.

## How to Run

1. Open a terminal in the `d:\CS4_Submission` directory.
2. Run the script with Python:

python answers.py


3. Check the generated output files:
   - `info_logs.txt`
   - `warning_logs.txt`
   - `error_logs.txt`
   - `search_result.txt`

## Notes

- The search keyword in `answers.py` is currently hardcoded to `ERROR`.
- The script uses file operations such as `write()` and `writelines()` to demonstrate different writing approaches.
- `CS4.txt` contains sample log entries for testing the script.
