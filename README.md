````md
# Room Booking System

A Smart Room Booking System built using Node.js, Express.js, Google Calendar API, and LowDB.

## Features

- Google OAuth Login
- Google Calendar Integration
- Dynamic Room Booking
- Prevent Double Booking
- View All Bookings
- Cancel Booking
- Local Database Storage

## Technologies Used

- Node.js
- Express.js
- Google APIs
- LowDB
- HTML
- CSS
- JavaScript

## Installation

```bash
npm install
````

## Run Project

```bash
node server.js
```

Open:

```bash
http://localhost:3000
```

## Environment Variables

Create `.env` file:

```env
CLIENT_ID=your_google_client_id
CLIENT_SECRET=your_google_client_secret
REDIRECT_URI=http://localhost:3000/auth/google/callback
```

## Google Calendar Setup

* Enable Google Calendar API
* Configure OAuth Consent Screen
* Create OAuth Client ID
* Add Redirect URI

## Future Improvements

* Admin Dashboard
* Email Notifications
* MongoDB Integration
* React Frontend
* Google Meet Link Generation

## Author

Srishti Pathak

```
```
