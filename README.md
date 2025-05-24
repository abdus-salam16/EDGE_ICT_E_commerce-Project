# Django E-Commerce Project

This is a full-featured e-commerce web application built with **Django**. It includes features such as product listings, user authentication, cart, orders, vendor management, blog integration, and more.

## Project Structure

e_commerce/
├── blog/ # Blog app for articles and updates
├── customer/ # Customer-related functionality (profiles, addresses)
├── e_commerce/ # Main project configuration
├── store/ # Product catalog and store logic
├── userauths/ # Custom user authentication system
├── vendor/ # Vendor profiles, products, and dashboards
├── db.sqlite3 # SQLite database
└── manage.py # Django project manage

## Features

-  Custom user authentication (`userauths`)
-  Product management (`store`)
-  Vendor support (`vendor`)
-  Customer profiles (`customer`)
-  Blog system (`blog`)
-  Shopping cart and checkout (TBD)
-  Order management (TBD)

## Requirements

- Python 3.8+
- Django 3.2+
- SQLite (default DB)
- Bootstrap 5 (for frontend templates)

## Installation

1. **Clone the repository**

git clone https://github.com/your-username/EDGE_ICT_E_commerce-Project.git
cd e_commerce

*Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate
Install dependencies

pip install -r requirements.txt
If requirements.txt is missing, you can generate it using:
pip freeze > requirements.txt

*Run migrations

python manage.py makemigrations
python manage.py migrate
Create a superuser

python manage.py createsuperuser
Run the development server

python manage.py runserver
Now visit: http://127.0.0.1:8000
