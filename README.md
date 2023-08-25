# Sellio - Your Online Marketplace

Sellio is a Django-based marketplace app that allows users to buy and sell items in a user-friendly environment. Sellers can easily list their items for sale, and buyers can browse, search, and connect with sellers. The app also features a messaging system that enables seamless communication between buyers and sellers.

## Features

- **User-friendly Interface:** Sellio provides an intuitive and responsive user interface that makes it easy for both buyers and sellers to navigate the platform.

- **Item Listings:** Sellers can create detailed listings for their items, including images, descriptions, and pricing information.

- **Browsing:** Buyers can browse through a wide variety of items, filter by categories or keywords, and view detailed information about each item.

- **Messaging:** A built-in messaging system allows buyers and sellers to communicate directly, making it simple to discuss item details, negotiate prices, and finalize transactions.

## Getting Started

These instructions will help you set up a local development environment for Sellio on your machine.

1. Clone this repository: `git clone https://github.com/yourusername/sellio.git`
2. Navigate to the project directory: `cd sellio`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Apply database migrations: `python manage.py migrate`
7. Create a superuser account: `python manage.py createsuperuser`
8. Run the development server: `python manage.py runserver`
9. Access the app at: `http://localhost:8000/`

## Contact

If you have any questions or feedback, feel free to reach out to me at demario326@gmail.com.

Thank you to FreeCodeCamp on their tutelage for helping me create Sellio!
