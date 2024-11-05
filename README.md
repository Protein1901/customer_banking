# Customer Banking System

## Overview
The **Customer Banking System** is a Python-based application that allows users to calculate and track the interest earned on savings and Certificate of Deposit (CD) accounts. Users can input their account balances, interest rates, and the number of months for which they want to calculate interest, and the application will output the interest earned and the updated balance.

## Project Structure
The project consists of the following files:
- **`Account.py`**: This file contains the `Account` class, which defines methods for setting the balance and interest.
- **`savings_account.py`**: Contains the `create_savings_account()` function, which calculates the interest earned on a savings account, updates the balance, and returns both.
- **`cd_account.py`**: Contains the `create_cd_account()' function, which calculates the interest earned on a CD account, updates the balance, and returns both.
- **`customer_banking.py`**: The main script that prompts the user for inputs, calls the appropriate functions, and displays the results.

## Features
-**Interest Calculation**: Calculates interest for savings and CD accounts based on user-provided balances, interest rates, and the duration in months.
-**User Interaction**: Prompts users for input and displays formatted results.
-**Object-Oriented Design**: Uses a reusable `Account` class for account management.

## Installation
To run this project, you need to have Python 3.x installed on your system.

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/customer_banking.git
    cd customer_banking```

2. **Ensure all project files** (`Account.py`, `savings_account.py`, `cd_account.py`, `customer_banking.py`) are in the same directory.
## Usage
Run the `customer_banking.py` script to start the program:
```bash
python customer_banking.py

## User Inputs
The program will prompt the user for the following details:
•	Savings Account:
•	Initial balance
•	Annual interest rate (APR)
•	Number of months
•	CD Account:
•	Initial balance
•	Annual interest rate (APR)
•	Number of months

## Example Interaction
Enter the savings account balance: 1000
Enter the annual interest rate (APR) for the savings account: 5
Enter the number of months: 12
Savings Account: Interest earned: $50.00, Updated balance: $1050.00

Enter the CD account balance: 5000
Enter the annual interest rate (APR) for the CD account: 4
Enter the number of months: 6
CD Account: Interest earned: $100.00, Updated balance: $5100.00

## How It Works
1. Account Class:
The base class is used to represent an account, with methods to set the balance and interest.
2. create_savings_account():
Takes the balance, interest rate, and months as input, calculates the interest earned, updates the balance, and returns both.
3. create_cd_account():
Similar to the create_savings_account() function but specific to CD accounts.
4. customer_banking.py:
The main script handles user input, calls the functions, and displays the interest earned and updated balances.

## Contributing
Contributions are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or further questions, please contact sps.cdri@gmail.com.

