----------------------------------------------------------------------------

Steps to set up this website in WAMP.

1) Create user in WAMP.
eg.
grant all privileges on *.* to 'abhij'@localhost identified by 'abhi';
Note: Change the username & password in db_login.php according to your username & password.


2) Create database with name 'book'.

3) Import tables in 'book' database. Go to import tab in WAMP & give path of below file to import.
Ticket-Booking\database\book.sql

4) Done.
