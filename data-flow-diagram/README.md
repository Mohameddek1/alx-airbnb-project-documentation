# 🔁 Airbnb Clone – Data Flow Diagram (DFD)

This directory contains the **Data Flow Diagram (DFD)** that illustrates how data moves throughout the backend of the Airbnb Clone system. The DFD is a visual representation of how inputs are transformed into outputs through various processes and data stores within the backend architecture.

---

## 🎯 Objective

To demonstrate how user data, bookings, property listings, and payments flow through the system, highlighting all major components, entities, and interactions. This helps ensure efficient system design and data integrity.

---

## 🧩 Key DFD Components

### 1. **External Entities**
- **Guest** – Interacts with listings, makes bookings, and payments.
- **Host** – Manages property listings and availability.
- **Admin** – Monitors platform operations.

### 2. **Processes**
- `User Registration & Authentication`
- `Property Listing Management`
- `Search & Filter Listings`
- `Booking Management`
- `Payment Processing`
- `Review System`
- `Notification System`

### 3. **Data Stores**
- `User Database`
- `Property Database`
- `Booking Database`
- `Payment Records`
- `Review Logs`
- `Notifications Queue`

### 4. **Data Flow**
- Registration data flows into `User Database`
- Listing data flows into `Property Database`
- Booking actions modify `Booking Database` and generate notifications
- Payments flow through `Payment Gateway` and are logged in `Payment Records`
- Review submissions are saved to `Review Logs`

---

## 🖼️ Diagram

📁 `data-flow-diagram/data-flow.png`  
This diagram was created using **Draw.io** and exported as a PNG. It illustrates the interaction of entities, processes, data stores, and the flow between them.

---

## 📂 Directory Structure

