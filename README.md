This is a Flask-based RESTful API for managing customers, products, and orders for an e-commerce platform.
I used Post man for testing 
Endpoints

Customers

    GET /customers: Get all customers
    GET /customers/{id}: Get customer by ID
    POST /customers: Create a new customer
    PUT /customers/{id}: Update customer details
    DELETE /customers/{id}: Delete customer by ID

Products

    GET /products: Get all products
    GET /products/{id}: Get product by ID
    POST /products: Create a new product
    PUT /products/{id}: Update product details
    DELETE /products/{id}: Delete product by ID

Orders

    GET /orders: Get all orders
    POST /orders: Place a new order
    DELETE /orders/{id}: Delete order by ID
    PUT /orders/{id}: Update order details
