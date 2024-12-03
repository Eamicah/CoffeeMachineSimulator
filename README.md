# Coffee Machine Simulator

This Python program simulates a simple coffee machine, allowing users to order drinks, check available resources, and manage transactions. 

## Features

1. **Menu Options**:
   - Offers three types of coffee: **Espresso**, **Latte**, and **Cappuccino**.
   
2. **Resource Management**:
   - Tracks available ingredients: water, milk, and coffee.
   - Checks if there are enough resources to make the selected drink.

3. **Coin Processing**:
   - Accepts coins (quarters, dimes, nickels, pennies) and calculates the total payment.

4. **Transaction Handling**:
   - Checks if the payment is sufficient for the selected drink.
   - Calculates and returns change if applicable.
   - Updates the machine's profit after a successful transaction.

5. **Reporting**:
   - Displays the current resource levels and total money earned.

6. **Exit Option**:
   - The machine can be turned off by entering `off`.

## How to Use

1. **Run the Program**:
   Execute the script using a Python interpreter.

2. **Select an Option**:
   - Enter the name of the drink you'd like: `espresso`, `latte`, or `cappuccino`.
   - Enter `report` to view the current resource levels and profit.
   - Enter `off` to turn off the machine.

3. **Insert Coins**:
   - The program will prompt you to insert coins.
   - Enter the number of quarters, dimes, nickels, and pennies.

4. **Receive Your Coffee**:
   - If sufficient resources and payment are available, you'll receive your coffee.
   - If not, the machine will notify you and return your money.

## Requirements

- Python 3.x

## Code Structure

- **`MENU`**: Defines the available drinks, their ingredients, and costs.
- **`resources`**: Tracks the remaining quantities of water, milk, and coffee.
- **`sufficient_resources()`**: Checks if enough ingredients are available for the selected drink.
- **`process_coins()`**: Handles coin input and calculates the total amount inserted.
- **`is_transaction_successful()`**: Verifies if the payment is sufficient and updates profits.
- **`make_coffee()`**: Deducts used ingredients and prepares the coffee.

## Example Usage

```plaintext
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
how many quarters?: 10
how many dimes?: 0
how many nickels?: 0
how many pennies?: 0
Here is $0.5 dollars in change.
Here is your latte ☕️. Enjoy!
```

## Known Issues

- The program assumes valid input from the user.
- There might be inconsistencies in error handling for invalid input types.

Feel free to modify the script to add more features or improve functionality! 😊