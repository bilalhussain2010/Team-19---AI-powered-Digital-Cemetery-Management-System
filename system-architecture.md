# System Architecture

## Overview

The Grave Management System follows a modern web-based architecture that integrates a public-facing website, a secure grave management application, backend services, automation workflows, and AI-powered assistants.

The system is designed to ensure security, scalability, and efficient data management for cemetery operations.

  

## High-Level Architecture

The system consists of the following major components:

1. Islamic Center Website (Public Interface)
2. Grave Management System (Admin Interface)
3. Backend Services (Supabase)
4. Database (PostgreSQL)
5. Automation Layer (n8n)
6. AI Assistants (Chatbots)

  

## 1. Islamic Center Website

The website serves as the public interface for visitors and includes:

- Information about the Islamic center
- Services, events, and programs
- Cemetery services
- Integrated AI chatbot for user queries

### Key Functionality
- Provides a **"Book a Grave"** entry point
- Redirects users to the Grave Management System
- Hosts an AI assistant for general inquiries

  

## 2. Grave Management System (Admin Panel)

This is the core application used by authorized staff.

### Features
- Grave inventory visualization (grid layout)
- Booking management
- Payment tracking
- Reporting and analytics
- Burial management
- Administrative controls
- AI assistant for quick data retrieval

### Access Control
- Restricted to authenticated users only
- Uses secure login system

  

## 3. Backend Services (Supabase)

Supabase is used as the backend platform providing:

- Authentication (user login)
- API layer for frontend communication
- Database access
- Security policies

### Key Features
- RESTful API access
- Real-time capabilities
- Secure data handling

  

## 4. Database (PostgreSQL)

The system uses a PostgreSQL database to store all data.

### Core Data Entities
- Graves
- Bookings
- Customers
- Payments
- Burial Records

### Security
- Row Level Security (RLS) is implemented
- Ensures users can only access authorized data

  

## 5. Automation Layer (n8n)

n8n is used for workflow automation.

### Key Functionality
- Triggered after booking submission
- Sends automated booking confirmation emails

### Benefits
- Reduces manual communication
- Ensures consistent notifications
- Improves customer experience

  

## 6. AI Assistants

The system includes two AI-powered assistants:

### Website Assistant
- Available on the Islamic center website
- Answers general queries about services and events

### Grave Assistant
- Available inside the management system
- Allows staff to:
  - Search bookings by name
  - Retrieve grave details
  - Check payment status

  

## Data Flow

### Booking Workflow

1. User accesses website
2. Clicks "Book a Grave"
3. Redirected to Grave Management System
4. Staff logs in
5. Staff selects graves
6. Staff enters customer details
7. Staff records payment
8. Booking is stored in database
9. n8n triggers email notification
10. Confirmation email is sent to customer

  

### Payment Update Flow

1. Staff searches booking
2. Enters installment payment
3. System updates:
   - Total paid amount
   - Remaining balance

  

### Burial Workflow

1. Staff accesses burial module
2. Verifies booking and payment
3. Authorizes burial
4. System:
   - Updates grave status
   - Stores burial record

  

## Security Architecture

- Authentication via Supabase Auth
- Row Level Security (RLS) for data protection
- Role-based access control
- Secure API communication

  

## Scalability Considerations

- Cloud-based backend (Supabase)
- Modular frontend design
- Decoupled automation (n8n)
- Extensible AI integration

  

## Future Architecture Enhancements

- Online self-service booking portal
- Payment gateway integration
- Mobile application
- Multi-location cemetery management
- Advanced analytics and reporting

  

## Summary

The   Grave Management System is built using a modern, scalable, and secure architecture that integrates web interfaces, backend services, automation workflows, and AI capabilities to deliver an efficient and intelligent cemetery management solution.
