
# Create customer and external user in T24
## Quick Start Guide 

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/xyz2.png)



#### This is a guide on how to: ####
+	[Create a customer record in T24 environment](#create-a-customer) 
+	[Open current and savings accounts](#open-accounts)
+	[Create and authorize an account transaction through FT (Funds Transfer) application](#account-transaction-through-funds-transfer) 
+	[Accustom with Teller module](#cash-deposit-through-teller) 
+	[Create External User to provide customer access on TCMB (Temenos Connect Mobile Banking) and TCIB (Temenos Connect Internet Banking) applications](#create-an-external-user) 





### Create a customer
#### Purpose of customer record: 
 Customer record holds all the basic information about a Customer. 
 	Ideally only one Customer record should exist for each Customer.  This can be created whenever a name, address and other such essential information is obtained and is not dependent on the existence of an account. 
 	In T24, creating a Customer record need not wait till we are ready to open an account or till we propose to have a business transaction. 
 	For example, a Customer record can be set up even when a Bank is considering having any relationship with. Later, when it decides to enter into any contractual obligation, like Foreign exchange or Money Market dealings, it can use the Customer record already created. If at any later stage, the Bank proposed to open a current account, it need not create another record for the Customer. It can as well use information already stored.
 	Once a customer record is authorised, it is not possible to reverse the record. We can however amend any details as and when needed

 #### Login

Insert your **Username** and **Password** for T24 sign in

<img src="https://github.com/cbenea/LearningGit/blob/master/image/2.png" width="300" height="150">
 
#### Fill in basic customer details 

Under **User Menu** click **Customer**, then **Individual Customer**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/3.png" width="380" height="650">
 

Following screen is open and a **Customer Id** (sequential number) is automatically generated (e. g. 190359):

 


 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/4.png" width="550" height="500">


`All available buttons, tags, signs or icons have a help information for better guidance when passing mouse over an element.
Mandatory fields are marked with asterisk. Some fields are expandable and some have drop down option so the value can be chosen from a pre-defined list`


![alt text](https://github.com/cbenea/LearningGit/blob/master/image/5.png)
	






 
	

 

Input the customer’s personal details:

`Details in Customer record are descriptive in nature and not financial. For example, it holds the occupation, residence and contact details of a Customer. It will not hold the account numbers or balances in those accounts of a Customer.`






 	Physical Address:
 


 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/6.png" width="700" height="500">

 	ID Doc:
	
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/7.png) 

 	Relation:

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/8.png)

 	
	Further Details:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/9.png" width="600" height="350">
 
 	
	Financial Details:

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/10.png)

 	
	Residential Details:
	
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/11.png)

 	
	Communication Details:
	
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/12.png)

 	
	KYC (Know Your Customer):
	 
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/13.png) 

 	
	Other Details:
 
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/14.png) 
 	
	
	Reporting Details: 

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/15.png)  

	
After filling one of the tag-screens, **validate** button can be used to check the information’s accuracy:
 
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/16.png) 
	
	
And then **commit** a deal (submitting for authorization): 
 
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/17.png) 
 
	
	After this step, a notification regarding client’s documents will pop-up:
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/18.png" width="700" height="450">

	
Submit again. Transaction is complete:
 
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/19.png" width="300" height="100"> 


## Authorize and search created customer 
	


A second user (supervisor) with additional rights has to authorize this transaction. Until then, the newly created customer can be checked into the unauthorized files list (**List Unauth File**).
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/20.png" width="650" height="400">
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/21.png" width="500" height="440">


## Authorize created customer:

 	
Log in with different **user** (with additional rights) and **password**:
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/22.png" width="350" height="180">

 
Under **User Menu** click **Customer**, then **Authorise/Delete Customer**
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/23.png" width="280" height="380">
 
 	
Search option – use **Selection Screen** button: 
 
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/24.png)
 
 	
Search customer by ID, name, short name, mnemonic etc:
 
![alt text](https://github.com/cbenea/LearningGit/blob/master/image/25.png)
 

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/26.png)
 
 
And authorize it through **commit** button 
 
 	
Original details screen will pop-up in order to check the input information:


<img src="https://github.com/cbenea/LearningGit/blob/master/image/28.png" width="600" height="530">
 

Authorize the deal:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/29.png" width="600" height="530"> 
 

Transaction is complete:
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/30.png" width="400" height="230">



### Open accounts

### Open a current account ###
	
	


Under **User Menu** click **Account**, then **Open Current Account**



<img src="https://github.com/cbenea/LearningGit/blob/master/image/31.png" width="280" height="380"> 

 	
An account number is automatically generated:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/32.png" width="600" height="380">
 

Complete details and commit:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/33.png" width="600" height="480">
 
Transaction is complete:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/34.png" width="300" height="130">




### Authorize and search created account ###

A second user (supervisor) with additional rights has to authorize this transaction. Until then, the newly created customer can be checked into the unauthorized files list (**List Unauth File**).
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/35.png" width="400" height="400">

<img src="https://github.com/cbenea/LearningGit/blob/master/image/36.png" width="550" height="500">


 
Click **Account Id** and then the key button:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/37.png" width="350" height="100">

 
And authorize the record:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/38.png" width="550" height="300">
 

Now search created account:

•	Under **User Menu** click **Account**, then **Open Current Account**. 
•	+ Under **MoreActions** scroll down for **List Live File**, click and press **Go**:   

This action will load all accounts database results.

<img src="https://github.com/cbenea/LearningGit/blob/master/image/39.png" width="540" height="500">

 
Go to **Selection Screen** button  

Input the account number and click **Find**:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/40.png" width="400" height="210">

Result:

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/41.png)
 

# Open a savings account #


Under **User Menu** click **Account**, then **Open Savings Account**


<img src="https://github.com/cbenea/LearningGit/blob/master/image/42.png" width="300" height="500">


 
An account number is automatically generated:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/43.png" width="700" height="410">
 

Complete details and commit:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/44.png" width="400" height="210">
 

Transaction is complete:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/45.png" width="350" height="130">
 

# Authorize and search created account #

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
 
 
### Account transaction through Funds Transfer
	
	Funds Transfer module (FT) is the part of T24 used to effect payments from one account to another either internally or externally and is related to Customer and Account applications.
	Under User Menu click Payment Services, then Funds Transfer and Account Transfer
 
	From new screen, choose Transfer between Accounts
 
 
 
 

4.1	Authorize transaction

	Log in with a new user with special approver rights:
 
	Under User Menu click Payment Services, then Funds Transfer and Authorise/ Delete FT transactions
 

 
 
	Transaction is complete:
 
 
### Cash deposit through Teller 

 
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
 
 ### Create an External User

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
 
