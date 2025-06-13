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

```
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
```


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

## Screenshots 

![1](https://github.com/user-attachments/assets/9b738c0c-8c16-4443-9be0-44fd150bf262)

![2](https://github.com/user-attachments/assets/930c1de5-9538-4f0b-bd5a-64fdb300467a)

![3](https://github.com/user-attachments/assets/f2120f23-633d-4d16-92a2-f9da0d27d22b)

![4](https://github.com/user-attachments/assets/138d1776-0265-48c1-948c-3dee13203f81)

![5](https://github.com/user-attachments/assets/d518cc00-5210-43c4-8101-6b63ca286ae7)

![6](https://github.com/user-attachments/assets/79ec939c-8897-4268-8166-16d58b645840)

![7](https://github.com/user-attachments/assets/3456e240-ad8c-4f05-8321-df829242eb41)

## Live Demo (SOON)

*   **Live URL:** - [DEMO LINK](https://diceflip.pythonanywhere.com/)

## Author

*   Muhammed Basil
*   [LinkedIn profile](https://www.linkedin.com/in/muhammed-basil-a83443317/)
*   [GitHub profile](https://github.com/diceflip)

