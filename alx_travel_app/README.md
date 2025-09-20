# ALX Travel App

A Django REST API application for managing travel listings, bookings, and reviews.

## Features

- **Listings Management**: Create and manage travel accommodation listings
- **Booking System**: Book accommodations with date ranges and guest counts
- **Review System**: Rate and review listings
- **User Authentication**: Secure user management
- **REST API**: Full RESTful API with Swagger documentation

## Models

- **Listing**: Travel accommodations with title, description, location, and pricing
- **Booking**: User bookings with date ranges and guest information
- **Review**: User reviews and ratings for listings

## Technology Stack

- Django 5.2.4
- Django REST Framework
- SQLite Database
- CORS Headers for cross-origin requests
- Swagger/OpenAPI documentation with drf-yasg

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirement.txt
   ```
3. Run migrations:
   ```bash
   python manage.py migrate
   ```
4. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```
5. Seed the database (optional):
   ```bash
   python manage.py seed
   ```
6. Start the development server:
   ```bash
   python manage.py runserver
   ```

## API Documentation

Once the server is running, visit:
- Swagger UI: `http://localhost:8000/swagger/`
- ReDoc: `http://localhost:8000/redoc/`

## Project Structure

```
alx_travel_app/
├── listings/          # Main app for listings, bookings, and reviews
├── settings.py        # Django settings
├── urls.py           # URL configuration
└── requirement.txt   # Python dependencies
```

## Development

This project is part of the ALX Software Engineering program and demonstrates Django REST API development with proper model relationships and API endpoints.
