# Console-based ATM

A simple console-based ATM application that simulates basic banking operations (create account, login, balance enquiry, deposit, withdrawal, transfer, mini-statement, change PIN, and exit). This project is intended as a learning/demo application for practicing core programming concepts such as input/output, control flow, data structures, and simple persistence.

> NOTE: Update the sections below (Language, build/run instructions, and file paths) to match the actual implementation in this repository.

## Features
- Create a new account with PIN and initial deposit
- Login using account number and PIN
- Check account balance
- Deposit money
- Withdraw money (with simple balance checks)
- Transfer funds to another account
- View mini-statement (recent transactions)
- Change PIN
- Simple console menu-driven UI
- Minimal/no external dependencies (pure standard library)

## Project status
This README is a general template. Please update the "How to run" section to reflect the actual language and instructions used in this repository (Java / Python / C++ / C# etc.). If the app persists data (e.g., to a file or database), document the persistence details and file locations.

## Prerequisites
- A supported language runtime / compiler:
  - Java 8+ (javac & java) OR
  - Python 3.6+ (python3) OR
  - g++ for C++ (C++11+)
- Terminal / command prompt

## How to run

Replace the instructions below with the actual commands for this repository.

If the project is in Java:
```bash
# compile
javac -d out src/*.java

# run (replace Main with your actual main class and package if any)
java -cp out Main
```

If the project is in Python:
```bash
# run
python3 atm.py
```

If the project is in C++:
```bash
# compile
g++ -std=c++11 -o atm main.cpp

# run
./atm
```

If the repository contains a build tool (Maven, Gradle, Makefile), use the provided build commands instead.

## Usage (typical console flow)
1. Start the app.
2. Main menu displays options:
   - Create new account
   - Login
   - Exit
3. After login, user sees an account menu:
   - View balance
   - Deposit
   - Withdraw
   - Transfer
   - Mini-statement
   - Change PIN
   - Logout / Exit
4. Enter numeric choices and amounts when prompted. Confirm operations if required.

## Sample interaction
(Representative — modify to match actual application prompts)

```
Welcome to Console ATM
1) Create account
2) Login
3) Exit
> 1
Enter your name: John Doe
Set a 4-digit PIN: 1234
Initial deposit: 5000
Account created. Your account number is: 1001

> 2
Enter account number: 1001
Enter PIN: 1234
Login successful.

Account Menu:
1) Balance Enquiry
2) Deposit
3) Withdraw
4) Transfer
5) Mini-statement
6) Change PIN
7) Logout
> 3
Enter amount to withdraw: 2000
Withdrawal successful. New balance: 3000
```

## Data & Persistence
- If this project currently stores accounts and transactions in memory, data will be lost when the program exits.
- If file-based persistence is implemented, document the file path/format (e.g., CSV, JSON, plain text) and how to back up/restore data.

## Project structure (suggested)
- src/            — source files
- data/           — optional persistent storage files (accounts, transactions)
- README.md
- LICENSE

Adjust this section to reflect the actual repository layout.

## Tests
- If unit tests exist, document the test runner and how to execute tests (e.g., `mvn test`, `pytest`, or `make test`).

## Contributing
Contributions, bug reports, and suggestions are welcome.
- Fork the repo
- Create a feature branch: `git checkout -b feature/foo`
- Commit your changes: `git commit -m "Add foo"`
- Push to the branch: `git push origin feature/foo`
- Open a pull request describing your changes

Please include a clear description of what you changed and why.

## License
If you have a license, put it here (e.g., MIT). If not, add a LICENSE file or choose an appropriate license.

Example:
```
MIT License
```

## Contact
Maintainer: OmPrakash-source
- GitHub: https://github.com/OmPrakash-source

---

If you'd like, I can:
- Customize this README to match the exact language and run instructions by reading the repository source.
- Add badges (build/test/coverage) and sample screenshots or GIFs of the console session.
Tell me if you want me to inspect the repo and update the README with precise build/run steps and the actual project structure.
