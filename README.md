# ChatBook-A-Social-Media-App

ChatBook is a modern social media platform built using Python 3.9 and Django, designed to create a community-focused experience. Developed on Ubuntu 20.04.

# Key Features:

# Community Servers

Users can join servers (similar to Discord) based on their interests and engage in topic-specific chats.
Open and inclusive spaces for discussions and sharing.

# Media Sharing

Post images and videos with captions to share moments with everyone.

# Custom User Authentication

Users log in using their email addresses, powered by a custom user model for enhanced flexibility and security.

# Built-In Entertainment

Feeling bored? Play the in-app Snake Game and compete for high scores without leaving the app!

# Setup Instructions:

# Environment Setup:

Create a virtual environment:

python3 -m venv env  
source env/bin/activate  

Install dependencies from the requirements.txt file:


pip install -r requirements.txt  

# Database Migrations:

Make migrations and apply them:

python manage.py makemigrations  
python manage.py migrate  

# Admin Dashboard Access:

Create a superuser to access the admin panel:

python manage.py createsuperuser  
Run the Server:

# Start the development server:

python manage.py runserver  

With ChatBook, users can stay connected, express themselves, and have fun—all in one platform!