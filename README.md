# Uber Fleet - Full-Stack Ride-Sharing Platform

**Uber Fleet** is a high-performance, real-time ride-sharing application built with the MERN stack. It provides a seamless experience for both passengers and drivers, featuring real-time location tracking, automated fare estimation, and secure authentication.

## 🚀 Features

### For Passengers
- **Real-Time Ride Tracking**: Watch your driver approach in real-time.
- **Fare Estimation**: Get instant price estimates for different vehicle types (Car, Auto, Moto).
- **Secure OTP Verification**: Ensures you're getting into the right vehicle.
- **Intuitive UI**: Smooth animations and a professional design for easy booking.

### For Drivers (Captains)
- **Ride Requests**: Receive and accept passenger requests in real-time.
- **Location Updates**: Keep passengers informed with continuous location synchronization.
- **Earnings Tracking**: (In development) Monitor your trip history and earnings.

## 🛠 Tech Stack

- **Frontend**: React.js, Tailwind CSS, GSAP, Socket.io-client.
- **Backend**: Node.js, Express.js, Socket.io, JWT, Mongoose.
- **Database**: MongoDB.
- **APIs**: Google Maps Platform (Geocoding, Distance Matrix, Places Autocomplete).

## 📦 Installation

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas account
- Google Maps API Key

### Setup
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd uber-video
   ```

2. **Backend Configuration**:
   - Navigate to `Backend/`
   - Create a `.env` file based on `.env.example`.
   - Add your `DB_CONNECT`, `JWT_SECRET`, and `GOOGLE_MAPS_API`.
   - Run `npm install`.

3. **Frontend Configuration**:
   - Navigate to `frontend/`
   - Create a `.env` file based on `.env.example`.
   - Add your `VITE_BASE_URL` (usually `http://localhost:4000`).
   - Run `npm install`.

## 🚀 Running the Project

1. **Start the Backend**:
   ```bash
   cd Backend
   npm start
   ```

2. **Start the Frontend**:
   ```bash
   cd frontend
   npm run dev
   ```

## 📄 License
This project is licensed under the ISC License.
