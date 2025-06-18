# 🎟️ Event Ticketing MVP

A full-stack MVP for a digital event ticketing system. This application allows users to register, log in, view events, book tickets, and access their booked tickets with basic membership functionality.

## 📁 Project Structure
event-ticketing-mvp/
├── client/      # React frontend
└── server/      # Node.js + Express + MongoDB backend

---

## 🔧 Tech Stack

### Frontend:
- React.js
- React Router DOM
- Axios
- QRCode Generator

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT (Authentication)
- Bcrypt.js (Password hashing)
- CORS
- dotenv

---

## 🔐 Features

- User registration and login with JWT-based authentication
- Passwords stored securely using bcrypt hashing
- View upcoming events
- Book tickets for events
- View purchased tickets
- Middleware to protect authenticated routes
- QR Code ticket rendering

---
### Future Enhancements
	-	Admin dashboard for event creation and management
	-	Payment integration (Stripe/Razorpay)
	-	Email ticket confirmations
	-	Ticket scanning with QR validation
---
## Acknowledgements

This is an independent MVP project to demonstrate end-to-end web development skills using the MERN stack.
