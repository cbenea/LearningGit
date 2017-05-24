
# Create customer and external user in T24
## Quick Start Guide 

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/xyz2.png)



##	Overview

	This is a guide on how to:
1.	Create a customer record in T24 environment 
2.	Open current and savings accounts
3.	Create and authorize an account transaction through FT (Funds Transfer) application 
4.	Accustom with Teller module 
5.	Create External User to provide customer access on TCMB (Temenos Connect Mobile Banking) and TCIB (Temenos Connect Internet Banking) applications 
 

##	Create a customer
 Purpose of customer record: 
 	Customer record holds all the basic information about a Customer. 
 	Ideally only one Customer record should exist for each Customer.  This can be created whenever a name, address and other such essential information is obtained and is not dependent on the existence of an account. 
 	In T24, creating a Customer record need not wait till we are ready to open an account or till we propose to have a business transaction. 
 	For example, a Customer record can be set up even when a Bank is considering having any relationship with. Later, when it decides to enter into any contractual obligation, like Foreign exchange or Money Market dealings, it can use the Customer record already created. If at any later stage, the Bank proposed to open a current account, it need not create another record for the Customer. It can as well use information already stored.
 	Once a customer record is authorised, it is not possible to reverse the record. We can however amend any details as and when needed

 	Login

Insert your **Username** and **Password** for T24 sign in


 
 	Fill in basic customer details 

Under User Menu click Customer, then Individual Customer

 ![alt text](https://github.com/cbenea/LearningGit/blob/master/image/3.png)
 

	Following screen is open and a Customer Id (sequential number) is automatically generated (e. g. 190359):

 
 


	






 
	

 

Input the customer’s personal details:








 	Physical Address:
 


 


 	ID Doc:
 

 	Relation:
 

 	Further Details:
 

 
 	Financial Details:
 

 	Residential Details:
 

 	Communication Details:
 

 	KYC (Know Your Customer):
	 
 

 	Other Details:
 

 	Reporting Details: 
 

	After filling one of the tag-screens, validate button can be used to check the information’s accuracy:
 

	And then commit a deal (submitting for authorization): 
 

 
	After this step, a notification regarding client’s documents will pop-up:
 


	Submit again. Transaction is complete:
 
 

2.1	Authorize and search created customer

	A second user (supervisor) with additional rights has to authorize this transaction. Until then, the newly created customer can be checked into the unauthorized files list (List Unauth File).
 

 

Authorize created customer:

 	Log in with different user (with additional rights) and password:
 

 	Under User Menu click Customer, then Authorise/Delete Customer
 
 	Search option – use Selection Screen button: 
 
 
 	Search customer by ID, name, short name, mnemonic etc:
 
 
 	And authorize it through commit button.  
 
 	Original details screen will pop-up in order to check the input information. 
 
 
 	Authorize the deal:
 
 
 	Transaction is complete:
 


3	Open accounts 
3.1	Open a current account
	
	Under User Menu click Account, then Open Current Account
 


 	An account number is automatically generated:
 
 
 	Complete details and commit:
 
 	Transaction is complete:
 

3.1.1	Authorize and search created account

	A second user (supervisor) with additional rights has to authorize this transaction. Until then, the newly created customer can be checked into the unauthorized files list (List Unauth File).
 

 
 	Click Account Id and then the key button:
 
 
 	And authorize the record:
 
 	Now search created account:

•	Under User Menu click Account, then Open Current Account. 
•	Under MoreActions scroll down for List Live File, click and press Go:   

•	This action will load all accounts database results.

 
 
 	Go to Selection Screen button  

 	Input the account number and click Find:
 
 	Result:
 

3.2	Open a savings account

	Under User Menu click Account, then Open Savings Account

 
 
	An account number is automatically generated:
 
	Complete details and commit:
 
	Transaction is complete:
 

3.2.1	Authorize and search created account

	A second user (supervisor) with additional rights has to authorize this transaction. Until then, the newly created account can be checked into the unauthorized files list (List Unauth File).
 

 
 
	And authorize the record:
 






	Or search the unauthorized account by its number. Go to Selection Screen button  
	Insert account number and click Find.
 
	And authorize:
 
	
 
	New screen appears. Click Authorise a deal
 
	Transaction is complete:
 

	Now search created account:
 	Under User Menu click Account, then Open Savings Account. 
 	Under MoreActions scroll down for List Live File, click it and press Go:   
		
		This action will load all accounts database results.

 
 
 	Go to Selection Screen button  
 	Input the account number and click Find:

 
	Result:
 
 
4	Account transaction through Funds Transfer
	
	Funds Transfer module (FT) is the part of T24 used to effect payments from one account to another either internally or externally and is related to Customer and Account applications.
	Under User Menu click Payment Services, then Funds Transfer and Account Transfer
 
	From new screen, choose Transfer between Accounts
 
 
 
 

4.1	Authorize transaction

	Log in with a new user with special approver rights:
 
	Under User Menu click Payment Services, then Funds Transfer and Authorise/ Delete FT transactions
 

 
 
	Transaction is complete:
 
 
5	Cash deposit through Teller

 
	Under User Menu click Retail Operations, then Account Transactions – Teller – Teller Operations – Teller Cash – Cash deposit Local

 
 

	Commit the deal  
 
	Transaction is complete
 
5.1	Create a Till

 


 

 	Choose from dropdown list
 

 
 
 	After completing the necessary inputs, commit the record by selecting the key at the top of the screen.
 
 	And then:
 
 	Transaction is completed.
 
5.1.1	Authorize new till

 	Log in with a new user with special approver rights:
 
 
 	Under User Menu click Retail Operations, then Account Transactions – Teller – Head Teller Operations – Till Administration – Authorise / Delete Till Closure

 

 

 

 	Transaction is complete.
 
6	Create an External User

	The user creation process involves the following steps:
1. Creating Online Banking Arrangement
2. Creating Group Permission using Manage Permissions option
3. Creating External User (For example, creation of RETAIL1)
4. Authorising the Channel User
5. Manage External User

6.1	Create Online Banking Arrangement

 
 
 	Click Create Online Banking Arrangement option under the Admin Menu of the T24 Model Bank
 

 	Under Product Groups select Temenos Connect Retail
Both the TCIB and TCMB products are arranged under the Product Groups and Products.
 
 

 	Input Customer ID and click Validate a Deal
 
On validating the above page, a newly created Arrangement is displayed with options for further configuration. 
















 

Authorize the deal   

 
Transaction is complete:
 

6.2	Create Group Permission 

The creation of group permission enables the user to add the customer accounts related to the user role (Clerk).
Under Admin Menu click External User Administration, then Create/ Manage Online Arrangement, then Manage Permissions

 
 
Create new Permission screen is open. Fields Customer must be populated with Customer ID and Group Name with TC Home name must be populated. Click Find
 

Click the displayed hyperlink

 

 
In the following screen, input Description, select Type as Individual scroll down and choose the required Product 
 
Add all required products and commit 
 

 


6.3	Create External User

Under Admin Menu click External User Administration, then Create/ Manage Online Banking Access – Create External User
 
 

 	The following screen is displayed for you to enter the External User ID (that is RETAIL1) in 
the External user creation field.
 
Transaction is complete
 
 
6.3.1	Authorize Channel User

A second user (supervisor) with additional rights has to authorize this transaction.  
 	Under Admin Menu, click External User Administration, then Authorise Online Banking Access and Authorise Channel User
 

 
Transaction is complete
 

 
 	Status field in the EB.EXTERNAL.USER of the user role Initiated. Change into Active
 
Press commit. There is no need for authorization at this step. External user creation is completed
 
