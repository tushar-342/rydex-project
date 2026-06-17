# 🚗 Rydex - AI-Powered Vehicle Booking Platform

Rydex is a modern full-stack vehicle booking platform inspired by Uber and Ola, designed to provide a seamless ride-booking experience through real-time tracking, AI-powered communication, secure authentication, online payments, and role-based management dashboards.

Built with a scalable architecture, Rydex enables users to book rides, partners/drivers to manage operations, and administrators to monitor and control the entire platform efficiently.

## 🌐 Live Demo

https://rydex-project-liart.vercel.app/

## 📌 Features

### 👤 User Dashboard

* Secure registration and login using Google OAuth
* Browse and book available vehicles
* Real-time ride tracking
* Booking history and ride management
* AI-powered assistance and support
* Secure online payments

### 🚖 Partner / Driver Dashboard

* Partner registration and onboarding
* Vehicle management system
* Ride request handling
* Real-time booking updates
* AI-assisted communication with users
* Earnings and booking overview
* Video KYC verification workflow

### 🛡️ Admin Dashboard

* User management
* Partner and driver management
* Booking monitoring and control
* Verification management
* Platform analytics and insights
* Centralized operational control

## 🗺️ Real-Time Live Tracking

Rydex uses Socket.io to provide real-time communication between users and partners.

Features include:

* Live vehicle location updates
* Real-time ride status synchronization
* Instant booking notifications
* Dynamic trip monitoring

## 🤖 AI-Powered Communication

Integrated AI assistance helps users and partners communicate efficiently by:

* Providing instant support
* Assisting with booking-related queries
* Enhancing user engagement
* Improving communication workflows

## 📹 Video KYC Verification

To improve trust and security, driver verification is performed through Video KYC.

Benefits:

* Driver identity verification
* Secure onboarding process
* Fraud prevention
* Improved platform reliability

## 💳 Online Payment Integration

Integrated Razorpay payment gateway enables:

* Secure transactions
* Instant payment processing
* Booking confirmation workflow
* Reliable payment management

## 🔐 Authentication & Security

* Auth.js (NextAuth) Authentication
* Google OAuth Integration
* Role-Based Access Control (RBAC)
* Protected Routes
* Secure Session Management

## 🎨 Modern User Experience

* Responsive Design
* Mobile-Friendly Interface
* Framer Motion Animations
* Smooth Navigation
* Optimized Performance

## 🏗️ System Architecture

The platform follows a Role-Based Access Control (RBAC) model:

### User

Can book rides, track vehicles, communicate with partners, and manage bookings.

### Partner / Driver

Can manage vehicles, handle bookings, complete verification, and communicate with customers.

### Admin

Can monitor platform activities, manage users and partners, verify accounts, and oversee operations.

## 🛠️ Technology Stack

### Frontend

* Next.js
* React.js
* Tailwind CSS
* Framer Motion

### Backend

* Next.js API Routes
* Node.js

### Database

* MongoDB
* Mongoose

### Authentication

* Auth.js (NextAuth)
* Google OAuth

### Real-Time Communication

* Socket.io

### Video Services

* ZEGOCLOUD

### Payment Gateway

* Razorpay

### Deployment

* Vercel

## 📂 Project Setup

### Clone Repository

```bash
git clone https://github.com/tushar-342/rydex-project.git
```

### Navigate to Project Directory

```bash
cd rydex-project
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file:

```env
MONGODB_URI=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
NEXTAUTH_SECRET=
NEXTAUTH_URL=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
ZEGO_APP_ID=
ZEGO_SERVER_SECRET=
```

### Run Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

## 🚀 Future Enhancements

* AI-powered ride recommendations
* Dynamic pricing engine
* Driver rating and review system
* Fleet management analytics
* Push notifications
* Predictive demand forecasting
* Advanced AI customer support

## 📈 Project Highlights

✅ Real-Time Vehicle Tracking

✅ AI-Powered Communication

✅ Video KYC Verification

✅ Secure Google Authentication

✅ Razorpay Payment Integration

✅ User Dashboard

✅ Partner Dashboard

✅ Admin Dashboard

✅ Role-Based Access Control

✅ Responsive UI/UX

✅ Production-Ready Architecture

## 👨‍💻 Author

Tushar Kumar

GitHub: https://github.com/tushar-342

LinkedIn:https://www.linkedin.com/in/tushar-kumar-he-him-3rd-44aa09281/

## 📄 License

This project is developed for educational, portfolio, and learning purposes.
