# LogIn-SignUp

Firstly, after having all the files/folders locally, enter the following command at the directory- /login npm install

Then, download MongoDb compass locally, create an account and connect it using the mongo url. (Make sure mongodb is setup properly on your system.)
After successful connection, create a database with the name "e-comm" and collection "loginCredentials". (You can change these names from mongoConfig.js file)

Then go to code editor, change the directory to /login/main 
And enter the following command- node form.js

Go to your default browser and search for http://localhost:8000/

You are now ready to go. As you SignUp for the first time, you will be able to see those credentials on mongo compass.

Later if you enter wrong credentials for login page, you will find the error msg on the terminal even though the browser takes you to the Home page.

Thank You.
