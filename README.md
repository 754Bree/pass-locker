# Password-Locker
## Author

 [Briana Odhiambo](https://github.com/754Bree/pass-locker.git)

## Description

 Pass-locker is an app that saves passwords.

## User Stories
 The user would like to.... :
 * To create an account for the application or log into the application.
 * Store existing acounts login details for various accounts.
 * Generate new password for an account that is yet to be registered and store it with the account name.   
 * Delete stored account login details.
 * Copy credentials to the clipboard


## Installation / Setup instruction

#### The application requires the following installations to operate 
* python3.9
* pip
* pyperclip

#### Cloning

* Open Terminal 

* git clone ```https://github.com/754Bree/pass-locker.git```

* cd Password

* code . or atom . based on the text editor you have.

### Running the Application
* To run the application, open the cloned file in terminal and run the following commands:

        
        python run.py
* To run test for the application
        python creditentials_test.py

## Behaviour Driven Development
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
|Open the application on the terminal | Run the command ```python run.py```|Hello Welcome to your Accounts Password manager... <br>* CA ---  Create New Account * LI ---  Have An Account |
|Select  CA| input username and password| Hello ```username```, Your account has been created succesfully! Your password is: ```password```|
|Select LI  | Enter your password and username you signed up with| Abbreviations menu to help you navigate through the application|
|Store a new credential in the application| Enter ```CC```|Enter Account, username, password<br>choose ```tp``` to enter your password or ```gp``` for the application to generate a password for you |
|Display all stored credentials | Enter ```DC```|A list of all credentials that has been stored or ```You don't have any credentials saved yet``` |
|Find a stored credential based on account name|Enter ```FC```| Enter the Account Name you want to search for and returns the account details|
|Delete an existing credential that you don't want anymore|Enter ```D```|Enter the account name of the Credentials you want to delete and returns true if the account has been deleted and false if the account doesn't exixt|
|Exit the application| Enter ```EX```| The application exits|

## Technologies Used

* python3.9


## Contact Information 
Email  me at [brianaodhiambo754@gmail.com]

## License
* *MIT License:*
* Copyright (c) 2022 **Briana Odhiambo**
