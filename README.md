# Simple-CLI-Banking-Application
This is a simple command line interface (CLI) banking application that uses arrays to store usernames, passwords, and account balances. Users can log in, view their balance, transfer funds to other users, and withdraw funds from their account.

Here is a brief overview of the code:

usernames, passwords, and amount_in_account are three arrays that store usernames, passwords, and account balances respectively.

choose() method prints a menu and prompts the user to select an option. Based on the selected option, the method calls other methods such as login(), create(), and close().

login() method prompts the user to enter a username and checks if the username exists in the usernames array. If the username exists, it calls the login_password() method to check if the entered password matches the password stored in the passwords array.

login_password() method checks if the entered password matches the password stored in the passwords array. If the password matches, it calls the menu() method to display the banking options.

menu() method prints a menu and prompts the user to select an option. Based on the selected option, the method calls other methods such as transfer(), withdraw(), and choose().

transfer() method prompts the user to enter the name of the user they want to transfer money to and checks if the entered username exists in the usernames array. If the username exists, it calls the transfer_1() method to prompt the user to enter the transfer amount and transfer the funds.

transfer_1() method prompts the user to enter the transfer amount and checks if the entered amount is valid. If the amount is valid, it transfers the funds from the user's account to the recipient's account.

withdraw() method prompts the user to enter the amount they want to withdraw and checks if the entered amount is valid. If the amount is valid, it withdraws the funds from the user's account.
