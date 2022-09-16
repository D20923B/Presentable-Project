E-market Application

Introduction

The Application was developed as an online retail store Where the owner is able to
see all the user's available in the program and all the orders which are placed and all the
list of items the store has

a Consumer user can create an account and then a otp will be send to his email address upon entering that
his profile will be completed and then he can access the store and look through all the add_items
and can place order for the items and can also delete them when needed

as an admin we are given the privilege to add items and remove items from the store
we can also make orders and cancel orders

as the owner of the store we will be given the special key present in the env file using which we can
see the number of people present in the shops database and all the items and all the orders


Drawbacks

The html and css part of the Website is not properly managed and thus need improvement and will be updated on the later versions
of the Application
the admin user can see the orders made only the head user can see the them
need to add java-script for input sanitation at front site
need to dynamically add and remove Special_key every time the server restarts
Feel free to notify on other aspects
Thank you

Configuration
Please add your email and password at the env file
Not the usual password because it does not support 2FA(factor authentications) you need to have a different forget_password
whose steps you will get here
https://stackoverflow.com/questions/45478293/username-and-password-not-accepted-when-using-nodemailer
now add them to you env file and run it


Architecture
Userdate is stored in the sqlite module present in database item_list and orders are both stored in a link_list
nodemailer has been used to send mails to self in case of forgot special key and when server starts
and send mails to others when we need to verify otp for them
Josnwebtokens has been used to sending and mainting sessions
express framework has been used here
multer has been used for file upload
once we click signout the cookies will be removed from browser


when we start the server it will send a mail to self which will contain the secret key
