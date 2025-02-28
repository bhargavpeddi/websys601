# MIDTERM_PROJECT 

## Project Description

This project processes JSON order data for a dosa restaurant to improve its order management system. The script reads raw order data, extracts and formats customer information, and analyzes menu item sales. It then generates two structured JSON files:

customers.json: Contains customer names and formatted phone numbers.

items.json: Lists menu items with their prices and the number of times they were ordered.
The project helps the restaurant better understand its customers and optimize menu item tracking.

## Input data

The project uses an input JSON file named example_orders.json, which contains raw order data. A new set of orders (in the same format) will be used for evaluation.

## Objectives
1.Read JSON Orders:
The program reads the JSON file provided as a command-line argument.

2.Generate Customers Data (customers.json):

Extracts customer names and phone numbers.
Stores them in a JSON file with phone numbers as keys and names as values.

3.Generate Items Data (items.json):

Extracts item names, their prices, and the number of times each item has been ordered.
Stores them in a JSON file with item names as keys and a dictionary containing price and order count.