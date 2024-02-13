Wormyreads(https://wormyreads.onrender.com)

Welcome to Wormyreads, a Django-based book review platform where users can explore, review, and add books to their wishlist. This project showcases a full-stack application deployed on Render, highlighting my ability to integrate frontend designs with backend efficiency. The application is directly connected to Render's PostgreSQL database, ensuring robust data management and dynamic content delivery.

Features

User Authentication: Sign up, log in, and manage user profiles.
Book Reviews: Users can post reviews for books and read reviews from others.
Wishlist Functionality: Add or remove books from a personal wishlist.
Responsive UI/UX: Adaptable interface for a seamless experience across all devices.
Secure Configuration: Utilizes environs for environment variable management, enhancing security.
Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Django, Django REST Framework
Database: PostgreSQL (Render)
Utilities: django-extensions, django-crispy-forms, Pillow, python-dotenv
Deployment: Render, Gunicorn, Whitenoise
Getting Started

To run Wormyreads locally, ensure you have Python installed on your machine. Follow these steps:

Clone the repository:

git clone https://github.com/yourusername/wormyreads.git
Navigate to the project directory:

cd wormyreads
Install the required dependencies:

pip install -r requirements.txt
Set up the database by running migrations:

python manage.py migrate
Create a .env file in the project root and configure the necessary environment variables, including the DATABASE_URL for PostgreSQL.

Start the development server:

python manage.py runserver
Access the application at http://127.0.0.1:8000/ in your browser.

Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Wormyreads is a testament to the dynamic capabilities of Django and its ecosystem. By leveraging a comprehensive suite of technologies, this project demonstrates a scalable approach to web application development and deployment.
