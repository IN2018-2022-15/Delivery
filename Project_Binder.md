# Project Binder

**Table of Contents**

- [Project Binder](#project-binder)
  * [Project Design](#project-design)
    + [Tech Stack](#tech-stack)
    + [Member Duty](#member-duty)
    + [Markdown File](#markdown-file)
  * [Description](#description)
  * [System Design](#system-design)
    + [Past Verison](#past-verison)
      - [Report Class Diagram V1](#report-class-diagram-v1)
      - [Report Class Diagram V2](#report-class-diagram-v2)
      - [Report Class Diagram V3](#report-class-diagram-v3)
      - [Report Class Diagram V4](#report-class-diagram-v4)
      - [Report Class Diagram V5](#report-class-diagram-v5)
      - [Report Class Diagram V6](#report-class-diagram-v6)
      - [UCD V1](#ucd-v1)
      - [UCD V2](#ucd-v2)
      - [UCD V3](#ucd-v3)
      - [UCD V4](#ucd-v4)
      - [UCD V5](#ucd-v5)
      - [UCD V6](#ucd-v6)
      - [GUI Class Diagram V1](#gui-class-diagram-v1)
      - [Package Diagram V1](#package-diagram-v1)
      - [Use Case 1 V1](#use-case-1-v1)
      - [Use Case 2 V1](#use-case-2-v1)
      - [Use Case 3 V1](#use-case-3-v1)
      - [Use Case 3.1 V1](#use-case-31-v1)
      - [Use Case 4 V1](#use-case-4-v1)
      - [Use Case 5 V1](#use-case-5-v1)
      - [Use Case 6 V1](#use-case-6-v1)
      - [Use Case 7 V1](#use-case-7-v1)
      - [Use Case 8 V1](#use-case-8-v1)
      - [Use Case 8.1 V1](#use-case-81-v1)
      - [Use Case 9 V1](#use-case-9-v1)
      - [Use Case 10 V1](#use-case-10-v1)
    + [Current Version](#current-version)
      - [UCD](#ucd)
      - [Account Management Class Diagram](#account-management-class-diagram)
      - [Stock Management Class Diagram](#stock-management-class-diagram)
      - [Report Class Diagram](#report-class-diagram)
      - [Database Diagram](#database-diagram)
      - [GUI Class Diagram](#gui-class-diagram)
      - [Job Class Diagram](#job-class-diagram)
      - [Package Diagram](#package-diagram)
      - [Use Case 1](#use-case-1)
      - [Use Case 2](#use-case-2)
      - [Use Case 3](#use-case-3)
      - [Use Case 3.1](#use-case-31)
      - [Use Case 4](#use-case-4)
      - [Use Case 5](#use-case-5)
      - [Use Case 6](#use-case-6)
      - [Use Case 7](#use-case-7)
      - [Use Case 8](#use-case-8)
      - [Use Case 8.1](#use-case-81)
      - [Use Case 9](#use-case-9)
      - [Use Case 10](#use-case-10)
      - [Indexed List](#indexed-list)
  * [Database Design](#database-design)
    + [Past Version](#past-version)
      - [Diagram V1](#diagram-v1)
    + [Current Verison](#current-verison)
      - [Diagram](#diagram)
      - [Code](#code)
  * [GUI Design](#gui-design)
    + [Current Version](#current-version-1)
      - [HomePage](#homepage)
      - [Login Page](#login-page)
      - [Add Stock](#add-stock)
      - [Stock Check](#stock-check)
      - [Add Booking](#add-booking)
      - [Modify Booking](#modify-booking)
      - [Search Booking](#search-booking)
      - [Add Customer](#add-customer)
      - [Modify Customer](#modify-customer)
      - [Secrch Customer](#secrch-customer)
      - [Order](#order)
      - [Add Invoice](#add-invoice)
      - [Stock Reminder List](#stock-reminder-list)
      - [Payment Reminder List](#payment-reminder-list)
      - [MOT Reminder List](#mot-reminder-list)
      - [MOT Reminder PDF](#mot-reminder-pdf)
      - [Efficiency Report List](#efficiency-report-list)
      - [Efficiency Report PDF](#efficiency-report-pdf)
      - [Booking Report List](#booking-report-list)
      - [Booking Report PDF](#booking-report-pdf)
      - [Stock Report List](#stock-report-list)
      - [Stock Report PDF](#stock-report-pdf)
      - [Success Page](#success-page)
      - [Confirm](#confirm)
      - [Fatal Confirm Page](#fatal-confirm-page)
      - [Error](#error)
      - [Low Premission Error](#low-premission-error)
      - [Cancel](#cancel)
      - [GUI Navi](#gui-navi)
- [Meeting Record](#meeting-record)
  * [20220202](#20220202)
  * [20220202](#20220202-1)
  * [20220203](#20220203)
  * [20220203](#20220203-1)
  * [20220207](#20220207)
  * [20220210](#20220210)
  * [20220215](#20220215)
  * [20220217](#20220217)
  * [20220223](#20220223)
  * [20220224](#20220224)
  * [20220303](#20220303)
  * [20220303](#20220303-1)
  * [20220304](#20220304)
  * [20220305](#20220305)
- [FAQ](#faq)
  * [20220203](#20220203-2)
  * [20220217](#20220217-1)

## Project Design

**All coding must obey basic coding guideline**
**Currently it is refering to this [Coding Guideline (External File)](https://github.com/alibaba/Alibaba-Java-Coding-Guidelines/blob/master/README.md)**

### Tech Stack
- Use Vue.js as frontend
- Use Java as backend
- Use restful API as middleware, program by Java
- Use MySQL as Database
- Running on AWS Cloud Service to achieve higher Reliability and Availiability
- Clients support major browser **except IE** 
- All customer data need to store safely according to GDPR
- Use Github to do the Version Control

### Member Duty
- Project Manager by Maksymillan
- Deputy Project Manager by Xinyan
- Description by Pedro
- Use Case Specifications 1-5 by Said
- Use Case Specifications 6-10 by Pedro
- System Design by Raj And Maksymillan
- Database Design by Kristof
- GUI Design by Xinyan
- Markdown by Xinyan

### Markdown File
- This PDF is generated by [Grip](https://github.com/joeyespo/grip) from Markdown file.
- If this PDF is hard to read, you can always go to the link below to get a better experience.
- https://github.com/IN2018-2022-15/Delivery/blob/main/Mar07.md
- To check the Image Time Stamp please go to the following repo to check.
- https://github.com/IN2018-2022-15/Img-Host
- You Also can click the photo, it will redirect you to the Github Image Host Service. You can see the original size photo

## Description
<p> Quick Fit Fitters plc currently operates without a comprehensive IT system which puts them at a significant disadvantage compared to their competition. To resolve this a specialised IT system (GARTIS) will be developed and tested to help optimise as well as improve the service the Ashford branch of Quick Fit Fitters currently provides. The purpose of this document is to detail the design, development, and the testing of the GARTIS system.<p>
<p> Within the old system customers can book their vehicles for a service MoT or repair via email or telephone, this is handled by reception. Allocated repair or MoT slots are recorded on a marker board between the reception and the repair shop. After booking a check is made of the customer card to see if they have any outstanding payments. If no money is owed, a job sheet will be developed detailing the problem to be resolved and given to the repair shop. For account customers, reception can dispatch a mechanic to collect the vehicle otherwise a customer must deliver their vehicle for service themselves. Customers can also decide to request a service without any prior booking, in this case their vehicle will wait in the yard until a repair bay becomes available. The customer is then told a price estimate for the service they require and asked whether they wish to proceed with the service. Account holders may have a discount plan and can choose to pay with credit allowing them to pay for the service at a later date. Non-account customers will receive an invoice once they collect their vehicle which details the jobs done and the price for which they must pay immediately. Parts which are needed for a job are taken from within the store, if a part is not present then an order to another garage or manufacturer will be placed. These orders are emailed and then collected by an allocated driver. If an issue obtaining a required part occurs the customer will be contacted, and their vehicle will stay in the yard until it can be repaired.<p>

  

## System Design

  

### Past Versions

 #### Jobs Class Diagram V1
 
![](https://raw.githubusercontent.com/IN2018-2022-15/project-binder/main/GARITS%20VPP%20Projects/Jobs%20and%20Invoices%20Class%20Diagram%20Version%200.1.jpg?token=GHSAT0AAAAAABR7JZYITHIMZSBRQWCJAQOYYRNBKNQ)
Author: Raj

 #### Jobs Class Diagram V2

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Jobs%20Class%20Diagram.png)
Author: Raj + Maksymilian

 #### Account Management Class Diagram V1
 ![](https://raw.githubusercontent.com/IN2018-2022-15/project-binder/main/GARITS%20VPP%20Projects/Account%20Management%20Class%20Diagram%20Version%200.1.jpg?token=GHSAT0AAAAAABR7JZYIBZNCF26SG4PZOCU2YRNBCFQ)
Author: Raj

#### Account Management Class Diagram V2

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Account%20Management%20Class%20Diagram.png)
Author: Raj + Maksymilian

#### Report Class Diagram V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Reports%20Class%20Diagram%201.png)
Author: Maksymilian 
  

#### Report Class Diagram V2

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Reports%20Class%20Diagram%202.png)
Author: Maksymilian + Raj
  

#### Report Class Diagram V3

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Reports%20Class%20Diagram%203.png)
Author: Maksymilian + Raj
  

#### Report Class Diagram V4

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Reports%20Class%20Diagram%204.png)
Author: Maksymilian + Raj
  

#### Report Class Diagram V5

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Reports%20Class%20Diagram%205.png)
Author: Maksymilian + Raj
  

#### Report Class Diagram V6

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Reports%20Class%20Diagram%206.png)
Author: Maksymilian + Raj
  

#### UCD V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCD1.png)
Author: Maksymilian
  

#### UCD V2

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCD2.png)
Author: Maksymilian
  

#### UCD V3

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCD3.png)
Author: Maksymilian + Raj
  

#### UCD V4

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCD4.png)
Author: Maksymilian + Raj
  

#### UCD V5

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCD5.png)
Author: Maksymilian + Raj
  

#### UCD V6

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCD6.png)
Author: Maksymilian + Raj
  

#### GUI Class Diagram V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/GUI%20Class%20Diagram%201%20.png)
Author: Maksymilian + Raj
  

#### Package Diagram V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/Package%20Diagram%201.png)
Author: Maksymilian

#### Package Diagram V2
![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Package%20Diagram.png)
Author: Maksymilian + Raj

#### Use Case 1 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS1%20V1.PNG)

  

#### Use Case 2 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS2%20V1.PNG)

  

#### Use Case 3 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS3%20V1.PNG)

  

#### Use Case 3.1 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS3.1%20V1.PNG)

  

#### Use Case 4 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS4%20V1.PNG)

  

#### Use Case 5 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS5%20V1.PNG)

  

#### Use Case 6 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS6%20V1.PNG)

  

#### Use Case 7 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS7%20V1.PNG)

  

#### Use Case 8 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS8%20V1.PNG)

  

#### Use Case 8.1 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS8.1%20V1.PNG)

  

#### Use Case 9 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS9%20V1.PNG)

  

#### Use Case 10 V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/UCS10%20V1.PNG)

  
  

### Current Version

  

#### UCD

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Use%20Case%20Diagram.png)
Author: Maksymilian + Raj 
  

#### Account Management Class Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Account%20Management%20Class%20Diagram.png)
Author: Raj + Maksymilian
  

#### Stock Management Class Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/StockManagement%20Class%20Diagram.png)
Author: Raj + Maksymilian
  

#### Report Class Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Reports%20Class%20Diagram.png)
Author: Raj + Maksymilian
  

#### Database Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Database%20Class%20Diagram.png)
Author: Raj
  

#### GUI Class Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/GUI%20Class%20Diagram%20.png)
Author: Maksymilian + Raj
  

#### Job Class Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Jobs%20Class%20Diagram.png)
Author: Raj + Maksymilian
  

#### Package Diagram

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Package%20Diagram.png)
Author: Maksymilian + Raj
  

#### Use Case 1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec1.PNG)

  

#### Use Case 2

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec2.PNG)

  

#### Use Case 3

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec3.PNG)

  

#### Use Case 3.1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec3.1.PNG)

  

#### Use Case 4

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec4.PNG)

  

#### Use Case 5

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec5.PNG)

  

#### Use Case 6

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec6.PNG)

  

#### Use Case 7

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec7.PNG)

  

#### Use Case 8

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec8.PNG)

  

#### Use Case 8.1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec8.1.PNG)

  

#### Use Case 9

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec9.PNG)

  

#### Use Case 10

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/Spec10.PNG)

  

#### Indexed List

  

| Use case name | Level | Justification |

|----|----|----|

|Set Customer Discount Plan|High|Having customer discount plan is needed and essential for the business to develop its product awareness and their business|

|Alter Customer Discount Plan|Low|Not so important altering the discount plan as when you state discount you don`t often change it|

|Alter customer account |High| Altering the customer account can be important if a change has been made to its previous account details|

|Search customer |Moderate| Searching a customer isn`t so important but still something that that needs to be done as you need to search for the customer to change the discount plan|

|Configure pay late |Moderate| Medium because it is not an often thing for customer to pay late|

|Acknowledge late payment alert |H| Important as if the franchisee doesn`t acknowledge this then non one will do anything or will know anything about the late payment|

|Configure automatic report |Moderate| Configuring the report is not so very important but it is still something they should do|

|Configure stock alert threshold |High| Quite important knowing how the stock levels are, as you never want to run out of stock|

|Alter job |Moderate| Not so important as not many people will check on the status of the job except the mechanic, but it is good to have, as the customer may want to know when they may get their vehicle back|

|View job |Low| Viewing the job isn\`t going to be done so much, apart from the mechanic, so this isn`t so important|

|Search stock |Moderate| Searching for stock can be important, as you need to search to see if there are any more parts still in stock, to see if you need to stock up|

|View report |Moderate| Viewing report can also be important, because it is good to check on the reports either printed for the stock or the booking summary|

|Print report |Moderate| Printing reports is something that is needed, because you can still have a digital copy, and it does take longer to print out each report, and cost more|

|Create booking summary report |High| Making a booking summary is important, because it is good to have previous booking records, to work of and keep contact of, just in case it may come in handy|

|Late payment alert |High| This is very important, as it keeps the business up to date with its inflow, and prevents loss of money, and wasted time |

|Generate stock report|High| Creating a stock report is vital, always want to be on top of what stock we have and what is needed|

|Order parts |High| Ordering parts is high, because without this you cannot complete vehicles. Without parts vehicles cannot be completed|

|Update stock |High| It`s Important to update stocks to keep everything up to date as it is good for the business top hold this information|

|Stock alert |Moderate| Not so important but is good to keep on top of how the stock is going, and prevent it from dropping too low|

|Send MOT reminder |Moderate| Sending mot reminders is something needed but not so important|

|View invoice |High| Viewing the invoice is important because it will be viewed by the customer |

|Add job |High| Adding a job is important because the mechanic needs to know when he has new jobs and how many jobs, he has to complete|

|Search job |Moderate| Searching a job can be quite important as all jobs will be in a list and to select any job ongoing, you will have to search for it.|

|Check progress |Moderate| Progress is not vital but a good thing to have updated, as it gives an estimate, of how far a vehicle is too being completed|

|Create customer record |Moderate| Making a customer record isn`t that important but good to keep in their contact details and addresses, it saves time not having to manually create a new customer account again and again|

|Create invoice |High| Creating invoice is important gives all the details and reports to the customer about their purchase|

|Create account |High| Creating accounts is quite important, as each account needs to have their own access to important data, and if there are no accounts, then there isn`t any security, so anyone can check valuable information|

|Delete account |Moderate| Deleting accounts isn\`t as important as creating but still it\`s good to be able to make space, and get rid of unnecessary accounts|

|Edit account |High| Important to be able to edit account because mistakes can be made and will need correcting, and if accounts are not altered, this can waste a lot of time and efficiency|

|Backup database |High| Backing up database is important, to have all the info and details incise of something bad happens and you lose it all|

|Restore database |High| Admin will need to restore the database when needed, so it is important|

|Configure Stock Report |High| This is vital, as the business needs to always be on top of the stock, so changing the stock is an important process to the system, as it can have a large impact on many other things.|

|Configure Booking Summary Report |Moderate| Changing the booking summary can be vital, because sometimes mistakes can be made, and a report will need to be altered.|

|Configure Price Timer Report |Moderate| This is important because, you give an estimate to the customer, so they know when they can expect the car.|

|Generate Booking Summary Report |Low| Generating a booking summary report isn\`t so important, but is a good thing to have, it isn`t very useful for the user|

|Generate Price Time Summary Report |Moderate| This is important as it tells us the expected time of the vehicle to be completed|

|Generate Stock Report |Moderate| Creating a stock report is vital, as it is free, digital and important to have, so the business know if they are out of stock or not|

|Send Annual Service Reminder |High| This is very important, because customers getting their car service is a necessity, for customers.|

|Send Mot Reminder |Moderate| Sending MOT reminder is vital, as the customer need to be reminded that they need to bring their vehicle for a check up to check if its legal on the roads.|

|View Booking Summary Reports |Moderate| Having a booking summary report again isn\`t vital, it's a good thing to have, to keep on track with all the bookings made but not a necessity.|

|View Stock Report |Moderate| Viewing the stock report isn`t important to where the business cannot run, however it is still a good thing to check and see constantly to keep up on the stock, and see the pattern of what is being used the most etc.|

|Log in |High| Logging in is so important as the business needs to have areas where only a few people can access, such as customer records. These cannot be accessible to everyone because that would be illegal.|

|Log out |High| Same with logging in, this is vital, because it protects the confidentiality of the account, and everything it can access.|

|Send reminder |High| Sending reminders is important, because cars need to be road worthy, and if it does not pass the MOT test that is a safety risk, for the driver, and other drivers and it should not be allowed on the roads. So, you will be putting people`s lives at risk, if this does not happened.|

  

## Database Design

  

### Past Version

  

#### Diagram V1

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/VC/dbv1.png)

  

### Current Verison

  

#### Diagram

  

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/db.jpeg)

  

#### Code

  

````sql

--MySQL table creations

  

CREATE  TABLE Manufacturers (

manufacturer_id int(11) NOT  NULL AUTO_INCREMENT,

manufacturer_name varchar(255) NOT  NULL,

manufacturer_address varchar(255) NOT  NULL,

manufacturer_website varchar(255) NOT  NULL,

manufacturer_phone int(11) NOT  NULL,

manufacturer_postcode varchar(255) NOT  NULL,

PRIMARY  KEY (manufacturer_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE Customer (

customer_id int(11) NOT  NULL AUTO_INCREMENT,

first_name_customer varchar(255) NOT  NULL,

last_name_customer varchar(255) NOT  NULL,

customer_address varchar(255) NOT  NULL,

customer_phone int(11) NOT  NULL,

PRIMARY  KEY (customer_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE Garage (

garage_id int(11) NOT  NULL AUTO_INCREMENT,

garage_name varchar(255) NOT  NULL,

garage_address varchar(255) NOT  NULL,

number_of_staff int(11) NOT  NULL,

number_of_bays int(11) NOT  NULL,

PRIMARY  KEY (garage_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE vehicle (

Vehicle_year year  NOT  NULL,

vehicle_brand varchar(255) NOT  NULL,

vehicle_name varchar(255) NOT  NULL,

vehicle_type SET('car', 'van') NOT  NULL,

vehicle_last_service date  NOT  NULL,

vehicle_MOT_date date  NOT  NULL,

vehicle_numberplate varchar(255) NOT  NULL,

vhec_id int(11) NOT  NULL AUTO_INCREMENT,

engineengin_id int(11) NOT  NULL,

Customercustomer_id int(11) NOT  NULL,

PRIMARY  KEY (vhec_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE Staff (

Staff_id int(11) NOT  NULL AUTO_INCREMENT,

first_name_staff varchar(255) NOT  NULL,

last_name_staff varchar(255) NOT  NULL,

staff_address varchar(255) NOT  NULL,

staff_phone int(11) NOT  NULL,

Positionsposition_id int(11) NOT  NULL,

PRIMARY  KEY (Staff_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE bays (

bay_id int(11) NOT  NULL AUTO_INCREMENT,

bay_type SET('MOT','Service') NOT  NULL,

Garagegarage_id int(11) NOT  NULL,

PRIMARY  KEY (bay_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE parts (

parts_id int(11) NOT  NULL AUTO_INCREMENT,

parts_name varchar(255) NOT  NULL,

vehicle_type varchar(255) SET('car','van') NOT  NULL,

parts_year year  NOT  NULL,

parts_price int(11) NOT  NULL,

stock_amount int(11) NOT  NULL,

stock_ordered int(11),

Manufacturersmanufacturer_id int(11) NOT  NULL,

PRIMARY  KEY (parts_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE invoice (

Customercus_id int(11) NOT  NULL,

vehiclevhec_id int(11) NOT  NULL,

partsparts_id2 int(11) NOT  NULL,

jobsjobs_id int(11) NOT  NULL,

Garagegarage_id int(11) NOT  NULL)

CHARACTER  SET UTF8;

  

CREATE  TABLE Positions (

position_id int(11) NOT  NULL AUTO_INCREMENT,

position_name varchar(255) NOT  NULL,

position_hourly_rate float  NOT  NULL,

PRIMARY  KEY (position_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE engine (

engin_id int(11) NOT  NULL AUTO_INCREMENT,

engine_size float  NOT  NULL,

engine_year year  NOT  NULL,

PRIMARY  KEY (engin_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE jobs (

job_type SET('MOT','Repair','Annual') NOT  NULL,

Positionspos_id int(11) NOT  NULL,

jobs_id int(11) NOT  NULL AUTO_INCREMENT,

job_status SET('Done','Started','In que') NOT  NULL,

job_description longtext,

est_time time,

actual_time time  NOT  NULL,

StaffStaff_id int(11) NOT  NULL,

partsparts_id int(11) NOT  NULL,

PRIMARY  KEY (jobs_id))

CHARACTER  SET UTF8;

  

CREATE  TABLE Staff_Garage (

StaffStaff_id int(11) NOT  NULL,

Garagegarage_id int(11) NOT  NULL,

PRIMARY  KEY (StaffStaff_id, Garagegarage_id))

CHARACTER  SET UTF8;

  

--

-- Add foreign keys

--

  

ALTER  TABLE invoice ADD  CONSTRAINT FKinvoice387753 FOREIGN KEY (Customercus_id) REFERENCES Customer (customer_id);

ALTER  TABLE vehicle ADD  CONSTRAINT FKvehicle633189 FOREIGN KEY (engineengin_id) REFERENCES engine (engin_id);

ALTER  TABLE jobs ADD  CONSTRAINT FKjobs574657 FOREIGN KEY (Positionspos_id) REFERENCES Positions (position_id);

ALTER  TABLE jobs ADD  CONSTRAINT FKjobs544844 FOREIGN KEY (StaffStaff_id) REFERENCES Staff (Staff_id);

ALTER  TABLE vehicle ADD  CONSTRAINT FKvehicle554026 FOREIGN KEY (Customercustomer_id) REFERENCES Customer (customer_id);

ALTER  TABLE invoice ADD  CONSTRAINT FKinvoice999275 FOREIGN KEY (vehiclevhec_id) REFERENCES vehicle (vhec_id);

ALTER  TABLE parts ADD  CONSTRAINT FKparts923036 FOREIGN KEY (Manufacturersmanufacturer_id) REFERENCES Manufacturers (manufacturer_id);

ALTER  TABLE invoice ADD  CONSTRAINT FKinvoice653466 FOREIGN KEY (partsparts_id2) REFERENCES parts (parts_id);

ALTER  TABLE invoice ADD  CONSTRAINT FKinvoice157612 FOREIGN KEY (jobsjobs_id) REFERENCES jobs (jobs_id);

ALTER  TABLE jobs ADD  CONSTRAINT FKjobs133119 FOREIGN KEY (partsparts_id) REFERENCES parts (parts_id);

ALTER  TABLE Staff_Garage ADD  CONSTRAINT FKStaff_Gara821762 FOREIGN KEY (StaffStaff_id) REFERENCES Staff (Staff_id);

ALTER  TABLE Staff_Garage ADD  CONSTRAINT FKStaff_Gara504844 FOREIGN KEY (Garagegarage_id) REFERENCES Garage (garage_id);

ALTER  TABLE Staff ADD  CONSTRAINT FKStaff78974 FOREIGN KEY (Positionsposition_id) REFERENCES Positions (position_id);

ALTER  TABLE bays ADD  CONSTRAINT FKbays23143 FOREIGN KEY (Garagegarage_id) REFERENCES Garage (garage_id);

ALTER  TABLE invoice ADD  CONSTRAINT FKinvoice161170 FOREIGN KEY (Garagegarage_id) REFERENCES Garage (garage_id);

  

--

-- Insert statements

--

  

-- Manufactureres

  

INSERT  INTO Manufacturers VALUES (2364, Fjord, 18 Dudley hill, www.fjordmotors.com, 07765134537, N6 4AC);

INSERT  INTO Manufacturers VALUES (3245, Velvet, 25 Stoner, www.velvetmotors.com, 07756385437, N8 8BC);

INSERT  INTO Manufacturers VALUES (4176, Vhuxhill, 235 Velcro road, www.vhuxhillmotors.com, 07798247563, NW4 3TQ);

INSERT  INTO Manufacturers VALUES (5037, Submaru, 123 Fanfar road, www.submarumotors.com, 07798745683, NS3 8QT);

INSERT  INTO Manufacturers VALUES (6488, Auditor, 144 Peterson street, www.auditormotors.com, 07798768235, S7 3BE);

INSERT  INTO Manufacturers VALUES (7529, Ferero, 139 Reilly road, www.fereromotors.com, 07776495763, W2 6RT);

  

-- Customers

  

INSERT  INTO Customer VALUES (47591, Jhon, Doh, 77 Silent hill, 07765136437);

INSERT  INTO Customer VALUES (57584, Jane, Beneth, 34 Sentinel hill, 07764385437);

INSERT  INTO Customer VALUES (77726, peter, Straub, 54 Norman road, 07793447563);

INSERT  INTO Customer VALUES (87399, Sarah, Shonne, 34 Queens avenue, 07798745683);

INSERT  INTO Customer VALUES (97772, Archibold, Liddle, 144 Vernon street, 07743466235);

  

-- Garage

  

INSERT  INTO Garage VALUES (114, Main Garits, 99 Balloon Road, 14, 10);

  

-- vehicle

  

INSERT  INTO vehicle VALUES (2017, Fjord, T-rex, car, 02/02/2022, 04/01/2022, JS00 GTZ, 677, 099, 57584);

INSERT  INTO vehicle VALUES (2017, Velvet, c99, car, 03/12/2021, 05/01/2022, HT10 FWF, 678, 008, 47591);

INSERT  INTO vehicle VALUES (2020, Fjord, T-rex, car, 01/02/2022, 06/01/2022, HB17 LWW, 689, 099, 97772);

INSERT  INTO vehicle VALUES (2007, Fjord, unicorn, car, 12/03/2021, 11/01/2022, HF18 RWZ, 698, 007, 77726);

INSERT  INTO vehicle VALUES (2015, Auditor, B2, car, 01/01/2022, 07/01/2022, HR15 GEB, 987, 008, 87399);

  

-- Staff

  

INSERT  INTO Staff VALUES (1134, Jhon, Doh, 72 Robert hill, 0776534537, 8);

INSERT  INTO Staff VALUES (1135, Jane, Juniper, 23 Stanford corner, 077563778437, 2);

INSERT  INTO Staff VALUES (1136, Pete, Evans, 12 Tristan road, 07798234563, 1);

INSERT  INTO Staff VALUES (1137, Helga, Humber, 178 Ferringdon road, 07794565683, 8);

INSERT  INTO Staff VALUES (1138, Frodo, Baggins, 123 Rambo street, 077923678235, 2);

INSERT  INTO Staff VALUES (1139, Attila, Hun, 167 Roadhouse lane, 07776445563, 2);

INSERT  INTO Staff VALUES (1140, Jhony, Greed, 134 Squires road, 07776444763, 2);

INSERT  INTO Staff VALUES (1141, Fred, Jhones, 166 Radish street, 0777677763, 2);

INSERT  INTO Staff VALUES (1142, Welma, Stuart, 190 Repley road, 07776411763, 2);

INSERT  INTO Staff VALUES (1143, Trevor, Banks, 13 Concrete avenue, 07747757763, 2);

INSERT  INTO Staff VALUES (1140, Jack, Purple, 198 Swiss road, 07776934763, 4);

INSERT  INTO Staff VALUES (1141, Sheamus, Shober, 135 Ragdoll street, 0777673763, 5);

INSERT  INTO Staff VALUES (1142, William, Fitzgerald, 147 Raven road, 07776893763, 4);

INSERT  INTO Staff VALUES (1143, Tristan, jenkins, 88 Lebanon avenue, 07749267763, 4);

  

-- bays

  

INSERT  INTO bays VALUES (45, MOT, 114);

INSERT  INTO bays VALUES (44, MOT, 114);

INSERT  INTO bays VALUES (40, Service, 114);

INSERT  INTO bays VALUES (39, Service, 114);

INSERT  INTO bays VALUES (38, Service, 114);

INSERT  INTO bays VALUES (37, Service, 114);

INSERT  INTO bays VALUES (36, Service, 114);

INSERT  INTO bays VALUES (35, Service, 114);

INSERT  INTO bays VALUES (34, Service, 114);

INSERT  INTO bays VALUES (33, Service, 114);

  

-- parts

  

INSERT  INTO parts VALUES (877, Exhaust, car, 2020, 500, 5, 0, 2364);

INSERT  INTO parts VALUES (878, Break_pedal, car, 2021, 30, 12, 0, 2364);

INSERT  INTO parts VALUES (879, Fog_lights, car, 2022, 250, 0, 6, 2364);

INSERT  INTO parts VALUES (880, Oil_filter, car, 2022, 80, 3, 10, 5037);

  

-- Positions

  

INSERT  INTO Positions VALUES (8, receptionist, 12.50);

INSERT  INTO Positions VALUES (2, mechanic, 105);

INSERT  INTO Positions VALUES (5, foreperson, 18);

INSERT  INTO Positions VALUES (4, storekeeper, 12.75);

INSERT  INTO Positions VALUES (1, master_mechanic, 125);

  

-- engine

  

INSERT  INTO engine VALUES (007, 1.8, 2017);

INSERT  INTO engine VALUES (008, 2.2, 2006);

INSERT  INTO engine VALUES (009, 1.6, 2022);

INSERT  INTO engine VALUES (003, 1.4, 2011);

INSERT  INTO engine VALUES (011, 1.2, 2017);

INSERT  INTO engine VALUES (099, 6.0, 2018);

  

-- jobs

  

INSERT  INTO jobs VALUES (Repair, 2, 001, Done, Oil change, 60, 30, 1140, 880);

INSERT  INTO jobs VALUES (MOT, 2, 002, Done, MOT test, 120, 120, 1142, );

INSERT  INTO jobs VALUES (MOT, 1, 003, Started, Exhaust change, 240, , 1136, 877);

  

--

-- Updates

--

  

UPDATE engine

SET engine_size = 2.0

WHERE engin_id = 011;

  

UPDATE engine

SET engine_year = 2017

WHERE engin_id = 003;

  

--

-- Deletes

--

  

DELETE  FROM parts WHERE parts_id = 878;

DELETE  FROM parts WHERE parts_id = 879;

  

--

-- Functions

--

  

SELECT  AVG(actual_time) FROM jobs;

SELECT job_type, AVG(est_time) FROM  GROUP BY job_type;

  

````

  

## GUI Design

  

### Current Version

  

#### HomePage

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Home%20Page.png)

  

-----

  

#### Login Page

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Home%20Page%20Expand.png)

  

-----

  

#### Add Stock

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Add%20stock.png)

  

-----

  

#### Stock Check

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Stock%20check.png)

  

-----

  

#### Add Booking

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/New%20Booking.png)

  

-----

  

#### Modify Booking

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Modify%20Booking.png)

  

-----

  

#### Search Booking

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Search%20Booking.png)

  

-----

  

#### Add Customer

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Add%20Customer.png)

  

-----

  

#### Modify Customer

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Modify%20Customer.png)

  

-----

  

#### Secrch Customer

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Search%20Customer.png)

  
  
  

#### Order

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Order.png)

  

-----

  

#### Add Invoice

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Inovice.png)

  

-----

  

#### Stock Reminder List

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Stock%20Reminder.png)

  

-----

  

#### Payment Reminder List

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Payment%20Reminder.png)

  
  

-----

  

#### MOT Reminder List

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/MOT%20Reminder.png)

  

-----

  

#### MOT Reminder PDF

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/MOT%20Reminder%20PDF.png)

  

-----

  

#### Efficiency Report List

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Efficiency%20Report%20List.png)

  

-----

  

#### Efficiency Report PDF

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Efficiency%20Report.png)

  

-----

  

#### Booking Report List

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Booking%20Report%20List.png)

  

-----

  

#### Booking Report PDF

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Booking%20Report.png)

  

-----

  

#### Stock Report List

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Stock%20Report%20List.png)

  

-----

  

#### Stock Report PDF

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Stock%20Report.png)

  

#### Success Page

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Success%20Page.png)

  

-----

  

#### Confirm

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Booking%20Confirm.png)

  

-----

  

#### Fatal Confirm Page

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Fatal%20Confirm.png)

  

-----

  

#### Error

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Error%20Page.png)

  

-----

  

#### Low Premission Error

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Low%20Premission.png)

  

-----

  

#### Cancel

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Xd/Cancel%20Page.png)

  

#### GUI Navi

  

![](https://raw.githubusercontent.com/IN2018-2022-15/Img-Host/main/Diagram/GUI%20NAV.PNG)

  
  

# Meeting Record

##  20220202
- Time: 14:00
- Duration: 30 min
- Meeting wth Consultant
- Take place on Teams
- All member present
- First meeting with consultant
- Say Hi
- Consultant brief the project

## 20220202
- Time: 14:30
- Duration: 50 min
- Team member meeting
- Take place on Teams
- All member present
- Discuss the project
- Discuss the tech stack of the project
- Discuss the structure of the project
- Discuss the interview Question

## 20220203
- Time: 17:00
- Duration: 40 min
- Team member meeting
- Take place on Discord
- All member present
- Discuss the interview Question

## 20220203
- Time: 17:40
- Duration: 20 min
- Customer interview meeting
- Take place on Teams
- All member present
- Ask Questions to customer, refer to FAQ section 20220203

## 20220207
- Time: 13:00
- Duration: 70 min
- Team member meeting
- Take place in person
- Pedro missing
- Assigned tasks to each person on person
- Discussed how the tasks will be approached

## 20220210
- Time: 15:00
- Duration: 30 min
- Meeting wth Consultant
- Take place on Teams
- All member present
- Clairify everyone duty
- Clairify first delivery requirement

## 20220215
- Time: 17:30
- Duration: 30 Min
- Team member meeting
- Take Place on Discord 
- All Member Present
- Clarify Jobs again
- Keep on track
- Discuss the Sequence to deal the work
- Discuss impact from the strike
- Restructure Meeting Record File
- Discuss the Use case Diagram from MAK and RAJ

## 20220217
- Time: 15:00
- Duration: 45 min
- Meeting wth Consultant
- Take place on Teams
- All member present
- Discuss some questions (refer to FAQ section 20220217) with Consultant

## 20220223
- Time: 16:00
- Duration: 30 min
- Team member meeting
- Take place on Discord
- All member present
- Keep on track
- Discuss the impact from the strike
- Discuss the Use case Diagram
- Discuss the Package Diagram

## 20220224
- Time: 15:00
- Duration: 30 min
- Meeting wth Consultant
- Take place on Teams
- All member present
- Check the Use case Diagram beta with Consultant
- Consult the project structure with Consultant
- Check the Package Diagram alpha wth Consultant

## 20220303
- Time: 13:30
- Duration: 30 min
- Meeting wth Consultant
- Take place on Teams
- All member present
- Check the Use Case Diagram with consualtant
- Check GUI design with consultant

## 20220303
- Time: 14:00
- Duration: 30 min
- Team member meeting
- Take place on Discord
- All member present
- Keep on track
- Discuss Consualtant`s feedback

## 20220304
- Time: 17:00
- Duration: 30 min
- Team member meeting
- Take place on Discord
- All member present
- Keep on track

## 20220305
- Time: 20:00
- Duration: 30 min
- Team member meeting
- Take place on Discord
- All member present
- Final Check
- Go through all part

# FAQ

## 20220203
-------------
- Replier Customer at 20220203 17:40

1. Should each mechincs hourly rate be held on the system to be used for the invoice?
> Customer: Yes

2. Should labour cost for mechanics be caluculated exactly in the situation a task takes a length of time that is not one whole hour? eg. the task takes 1h and 30m.
> Customer: Pro rata.

3. Does the stock control functionality have to include the actual purchasing of new parts or is it only there to update the amounts of parts are in stock. 
> Customer: When the new stock comming in, the system should reflect the stock change.

4. Clarify discounts and specifically flexible discounts. How does the system calculate the applied discount?
> Customer: Franchiess need a flexible discount plan, depands on the size of the order. Franchiess will set the plan

5. Are customers interacting with the system?
> Customer: No

6. Can we use online open source code or do we need to code everything from scratch?
> Customer: Yes, but be aware of plagiarism

7. Can the system be cloud based?
> Customer: Yes

8. Should jobs have any priority levels?
> Customer: No

9. Is there a prefered method of concurrency control?
> Customer: Just make sure the thread safe

10. What are all the expectations of the outputs of the system? Invoices in what forms? MOT reminders in what forms? And is there anything else?
> Customer: Page 19, MOT reminder Template. Page 20, inovoice Template. Check all template. Report viewable in the system and printable. Two types of alart, stock alart, payment alart. Just need generate reminder, no need stmp service.

## 20220217
-------------
- Replier Vlad at 20220220 22:00

1. Is it necessary to have a shopkeeper actor as the receptionist will be doing everything the shopkeeper will be in the new system? 
> Vlad: The required roles/actors are explained in the SB document, on p15, 16. In particular the following is stated:  “Thus, in the new system, the role of Receptionist can carry all the activities the storeroom staff can do in the existing system (including all activities of (Senior) Storekeeper). “

2. Is the receptionist creating a "customer record" the same thing as the franchisee creating a "customer account", and if not, how are they different?
>  This is the same

3. If an alert is only visible for certain actors, should they be connected to the use case with an association? For example, the late payment alert is initiated by time but is connected to the franchisee actor?
> Vlad: For the Late Payments, one should model both the alert – triggered by Time, and acknowledgement – triggered by the human Actor – Franchisee in this case.
> - One can model the alert and the acknowledgement in the same flow. This is OK only if the human recipient of the alert is modelled as a secondary actor (the flow is triggered by Time), and the acknowledgement is modelled as an extension (the presence of the secondary actor is not guaranteed).
> - A better solution is to keep the automatically created alerts and their acknowledgements as separate use cases because:
>   - They may be a long time apart
>   - More importantly the alert does not check whether the acknowledgement arises or not – asynchronous relationship.
>   - Instantaneous acknowledgements (in case the human actor receiving the alert is logged in) are still possible.

4. Will invoices and reports always be printed or should there be an option to choose if you want to print or not?
> Vlad: Invoices and reports must be both viewable and printable (e.g. “All types of reports must be both viewable and printable.” SB document, p16)
