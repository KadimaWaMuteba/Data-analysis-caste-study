# All documentation of the cleaning process will be here
The complete list of things checked : 
- Business Logic (Check to see if the data makes sense given my understanding of the business) 
- Adapt the name of the columns by naming them in a meaningful way
- Check that numeric, date, and string data are typecast correctly
- Remove Null or Empty values
- Correct mispelled words and mistyped numeric values
- Check for incorrect values
- Removal of extra spaces and characters using the TRIM function
- Remove duplicates in spreadsheets using the Remove Duplicates function or DISTINCT in SQL
- Messy (inconsistent) strings 
- Messy (inconsistent) date formats throughout the dataset
- Truncated data : missing data that needs correction (Not applied)
- Multiple Umputation of xxxx variable(Not applied)
Used to fill the missing values to approach something that is likely true based on probability, NA

## New
    - Added column classifiers (Date, Time, PerUnitCost, TotalCost, etc. )
    - Added Column "AveCost" to track average item cost

## Changes
    - Removal of columns (trip_id, bike_id)
    - Changed start_time, end_time format to YMD-HMS
    - Changed tripduration format to Integer 
    - Changed the columns name start_time to started_at
    - Changed the columns end_time to ended_at
    - changed the column tripduration to trip_duration
    - changed the column from_station_id to start_station_at
    - Changed the column from_station_name to start_station_name 
    - Changed the column to_station_id to end_station_id
    - Changed the column to_station_name to end_station_name 
    - Changed the column usertype to user_type
    - Changed the column birthyear to birth_year
    - Removal of 18023 lines where birthyear was missing 

## Fixes
    - Fixed misalignment in Column "TotalCost" where some rows did not match with correct dates
    - Fixed SUM to run over entire column instead of partial
