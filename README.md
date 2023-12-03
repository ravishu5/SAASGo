# SaaSGo , a SaaS WebApp with Stripe Integration

Welcome to the repository of our SaaSGo WebApp, a comprehensive platform that offers various subscription plans through the Stripe payment gateway. This application allows users to browse different services, manage subscriptions, and securely process payments.

## Website

Visit our live application: [SaaSGo WebApp](https://saas-tgo.vercel.app/)

## Demo Video

For a detailed walkthrough, watch our [Implementation Video]().

## Features

- **Subscription Plans**: Offers “Basic”, “Standard”, and “Plus” plans.
- **Plan Details**: Displays a list of available plans with detailed descriptions.
- **Shopping Cart**: Users can add desired services to the cart for review and purchase.
- **Stripe Integration**: Secure checkout process with support for multiple subscriptions.
- **User Authentication**: Features Login and SignUp pages for user accounts.
- **Admin Dashboards**: Separate dashboards for Admin and Super Admin for user and plan management.

## Tech Stack

- **Frontend**: React JS, Material UI
- **Backend**: Node JS, Express JS
- **Database**: MongoDB, Mongoose
- **API**: REST API

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm (Node Package Manager)
- [Git](https://git-scm.com/) for cloning the repository

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/knehaa/subscription-services.git
2. **Install Dependencies**
   * For frontend : 
    ```bash
   cd frontend
   npm install
   * For backend :
   ```bash
   cd backend
   npm install
3. **Configure Environment Variables**
   .env backend
   ```bash
   DATABASE_URL //is mongodb url
   SECRET=ThisIsOurLittleSecret
   STRIPE_SECRET_KEY
   .env
