Run a test import
==========

Import contact information, demographics and bank data
------------------------

-   Navigate to the Import Contacts page as shown:

![image](../img/import-contacts.PNG)

-   Select your import CSV file containing contact, demographic and bank data. Confirm whether the first row of the file contains column headers. Select the date format used in your CSV file. Click Continue. 

![image](../img/data-source.PNG)

-   Match fields from your CSV file to appropriate CiviHR fields. 

![image](../img/match-fields.PNG)

The first time you import from a particular file, it's a good idea to check the box to "Save this field mapping" at the bottom of this page before continuing. The saved mapping can then be easily reused the next time similar data is imported, by requesting that it be loaded at this step. Click Continue. 


-   Preview: This screen previews the results of importing your data, reports the number of rows to be imported, and allows you to double check your field matches. If some of the rows in your spreadsheet contain data that doesn't match CiviHR’s requirements you'll see an error message. Click the Download Errors link and review the errors reported in the downloaded file, so you can fix them before doing the import. Once you have no errors reported on the Preview screen, click Continue to start the import

![image](../img/preview.PNG)

-   Summary: This screen shows you how many contacts were successfully imported. 

-   Check to make sure that your import has worked as expected. Search for the contacts that you just imported and examine their staff profiles. 

Import job contract information
------------------------

-   Navigate to the Import Job Contracts page as shown:

![image](../img/import.PNG)

-   All job contracts in your import CSV file should contain one of the following to tell CiviHR which staff profile to add a particular contract to: a unique Email address, External Identifier or CiviHR ID. 

-   Repeat the import process with the job contracts CSV file. 

Import job role 
------------------------

You will need to tell CiviHR which job roles should be linked to which job contracts. For this, you must export out the Job Contract ID for all staff members and copy that into the Job Roles CSV file. 

-   Run a search for your staff members using Quick or Advanced Search.

-   Select all staff and pick the Export Contacts option from the Actions dropdown

![image](../img/advanced-search.PNG)

Pick the Select fields for export option and click Continue

![image](../img/export.PNG)

-   Export the following fields:

![image](../img/select-export-fields.PNG)

-   Open the exported CSV file and copy the Contract ID to your Job Roles CSV. 

-   Navigate to the Import Job Roles page as shown:

![image](../img/import-job.PNG)

-   Repeat the import process with the job roles CSV file.

Step 5: Run the full import
------------------------

If you are happy with how your test data was mapped and imported, import your full data using the same process described above.
