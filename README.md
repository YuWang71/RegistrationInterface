# RegistrationInterface
Basic Sign Up/In  Interface

This is my first PHP x Mysql project.
There are serval steps to complete this thing.
Based on the XAMPP, this is easy to implement the website by PHP and Mysql at localhost.
1. Setup the database. I only need 4 information when user registers, name, email, password, and Confirm password.
In the future, I would like to try some things new in the database. For example, user can add photo or picture as icon.
And show the password strength.
2. Register interface (Register.PHP). The construct is very easy.
Also, I setup the error message. When user inputs something not valid, the error alarm will be shown up,
to tell where input is invalid.  There 4 variables to connect with server.php. And server.php will connect to the database, like bridge.
Duplicate username. If there are 2 users register with same username, it is not available for now.
3. Login interface (login.PHP). You already have account, just click the login, then will jump to the login interface.
As register interface, I also setup the error alarm for it.
4. After register/login, it will simply jump to the index.php (Nothing for now).


Need to update:
1. Password strength.
2. User photo.
