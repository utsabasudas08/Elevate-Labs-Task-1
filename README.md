# Elevate-Labs-Task-1
Intern: Utsa Basu Das

1. Handling Missing Values
Identified null values across all columns using .isnull().

Handled missing data by either dropping rows with critical missing information or filling numeric gaps with the median/mean to maintain dataset integrity.

2. Duplicate Removal
Detected and removed duplicate records using .drop_duplicates() to prevent skewed analysis and ensure each transaction is unique.

3. Text Standardization
Cleaned categorical values like 'Country' by removing leading/trailing whitespaces.

Standardized text casing to ensure consistency across the dataset.

4. Date Formatting
Converted the 'OrderDate' column into a standardized datetime object.

Reformatted all dates to a uniform dd-mm-yyyy type to ensure chronological consistency.

5. Header Renaming & Data Types
Renamed column headers to lowercase and replaced spaces with underscores for better coding efficiency.

Verified and corrected data types (e.g., ensuring 'Ordernumber' is an integer and 'orderdate' is a datetime).
