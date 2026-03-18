# Grave Management System

## Overview

The Grave Management System is a modern, AI-enabled cemetery management platform designed for Islamic centers. It replaces traditional paper-based and spreadsheet-driven processes with a secure, centralized system for managing grave inventory, bookings, payments, burial records, reporting, and administrative operations.

The system is integrated with the Islamic center website, allowing seamless access to cemetery services while improving operational efficiency, transparency, and data accuracy.

## Live Demo

You can access the live system here:

- Islamic Center Website: https://kamalkeweb.com/
- Grave Management System: https://grave.kamalkeweb.com/
- Login Credentails for Grave Management System
- User id : bilalhussain2010@yahoo.com
- Password : Test@123456

Note: Access to the management system is restricted to authorized users.

## Key Features

### Website Integration
The system is integrated with the Islamic center website. A “Book a Grave” option allows users to access the grave management system directly from the website, improving accessibility and workflow continuity.

### Security and Access Control
- Secure staff login system  
- Database-level protection using Row Level Security (RLS)  
- Ensures only authorized users can access and manage records  

### Grave Inventory Management
- Visual cemetery layout in grid format  
- Real-time status tracking of graves:
  - Available  
  - Reserved  
  - Booked  
  - Occupied  

### Booking Workflow

The system provides a structured three-step booking process:

1. Grave Selection  
   Staff can select one or multiple graves from the visual layout. Multiple selections support family plot reservations.

2. Customer Details  
   Capture customer information including name, contact details, membership type, and address.

3. Payment Processing  
   - Payment modes: Cash or Cheque  
   - Payment types: Full payment or Installments  

### Automated Email Notifications
Upon successful booking, the system automatically sends a confirmation email to the customer. The email includes:
- Allocated grave details  
- Total cost  
- Payment summary  
- Outstanding balance  

This ensures transparency and provides a permanent record for the customer.

### Financial Management
The system tracks and manages:
- Total booking value  
- Payments received  
- Outstanding balances  
- Installment payments  

This enables accurate and auditable financial record keeping.

### Reporting and Analytics

#### Search Capabilities
- Search booking records by customer name  
- Search graves by grave code  

#### Financial Dashboard
- Overview of total revenue  
- Payments collected  
- Outstanding balances  
- Installment tracking  

#### Cemetery Status Dashboard
- Real-time overview of:
  - Available graves  
  - Reserved graves  
  - Booked graves  
  - Occupied graves  

### Installment Payment Management
A dedicated payment update module allows staff to:
- Record installment payments  
- Automatically update paid and remaining balances  

### Burial Management

#### Burial Authorization
- Ensures burial is authorized based on booking and payment status  

#### Burial Register
- Maintains permanent burial records including:
  - Deceased name  
  - Burial date  
  - Grave location  
  - Customer details  
  - Payment status  


### AI-Based Features

#### Website Assistant
An AI chatbot integrated into the Islamic center website provides information about:
- Services  
- Events  
- Education programs  
- Grave booking procedures  

#### Grave Assistant
An AI assistant within the system allows staff to:
- Retrieve booking details  
- Check grave status  
- View payment information  
using simple conversational queries  

### Automated Email Notifications
Upon successful booking, the system automatically sends a confirmation email to the customer. The email includes:
- Allocated grave details  
- Total cost  
- Payment summary  
- Outstanding balance  

### Administrative Controls

#### Customer Data Correction
Allows updating customer information such as:
- Name  
- Contact details  
- Address  

#### Payment Correction
- Reverse incorrect transactions  
- Maintain accurate financial records  

#### Booking Cancellation
- Bookings can be canceled only after reversing associated payments  
- Ensures financial and data consistency  


## Video Demonstration

A complete system walkthrough demonstrating all features, including booking workflow, reporting, payment management, burial management, AI assistants, and administrative controls, is provided in the repository.

Video link is as : https://drive.google.com/file/d/1yAfuElpvPiGaOLdLPGZ2PhA68Jsp34l7/view?usp=sharing


## Tech Stack

- Frontend: React / Next.js  
- Backend: Supabase / Node.js  
- Database: PostgreSQL  
- Authentication: Supabase Auth  
- Automation: n8n (email workflows)  
- AI: Chatbot integration  


## Project Status

Active development / MVP ready

