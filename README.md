# BAMAZON - Node.js & MySQL

## Overview

In this activity I created an Amazon-like storefront with the MySQL skills we learned this week. The app will take in orders from customers and deplete stock from the store's inventory. As a bonus task, you can program your app to track product sales across your store's departments and then provide a summary of the highest-grossing departments in the store.

## Submission Guide

This assignment is saved in GitHub. It is a CLI App, it is not deployed it to Heroku. 

## Instructions

### Challenge #1: Customer View 

1. I Created a MySQL Database called `bamazon`.

2. Then I created a Table inside of that database called `products`.

3. The products table have each of the following columns:

   * item_id (unique id for each product)

   * product_name (Name of product)

   * department_name

   * price (cost to customer)

   * stock_quantity (how much of the product is available in stores)

4. I Populated this database with different products. 

5. Then created a Node application called `bamazon.js`. Running this application will first display all of the items available for sale. Include the ids, names, and prices of products for sale.

6. The app should then prompt users with two messages.

   * The first should ask them the ID of the product they would like to buy.
   * The second message should ask how many units of the product they would like to buy.

7. Once the customer has placed the order, the application should check if your store has enough of the product to meet the customer's request.

   * If not, the app should log a phrase like `Insufficient quantity!`, and then prevent the order from going through.

8. However, if your store _does_ have enough of the product, you should fulfill the customer's order.
   * This means updating the SQL database to reflect the remaining quantity.
   * Once the update goes through, show the customer the total cost of their purchase.


