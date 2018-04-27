# `UX ASSESSMENT:` DASHBOARD FOR MERCHANT

* This assessment requires [Sketch](https://www.sketchapp.com) and [Zeplin](https://www.zeplin.io).
* Deadline: 
	* 3 days upon receiving this assessment. (let us know if you require an extension)

## Project Brief

To enable PrimeKeeper’s merchants to easily check the details of PrimePay transactions carried out at their business premises and the `settlement amount` due to them from PrimeKeeper.

>*Settlement Amount – PrimeKeeper collects all payments made via the APP. PrimeKeeper will then deduct the transaction fees and bank in the remaining amount to each merchant.*

This Dashboard contains many different aspects and features but for the purpose of this assessment, we only require that you design this single page called `Transactions`.

All the following is to be visible on a single screen for easy-viewing as merchants don’t like too many clicks.




## Project 1: Designing `Transactions` Page

Transactions are to be updated in real-time. The transaction listing is to display transactions for the past 30 days from the current date.

##### Show summaries for:

1.	`Total Transactions` - the total number of transactions carried out, based on User’s search filter selections.

2.	`Total Sales` - the total sales amount of transactions carried out, based on User’s search filter selections.

3.	`Receipts from PrimePay` - The total payments made using PrimePay, including `PrimeVoucher` redemptions, based on the User’s search filter selections.

>*PrimeVouchers are RM20 vouchers given by PrimeKeeper to our newly registered Users. Users can use these vouchers at any of PrimeKeeper Merchant’s premises.*

4.	`Total Settlement Amount` – The total settlement amount from PrimeKeeper, based on User’s search filter selections.

>*Important Note:* The figures should change based on the search results.



#### Columns to display:

##### The Transactions table will display the following columns:

Column Name|Description
--- | ---
Date/Time|The date and time the transaction was carried out. `YYYY-MM-DD HH:MM:SS`
QR Code Name/Terminal Name|The QR Code that was scanned or the Terminal that was used for the transaction.
Cashier Code|The Cashier Code of the QR Code that was scanned for the transaction.
Transaction Type|Indicates if the transaction was carried out using a QR Code scan or a POS Terminal.
Status|The status of the transaction i.e. if it was a successful transaction or a failed transaction.
Bill Amount|The amount billed for this transaction.
Nett Amount|The Nett amount that PrimeKeeper will pay the User in the Settlement for this transaction i.e. after deducting PrimeKeeper’s Merchant Transaction Charges.
Details|Click this link to get a detailed view of the transaction.
 
 
##### Include ability for User to view additional columns, if required: 
 
Column Name|Description
--- | ---
Payment Method|Displays the payment method used for the transaction i.e. e-Money/Bank with PrimeVoucher or only PrimeVoucher.
PrimeVoucher Amount|Displays the amount paid using PrimeVoucher for this transaction.
e-Money/Bank Amount|Displays the amount paid using e-Money or Bank Account for this transaction.
Transaction Charge|PrimeKeeper’s transaction charge that will be deducted for this transaction prior to settlement. The transaction charge displayed includes 6% GST.
GST|If the ‘Transaction Charge’ column is selected, then this column will be displayed as well. Displays the GST amount charged on PrimeKeeper’s Transaction Charge.
 
 
##### Include ability for User to see a detailed view of each transaction:
 
Column Name|Description
--- | ---
Transaction ID|The system-generated transaction ID assigned to this transaction. E.g. `YYMMDD0000001` (sequential).
Transaction Type|Indicates if the transaction was carried out using a QR Code scan or a POS Terminal.
Payment Reference|The system-generated payment reference assigned to this transaction.
Payment Method|Displays the payment method used for the transaction i.e. `e-Money/Bank with PrimeVoucher` or only `PrimeVoucher`.

Payment Details| Description
--- | ---
Bill Amount|The amount billed for this transaction.
PrimeVoucher Amount	| The portion of the billed amount that was paid using a PrimeVoucher.
e-Money/Bank Amount|The portion of the billed amount that was paid using an e-Money or Bank Account.
Transaction Charge|PrimeKeeper’s transaction charge for this transaction. The transaction charge displayed includes 6% GST.
GST|Displays the GST amount charged on PrimeKeeper’s Transaction Charge. The Transaction Charge displayed includes the 6% GST.
Total Nett Amount|The Nett amount that PrimeKeeper will pay you in the Settlement for this transaction i.e. after deducting PrimeKeeper’s Merchant Transaction Charges.
 
 
 
#### Search Filters
 
##### Possible search filters are:
1. `Specific Filters` –display transactions by `Transaction ID` (one at a time), `Cashier Code` (multi- select), `QR Code Name` (multi- select), `Outlet` (multi- select) or `Terminal Name` (multi- select). Click Search.  

>*Note:* Each QR Code is tied to a specific Cashier Code and Outlet. Consider how you want to make this search simpler. 

2. `Status` – filter by successful or unsuccessful.

3. `Date range` – Click the `calendar` icon to bring up the calendar. Filter transactions based on a single date or a specific date range. Pre-defined filters for quick search: `Today`, `Yesterday`, `Last 7 Days`, `Last 30 Days`, `This Month`, `Last Month` or `All Transactions`.



#### View Transaction Charge Rate

To enable Merchant to view the current transaction charge rate charged by PrimeKeeper. Rate to be dynamic as different merchants can have different rates. 



#### Downloading a Transaction Report

Ability to download a report based on specific date range. 



## Final Output

Once you are done with your proposed design, you are required to export your design using Sketch to Zeplin for review.

#### Step by step guide:

1. Download and install [Zeplin](https://www.zeplin.io) and [Zeplin plugin](https://github.com/zeplin/zeplin-sketch-plugin/archive/v1.6.4.zip).
2. Create an account with Zeplin.
3. Create new project with proper configuration based on your final output.
4. Invite `claytonchew_primekeeper` and `sdcruz` to the project.
5. Export the artboard(s) of your design in Sketch to Zeplin.