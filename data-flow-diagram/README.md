# 📂 Data Flow Diagram (DFD) Directory

This directory contains the **Data Flow Diagrams (DFDs)** for the Airbnb-like booking system. The DFDs illustrate how data moves through the system, from user input to backend processes and outputs.

## 🎯 Purpose

The purpose of this directory is to:

- Visualize the flow of data between system entities, processes, and data stores.
- Help developers and learners understand the backend operations.
- Serve as a reference for system design, testing, and documentation.

## 📝 Components of the DFD

1. **External Entities**  
   Represent actors outside the system that interact with it. Examples:  
   - `User` – registers, searches, books, and pays.  
   - `Admin` – manages properties and views bookings.  
   - `Payment Gateway` – processes payments.

2. **Processes**  
   Represent core backend operations:  
   - User Registration/Login  
   - Property Search/Browsing  
   - Booking Management  
   - Payment Processing  
   - Notification/Confirmation

3. **Data Stores**  
   Represent where data is stored:  
   - `User Data` – profiles, credentials  
   - `Property Data` – listings, availability  
   - `Booking Data` – reservations, statuses  
   - `Payment Data` – payment records, receipts

4. **Data Flows**  
   Arrows indicate the flow of data between entities, processes, and stores. Examples:  
   - User → Registration → User Data  
   - User → Search → Property Data → User  
   - User → Booking → Booking Data → Confirmation → User  
   - User → Payment → Payment Gateway → Payment Data → Confirmation → User

