# 🏠 Airbnb Clone – Features and Functionalities

This document provides a high-level overview of the core features and backend functionalities required for the Airbnb Clone project. It is based on the official project requirements and is designed to guide backend implementation and system architecture planning.

---

## 📌 Overview

The backend system must support secure user authentication, property listing and management, a robust booking mechanism, integrated payments, and administrative oversight. This architecture ensures a scalable, secure, and user-friendly experience.

---

## 🧩 Core Features

### 1. **User Management**
- User registration and login
- JWT-based authentication
- OAuth login (Google, Facebook – optional)
- Profile updates (name, photo, contact info)
- Role assignment (Guest, Host, Admin)

### 2. **Property Management**
- Hosts can create, update, and delete listings
- Listings include details like location, description, images, price, and availability
- File storage support for listing images

### 3. **Search and Filtering**
- Users can search listings by location, price, guest capacity, and amenities
- Pagination for efficient data handling
- Sorting by rating, price, or availability

### 4. **Booking System**
- Guests can book available properties for specific dates
- System prevents double bookings
- Bookings include status tracking (pending, confirmed, cancelled, completed)
- Booking cancellation rules

### 5. **Payment Integration**
- Secure checkout using Stripe or PayPal
- Currency support
- Automatic payouts to hosts
- Payment status tracking

### 6. **Review System**
- Guests can rate and review properties after completed stays
- Reviews are linked to specific bookings
- Hosts can respond to reviews

### 7. **Notifications**
- Email and in-app notifications for:
  - Booking confirmations
  - Cancellations
  - Payment updates

### 8. **Admin Dashboard**
- Monitor and manage:
  - Users
  - Listings
  - Bookings
  - Payments and reviews
- Resolve flagged issues or complaints

### 9. **Security**
- JWT authentication and authorization
- Role-based access control (RBAC)
- Rate limiting and input validation
- Encrypted data handling

---

## 📄 Visual Diagram

The visual representation of the system’s features and relationships is included in this directory:

📁 `features-and-functionalities/features-and-functionalities.png`

---

## 📂 Directory Structure

