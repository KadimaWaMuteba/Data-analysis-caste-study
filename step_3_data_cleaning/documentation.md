# All documentation of the cleaning process will be here

## Step 1 :  Remove Null or Empty values 

Misspelled words: Did you locate all misspellings?

Mistyped numbers: Did you double-check that your numeric data has been entered correctly?

## Step 2 : Format all column correctly 

## check for incorrect values

## 

Extra spaces and characters: Did you remove any extra spaces or characters using the TRIM function?

Duplicates: Did you remove duplicates in spreadsheets using the Remove Duplicates function or DISTINCT in SQL?

Mismatched data types: Did you check that numeric, date, and string data are typecast correctly?

Messy (inconsistent) strings: Did you make sure that all of your strings are consistent and meaningful?

Messy (inconsistent) date formats: Did you format the dates consistently throughout your dataset?

Misleading variable labels (columns): Did you name your columns meaningfully?

Truncated data: Did you check for truncated or missing data that needs correction?

Business Logic: Did you check that the data makes sense given your knowledge of the business? 


## New
    - Added column classifiers (Date, Time, PerUnitCost, TotalCost, etc. )
    - Added Column "AveCost" to track average item cost

## Changes 
    - Changed date format to MM-DD-YYYY
    - Removal of whitespace (cosmetic)

## Fixes
    - Fixed misalignment in Column "TotalCost" where some rows did not match with correct dates
    - Fixed SUM to run over entire column instead of partial
