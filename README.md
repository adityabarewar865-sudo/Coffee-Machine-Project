 ☕ Coffee Machine Project.☕

☕ A beginner-friendly Python Coffee Machine simulator that allows users to order drinks, processes payments, manages resources, and generates reports.


## ✨ Features

- Offers three coffee options: Espresso, Latte, and Cappuccino.
- Checks if enough ingredients are available before preparing a drink.
- Accepts coin input and processes payments.
- Calculates and returns change when necessary.
- Updates the machine's resources after each successful order.
- Displays a report of the remaining ingredients and total money earned.
- Allows the machine to be turned off using the `off` command.
- Beginner-friendly Python project demonstrating dictionaries, functions, loops, conditional statements, and resource management.

---

## 📂 Project Structure

```text
Coffee-Machine/
├── main.py
└── README.md
```

---

## ▶️ How to Run

```bash
python main.py
```

---

## 🖥️ Example Output

```text
What would you like?
(espresso/latte/cappuccino): latte

Please insert coins.

How many quarters?: 10
How many dimes?: 2
How many nickels?: 0
How many pennies?: 0

Here is $0.50 in change.

☕ Here is your latte. Enjoy!

--------------------------------------

What would you like?
(espresso/latte/cappuccino): report

Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $3.50

--------------------------------------

What would you like?
(espresso/latte/cappuccino): off
```

---

## 🛠️ Technologies Used

- Python 3
- Dictionaries
- Functions
- Loops
- Conditional Statements
- User Input
- Resource Management
