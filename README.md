# npd-well-headers-for-ic
Reformat NPD Well Headers for IC

This script reformats NPD Well Headers for IC so that column names match up perfectly first time, allowing you to prepares well header files for nearly 1900 exploration and 5000 development wells in seconds. It automatically creates separate URL/Reference files for IC with links to NPD FactPages, FactMaps and Press Releases. It also advises which Well Attibutes you need to manually create in IC.

<br>Imports NPD well headers from:</b>
NPD Factpages > Wellbore > Table View > Exploration > All - Long List (permanent link)
NPD Factpages > Wellbore > Table View > Development > All - Long List. (permanent link)

<b>Run the script as it is, or edit options to:</b>
A. Rename dozens of header fields to match IC defaults, e.g. 'Entered date' to 'SPUD date'.
B. Truncate well list based on any field, e.g. 'Location: Barent's Sea'.
C. Add/remove spaces or characters in well names.
D. Concatenate cells to create 'Grid system' in IC format, e.g. "ED50 / UTM Zone 31N".
E. Concatenate Status & Content to match IC's Well Symbols dictionary, e.g. "P & A Gas/Condensate".
F. Add and populate new columns, e.g. 'Country: NORWAY'.
G. Copy data from one column to another, e.g. 'NPDID wellbore' to 'UWI Number'.
H. Re-order all columns, and delete unwanted columns.
I. Convert three URL columns into rows to match format required for IC References.
J. Create separate well header files for exploration and development wells, or combine into one.
Outputs four files for import to IC:

IC_explo_references.csv<br>
IC_dev_references.csv
IC_wellbore_exploration.CSV
IC_wellbore_development.CSV
