# Excel Data Processing Script

## Description
This Python script processes an Excel workbook to:
1. Apply a 10% discount to values in the third column
2. Add the discounted values to a new fourth column
3. Create a bar chart visualizing the discounted prices

## Features
- Uses the `openpyxl` library to manipulate Excel files
- Reads data from "Sheet1" of the specified workbook
- Processes all rows from row 2 to the last row with data
- Creates a new column with corrected prices (original prices × 0.9)
- Generates a bar chart from the corrected prices
- Saves the modified workbook with the same filename

## Usage
1. Install the required dependency:
   ```bash
   pip install openpyxl
   ```

2. Call the function with your Excel filename:
   ```python
   process_workbook('your_file.xlsx')
   ```

## Parameters
- `filename`: Path to the Excel file to be processed (must be .xlsx format)

## Output
The script modifies the input file by:
- Adding corrected prices in column D
- Inserting a bar chart starting at cell E2

## Requirements
- Python 3.x
- openpyxl library
