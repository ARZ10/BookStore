# Book Store Application

## Overview

The Book Store Application is a GUI-based system for managing a virtual bookstore. It features two user roles—Owner and Customer—allowing for efficient management of book inventories, customer profiles, and transactions within a single-window interface.

## Key Features

### Login System
- **Initial Access**: The application launches with a login screen.
- **Owner Login**: Owners can access the system using default credentials (`username: admin`, `password: admin`).
- **Customer Login**: Customers use their unique credentials for access.

### Owner Dashboard
- **Navigation**: Post-login, owners reach the owner-start-screen with options to navigate to either the 'Books' or 'Customers' sections, or to log out.

### Books Management
- **Inventory Control**: Owners can add to or delete books from the inventory.
- **Display and Interaction**: The 'Books' section shows available inventory with names and prices, allowing for the addition of new books or deletion of existing ones.

### Customers Management
- **Profile Management**: Owners can add or remove customer profiles.
- **Customer List**: Displays registered customers with details such as usernames, passwords, and loyalty points, with options to add or delete profiles.

### Customer Dashboard
- **User Interface**: Upon login, customers view their dashboard showing their name, accrued points, and status (Silver or Gold).

### Book Purchases
- **Shopping**: Customers can browse and select books for purchase.
- **Transactions**: Purchases can be made with currency via the 'Buy' button, or by redeeming loyalty points for discounts through the 'Redeem points and Buy' button.
- **Loyalty Points**: Points are earned based on expenditure and can be redeemed for discounts.

## Technical Details
- **Framework**: Developed in Java with JavaFX for the GUI.
- **Data Management**: Book and customer data are stored and managed through `books.txt` and `customers.txt`.
- **Session Handling**: Data is saved upon exit and loaded at startup.

## Conclusion
The Book Store Application offers an intuitive and comprehensive platform for bookstore management, merging inventory and customer management with transactional capabilities. This project showcases the application of Java and JavaFX in creating functional, user-friendly software.

## Tools Used
- Java
- JavaFX
- Visual Paradigm (for UML Diagrams)
