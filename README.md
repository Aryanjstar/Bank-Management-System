This C++ program implements a **simple banking system** using object-oriented programming principles. It allows users to create and manage bank accounts with the following features:

### Features:
1. **Account Creation:**
   - Users can open a new account by entering their name, address, account type (savings or current), and an initial deposit.

2. **Deposit Money:**
   - Users can deposit additional funds into their account.

3. **Withdraw Money:**
   - Users can withdraw funds from their account, with the remaining balance updated accordingly.

4. **Account Details Display:**
   - Users can view their account details, including the name, address, account type, and current balance.

5. **Menu-Driven Interface:**
   - A user-friendly, menu-driven interface allows users to select various operations such as opening an account, depositing money, withdrawing money, viewing account details, or exiting the program.

### Implementation Highlights:
- The program uses a `bank` class containing private data members (`name`, `add`, `y`, `balance`, `amount`) and public member functions for account operations.
- The `switch` case construct is used to handle user choices from the menu.
- `system("cls")` and `system("color")` commands are used for clearing the screen and enhancing visual appeal.
- Input handling for account operations is provided using standard input/output streams (`cin`, `cout`).
- The program runs in a loop, allowing users to perform multiple operations until they decide to exit.

### Limitations:
- No validation for negative deposits or withdrawals exceeding the account balance.
- The `balance` is stored as an integer, limiting precision for fractional amounts.
- No persistent storage; all data is lost when the program exits.

This program serves as a foundational example of building interactive console-based applications with classes in C++.
