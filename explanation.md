
## Folder Creation
1. Requests folder which stores the Requests spreadsheet that contains the data to be processed.

2. Processed folder which stores the processed spreadsheet that contains the processed data.

## Automation Files
There are three files used to creation the workflow process automation which are:

1. Main.xaml
This file contains the main workflow which will when run invokes all other workflows and orchestrates the automation.

2. ReadRequest.xaml
This file contains the workflow for retrieving the Requests spreadsheet from the Requests folder, read the file data, and put them in variables for processing by the next workflow.

3. SaaSAutomation.xaml
Zoho Desk a SaaS application is used to read data from the Requests spreadsheet and to automatically create a support ticket containing this data.

## Hotkey Triggers
Since this is an attended automation, it was further enhanced by the use of a hotkey trigger (Pressing ALT+S keys on the keyboard) to stop the automation.
