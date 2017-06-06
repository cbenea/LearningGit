
# Create customer and external user in T24
## Quick Start Guide 

![alt text](https://github.com/cbenea/LearningGit/blob/master/image/xyz2.png)



#### This is a guide on how to: ####
+	[Create a customer record in T24 environment](#create-a-customer) 
+	[Open current and savings accounts](#open-accounts)
+	[Create and authorize an account transaction through FT (Funds Transfer) application](#account-transaction-through-funds-transfer) 
+	[Accustom with Teller module](#cash-deposit-through-teller) 
+	[Create External User](#create-an-external-user) to provide customer access on TCMB (Temenos Connect Mobile Banking) and TCIB (Temenos Connect Internet Banking) applications 





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
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/30.png" width="400" height="200">



### Open accounts

# Open a current account 
	
	


Under **User Menu** click **Account**, then **Open Current Account**



<img src="https://github.com/cbenea/LearningGit/blob/master/image/31.png" width="300" height="430"> 

 	
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

<img src="https://github.com/cbenea/LearningGit/blob/master/image/44.png" width="650" height="380">
 

Transaction is complete:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/45.png" width="350" height="130">
 

## Authorize and search created account ##

A second user (supervisor) with additional rights has to authorize this transaction. Until then, the newly created account can be checked into the unauthorized files list (**List Unauth File**).

<img src="https://github.com/cbenea/LearningGit/blob/master/image/46.png" width="390" height="400">

<img src="https://github.com/cbenea/LearningGit/blob/master/image/47.png" width="390" height="400"> 
 

And authorize the record:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/48.png" width="420" height="420">




Or search the unauthorized account by its number. Go to **Selection Screen** button 
Insert **account number** and click **Find**.

<img src="https://github.com/cbenea/LearningGit/blob/master/image/49.png" width="420" height="230">

 
And authorize:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/50.png" width="320" height="130">
	
 
New screen appears. Click **Authorise a deal**
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/51.png" width="420" height="400">	
	
	
Transaction is complete:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/52.png" width="320" height="200">


Now search created account:
 	

+ Under **User Menu** click **Account**, then **Open Savings Account**. 

+ Under **MoreActions** scroll down for **List Live File**, click it and press **Go**: <img src="https://github.com/cbenea/LearningGit/blob/master/image/53.png" width="40" height="40">  
		

This action will load all accounts database results.

<img src="https://github.com/cbenea/LearningGit/blob/master/image/54.png" width="520" height="400">
 
 	
Go to **Selection Screen** button  

Input the account number and click **Find**:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/55.png" width="140" height="70">
 

Result:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/56.png" width="480" height="270">
 

### Account transaction through Funds Transfer
	
`Funds Transfer module (FT) is the part of T24 used to effect payments from one account to another either internally or externally and is related to Customer and Account applications.`

Under **User Menu** click **Payment Services**, then **Funds Transfer** and **Account Transfer**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/58.png" width="320" height="480">
 

From new screen, choose **Transfer between Accounts**
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/59.png" width="650" height="100">

<img src="https://github.com/cbenea/LearningGit/blob/master/image/60.png" width="750" height="450">

<img src="https://github.com/cbenea/LearningGit/blob/master/image/61.png" width="400" height="200">

<img src="https://github.com/cbenea/LearningGit/blob/master/image/62.png" width="550" height="130">
 

### Authorize transaction

Log in with a new user with special approver rights:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/63.png" width="350" height="150">


Under **User Menu** click **Payment Services**, then **Funds Transfer** and **Authorise/ Delete FT transactions**
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/64.png" width="250" height="500">


<img src="https://github.com/cbenea/LearningGit/blob/master/image/65.png" width="250" height="50">


<img src="https://github.com/cbenea/LearningGit/blob/master/image/66.png" width="700" height="400">


Transaction is complete:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/67.png" width="400" height="70">

 
 
### Cash deposit through Teller 


<img src="https://github.com/cbenea/LearningGit/blob/master/image/68.png" width="450" height="200">

 
Under **User Menu** click **Retail Operations**, then **Account Transactions** – **Teller** – **Teller Operations** – **Teller Cash** – **Cash deposit Local**


<img src="https://github.com/cbenea/LearningGit/blob/master/image/69.png" width="300" height="420"> 
 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/70.png" width="300" height="420">


Commit the deal <img src="https://github.com/cbenea/LearningGit/blob/master/image/71.png" width="30" height="20">
 

Transaction is complete

<img src="https://github.com/cbenea/LearningGit/blob/master/image/72.png" width="400" height="130">


 
**Create a Till**


<img src="https://github.com/cbenea/LearningGit/blob/master/image/73.png" width="250" height="400">


<img src="https://github.com/cbenea/LearningGit/blob/master/image/74.png" width="400" height="70">

 	
Choose from dropdown list
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/75.png" width="400" height="200">

<img src="https://github.com/cbenea/LearningGit/blob/master/image/76.png" width="400" height="200">
 
 
After completing the necessary inputs, commit the record by selecting the key at the top of the screen.

<img src="https://github.com/cbenea/LearningGit/blob/master/image/77.png" width="400" height="70">
 

And then:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/78.png" width="400" height="70">
 
Transaction is completed.

<img src="https://github.com/cbenea/LearningGit/blob/master/image/79.png" width="350" height="70">



**Authorize new till**

Log in with a new user with special approver rights:
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/80.png" width="350" height="150">

 
 Under **User Menu** click **Retail Operations**, then **Account Transactions** – **Teller** – **Head Teller Operations** – **Till Administration** – **Authorise / Delete Till Closure**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/81.png" width="300" height="80">

 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/82.png" width="450" height="350">
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/83.png" width="400" height="150">

Transaction is complete.
 	
 
 ### Create an External User

	The user creation process involves the following steps:
1. Creating Online Banking Arrangement
2. Creating Group Permission using Manage Permissions option
3. Creating External User (For example, creation of RETAIL1)
4. Authorising the Channel User
5. Manage External User


#### Create Online Banking Arrangement ####

<img src="https://github.com/cbenea/LearningGit/blob/master/image/84.png" width="290" height="150">
 

Click **Create Online Banking Arrangement** option under the **Admin Menu** of the T24 Model Bank
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/85.png" width="290" height="300">
 
Under **Product Groups** select **Temenos Connect Retail**

Both the **TCIB** and **TCMB** products are arranged under the Product Groups and Products.
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/86.png" width="500" height="180"> 

 
Input **Customer ID** and click **Validate a Deal**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/87.png" width="550" height="400"> 
 
On validating the above page, a newly created Arrangement is displayed with options for further configuration. 

`In this page, most of the fields in the Customer and User Rights sections are pre-defined with basic functionality. For more functionality, user is advised to configure additional TC.Operations fields and select the additional options from the dropdown according to preferences.`

`Under Product Access section, the required products CURRENT.ACCOUNTS, CURRENT.ACCOUNTS.CATEGORY and SAVINGS.ACCOUNT.CATEGORY are selected in order to provide access to these accounts.`

`Note: User is advised to take note of the Arrangement ID, SMS Group and Customer ID to use them during the upcoming configuration`

<img src="https://github.com/cbenea/LearningGit/blob/master/image/88.png" width="600" height="600">



 

Authorize the deal  <img src="https://github.com/cbenea/LearningGit/blob/master/image/89.png" width="50" height="30">

 
Transaction is complete:

<img src="https://github.com/cbenea/LearningGit/blob/master/image/90.png" width="600" height="80">


### Create Group Permission ###

The creation of group permission enables the user to add the customer accounts related to the user role (Clerk).

Under **Admin Menu** click **External User Administration**, then **Create/ Manage Online Arrangement**, then **Manage Permissions**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/91.png" width="300" height="400"> 
 

**Create new Permission** screen is open. Fields **Customer** must be populated with Customer ID and **Group Name** with TC Home name must be populated. Click **Find**
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/92.png" width="500" height="180"> 

Click the displayed **hyperlink**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/93.png" width="500" height="250">  

 
In the following screen, input **Description**, select **Type** as Individual scroll down and choose the required Product 

<img src="https://github.com/cbenea/LearningGit/blob/master/image/94.png" width="800" height="400">  

 
Add all required products and commit 
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/95.png" width="800" height="400"> 
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/96.png" width="500" height="100"> 


### Create External User ###

`An External User who is entered into the system must be created in the EB.EXTERNAL.USER application. Each External User is related to a customer (i.e., the person who enters the system through an External User), an Internet Service Arrangement and Channel Permissions.`

Under **Admin Menu** click **External User Administration**, then **Create/ Manage Online Banking Access – Create External User**
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/97.png" width="270" height="450"> 
 

The following screen is displayed for you to enter the External User ID (that is RETAIL1) in the External user creation field.

<img src="https://github.com/cbenea/LearningGit/blob/master/image/98.png" width="500" height="300"> 
 
Transaction is complete

<img src="https://github.com/cbenea/LearningGit/blob/master/image/99.png" width="750" height="100"> 
 

### Authorize Channel User ###

A second user (supervisor) with additional rights has to authorize this transaction.  
 	
<img src="https://github.com/cbenea/LearningGit/blob/master/image/100.png" width="300" height="150">	
	
	
Under **Admin Menu**, click **External User Administration**, then **Authorise Online Banking Access** and **Authorise Channel User**
 
<img src="https://github.com/cbenea/LearningGit/blob/master/image/101.png" width="250" height="400">	

<img src="https://github.com/cbenea/LearningGit/blob/master/image/102.png" width="550" height="450">	
 
Transaction is complete

<img src="https://github.com/cbenea/LearningGit/blob/master/image/103.png" width="600" height="70">

 
Status field in the EB.EXTERNAL.USER of the user role **Initiated**. Change into **Active**

<img src="https://github.com/cbenea/LearningGit/blob/master/image/104.png" width="550" height="500">
 
Press commit. There is no need for authorization at this step. External user creation is completed

<img src="https://github.com/cbenea/LearningGit/blob/master/image/105.png" width="400" height="80">
 
