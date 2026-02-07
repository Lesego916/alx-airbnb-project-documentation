# Backend Requirements

## Authentication

POST /api/register  
POST /api/login  

Input: email, password  
Output: JWT token  

Passwords must be hashed.

---

## Property Management

POST /api/properties  
GET /api/properties  
PUT /api/properties/{id}  
DELETE /api/properties/{id}  

Fields:
- title
- description
- price
- location

---

## Booking System

POST /api/bookings  
GET /api/bookings  

Validations:
- Property must exist
- Dates must be available

---

## Performance

- API response < 500ms
- Secure authentication
- Scalable architecture
