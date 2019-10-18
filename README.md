# Data-Doctors

The datadoctor is built on the tray.io middleware platform using typeform. 

Currently, the datadoctor:
- Notifies user of missing required/recommended columns
- Cleans headers (newlines, double column, special characters, etc.)
- Removes blanks from first row
- Checks for valid emails updates if not
- Formats date fields
- Formats phone fields
- Produces email with cleaned file, errors and updates performed

When a CSV is submitted to the typeform, found [here](https://zd843515.typeform.com/to/uZwXq5) the tray workflow is trigger. Once the workflow has ran the user will receive an email with the identified errors, a list of updates made, and the cleaned sheet. Like so, 




In a futurestate, the datadoctor will:
- Seemlessly fit into product and utilize the existing importer and duplication management functionality
- Ensure proper number, single-line-text and paragraph custom field formatting 
- Produce row number specific error messages
- Handle zips and multi-object CSVs



