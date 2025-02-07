# Coffee_Maker_Machine_Simulation

This is a simple coffee maker machine simulation written in Python. The simulation allows users to order different types of coffee, check the machine's resources, and handle payments.

## Project Structure


## Files

- `coffee_maker.py`: Contains the `CoffeeMaker` class which models the coffee machine.
- `main.py`: The main script to run the coffee maker simulation.
- `menu.py`: Contains the `Menu` and `MenuItem` classes which model the menu and its items.
- `money_machine.py`: Contains the `MoneyMachine` class which handles the financial transactions.

## Classes

### CoffeeMaker

- `report()`: Prints a report of all resources.
- `is_resource_sufficient(drink)`: Checks if there are enough resources to make the drink.
- `make_coffee(order)`: Deducts the required ingredients from the resources.

### MenuItem

- `__init__(name, water, milk, coffee, cost)`: Initializes a menu item with its name, ingredients, and cost.

### Menu

- `get_items()`: Returns all the names of the available menu items.
- `find_drink(order_name)`: Searches the menu for a particular drink by name.

### MoneyMachine

- `report()`: Prints the current profit.
- `process_coins()`: Returns the total calculated from coins inserted.
- `make_payment(cost)`: Returns True when payment is accepted, or False if insufficient.

## How to Run

1. Make sure you have Python installed on your machine.
2. Run the `main.py` script:

```sh
python main.py