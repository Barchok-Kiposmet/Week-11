# Creation of folders

## Requests Folder
To accommodate the spreadsheet containing the data to process.

## Open Tickets Folder
To accommodate the processed spreadsheets from Zoho with an updated date and time

## Type of XML files used:

### Main.xaml

This is the main workflow which will invoke other workflows and orchestrate the automation.

### ReadRequest.xaml

This picks the Request Excel file from the folder we created, read the ticket data, and incorporate them in variables for the next workflow to process.

### SaaSAutomation.xaml (embeded in the main and not separate)
SaaS - Software as a Service
Zoho application is used here to obtained/read data from Request file to create support ticket/job card. 

NB: Enhanced the "attended automation" type of RPA by including Stop Automation using hotkey triggers. ie. Ctl + k
