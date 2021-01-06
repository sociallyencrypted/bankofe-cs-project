# Bank Of E - A class 12th CBSE CS Project

This is a class 12th CBSE Computer Science project, coded in python. It uses Python-MySQL connectivity to function. Bank Of E provides a system that allows customers to create accounts, deposit or withdraw money, or transfer money to other accounts. The program also allows for a user with admin-level priviledges to log in and check details related to customers and transactions. 

### Prerequisites

The project requires mysql-conector-python to function

```
$pip install mysql-connector-python
```

### Installing

First, open startup.py, and change the value of "passwd" in line 4 to the password of the root user in your MySQL installation. Then run setup.py to install the required database. After that, you can run main.py to use the project.

ALTERNATE: Edit BankOfE_DatabaseInstaller.sql and change admin names at the end of the file as per your choice. Then run BankOfE_DatabaseInstaller.sql .
```
mysql> source \bankofe-cs-project\BankOfE_Databaseinstaller.sql;
```

## Acknowledgments

* Thanks to my school teacher, Ms. Pragya Gulati for helping me with this project.
* Thanks to @kamalesh-Kavin for the startup.py template
