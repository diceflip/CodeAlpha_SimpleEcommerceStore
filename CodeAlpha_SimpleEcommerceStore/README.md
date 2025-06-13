# FlipWear - CodeAlpha Simple E-commerce Store (Task 1)

FlipWear is a simple e-commerce store application built with Django and Python as part of the CodeAlpha Full Stack Development Internship (Task 1). It features product listings, product details, a shopping cart, user registration/login, order processing, and an order history page.

## Features

*   User Authentication (Registration, Login, Logout)
*   Product Listing Page
*   Product Detail Page
*   Shopping Cart (Add, Update, Remove items, View Cart)
*   Session-based cart for guest users
*   Order Processing (Checkout with shipping information)
*   Order History for authenticated users
*   Admin panel for managing products and orders
*   Basic responsive design for improved viewing on different devices.

## Tech Stack

*   **Backend:** Python, Django
*   **Frontend:** HTML, CSS, JavaScript
*   **Database:** SQLite3 (for development)
*   **Version Control:** Git & GitHub

## Project Structure

CodeAlpha_SimpleEcommerceStore/
├── codealpha_ecommerce_store/ # Django project directory
│ ├── settings.py
│ ├── urls.py
│ └── ...
├── store/ # Django app for e-commerce logic
│ ├── templates/
│ ├── static/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── ...
├── media/ # For user-uploaded product images (sample images included)
├── venv/ # Virtual environment (in .gitignore)
├── .gitignore
├── manage.py
├── README.md
└── requirements.txt


## Setup and Run Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/CodeAlpha_SimpleEcommerceStore.git
    cd CodeAlpha_SimpleEcommerceStore
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Apply migrations:**
    ```bash
    python manage.py migrate
    ```

5.  **Create a superuser (for admin access):**
    ```bash
    python manage.py createsuperuser
    ```
    (Follow the prompts to set a username, email, and password)

6.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

7.  Open your browser and navigate to `http://127.0.0.1:8000/`.
    *   Admin panel: `http://127.0.0.1:8000/admin/`

## Screenshots (Optional but Recommended)

(Consider adding 2-3 key screenshots of your application, e.g., product list, cart, a product detail page. You can embed them in the README if you upload them to the repo or link to them if hosted elsewhere.)

## Live Demo (Optional)

*   **Live URL:** [e.g., `https://github.com/diceflip/CodeAlpha_SimpleEcommerceStore`](NOT YET ADDED)

## Author

*   Muhammed Basil
*   [LinkedIn profile](https://www.linkedin.com/in/muhammed-basil-a83443317/)]
*   [GitHub profile](https://github.com/diceflip)

