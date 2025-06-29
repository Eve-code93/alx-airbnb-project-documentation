# 🏡 Airbnb Clone – Backend Features & Functionalities

## 📌 Objective

This document outlines the **core features and system functionalities** supported by the Airbnb Clone backend. The system is designed to mimic real-world Airbnb operations, with a focus on robust database interaction, secure authentication, and scalable APIs.

A corresponding visual diagram of these features is available as a PNG file:  
📁 `features-and-functionalities/airbnb_features.png`

---

## 🔐 1. User Management & Authentication

- User Registration (guest, host, admin)
- Secure Login (password hash)
- Role-based Access Control (RBAC)
- Session management with JWT
- Password reset and profile updates
- Email uniqueness enforcement

---

## 🏠 2. Property Listings

- Add new property (hosts only)
- Edit or delete listings (hosts only)
- View available properties (guests and admins)
- Detailed property view with price, location, and description
- Indexing by location, price range, or rating

---

## 📆 3. Booking System

- Book property (guests)
- View user bookings
- Cancel booking (status: pending/canceled/confirmed)
- Prevent double-booking for overlapping dates
- Booking price calculation (based on nights × price_per_night)

---

## 💳 4. Payments

- Link payments to bookings
- Supported payment methods: credit card, PayPal, Stripe
- Record payment date, amount, and method
- Verify booking payment before confirming

---

## 🌟 5. Reviews & Ratings

- Leave reviews after booking
- Rate properties from 1–5 stars
- View average property rating
- Admin moderation (optional)

---

## ✉️ 6. Messaging System

- Host-guest communication
- Send and receive messages via user ID
- Timestamped messages
- View message history with another user

---

## 🧠 7. Admin Functionalities

- View all users, bookings, and listings
- Delete or ban user accounts
- Access system logs or dashboard stats (optional future enhancement)

---

## 📈 8. Performance and Optimization

- UUIDs for scalable primary keys
- Indexed key fields (email, booking_id, property_id)
- Normalized database (up to 3NF)
- Scalable architecture ready for containerization and API deployment

---

## 🖼️ Visual Diagram

The full feature breakdown and their interrelationships are visually represented in the diagram below:

🖼️ [Click to view PNG](./airbnb_features.png)

You can edit the original source in [draw.io](https://draw.io) or [diagrams.net](https://www.diagrams.net) and re-export if updates are needed.

---

## 📁 File Structure

