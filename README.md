# Nigeria-Railway-Data-Cleaning-Project
## Problem Statement
The Nigerian Railway maintenance dataset from Kaggle was cluttered with inconsistent formatting, missing values, and various data quality issues that made it unsuitable for meaningful analysis. This project focused on cleaning and standardizing the dataset to ensure data integrity and usability for future reporting and insights.

### Dataset & Tools
Dataset: Nigerian Railway Maintenance Data (https://docs.google.com/spreadsheets/d/1LxQ_HrQHeTLoXjCze0R_rnFSPHm7NZ8Q/edit?usp=drive_link&ouid=114765443762891391545&rtpof=true&sd=true)

### Tools Used: Microsoft Excel
### Key Columns: Date, Make/Model, Item Description, Assigned To, Service KM, Workshop Name, Invoice No., Amount (NGN)

#### Cleaning Process Overview
 ##### Column: Date
Converted the format from General to Short Date (MM/DD/YY) for consistency.
Identified and corrected two inconsistent entries (e.g., 02/08/17/ ➝ 02/08/17) using Find and Replace.

##### Column: Make / Model
Applied the PROPER() function to capitalize each word properly.
Fixed spelling errors for accuracy.
Removed only closing brackets from entries like Toyota (Prado) ➝ Toyota Prado for clean formatting.

##### Column: Item Description
Applied proper case formatting across all entries.
Corrected spelling mistakes using Find and Replace.
Manually reviewed all entries to ensure proper spelling and formatting.

##### Column: Assigned To
Fixed grammatical inconsistencies and standardized names.
Removed duplicates and ensured uniform formatting.

##### Column: Service KM
Replaced all blanks with "N/A" to preserve structure and indicate missing data explicitly.

##### Column: Workshop Name
Merged duplicate entries with consistent formatting.
Corrected spelling mistakes and ensured uniformity.

##### Column: Invoice No.
Replaced missing values with "N/A" for clarity.
Converted data type to Number and used the TEXT() function for consistent formatting.

##### Column: Amount (NGN)
Changed data type to Currency, applying the Naira (₦) symbol using Excel’s currency format.

##### Dataset Standardization & Final Adjustments
Structured the dataset as an Excel Table to enable easy filtering, sorting, and referencing.
Standardized column headers for naming consistency (e.g., capitalization).
Verified and reassigned correct data types for each column (dates, text, numbers, currency).

##### Outcome & Key Impact
Cleaned and standardized all 9 core columns.
Resolved 100% of formatting issues and clearly flagged missing data with "N/A".
Dataset is now fully analysis-ready, enabling clearer visualization, trend analysis, and reporting for transportation performance and service budgeting.

![Cleaned Excel Table](https://github.com/MISYUSENI18/Nigeria-Railway-Data-Cleaning-Project/blob/main/Nigeria%20railway%20data%20clean.jpg?raw=true)

