Prepare data for import
==========

On completing the abovementioned steps, you will be able to map plan what existing staff data point should get saved into which CiviHR field. 


Download ([https://docs.google.com/spreadsheets/d/1Jo_LrtFerb1uS7ioBWbmuXugA5V_r3R58kKorVW9ffU/edit#gid=1808962477) this file containing the full list of importable CiviHR fields and edit it as required. It may be more convenient for you to use it for data collation. At the time of import save staff contact, staff job contract and staff job role data in three separate CSV files.


-   In CiviHR, data is imported in several passes. For instance, you will first import employee contact and demographic data in the first pass, followed by job contract data, and job role data. CiviHR needs to identify accurately the staff profile where data should be added in every successive pass. You can use unique email addresses for each staff for this purpose. The External ID field can also be used to hold unique values such as an employee number. 
-   Do not delete any columns marked ‘mandatory’. The import will not go through unless these columns contain valid data for each staff member. You can delete any non-mandatory columns that you do not want to use. 
-   For fields that have dropdown options, it is important to use the same spelling throughout your import file. For example, if you want to import the individual prefix ‘Ms.’, ensure that you do not have variation like ‘Ms’,‘ms’ or ’Ms ‘ in your CSV file. Also ensure that your CiviHR is configured to list the exact same option (see Configuring dropdown options) - in this example ‘Ms.’ in the Individual Prefixes dropdown.   
-   Ensure that country, states/province, currency names are expressed in the same way as they are in CiviHR. For example, use 'United Kingdom', not 'Britain'. 
-   Use one row for each staff member. If you want to import more than one email address, phone or address for your staff, insert additional columns in the import sheet. If you are importing multiple email addresses, phone numbers or addresses, the first of each will be set as the primary email, phone or address. 
-   If you have added custom fields to the CiviHR staff profile, add a separate column for each such field.
