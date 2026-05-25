IIT BHU Smart Room Scheduler

A professional smart room booking and scheduling system for faculty members with Google Calendar integration.

Features
Smart Room Booking
Book seminar halls, labs, and conference rooms
Prevent double booking
Detect busy/available rooms automatically
Google Calendar Integration
Login with Google
Automatically create calendar events
Sync meetings with Google Calendar
Send meeting invitations to attendees
Dashboard UI
Professional faculty dashboard
Calendar schedule view
Meeting timeline
Room availability status
Statistics cards
Main Functionalities
Schedule Meetings

Faculty can:

Select room
Choose date
Choose start and end time
Add meeting title
Add attendee email
Add faculty name/ID
Availability Checking

Before booking:

System checks conflicts
Shows:
AVAILABLE
BUSY
Google Calendar Sync

After successful booking:

Event created automatically
Visible in Google Calendar
Attendees receive invitation
Tech Stack
Frontend
HTML
CSS
JavaScript
Backend
Node.js
Express.js
Database
LowDB
API
Google Calendar API
Project Structure
room-booking-system/
│
├── public/
│   └── index.html
│
├── db.json
├── .env
├── package.json
├── server.js
└── README.md
Installation
Clone Repository
git clone https://github.com/YOUR_USERNAME/room-booking-system.git
Install Dependencies
npm install
Environment Variables

Create .env file:

CLIENT_ID=YOUR_GOOGLE_CLIENT_ID
CLIENT_SECRET=YOUR_GOOGLE_CLIENT_SECRET
REDIRECT_URI=http://localhost:3000/auth/google/callback
Run Project
node server.js

Server runs on:

http://localhost:3000
Google OAuth Setup
Enable APIs

Enable:

Google Calendar API

inside:

Google Cloud Console
Authorized Redirect URI

Add:

http://localhost:3000/auth/google/callback

For Render deployment:

https://YOUR_RENDER_URL.onrender.com/auth/google/callback
Main Routes
Route	Purpose
/	Dashboard
/auth/google	Google Login
/auth/google/callback	OAuth Callback
/book-room	Create Meeting
/check-availability	Check Room Status
/bookings	Show All Bookings
/api/bookings	JSON Booking Data
Future Improvements
MongoDB integration
Admin panel
Recurring meetings
Email notifications
PDF export
Analytics dashboard
QR attendance
Multi-user authentication
Developed For

Faculty scheduling and smart department room management.

Author

Srishti Pathak
