Agenda :
To try and encourage more sales of different books from a popular 5 book series, a bookshop
has decided to offer discounts on multiple book purchases.

Technologies :
Front End : Angular CLI 8.3.23 
Back End : Laravel 6+
Database : MYSQL 5.0.12

Software Requirements :
Node Version : 12.1.1
PHP : 7.3.9

Explaination :
- The project is divided in to 2 parts :

1) Front End - Angular
- This is used to perform the front end task where user do several requests and get the out put through the API which is developed in back end (Laravel).

Download the script : https://github.com/aliasgarvanak/mooments/frontend.zip and extract it

Open the script folder in to the terminal and run the following commands :
npm intall
npm update
ng serve --open

- After running that commands, all the necessary packages will be installed and angular project will open in to the browser with the following URL : http://localhost:4200/

2) Back End - Laravel
- This is used to perfrom the back end tasks whose requests coming from the front end by the user and perform the logics and give the output.

Download the script : https://github.com/aliasgarvanak/mooments/backend.zip and extract it

Open the script folder in to the terminal and run the following commands :
php artisan serve

- After running that commands, all the necessary packages will be installed and laravel project will open in to the browser with the following URL : http://127.0.0.1:8000/

- Database file, I have also added as mooments.sql in the root folder of backend. You can directly import it in to the database.So, you will get all the tables which is required in this project.


- There are two functionalitieis I have added which are not required in the task but still to apply JWT, I have done that.

a) Register http://localhost:4200/register
- Simple Registration
b) Login http:://localhost:4200/login
- Simple Login
Demo User : aliasgar.vanak@gmail.com / abc123
c) Dashboard : 
- After logged in to the application, you will be able to see all the products with their individual count item. You just have to add the quantity for each product and calculate the amount. At the top of the page, you will get the amount as per the discount. Price for each product is 8 which is set in the backend.
