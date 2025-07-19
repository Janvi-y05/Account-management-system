# Account-management-system
Here's a description you can use for the README file on GitHub for your project:

---

## 🏦 ABC Bank - Simple Python Banking Application

This is a simple terminal-based banking application that simulates basic ATM operations like deposit, withdraw, and balance check using Python.

### 📂 Project Structure

* **`main.py`**
  This is the entry point of the application. It handles user login, displays the welcome message, and routes user choices to the appropriate functionality like deposit, withdraw, and check balance.

* **`account_logic.py`**
  Contains the core logic for banking operations:

  * `deposit()` – Allows users to deposit an amount.
  * `withdraw()` – Allows users to withdraw funds.
  * `check_balance()` – Displays the current account balance.

  > ⚠️ Note: This file has a few bugs like `josn` instead of `json` and logic errors that need correction.

* **`validation.py`**
  Handles user authentication. Users must input a valid 4-digit PIN to proceed. It also invokes the menu once login is successful.

* **`display_menu.py`**
  Displays the list of available banking options to the user in a simple menu format.

* **`balance.json`**
  A JSON file used for storing and updating the user's balance. It initially contains:

  ```json
  {
    "balance": 3000
  }
  ```

---

Let me know if you'd like me to include fixed code examples or a "How to Run" section for this project.
