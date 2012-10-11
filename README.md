Login and logout system-header and footer:
Scheme:
A user can log in to his account by offering his email address and password. 
When a user clicks a login link in headers, he will be redirected to the login page (Slide 1).
A user can log out his account by clicking the embedded link in the footer. 
The user might be redirect to the homepage.

Slides and PHP files:  
Slide 1 and header or footer.
Login.php
logout.php
header.php
footer.php
Coding suggestions:

For login page:
Accept user email address and password.
Search for both items within the database. If they don't BOTH match, and error message will pop up saying something to the effect of,
"Incorrect login information provided."

For password help, the user will be asked to enter their email address to reset their password.

Log out page:
A static page that simply has a goodbye message to the user.


Contributors:
a. login.php Alabi, Adebanke
b. logout.php Alabi, Adebanke
c. header.php Alabi, Adebanke
d. footer.php Alabi, Adebanke