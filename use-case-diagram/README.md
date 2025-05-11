# Use Case Diagram for Airbnb Clone

## Overview
This document presents the use case diagram for the Airbnb Clone application, visualizing the interactions between users and the system across key functionalities.

## Diagram
The use case diagram below illustrates how different actors (Guest Users, Host Users, and Admin Users) interact with the system's core features:

![Use-case-diagram](https://github.com/user-attachments/assets/d897b071-4e17-4ed6-a42e-686d76f1d3dc)
 Use Case Diagram]

## Actors
The system interacts with three main types of users:

### Guest User
Users who browse and book properties on the platform.

### Host User
Users who list and manage properties for rent.

### Admin User
System administrators who oversee the platform's operation.

### Payment System
External payment processing services that handle financial transactions.

## Key Use Cases

### User Management
- **Register Account**: New users can create accounts as either guests or hosts
- **Login to Account**: Existing users can authenticate and access the system
- **Manage Profile**: Users can update their personal information and preferences
- **Recover Password**: Users can reset their passwords when forgotten

### Property Management (Host)
- **Create Property Listing**: Hosts can add new properties to the platform
- **Update Property Details**: Hosts can modify property information and availability
- **Delete Property Listing**: Hosts can remove properties from the platform
- **Manage Availability Calendar**: Hosts can set dates when properties are available

### Booking System (Guest)
- **Search Properties**: Guests can find properties using various search criteria
- **View Property Details**: Guests can access detailed information about properties
- **Book Property**: Guests can reserve properties for specific dates
- **Cancel Booking**: Guests can cancel their existing reservations
- **View Booking History**: Guests can see their past and upcoming bookings

### Payment System
- **Process Payment**: The system handles payment for bookings
- **Process Refund**: The system manages refunds for canceled bookings
- **Payout to Host**: The system transfers funds to hosts after completed stays

### Review System
- **Write Review**: Guests can review properties they've stayed at
- **Respond to Review**: Hosts can reply to guest reviews
- **View Reviews**: All users can read property reviews

### Communication
- **Send Message**: Users can communicate with each other
- **Receive Notifications**: Users get alerts about bookings, messages, etc.

### Admin Functions
- **Moderate Listings**: Admins can review and approve/reject property listings
- **Manage Users**: Admins can oversee user accounts
- **Monitor Transactions**: Admins can track financial activities
- **Generate Reports**: Admins can create system performance reports

## Relationships
The diagram shows how actors interact with specific use cases and how some use cases include or extend others. For example:

- The "Book Property" use case includes the "Process Payment" use case
- The "Cancel Booking" use case may include the "Process Refund" use case
- The "Register Account" use case extends to either Guest or Host registration

This comprehensive view helps in understanding the system's scope and the interactions between users and functionality
