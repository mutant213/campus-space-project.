I am working on lab3 
Sample data: data/sample/campus_spaces.csv.
Folder roles: scripts/ for code, data/sample/ for data, docs/ for documentation, and outputs/ for generated results.
Rscript scripts/summarize_spaces.R data/sample/campus_spaces.csv
The script prints its summary in the terminal and does not create a result file.
## How to run

Run this command from the repository root:

```bash
Rscript scripts/summarize_spaces.R data/sample/campus_spaces
```
## Purpose

This project summarizes observed use of campus study spaces using synthetic teaching data.

## Requirements

Tested with R 4.3.3. No additional R packages are required.

## Running the analysis

Run the command shown above from the repository root, campus-space-project.

## Expected results

- Rows: 12
- Total seats: 278
- Occupied seats: 214
- Available seats: 64
- Occupancy rate: 77.0%
- Busiest observed space: S103


