# SecureAccess
This project demonstrates a safe architecture for MS Access Databases.

The architecture is a 3 step architecture. The data should be protected with a password encrypted database. The 'app' which contains the business logic has connected tables to the database. It therefor need to store the database password. In order to hide the datbase password the 'app' should be password encrypted too. 
The last step is the opener or launcher. In order not to spread the encryption password, it is hidden in compiled code in the launcher. The user will not see or be aware of the password. The launcher will open the encrypted app. The app will read the encrypted database.

In this repository you find:
1) a sample database called 'EZAccessSecurityDemoData.accdb'. This is the password protected back-end database.
2) a sample application called 'EZAccessSecurityDemoApp.accdb'. This is the password protected front-end database.
3) the launcher called 'EZAccessSecurityDemo.accdb'. This is an un-protected database to be able to evaluate the code being used.
4) the launcher called 'EZAccessSecurityDemo64.accdr'. This is the compiled version that should be distributed.

This repository shows the demo or proof of concept. The concept is free to be used in any way that will help you create saver applications.

Best Regards,

EZ Access Gideon
