# bank-manager
This project provides a basic system to manage all credit card charges and bank transactions you've made all in one place.

August 6, 2025
Version 1.1.0

The user can:
View list of registered accounts, months within an account, or registered charges within a month of an account
Add or remove accounts, months within an account, or charges within a month of an account

Loop:
1. User prompted to select an existing account, add a new account, remove an existing account (entering -128), 
	or quit program (entering 0)
2. With an account selected, user prompted to select a month registered in that account, add a new month, remove 
	an existing month (entering -128), or exit selected account (entering 0)
3. With an account and month selected, user prompted to exit selected month (entering 0), add a new 
	charge, or remove an existing charge (entering -128)

SETUP:
Place directory in file system like so: C:\programs\camino
Put *.bat files anywhere desired and execute or compile and run a driver class from command prompt
-bankviewer.bat: use to simply view accounts, transactions, etc. (BankInterface.java)
-bankmanager.bat: use to add or remove accounts, transactions, etc. (BankOpInterface.java)

Also:
simbolos directory contains headers you can use for different banks
To use them:
1. once new account created, replace simbolo.txt in account in camino/cuentas/*accountname*/simbolos
	directory with desired header text file from camino/simbolos directory
2. rename header text file to simbolo.txt
