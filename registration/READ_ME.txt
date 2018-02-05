creating a user registration system where users can create an account by providing Name, username, Phone Number, email and password, login and logout using PHP and MySQL.
I will also show you how you can make some pages accessible only to logged in users. Any other user not logged in will not be able to access the page.

STEP 1:-
The first thing we'll need to do is set up our database. 
	Create a database called "registration". In the registration database, add a table called users. The users table will take the following four fields.
		id
		username  -  varchar(100)
		email  -  varchar(100)
		password  -  varchar(100)
		
STEP 2:- Create a folder inside "C://xampp/htdocs/registration"
		Inside the folder "registration", create the following files:
			error.php
			index.php
			login.php
			register.php
			sever.php
			style.css
			
STEP 3:- Now for User Checkout With Promo Code:
			create a 4 table inside "registration" database these are:-
				 customers, 
				 products, 
				 orders, and
				 order_items)
				 
STEP 4:- Inside the folder "registration", create the following files:
			cart.php
			cartAction.php
			checkout.php
			dbConfig.php
			item.php
			orderSuccess.php
			viewCart.php