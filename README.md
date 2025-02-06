# Publisher: Rachit Nigam
# Car Rental System

## Overview
The **Car Rental System** is a full-stack web application built using the **MERN (MongoDB, Express, React, Node.js) stack**. This platform allows users to browse, book, and manage car rentals seamlessly.

## Features
- **User Authentication & Authorization** (JWT-based login & signup)
- **Car Listings** (View available cars with details & pricing)
- **Car Booking System** (Rent cars for specific durations)
- **Admin Dashboard** (Manage cars, bookings, and users)
- **Responsive Design** (Optimized for mobile & desktop devices)

## Tech Stack
### Frontend:
- React.js (with Redux for state management)
- Tailwind CSS or Bootstrap for styling
- Axios for API requests

### Backend:
- Node.js with Express.js
- MongoDB with Mongoose ORM
- JWT-based authentication

## Installation & Setup
### Prerequisites:
- Node.js & npm installed
- MongoDB running locally or using MongoDB Atlas

### Steps:
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/car-rental-system.git
   cd car-rental-system
   ```

2. **Install dependencies**
   ```sh
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Configure environment variables**
   Create a `.env` file in the `backend` directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET=your_stripe_secret_key
   CLOUDINARY_API_KEY=your_cloudinary_key
   ```

4. **Run the application**
   ```sh
   cd backend
   npm start
   ```
   In another terminal:
   ```sh
   cd frontend
   npm start
   ```

5. **Access the application**
   Open `http://localhost:3000` in your browser.

## API Endpoints
| Method | Endpoint        | Description                |
|--------|----------------|----------------------------|
| GET    | /api/cars      | Fetch all cars            |
| POST   | /api/bookings  | Create a new booking      |
| GET    | /api/users     | Fetch user details        |
| POST   | /api/auth      | User authentication       |

## Future Enhancements
- Mobile app integration
- AI-based car recommendations
- Multi-language support

## License
This project is licensed under the MIT License.

## Author
Rachit Nigam (https://github.com/your-rachit7224)

