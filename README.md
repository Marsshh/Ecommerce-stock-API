# CRUD in Python with FastAPI and PostgreSQL

This project implements a CRUD (Create, Read, Update, Delete) using FastAPI as a web framework and PostgreSQL as a database.

## Functionalities:

- **Route /product GET**: Returns a JSON list with all the information of the products from the `products` table.
- **Route /product/{id} GET**: Returns a JSON object with the information of the product whose ID matches the ID provided as a parameter.
- **Route /product/ POST**: Allows adding a new product to the database and returns a JSON object with the message "Successfully added".
- **Route /product/{id} PUT**: Allows modifying a product in the database defined by the ID provided as a parameter. Returns a JSON object with the message "Successfully modified".
- **Route /product/{id} DELETE**: Allows deleting a product from the database and returns a JSON object with the message "Successfully deleted".
- **Route /productAll/ GET**: Returns a JSON list with the following information: category name, subcategory name, product name, product brand, and price.

- **Bulk product loading**:
  - **Route /loadProducts POST**: Used to perform a bulk load of categories, subcategories, and products into the database via a CSV file.
