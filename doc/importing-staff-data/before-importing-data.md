Before importing data 
==========

**Step 1: Get to know CiviHR fields**  
---------------

CiviHR has a large number of pre-built fields to store information about your staff. It is helpful to manually create a couple of test staff in your CiviHR installation and fill each tab of their staff profile to be aware of all fields that are available to store data. 

**Step 2: Review existing data**
-------------

Most database applications such as OpenOffice.org Calc, Google Spreadsheets allow exporting data as spreadsheets or CSV files. Look through your staff data in these spreadsheets and mark what you would like to save in CiviHR. 

Try to make as much use of pre-built fields because many of them are linked to additional features. For example, CiviHR has a pre-built field for contract start dates which is linked to headcount and key date reports. If this field is overlooked and a new custom field is created to hold the contract start date, you will not be able to get the most out of the reports feature.

If you have data that cannot be saved in any pre-built CiviHR field, you may need to add custom data fields (see creating custom data fields).

**Step 3: Prepare data for import**
-------------

On completing the abovementioned steps, you will be able to map plan what existing staff data point should get saved into which CiviHR field. 

Download (https://docs.google.com/spreadsheets/d/1Jo_LrtFerb1uS7ioBWbmuXugA5V_r3R58kKorVW9ffU/edit?usp=sharing) this file containing the full list of importable CiviHR fields and edit it as required. It may be more convenient for you to use it for data collation. At the time of import save staff contact, staff job contract and staff job role data in three separate CSV files.

-   In CiviHR, data is imported in several passes as described next. For instance, you will first import employee contact and demographic data in the first pass, followed by job contract data, and job role data. You need to help CiviHR to identify the staff members in whose profiles the additional data should be added. You can use unique email addresses or employee ID numbers for each staff member for this purpose. 
-   Do not delete any columns marked ‘mandatory’. The import will not go through unless these columns contain valid data for each staff member. You can delete any non-mandatory columns that you do not want to use. 
-   For fields that have dropdown options, it is important to use the same spelling throughout your import file. For example, if you want to import the individual prefix ‘Ms.’, ensure that you do not have variation like ‘Ms’,‘ms’ or ’Ms ‘ in your CSV file. Also ensure that your CiviHR is configured to list the exact same option (see Configuring dropdown options) - in this example ‘Ms.’ in the Individual Prefixes dropdown.   
-   Ensure that country, states/province, currency names are expressed in the same way as they are in CiviHR. For example, use 'United Kingdom', not 'Britain'. 
-   Use one row for each staff member. If you want to import more than one email address, phone or address for your staff, insert additional columns in the import sheet. If you are importing multiple email addresses, phone numbers or addresses, the first of each will be set as the primary email, phone or address. 
-   If you have added custom fields to the CiviHR staff profile, add a separate column for each such field.
-   It is strongly recommended that a small batch of data should be imported first as a test. Search and review this test data once it is imported. If you are happy with the result, proceed to import the rest of your data.
