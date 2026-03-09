# Budget System📚💵💭

A simple **console-based personal finance management system** written in Java. This program allows users to manage multiple accounts, track spending by categories, set savings goals, and generate reports.

---

## Features

* **Account Management**

  * Open, deposit, withdraw, transfer funds between accounts
  * Lock/unlock accounts to prevent transactions
  * View account balances and all existing accounts

* **Spending Tracking**

  * Record spending by categories
  * Set budget limits per category
  * Display category spending and top spending categories
  * Alerts when budget limits are exceeded

* **Savings Goals**

  * Set savings goals with target amounts
  * Save funds toward goals
  * View goal progress
  * Automatic saving rules with percentage of account balances

* **Ledger & Reports**

  * Record all operations in a transaction ledger
  * Generate reports including account balances, goal status, and top spending categories

* **Reset System**

  * Clear all accounts, spending data, goals, and ledger

---

## Commands

| Command          | Description                                 |
| ---------------- | ------------------------------------------- |
| `HELP`           | Show list of available commands             |
| `OPEN`           | Open a new account                          |
| `DEPOSIT`        | Deposit money into an account               |
| `WITHDRAW`       | Withdraw money from an account              |
| `TRANSFER`       | Transfer money between accounts             |
| `BALANCE`        | Show account balance                        |
| `ACCOUNTS`       | List all accounts and balances              |
| `SPEND`          | Record spending in a category               |
| `CATEGORY`       | Show total spending in a category           |
| `TOP_CATEGORIES` | Show top spending categories                |
| `SET_GOAL`       | Set a savings goal                          |
| `SAVE`           | Save money towards a goal                   |
| `GOAL_STATUS`    | Check progress of a specific goal           |
| `GOALS`          | List all goals and progress                 |
| `LOCK`           | Lock an account                             |
| `UNLOCK`         | Unlock an account                           |
| `LEDGER`         | Show transaction history                    |
| `RESET`          | Reset all system data                       |
| `SET_BUDGET`     | Set budget for a category                   |
| `BUDGET_STATUS`  | Show spending vs budget                     |
| `RULE_SAVE`      | Set auto-saving percentage for all accounts |
| `APPLY_RULES`    | Apply auto-saving rules                     |
| `REPORT`         | Generate a system report                    |
| `EXIT`           | Exit the program                            |

---

## How to Run

1. Make sure you have **Java JDK** installed (version 8 or higher).

2. Clone this repository:

   ```bash
   git clone <your-repo-url>
   ```

3. Navigate to the project folder:

   ```bash
   cd <repo-folder>
   ```

4. Compile the Java program:

   ```bash
   javac BudgetSystem.java
   ```

5. Run the program:

   ```bash
   java BudgetSystem
   ```

6. Follow the console prompts to use the system.

---

## Example Usage

```text
Command: OPEN
Account: MyAccount
Account created🥳

Command: DEPOSIT
Account: MyAccount
Amount: 1000
Deposit complete💚

Command: SPEND
Account: MyAccount
Category: Food
Amount: 200
Withdraw complete💚
```

---

## Files in Repository

* `BudgetSystem.java` – Main program file.
* `Presentation_AizhanEsenbekova.pdf` – Presentation for the project.
* `Research_Brief_AizhanEsenbekova.pdf` – Research summary related to budgeting system.
* `Short_Report_PL2_AizhanEsenbekova.pdf` – Short report on project work.
* `test1.java`, `test2.java` – Sample test cases or experimental Java files.

---

## Notes

* The system uses `HashMap` and `HashSet` for efficient storage and retrieval of accounts, categories, and goals.
* All monetary values are stored as integers (KGS currency).
* This project can be extended to include file persistence or a graphical user interface.

---

