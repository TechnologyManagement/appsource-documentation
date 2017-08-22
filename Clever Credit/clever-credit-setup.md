# Clever Credit Setup
The setup page is accessed through the "Setup & Extensions" menu. Two new "Assisted Setup" records are added to the system by the Clever Credit app.
- Setup Clever Credit
- Setup a new credit controller
## Setup Clever Credit
This page steps you through the setup of the Clever Credit app. Default data will have been created when the app was installed, but this page will help you alter it as necessary.

### Credit Hold Documents
This setting determines whether you want Clever Credit to place sales documents on "Credt Hold" if a customer has an overdue balance or is over their credit limit. Credit held documents are visible on the [Credit Held](.\credit-held) page. If you select 'Yes' you will be prompted to select which types of sales documents you want to apply the credit check to. By default the checks are applied to invoices and order.

### Default Credit Controller
Choose the [credit controller](.\credit-controllers) who is designated as the default. This controller will be able to see all customer accounts on the [Clever Credit](.\clever-credit) page. A credit controller will have been created and assigned as the default controller when the app was installed.

### Status Codes
Clever Credit allows you to set status codes against customer ledger entries. Track whether the customer has promised payment, is querying the invoice or whether you have left a message with them for a future call. The codes created on this page will be available for credit controllers to assign to ledger entries.

### Ageing Bands
This step determines the columns that will be visible on the [Clever Credit](.\clever-credit) page. The Period Start and Period End calculations will determine the invoices that fall into each band (according to their Due Date). Some default bands will have been created when the app was installed, but they can be changed here.

### Finish
Click 'Finish' to confirm your changes. Otherwise, close the setup page without clicking 'Finish' to discard any changes that you have made.

## Setup a new Credit Controller
This page steps you through the creation of a new credit controller.

### User
Select the Dynamics 365 user that you are designating as a credit controller. The system will attempt to populate the Code and Name fields and they can be corrected before proceeding if necessary.

### Release
Decide whether the user should be allowed to release documents that have been [credit held](.\credit-held). If so, decide the limit that they should be able to release. Controllers will be unable to release documents that are for a value greater than their limit. Otherwise, check the "Credit Held Rel. Unlimited" box to indicate that the controller can release sales documents of any value.

### Customers
Clever Credit allows you to assign customer accounts to specific [credit controllers](.\credit-controllers). Only these customers will appear on the [Clever Credit](.\clever-credit) page for this credit controller. The default credit controller will always be able to view all customers.

### Finish
Click 'Finish' to confirm your changes. Otherwise, close the setup page without clicking 'Finish' to discard any changes that you have made.