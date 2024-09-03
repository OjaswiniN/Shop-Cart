# Simple Shopping Cart System

## Overview
This project implements a basic shopping cart system using C++. It provides functionality for users to view available products, add items to a cart, view the cart's contents, and complete the checkout process.

## Components

### Product Class
- Represents individual products.
- Attributes: ID, name, and price.
- Methods: Includes methods for retrieving product information and display name.

### Cart Class
- Manages a collection of products added by the user.
- Methods: 
  - `addProduct(Product &product)`: Adds a product to the cart.
  - `viewCart()`: Displays the contents of the cart and the total price.
  - `isEmpty()`: Checks if the cart is empty.
  - `getTotal()`: Calculates the total price of items in the cart.

### Main Functionality
1. **Display Available Products**:
   - Lists all products with their names and prices.
   - Users can choose a product to add to their cart by entering its short name.

2. **Add to Cart**:
   - Allows users to select a product and add it to their cart.

3. **View Cart**:
   - Displays the items currently in the cart and their total price.

4. **Checkout**:
   - Users pay for their items. The system checks if the amount paid is sufficient and provides change if necessary.
