## README: Food Truck Ordering System
# Overview
This project implements an interactive food truck ordering system using Python. The system allows customers to select items from a menu, specify quantities, and view their final order and total cost. The menu is structured as a nested dictionary, and the order details are stored in a list of dictionaries.

# Requirements
Python 3.x
How to Run the Program
Ensure you have Python installed on your system.
Save the script as food_truck_ordering.py.
Open a terminal or command prompt and navigate to the directory where the script is saved.
Run the script using the command:
python food_truck_ordering.py

# Menu Structure
The menu is defined as a nested dictionary with categories, items, and prices. Below is the structure:
menu = {
    "Snacks": {
        "Cookie": .99,
        "Banana": .69,
        "Apple": .49,
        "Granola bar": 1.99
    },
    "Meals": {
        "Burrito": 4.49,
        "Teriyaki Chicken": 9.99,
        "Sushi": 7.49,
        "Pad Thai": 6.99,
        "Pizza": {
            "Cheese": 8.99,
            "Pepperoni": 10.99,
            "Vegetarian": 9.99
        },
        "Burger": {
            "Chicken": 7.49,
            "Beef": 8.49
        }
    },
    "Drinks": {
        "Soda": {
            "Small": 1.99,
            "Medium": 2.49,
            "Large": 2.99
        },
        "Tea": {
            "Green": 2.49,
            "Thai iced": 3.99,
            "Irish breakfast": 2.49
        },
        "Coffee": {
            "Espresso": 2.99,
            "Flat white": 2.99,
            "Iced": 3.49
        }
    },
    "Dessert": {
        "Chocolate lava cake": 10.99,
        "Cheesecake": {
            "New York": 4.99,
            "Strawberry": 6.49
        },
        "Australian Pavlova": 9.99,
        "Rice pudding": 4.99,
        "Fried banana": 4.49
    }
}

# Program Flow
1. Initialize the Order List:

The order_list stores dictionaries containing menu item names, prices, and quantities.

2. Greeting and Menu Category Selection:

The program welcomes the customer and prompts them to select a menu category.
It displays the available categories and their corresponding numbers.

3. Item Selection and Quantity Input:

Once a category is selected, the program lists the items in that category.
The customer selects an item by typing its number and specifies the quantity.

4. Order Confirmation and Continuation:

The customer can choose to continue ordering or finalize their order.

5. Order Summary and Total Calculation:

The program displays the ordered items, their prices, quantities, and the total cost.

# Key Functions and Features
Dynamic Menu Display: The program dynamically displays menu categories and items based on the nested dictionary structure.
Input Validation: The program validates user inputs to ensure they are numbers and within the valid range.
Order Management: It allows adding multiple items to the order and specifies quantities for each item.
Total Calculation: The program calculates the total cost of the order, including the quantity of each item.

# Conclusion
This interactive food truck ordering system efficiently handles menu navigation, item selection, and order summarization. It ensures a seamless and user-friendly experience for customers.
