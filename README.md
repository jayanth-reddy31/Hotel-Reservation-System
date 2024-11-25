# 🏨 Hotel Reservation System

A console **Hotel Reservation System** built in Java, designed to streamline the booking process for hotel rooms. This project demonstrates effective use of **object-oriented programming (OOP)** concepts, while providing an intuitive interface for customers to search for rooms, make reservations, and view booking details.

---

## 📋 Features

### 1. **Search Available Rooms**
- Allows users to search for rooms based on the desired category (**Single, Double, Suite**).  
- Displays available rooms and ensures only unoccupied rooms are shown.  

### 2. **Make a Reservation**
- Customers can reserve available rooms in their preferred category.  
- Accepts customer details and payment method during the booking process.  
- Marks the reserved room as unavailable once the booking is completed.  

### 3. **View Booking Details**
- Retrieve and display booking information by entering the customer’s name.  

### 4. **Exit**
- Gracefully terminates the application with a thank-you message.  

## 📂 Project Structure
- **Room Class**: Represents a room with attributes like room number, category, price, and availability status.  
- **Booking Class**: Handles customer bookings and displays booking details.  
- **HotelReservationSystem Class**: Contains the main logic for room management, reservations, and user interaction.  

### Searching for Rooms:
Enter room category to search (Single/Double/Suite): Single
Available Rooms in category 'Single':
Room Number: 101
Room Number: 102

### Making a Reservation:
Enter your name: John Doe
Room 101 is available.
Price: 1000.0
Enter payment method: Credit Card
Reservation successful! Room 101 is booked.

### Viewing Booking Details:
Enter customer name to view booking: John Doe
Booking Details:
Customer Name: John Doe
Room Number: 101
Category: Single
Price: Rs. 1000.0
Payment Amount: Credit Card


## 📚 What I Learned
- Implementing **object-oriented principles** like encapsulation and abstraction.  
- Managing collections dynamically using Java’s `ArrayList`.  
- Creating seamless user interactions with menu-driven applications.  
- Validating inputs and handling edge cases for a smoother user experience.  
