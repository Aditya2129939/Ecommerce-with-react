Full-Stack E-Commerce Application
Objective
Develop a basic e-commerce application with user authentication, product listing, and a shopping cart to demonstrate proficiency in both frontend and backend development, including database and API integration.

Figma Design
View the design for this project on Figma: Figma Design

Requirements
Backend Development
API Development:

Node.js and Express: Create a RESTful API with the following endpoints:
User Authentication:
POST /register: Register a new user.
POST /login: Authenticate a user and return a JWT.
Product Management:
GET /products: Retrieve a list of products.
GET /products/:id: Retrieve details of a specific product.
POST /products: Add a new product (admin only).
PUT /products/:id: Update an existing product (admin only).
DELETE /products/:id: Delete a product (admin only).
Shopping Cart:
GET /cart: Retrieve the user's shopping cart.
POST /cart: Add an item to the cart.
DELETE /cart/:id: Remove an item from the cart.
Database:

Use MongoDB to store user information, product data, and shopping cart details.
Ensure proper schema design and relationships.
Authentication & Authorization:

Use JWT for user authentication.
Implement middleware to protect routes (e.g., adding, updating, deleting products should be admin-only).
Frontend Development
React Application:

Develop a React frontend to interact with the backend API with the following components:
AuthForm: Registration and login forms.
ProductList: Display a list of products.
ProductDetail: Display details of a selected product.
Cart: Display the user's shopping cart and allow item removal.
State Management:

Use Redux for state management, including handling user authentication state and shopping cart state.
Routing:

Use React Router to manage navigation between pages (e.g., home, product details, cart, login).
Functionality
User Authentication:

Users should be able to register, log in, and log out.
Authenticated users should be able to view and interact with their shopping cart.
Product Management:

Display a list of products on the home page.
Allow users to view detailed information about a product.
Allow admins to add, update, and delete products.
Shopping Cart:

Users should be able to add products to their cart.
Display the user's cart with options to remove items.
Bonus (Optional)
Order Management:

Implement an order system where users can place orders for the items in their cart.
Add endpoints and components to manage orders (view order history, order details).
Product Search and Filtering:

Implement search functionality to find products by name.
Add filtering options (e.g., by category, price range).
Persistent Storage:

Save the user's cart to local storage to persist it across sessions.
