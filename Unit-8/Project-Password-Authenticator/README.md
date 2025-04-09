# Password Authenticator

View an example of this project running [here](https://codehs.com/sandbox/stefanfritz/password-auth-run/run)

## Description
Create a password authentication program that prompts the user to enter a username and password. The program should compare the entered username and password with a predefined correct username password and provide feedback on whether the entered credentials is correct or incorrect. The program should allow the user to try again a limited number of times before locking them out.

## Requirements
1. Set a predefined correct username and password that the user needs to guess.
2. Use a loop to allow the user to enter their username and password multiple times.
3. Prompt the user to enter their username and password and compare it with the correct username and password.
4. Use conditional branching (`if` statements) to provide feedback on whether the entered information is correct or incorrect.
5. Limit the number of attempts allowed and provide feedback when the user exceeds the maximum number of attempts.
6. Use the `break` statement to exit the loop when the correct password is entered.

## Extensions 

1. Create a second possible username and password combination, and allow a user to use those as well. Access should be granted only if the matching credentials are used
2. Research the `getpass` module and collect the user’s password in a safer way

---

### Example Output 1

```
Password Authentication Program

Enter your username: coderz012
Enter your password: 12345
Incorrect. You have 2 attempts left. Please try again.

Enter your username: coderz012
Enter your password: abcde
Incorrect. You have 1 attempt left. Please try again.

Enter your username: coderz012
Enter your password: password123
Correct password! Access granted.
```

### Example Output 2

```
Password Authentication Program

Enter your username: coderz012
Enter your password: qwerty
Incorrect. You have 2 attempts left. Please try again.

Enter your username: coderz012
Enter your password: 123456
Incorrect. You have 1 attempt left. Please try again.

Enter your username: coderz012
Enter your password: abcdef
Incorrect. Maximum number of attempts reached. Access denied.
```
