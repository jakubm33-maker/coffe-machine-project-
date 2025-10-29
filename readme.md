☕ Coffee Machine (Python Console App)

A simple, menu-driven console application that simulates a coffee vending machine.
Users can select a drink, insert coins, and receive their order if resources and payment are sufficient.

🧩 Features

Interactive CLI menu for choosing coffee type: espresso, latte, cappuccino

Tracks available resources (water, milk, coffee beans)

Handles coin input and calculates total money inserted

Validates transactions and returns change

Generates machine reports (report command)

Supports machine shutdown with the off command

⚙️ How it works

The program loads a predefined MENU dictionary containing ingredient requirements and prices.

Each drink request checks resource availability (is_resource_sufficient).

The user inserts coins (process_coins) — quarters, dimes, nickels, and pennies.

Payment is validated (is_transaction_successful); if accepted, resources are updated and coffee is served.

Profit and remaining ingredients are displayed with report.

🧠 Concepts demonstrated

Functions with parameters and return values

Dictionaries and nested data structures

Loops and conditional statements

Global variables and resource management

Basic user input/output handling

Procedural program structure and modular design
