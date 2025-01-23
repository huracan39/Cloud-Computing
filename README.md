optimisation of cart.py is because
Replaced 'eval' with 'json.loads': Ensures safe parsing of JSON instead of using insecure eval.
Error Handling: Added checks for invalid JSON and skipped malformed data.
Factory Method: Made 'Cart.load' a class method with default values for better structure.
Input Validation: Validated username and product_id in functions to prevent errors.
Simplified Logic: Removed redundant loops and streamlined data processing.
Better Naming and Docs: Improved readability with clear names and docstrings.
The updated code is safer, more efficient, and easier to maintain.

optimisation of browse.py is because
'Product.load' as a Class Method:
Converted 'load' to '@classmethod' for better structure and readability.
Added default values (id=0, name="") for safety.

Error Handling:
Added checks for missing product data in 'get_product'.
Validated required keys in add_product to prevent incomplete data.
Ensured update_qty checks if the product exists before updating.

List Comprehension:
Replaced for loop in list_products with a list comprehension for cleaner and more efficient code.

Improved Documentation:
Added meaningful docstrings for all functions, improving maintainability.

Result: The new code is safer, more efficient, and easier to read and maintain.
