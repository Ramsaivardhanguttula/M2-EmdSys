# AUTOMATED MONEY TELLER MACHINE
---> ATM embedded system is an Agile model for designing because the features can be improved and modified consequently.
## Introduction
* The term ATM stands for automated teller machine.
* It is an electronic device that is used by only bank customers to process account transactions. 
* The users access their accounts through a special type of plastic card that is encoded with user information on a magnetic strip. The strip contains an identification code that is transmitted to the bank’s central computer by modem. 
* The users insert the card into ATMs to access the account and process their account transactions. 
* The automated teller machine was invented by **John Shepherd-Barron** in the year 1960. This article discusses an overview of the automated teller machine (ATM).
## Features
The features of the automated teller machine include the following.

* Transfer funds between linked bank accounts
* Receive account balance
* Prints recent transactions list
* Change your pin
* Deposit your cash
* Prepaid mobile recharge
* Bill payments
* Cash withdrawal
* Perform a range of features in your foreign language.
## Requirements
### High-Level requirements
The user/customer should perform following tasks
* The user could be able to check the Balance in his bank account.
* The user should be able to withdraw cash from ATM.
* The user should be able to deposit cash.
### Low-Level Requirements
* ATM System displays error message saying no balance are available the amount which the customer choose or enter greater than his balance.
* The system asks the user after every transaction [successfull/unsuccessful] weather he want to perform a transaction again.



## Description
* By using an automated teller machine or ATM we can perform different financial transactions such as cash deposits, withdrawals, transfer funds, information of account, ATM PIN change, and also linking the Aadhaar number to the bank account so that the interaction between the bank staff and the customer can be reduced.
* The automated teller machine (ATM) is an automatic banking machine (ABM) that allows the customer to complete basic transactions without any help from bank representatives. There are two types of automated teller machines (ATMs). The basic one allows the customer to only draw cash and receive a report of the account balance. Another one is a more complex machine that accepts the deposit, provides credit card payment facilities and reports account information
## Block Diagram of Automated Teller Machine
* The block diagram of the automated teller machine consists of mainly two input devices and four output devices. 
* The input devices like card reader and keypad whereas output devices are speaker, display screen, receipt printer, and cash depositor.
 ![ATM_Block_diagram](https://user-images.githubusercontent.com/98812447/154794393-0c1bbb80-5f4c-4910-bfc5-7b10d6e8c96a.png)
## Input Devices
The input devices like card reader and keypad.
### Card reader 
* The card reader is an input device that reads data from a card. 
* The card reader is part of the identification of your particular account number and the magnetic strip on the backside of the ATM card is used for connection with the card reader.
* The card is swiped or pressed on the card reader which captures your account information i.e. the data from the card is passed on to the host processor (server). 
* The host processor thus uses this data to get the information from the cardholders.
### Keypad
* The card is recognized after the machine asks for further details like your identification number, withdrawal, and your balance inquiry Each card has a unique PIN so that there is little chance for some else to withdraw money from your account. 
* There are separate laws to protect the PIN code while sending it to the host processor. The PIN is mostly sent in encrypted form.
* The keyboard contains 48 keys and is interfaced to the processor.
## Output Devices
The output devices are speaker, display screen, receipt printer, and cash depositor.
### Speaker
The speaker provides audio feedback when a particular key is pressed.
### Display Screen
The display screen displays the transaction information. Each step of withdrawal is shown by the display screen. A CRT screen or LCD screen is used by most of the ATMs.
### Receipt Printer
The receipt printer prints all the details recording your withdrawal, date and time, and the amount of withdrawal and also shows the balance of your account in the receipt.

### Cash Dispenser
* The cash dispenser is the heart of the ATM.
* This is a central system of the ATM from where the required money is obtained. From this portion, the user can collect the money. 
* The cash dispenser must count each bill and give the required amount. 
* If in some cases the money is folded, it will be moved to another section and becomes the reject bit.
* All these actions are carried out by high precision sensors. 
* A complete record of each transaction is kept by the ATM with the help of an RTC device.
## ATM Networking
* The internet service provider (ISP) also plays an important role in the ATMs. 
* This provides communication between ATM and host processors. 
* When the transaction is made, the details are input by the cardholder. This information is passed on to the host processor by the ATM. The host processor checks these details with an authorized bank. If the details are matched, the host processor sends the approval code to the machine so that the cash can be transferred.
## Automated Teller Machine Working Principle
The automated teller machine is simply a data terminal with two inputs and four output devices. These devices are interfaced with the processor. The processor is the heart of the ATM. All the ATMs working around the world are based on a centralized database system. The ATM has to connect and communicate with the host processor (server).

 The host processor is communicating with the internet service provider (ISP). It is the gateway through all the ATM networks available to the cardholder. When a cardholder wants to do an ATM transaction, the user provides necessary information through a card reader and keypad. The ATM forwards this information to the host processor. The host processor enters the transaction request to the cardholder bank.

 If the cardholder requests the cash, the host processor takes the cash from the cardholder’s account. Once the funds are transferred from the customer account to the host processor bank account, the processor sends the approval code to the ATM and the authorized machine to dispense the cash. This is the way to get the amount on ATMs. The ATM network is fully based on a centralized database environment. This will make life easier and secure cash.
 ## ATM Software
* The ATM (Automated Teller Machine) design is a combination of hardware and software.
* The hardware of the machine is mainly designed for deposits of cash, withdrawal, payments of credit card & for reporting the information of account. 
* The software of ATM is designed to control ATM transactions & channels on centralized databases.
* The famous ATM software that works on the XFS platform comprises Diebold Agilis EmPower, Triton PRISM, NCR APTRA Edge, AbsoluteINTERACT, KAL Kalignite Software Platform, Wincor Nixdorf ProTopas, Phoenix Interactive VISTAatm, Intertech inter-ATM & Euronet EFTS.
* Once the ATM machines were shifted to industry standards then anxiety has increased on the software stack of ATM.
## Interrupts
* Once ATM card damages then cash withdraw is not possible.
* Possibility of cash robbery from ATMs.
* ATM pin can be easily hacked by criminals by operating an ATM.
* IT charges some amount once free transactions exceed.
* The risk of theft is high while going to ATMs.
