🧺 Laundry Management System

A full-stack Laundry Management System developed for a real-world client to simplify laundry bookings, customer management, and daily business operations.

The system is currently being used by the client in their day-to-day laundry business.

🚀 Features

- 👤 Customer registration and management --INPROGRESS
- 📦 Online laundry booking
- 📋 Booking and service management
- 🔔 Real-time Telegram notifications
- 📱 Instant notification to the laundry owner whenever a new booking is placed
- 🗂️ Booking status management
- 📊 Organized business workflow
- 📱 Responsive and user-friendly interface

🔔 Telegram Notification System

The system is integrated with a Telegram Bot to notify the laundry owner instantly when a customer creates a new booking.

Workflow

Customer
   ↓
Creates Laundry Booking
   ↓
Backend API
   ↓
Booking Stored in Database
   ↓
Telegram Bot
   ↓
📲 Owner Receives Notification

Example notification:

🔔 New Laundry Booking

👤 Customer: Rahul
📞 Phone: 9876543210
🧺 Service: Washing & Ironing
📅 Pickup Date: 06/09/2026
📍 Address: Indore

🛠️ Tech Stack

Frontend

- HTML
- CSS
- JavaScript
- Bootstrap

Backend

- Python
- Flask / FastAPI

Database

- MySQL

Integration

- Telegram Bot API

Deployment

- GitHub
- Render
- netlify

📌 Real-World Project

This project was developed for a real client and is currently being used to manage daily laundry bookings.

The main goal was to replace manual booking management with a centralized digital system and provide instant notifications to the business owner.

💡 What I Learned

- Full-stack application development
- REST API development
- Database integration
- Telegram Bot API integration
- Real-time notification workflow
- Deployment and environment configuration
- Working with real client requirements
- Building and maintaining a production-oriented application

🔐 Environment Variables

Sensitive credentials are stored using environment variables instead of being hard-coded.

DATABASE_URL=your_database_url
TELEGRAM_BOT_TOKEN=your_bot_token
TELEGRAM_CHAT_ID=your_chat_id

📂 Project Structure

laundry-management-system/
│
├── frontend/
├── backend/
├── requirements.txt
├── .env
├── .gitignore
└── README.md

🎯 Future Improvements

- Admin dashboard
- Customer booking history
- Automated booking status notifications
- Monthly revenue reports
- Customer SMS/WhatsApp notifications
- Advanced analytics

👨‍💻 Developer

Developed as a real-world full-stack project with a focus on automation, backend development, database management, and third-party API integration.
