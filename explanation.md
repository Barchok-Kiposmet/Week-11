# Creation of folders

## Requests Folder

To accommodate the spreadsheet containing the data to process.

## Open Tickets

To accommodate the processed spreadsheets from Zoho

* There are 3 types of xaml files used to create automation, these are as follows;

# Main.xaml

This is the main workflow which will invoke other workflows and orchestrate the automation.

# ReadRequest.xaml

This picks the Request Excel file from the folder we created, read the ticket data, and incorporate them in variables for the next workflow to process.

# SaaSAutomation.xaml

SaaS - Software as a Service
Zoho application is used here to obtained/read data from Request file to create support ticket/job card. This was embended in the main file and not separate.

NB: Enhanced the "attended automation" type of RPA by including Stop Automation using hotkey triggers. ie. Ctl + k