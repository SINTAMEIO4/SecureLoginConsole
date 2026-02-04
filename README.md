# Login System - Java Console Application

A simple secure console-based login program written in Java.  
It accepts a username and password, gives the user *3 attempts* to log in correctly, and displays appropriate messages after each try.

*Features:*
- Secure password input (no characters shown while typing — uses java.io.Console)
- 3 login attempts before locking the account
- Clear feedback messages for success, failure, and lockout
- Hardcoded demo credentials:  
  *Username:* admin  
  *Password:* secret123

## Screenshots

### Successful Login (1st attempt)
![Successful Login](screenshots/successful-login.png)

### Failed Attempts → Account Locked
![Account Locked](screenshots/account-locked.png)

(Add your actual screenshot files here — see instructions below)

## How to Run

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- NetBeans IDE (or any Java IDE / command line)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/LoginSystem.git
