# Mangolazo - Soccer Game Scheduling App

A modern web application for scheduling and managing soccer games, tracking match statistics, and managing league dues.

## Features

- User Profiles with authentication
- Team Management System
- Game Scheduling & RSVP System
- League Dues Management
- Match Statistics Tracking

## Tech Stack

### Frontend
- React + Next.js
- TailwindCSS
- Axios for API calls

### Backend
- Node.js + Express
- JWT Authentication
- SQLite Database
- Dues Management System

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install frontend dependencies
   cd frontend
   npm install

   # Install backend dependencies
   cd ../backend
   npm install
   ```

3. Set up environment variables:
   - Create `.env` files in both frontend and backend directories
   - Copy the example environment variables and fill in your values

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend server
   cd frontend
   npm run dev
   ```

## Environment Variables

### Backend
```
PORT=3001
JWT_SECRET=your_jwt_secret
DATABASE_URL=sqlite://./database.sqlite
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
SENDGRID_API_KEY=your_sendgrid_key

# Dues Management Configuration
TEAM_REGISTRATION_FEE=500
REFEREE_FEE_PER_GAME=100
REGULAR_SEASON_GAMES=10
```

### Frontend
```
NEXT_PUBLIC_API_URL=http://localhost:3001
```

## Dues Management

The app helps team captains manage league dues by:
1. Tracking team registration fees
2. Managing referee fees per game
3. Splitting costs among team members
4. Monitoring payment status
5. Sending payment reminders

## License

MIT 