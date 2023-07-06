# Project-IV

# Compulsory Task - README

This project involves coding a Python program that reads data from the text file inventory.txt and performs various operations on the data for presentation to managers. The program uses a provided template file named inventory.py, which includes a class named Shoe with attributes such as country, code, product, cost, and quantity. Several methods are defined inside the Shoe class, including get_cost, get_quantity, and __str__.

## Table of Contents

1. [Project Setup](#project-setup)
2. [Shoe Class](#shoe-class)
   - [get_cost Method](#get-cost-method)
   - [get_quantity Method](#get-quantity-method)
   - [__str__ Method](#__str__-method)
3. [Functions](#functions)
   - [read_shoes_data Function](#read-shoes-data-function)
   - [capture_shoes Function](#capture-shoes-function)
   - [view_all Function](#view-all-function)
   - [re_stock Function](#re-stock-function)
   - [seach_shoe Function](#seach-shoe-function)
   - [value_per_item Function](#value-per-item-function)
   - [highest_qty Function](#highest-qty-function)
4. [Main Menu](#main-menu)

## Project Setup <a name="project-setup"></a>

To get started with this project, follow these steps:

1. Open the provided template file named inventory.py.
2. Ensure you have a text file named inventory.txt that contains the data to be processed.
3. Implement the required functionalities and menu within the main section of the code.

## Shoe Class <a name="shoe-class"></a>

The Shoe class represents a shoe object and includes the following attributes:

- country
- code
- product
- cost
- quantity

### get_cost Method <a name="get-cost-method"></a>

- The `get_cost` method returns the cost of the shoes.

### get_quantity Method <a name="get-quantity-method"></a>

- The `get_quantity` method returns the quantity of the shoes.

### __str__ Method <a name="__str__-method"></a>

- The `__str__` method returns a string representation of the Shoe class.

## Functions <a name="functions"></a>

The program includes several functions outside the Shoe class to perform various operations on the shoe data.

### read_shoes_data Function <a name="read-shoes-data-function"></a>

- The `read_shoes_data` function opens the inventory.txt file, reads the data, creates a Shoe object with the data, and appends the object to the shoe list.
- Error handling using try-except is implemented in this function.
- The first line of the file is skipped.

### capture_shoes Function <a name="capture-shoes-function"></a>

- The `capture_shoes` function allows the user to input data about a shoe and uses this data to create a Shoe object, which is then appended to the shoe list.

### view_all Function <a name="view-all-function"></a>

- The `view_all` function iterates over the shoe list and prints the details of each shoe using the __str__ method.
- Optional: The data can be organized in a table format using Python's tabulate module.

### re_stock Function <a name="re-stock-function"></a>

- The `re_stock` function finds the shoe object with the lowest quantity, which indicates the shoes that need to be restocked.
- The user is prompted to add a quantity for restocking, and the quantity for that shoe is updated in the file.

### seach_shoe Function <a name="seach-shoe

-function"></a>

- The `seach_shoe` function searches for a shoe in the shoe list using the shoe code provided.
- If a matching shoe is found, the function returns the shoe object.

### value_per_item Function <a name="value-per-item-function"></a>

- The `value_per_item` function calculates the total value for each item by multiplying the cost and quantity of each shoe.
- The calculated values are printed on the console for all the shoes.

### highest_qty Function <a name="highest-qty-function"></a>

- The `highest_qty` function determines the product with the highest quantity among the shoes and prints that shoe as being for sale.

## Main Menu <a name="main-menu"></a>

- The main section of the code should include a menu within a while loop that allows the user to execute each function mentioned above.
- Be creative in designing and implementing the menu to provide a user-friendly and interactive experience.

