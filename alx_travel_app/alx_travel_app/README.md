# ALX Travel App (0x01)

This project extends the previous travel app by adding a full REST API for managing Listings and Bookings.

## API Endpoints

The API is accessible at `/api/`.

### Listings
- **GET** `/api/listings/` - List all listings
- **POST** `/api/listings/` - Create a new listing
- **GET** `/api/listings/{id}/` - Retrieve a specific listing
- **PUT/PATCH** `/api/listings/{id}/` - Update a listing
- **DELETE** `/api/listings/{id}/` - Delete a listing

### Bookings
- **GET** `/api/bookings/` - List all bookings
- **POST** `/api/bookings/` - Create a new booking
- **GET** `/api/bookings/{id}/` - Retrieve a specific booking
- **PUT/PATCH** `/api/bookings/{id}/` - Update a booking
- **DELETE** `/api/bookings/{id}/` - Delete a booking

## Setup & Testing
1. Run migrations: `python manage.py migrate`
2. Start server: `python manage.py runserver`
3. Use Postman or curl to test the endpoints listed above.