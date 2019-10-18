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

When a CSV, suchs as, 
<img width="595" alt="Screen Shot 2019-10-18 at 12 13 59 PM" src="https://user-images.githubusercontent.com/56731948/67123089-29385900-f1a4-11e9-81f8-a0bc658ba7ad.png">



is submitted to the typeform, found [here](https://zd843515.typeform.com/to/uZwXq5) the tray workflow is trigger. Once the workflow has ran the user will receive an email with the identified errors, a list of updates made, and the cleaned sheet. Like so, 

<img width="381" alt="Screen Shot 2019-10-18 at 12 20 53 PM" src="https://user-images.githubusercontent.com/56731948/67123084-276e9580-f1a4-11e9-9725-e5a980f1bb59.png">



In a futurestate, the datadoctor will:
- Seemlessly fit into product and utilize the existing importer and duplication management functionality
- Ensure proper number, single-line-text and paragraph custom field formatting 
- Produce row number specific error messages
- Handle zips and multi-object CSVs



