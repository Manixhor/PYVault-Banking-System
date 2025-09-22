# PYValut-Banking-System 

## Description:
The following implementation symbolizes a **banking system** etc. simulation using classes, inheritance, and user interaction. The user is capable of opening accounts, depositing, withdrawing, and viewing their deposits/withdraws. This program is developed using **object-oriented programming** principles using two major classes: `User` and `Bank`.

### Main Components:

1. **User class**: This class symbolizes a user and has user attributes such as `name` and `age`. The `__init__` method initializes these attributes and finally, the `show_details` method displays the users with basic info such as their age and name. The class acts as a **parent class** for the `Bank` class.

2. **Bank class**: The `Bank` class inherits from the `User` class, the `Bank` class stores additional attributes such as `balance`, `total_deposits`, and `total_withdraws`. The Bank class contains the following methods:
   
   * `show_info()`: This will display their remaining balance.
   * `deposit()`: This will allow the user to deposit cash and will require an updated balance and increases the user's number of deposits.
   * `withdraws()`: This will allow the user to withdraw cash checking for balance before proceeding.
   * Class-level attributes `total_deposits` and `total_withdraws` will keep track of the total number of deposits and the total number of withdrawals for all instances of a `Bank` class.
3. **User Interaction**: The `options()` function provides an interactive menu in which users can:

   * Check available balance
   * Deposit or withdraw money
   * See the total number of deposits and withdrawals
   * Quit the system

4. **Bank Creation**: The `bank_creation()` function allows a user to establish an initial deposit, when establishing their bank account. The system will allow the user accounts to be either **one or two user accounts**. If two users are registered, each user can then participate in the banking system.

### Program Flow:

The user is prompted to make user accounts and enter their positions, and then use their account through a series of options to interact with their account. The loop will continue until the user decides to quit.

This structure provides a simple simulation of a banking system with basic account management functionality.


### Installation:

1. clone the repository:
    git clone https://github.com/Manixhor/PYVault-Banking-System.git
2. Navigate into the project directory:
    cd PYValut-Banking-System
3. Create a virtual environment (optional but recommended):
    python3 -m venv venv
4. Activate the virtual environment:
    -> On Mac/Linux:
        source venv/bin/activate
    -> On Windows:
        .\venv\Scripts\activate
