# Simple Django Restaurant Web App

A simple yet elegant Django web application designed for restaurants. The app provides functionalities like viewing the menu and booking for customers.

## Features

- **Menu Viewing**: Allows customers to browse through the available dishes, their descriptions, and prices.
- **Table Booking**: Provides an easy interface for customers to book tables in advance, ensuring a seamless dining experience.

## Getting Started

### Prerequisites

- Python (version 3.8 or newer recommended)
- pip
- Virtual Environment (recommended)

### Installation

1. Clone the repository:
git clone https://github.com/Artemii1/Django-sample.git
cd restaurant-app

2. (Recommended) Set up a virtual environment:
python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate

3. Install the required packages:
pip install -r requirements.txt

4. Run migrations:
python manage.py migrate

5. Start the development server:
python manage.py runserver

Visit `http://127.0.0.1:8000/` in your browser to access the app.

## Usage

- Navigate to `/menu/` to view the available dishes.
- Visit `/book/` to book a table. Simply fill in your details and select a suitable date and time.

## Acknowledgments

- Thanks to [Django Documentation](https://docs.djangoproject.com/) for being an invaluable resource.
