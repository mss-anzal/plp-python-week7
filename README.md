# PLP Python Week 7 Assignment

## Assignment Overview
This project demonstrates Python file handling, CSV processing, exception handling, and report generation.

## Files

- **my_notes.py** – Creates, appends, reads, and counts notes in a text file.
- **my_notes.txt** – Stores the notes created by the Python program.
- **report_builder.py** – Reads learner records from a CSV file, calculates results, and generates a report.
- **hubs.csv** – Contains learner names, hubs, and scores.
- **report.txt** – Contains the generated learner performance report.

## What happens if "a" is changed to "w"?

Changing the file mode from `"a"` (append) to `"w"` (write) would overwrite the existing file contents instead of adding new information. Therefore, the earlier notes would be erased when the fourth note is written.