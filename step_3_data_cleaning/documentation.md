# All documentation of the cleaning process will be here
The tool for the processing is R language with Rposit

### Business Logic (Check to see if the data makes sense given my understanding of the business) 
The column of trip_id, bike_id,readible_type, start_lat, start_long, end_lat, end_long are not necessary for this use case analysis

### Adapt the name of the columns by naming them in a meaningful way

### Check that numeric, date, and string data are typecast correctly

### Remove Null or Empty values 
Remove lines where the sex and year of birth are missing

### Correct mispelled words and mistyped numeric values

### Check for incorrect values

### Format all column correctly 

### Removal of extra spaces and characters using the TRIM function

### Remove duplicates in spreadsheets using the Remove Duplicates function or DISTINCT in SQL

### Messy (inconsistent) strings 

### Messy (inconsistent) date formats throughout the dataset

### Truncated data : missing data that needs correction

### Multiple Umputation of the gender and year variable
Used to fill the missing values to approach something that is likely true based on probability


## New
    - Added column classifiers (Date, Time, PerUnitCost, TotalCost, etc. )
    - Added Column "AveCost" to track average item cost

## Changes 
    - Changed date format to MM-DD-YYYY
    - Removal of whitespace (cosmetic)

## Fixes
    - Fixed misalignment in Column "TotalCost" where some rows did not match with correct dates
    - Fixed SUM to run over entire column instead of partial
