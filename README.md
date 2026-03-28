bBANK MANAGEMNT SYSTEM
The Bank Management System Database is a Python program that simulates essential banking operations in a simple, menu‑driven format. It allows users to create accounts, deposit and withdraw money, check balances, calculate interest for savings accounts, and display all account details. The system enforces rules such as maintaining a minimum balance of 500 and restricting interest calculations to savings accounts, making it closer to real‑world banking logic.

🔑 What is Used in the Project
• 	Python Lists and Dictionaries
• 	Accounts are stored in a list, with each account represented as a dictionary containing account number, name, balance, and type.
• 	This structure makes it easy to manage multiple accounts and perform CRUD operations.
• 	Functions for Modularity
• 	 → Creates a new account with validation checks.
• 	 → Adds money to an account.
• 	 → Withdraws money while ensuring minimum balance.
- calculate_interest() → Computes yearly interest for savings accounts.
- display_all() → Shows all accounts in the system.
- Conditional Logic
- Used to enforce rules like minimum deposit, minimum balance, and interest calculation only for savings accounts.
- Loops and Menu‑Driven Interface
- A continuous while True loop provides an interactive menu for users to select operations.
- Ensures the program runs until the user chooses to exit.
- Basic Financial Logic
- Minimum deposit requirement (₹500).
- Minimum balance enforcement during withdrawals.
- Interest rate applied to savings accounts (7.25% annually).
