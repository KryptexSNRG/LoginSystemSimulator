# Login System Simulator
A Python project that simulates a basic login system with built-in password strength validation.

This program allows a user to create login credentials, checks whether the chosen password is strong enough, and then simulates a login process with limited attempts before the account is locked.

## Features

- Prompts the user to create a username and password
- Analyzes password strength before allowing setup
- Checks for:
  - minimum length
  - uppercase letters
  - lowercase letters
  - numbers
  - special characters
  - common weak passwords
  - excessive repeated characters
- Classifies passwords as **Weak**, **Moderate**, or **Strong**
- Gives feedback on how to improve weak passwords
- Simulates a login process with username and password verification
- Locks the account after 4 failed attempts
- Stores and displays incorrect login attempts after lockout

## How it works

1. The user creates a username and password.
2. The password is checked using password strength rules.
3. If the password is weak or moderate and has issues, the user is asked to try again.
4. Once a valid password is accepted, the program starts the login simulation.
5. The user has up to 4 attempts to enter the correct username and password.
6. If all attempts fail, the account is locked and incorrect attempts are displayed.

## How to run

Make sure Python is installed, then run:

```bash
python login_simulator.py
