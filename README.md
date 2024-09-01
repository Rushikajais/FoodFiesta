# FoodFiesta

FoodFiesta is a fictional food delivery platform developed to simulate a collaborative software development environment using Git and GitHub. The project is inspired by real-world applications like Zomato and Swiggy, focusing on implementing core functionalities needed for a food delivery service.

## Features Developed

### 1. User Authentication (`feature-user-authentication`)
- **Purpose**: This feature allows users to create accounts, log in, and manage their profiles securely. It includes functionality for password recovery and user session management.
- **Key Components**:
  - User registration form
  - Login/logout functionalities
  - Password recovery system
- **Challenges Encountered**: Implementing secure password hashing and managing user sessions across different devices.

### 2. Order Tracking (`feature-order-tracking`)
- **Purpose**: Enables users to track their food orders in real time, from order placement to delivery. It also allows users to view their order history.
- **Key Components**:
  - Real-time order status updates
  - Order history page
  - Notifications for order status changes
- **Challenges Encountered**: Integrating a real-time tracking system and ensuring the order status is accurately updated across the platform.

### 3. Payment System (`feature-payment-system`)
- **Purpose**: Implements a secure payment gateway to handle transactions for food orders. Supports multiple payment methods, including credit/debit cards, UPI, and wallets.
- **Key Components**:
  - Payment gateway integration
  - Order confirmation and receipt generation
  - Transaction history for users
- **Challenges Encountered**: Ensuring secure payment transactions and handling payment failures gracefully.

## Branch Purpose

- **main**: The primary branch containing the stable version of the project after merging all feature branches.
- **feature-user-authentication**: Dedicated to developing the user authentication module, including registration, login, and profile management.
- **feature-order-tracking**: Focuses on building the order tracking system, allowing users to monitor their food delivery in real time.
- **feature-payment-system**: Implements the payment gateway and transaction handling functionalities required for processing orders.

## Challenges and Learnings

Throughout the development of FoodFiesta, several challenges were encountered, including handling merge conflicts, implementing secure authentication, and ensuring real-time updates. These challenges provided valuable learning experiences in collaborative development and using Git/GitHub effectively.

## How to Run the Project

To run the project locally, clone the repository and follow the setup instructions provided in each feature branch's documentation.

```bash
git clone https://github.com/your-username/FoodFiesta.git
cd FoodFiesta
