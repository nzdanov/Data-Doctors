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
<br/>
<img width="593" alt="Screen Shot 2019-10-18 at 12 49 44 PM" src="https://user-images.githubusercontent.com/56731948/67123671-d52e7400-f1a5-11e9-9aab-68b95f2e0b58.png">
<br/>
is submitted in the typeform, found [here](https://zd843515.typeform.com/to/uZwXq5) the tray workflow is trigger. Once the workflow has run...<br/>
![ezgif com-video-to-gif](https://user-images.githubusercontent.com/56731948/67123425-21c57f80-f1a5-11e9-9d1e-b2bbacfe750c.gif)<br/>


the user will receive an email with the identified errors, a list of updates made, and the cleaned sheet. Like so, <br/>
&nbsp;
<img width="863" alt="Screen Shot 2019-10-18 at 12 20 21 PM" src="https://user-images.githubusercontent.com/56731948/67123465-3dc92100-f1a5-11e9-8646-62886371e1b5.png">
&nbsp;<br/>
<img width="381" alt="Screen Shot 2019-10-18 at 12 20 53 PM" src="https://user-images.githubusercontent.com/56731948/67123084-276e9580-f1a4-11e9-9725-e5a980f1bb59.png"><br/>


In a futurestate, the datadoctor will:
- Seemlessly fit into product and utilize the existing importer and duplication management functionality
- Ensure proper number, single-line-text and paragraph custom field formatting 
- Produce row number specific error messages
- Handle zips and multi-object CSVs



