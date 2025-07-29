# Super-Market-Billing-System

Purpose:
This Python program simulates a simple supermarket billing system, which handles customer details, lets customers select items to purchase from an available inventory, manages stock updates, and generates a detailed receipt.

How it works:

1. Inventory Initialization:
   A dictionary named inventory stores products as keys with a tuple (price, stock) as the value.
   
2. Customer Details Input:
   The system asks the user to enter:
   - Customer Name
   -Phone Number
   -Address
These details are later printed on the receipt.

3. Item Selection Loop:
   -The user is repeatedly prompted to enter the item they want to buy (case-insensitive).
   -Input 'no' ends the shopping loop.
   -For every valid item, the customer enters the desired quantity.
   -The program checks if enough stock is available. If not, it asks for a lower quantity.
   -Purchased items and quantities are recorded in the cart dictionary.
   -The stock in the inventory is decreased accordingly after each purchase.

4. Receipt Generation:
   Once shopping finishes:
   -The system prints customer information.
   -Displays all purchased items, their quantities, price per unit, and total price per item.
   -Calculates and prints the final total amount.
   -If no items were bought, it notifies the user.
   -Thanks the customer at the end.     
