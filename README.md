# Ultimate Collections - Production E-Commerce Platform

A production-ready e-commerce storefront built with Next.js 16, TypeScript, Tailwind CSS, Neon PostgreSQL, and Vercel.

---

## Live Application

Production URL:

https://jewellery-clothing-store.vercel.app

GitHub Repository:

https://github.com/prasadpj509

---

## Project Overview

Ultimate Collections is a modern e-commerce platform designed for jewellery and fashion product showcasing, customer engagement, and online order generation.

The platform includes:

* Product catalog management
* Dynamic product APIs
* PostgreSQL database integration
* Admin dashboard
* Audit logging system
* Authentication layer
* Cart and checkout workflow
* SEO optimization
* Production deployment

---

## Features

### Customer Features

#### Product Catalog

* Jewellery Collection
* Sarees Collection
* Kurtis Collection
* Handbags Collection
* Kids Wear Collection

#### Product Search

* Search products by name
* Dynamic filtering

#### Product Details

* Dynamic product pages
* Product descriptions
* Product images
* WhatsApp ordering

#### Shopping Experience

* Add To Cart
* Cart Summary
* Checkout Page

#### Customer Engagement

* WhatsApp Integration
* Instagram Integration
* Testimonials
* Shop By Category

#### Responsive Design

* Mobile Friendly
* Tablet Friendly
* Desktop Friendly

---

## Admin Features

### Admin Dashboard

* Product Management
* Product CRUD Operations
* Admin Authentication
* Audit Tracking

### Audit Logging

Tracks:

* Product Creation
* Product Updates
* Product Deletion
* Administrative Actions

Audit records are stored in PostgreSQL.

---

## Backend APIs

### Products API

/api/products

Supports:

* Product Listing
* Product Retrieval
* Filtering
* Database Queries

### Admin Audit API

/api/admin/audit

Supports:

* Audit Log Retrieval
* Pagination
* Filtering

### Authentication API

/api/auth/[...nextauth]

Powered by NextAuth.

### Database Health API

/api/db-test

Used for production database verification.

---

## Database

### PostgreSQL (Neon)

Tables:

#### products

Stores:

* Product Name
* Category
* Price
* Description
* Images

#### admin_audit

Stores:

* Admin User
* Action
* Product ID
* Payload
* IP Address
* Timestamp

---

## Technology Stack

### Frontend

* Next.js 16
* React
* TypeScript
* Tailwind CSS

### Backend

* Next.js Route Handlers
* PostgreSQL
* Neon Database

### Authentication

* NextAuth

### Deployment

* Vercel

### Version Control

* Git
* GitHub

### Development Environment

* Windows
* WSL (Ubuntu)
* VS Code

---

## Architecture

Client
↓
Next.js Application
↓
API Routes
↓
Neon PostgreSQL
↓
Vercel Deployment

---

## DevOps Skills Demonstrated

### Source Control

* Git
* GitHub Workflow
* Branch Management

### Cloud & Hosting

* Vercel Deployment
* Environment Variable Management
* Production Releases

### Database Operations

* PostgreSQL
* Neon Database
* Connection Troubleshooting
* Query Optimization

### Application Deployment

* Production Builds
* Runtime Validation
* Deployment Verification
* Environment Configuration

### Linux Skills

* WSL Administration
* Networking Troubleshooting
* Process Management
* Port Debugging

### Troubleshooting Experience

Resolved:

* PostgreSQL Connection Issues
* Environment Variable Problems
* Build Failures
* Next.js Route Issues
* Vercel Deployment Issues
* Production Runtime Errors

---

## Local Development

Clone Repository

```bash
git clone <repository-url>
cd jewellery-clothing-store
```

Install Dependencies

```bash
npm install
```

Run Development Server

```bash
npm run dev
```

Build Application

```bash
npm run build
```

Run Production Build

```bash
npm start
```

---

## Environment Variables

```env
DATABASE_URL=
NEXTAUTH_SECRET=
ADMIN_USER=
ADMIN_PASS=
CONTACT_WHATSAPP=
INSTAGRAM_HANDLE=
NEXT_PUBLIC_CONTACT_WHATSAPP=
NEXT_PUBLIC_INSTAGRAM_HANDLE=
```

---

## Production Validation

Verified:

* Successful Build
* Successful Deployment
* Database Connectivity
* Product APIs
* Admin Audit APIs
* PostgreSQL Integration
* Environment Variables
* Dynamic Routes

---

## Future Enhancements

* Payment Gateway Integration
* Razorpay Integration
* Inventory Management
* Order Management
* Customer Accounts
* Email Notifications
* Analytics Dashboard
* Product Reviews
* Wishlist Functionality
* Role Based Access Control

---

## Author

Durga Prasad P J

DevOps Engineer

Skills:

* AWS
* Docker
* Kubernetes
* Terraform
* CI/CD
* Linux
* PostgreSQL
* Next.js
* Vercel

GitHub:
https://github.com/prasadpj509

LinkedIn:
(Add your LinkedIn URL)

---

## Project Status

Production Ready

Successfully deployed and running on Vercel with Neon PostgreSQL backend.
