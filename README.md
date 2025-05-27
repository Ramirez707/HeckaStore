HeckaStore

HeckaStore is a full-stack web application designed to serve as a digital marketplace for downloadable content. Built using Python (Flask) for the backend and HTML, CSS, and JavaScript on the frontend, the platform supports secure user authentication, seller uploads, and a shopping cart system with real-time feedback. HeckaStore allows customers to register, browse digital products, manage a cart, and check out seamlessly. Sellers can upload content with detailed descriptions and pricing, while role-based access control enforces secure feature separation between customers, sellers, and admins.

This project emphasizes clean architecture, performance-aware design, and real-world usability. It integrates frontend/backend systems and enforces security best practices, all while staying lightweight and scalable.

-------

Features

| Feature                  | Description                                                                 |
| ------------------------ | --------------------------------------------------------------------------- |
| Digital Product Listings | Browse and purchase downloadable items uploaded by verified sellers         |
| User Authentication      | Secure login, registration, and role-based access (customer, seller, admin) |
| Account Management       | Users can edit profiles, view upload history, and manage credentials        |
| Shopping Cart System     | Add/remove/update items with real-time total calculation and live feedback  |
| Checkout Workflow        | Reliable checkout interface for digital orders                              |
| Seller Upload Interface  | Authenticated sellers can upload products with images and pricing details   |
| Flash Messaging          | Provides real-time feedback for actions like login, upload, and checkout    |
| Form Validation          | WTForms integrated across all interactive pages                             |
| Secure File Uploads      | Handles product image uploads with sanitization and secure access paths     |

-------

Tech Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Python (Flask), WTForms, Jinja2 templates
* Database: SQLite (lightweight relational storage)
* Communication: REST-style routes and server-rendered templates

-------

Setup Instructions (Windows)

1. Install Python
   Download and install from: [https://www.python.org/](https://www.python.org/)

2. Install Dependencies
   In the terminal, navigate to your project folder and run:

   ```bash
   pip install -r "requirements.txt"
   ```

3. Run the App
   In the terminal, execute:

   ```bash
   flask run
   ```

   or

   ```bash
   python -m flask run
   ```

-------

Setup Instructions (Linux/macOS)

1. Install Python
   Download and install from: [https://www.python.org/](https://www.python.org/)

2. Install Dependencies
   Navigate to the project directory and run:

   ```bash
   pip3 install -r "requirements.txt"
   ```

3. Run the App

   ```bash
   flask run
   ```

   or

   ```bash
   python3 -m flask run
   ```

-------

Key Modules

| Module           | Description                                                                  |
| ---------------- | ---------------------------------------------------------------------------- |
| Auth             | Secure registration/login with session management and role assignment        |
| Product Listings | Displays digital goods uploaded by sellers with dynamic content rendering    |
| Cart             | Session-based cart tracking with quantity editing and subtotal calculation   |
| Checkout         | Handles final order processing with confirmation feedback                    |
| Upload           | Allows verified sellers to list new products with metadata and image support |
| Admin Panel      | (Optional) Admin-only view for overseeing user/product data                  |

-------

Author

Alex Ramirez
* https://www.linkedin.com/in/alex-ramirez-5b673a367

-------