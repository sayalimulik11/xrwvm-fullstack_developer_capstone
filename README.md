# Dealership Review Application

## Project Name
**Best Cars - Full Stack Dealership Review Application**

## Description
A full stack web application where users can browse car dealerships across the US,
read customer reviews, and post their own reviews. Built as the capstone project fo.
the IBM Full Stack Developer Professional Certificate.

## Features
- User registration, login and logout
- View all dealerships and filter by state
- View dealer details and customer reviews
- Post reviews for dealerships (with sentiment analysis)
- Car makes and models managed through the Django admin
- Static "About Us" and "Contact Us" pages

## Tech Stack
- **Backend:** Django (Python), Node.js/Express, MongoDB
- **Frontend:** React, HTML, CSS, Bootstrap
- **Microservices:** Sentiment analyzer (Flask)
- **Deployment:** Docker, Kubernetes / IBM Code Engine

## Project Structure
- `server/` - Django project (djangoapp, frontend, database)
- `server/frontend/` - React application and static pages
- `server/database/` - Dealerships and reviews service (Node.js + MongoDB)
- `server/djangoapp/microservices/` - Sentiment analyzer service

## Setup
1. Clone the repository
2. `cd server && pip install -r requirements.txt`
3. `python3 manage.py makemigrations && python3 manage.py migrate`
4. `python3 manage.py runserver`

## Author
Your Name - sayali mulik.
