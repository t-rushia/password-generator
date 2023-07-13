# password-generator

Using vanilla Javascript this is my take on a random password generator.

A single array containing all the characters that are standard in passwords is used for all possible values that should be chosen. The generate passwords will call a function password() onclick. I set two seperate variables passwordOne and passwordTwo which will both hold unique 15 character passwords.

Within the password() function I used a for loop to loop the iteration 15 times, in this case for the 15 case minimum password requirement. Within the for loop both variables passwordOne and passwordTwo select a random character from the array and += assign its value to the string. The loop will run 15 times until both passwords are generated and displayed on the web page.
