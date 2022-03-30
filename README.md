# eBuy Shopping

> eCommerce platform built with the MERN stack & Redux.

## Live Demo

Explore the live application: [eBuy Shopping](https://ebuynow.vercel.app/)

## Description

eBuy Shopping is built to emulate a real-world online shopping platform, providing essential features for both customers and administrators. It includes product management, user management, order tracking, and an intuitive checkout process, ensuring a complete e-commerce solution.

## Built With

- **Node.js**: JavaScript runtime for building fast and scalable server applications.
- **Express**: Web framework for Node.js, used to build RESTful APIs.
- **React.js**: Front-end library for building interactive user interfaces.
- **Redux**: State management library for JavaScript apps.
- **MongoDB**: NoSQL database for storing application data.
- **React Hooks**: Functions to manage state and side effects in functional components.
- **React Bootstrap**: Front-end framework for React, offering reusable UI components.
- **Axios**: Promise-based HTTP client for making API requests.
- **Bcrypt**: Library for hashing passwords.
- **JSON Web Tokens**: Standard for securely transmitting information between parties.
- **Prettier**: Code formatter to ensure consistent style.
- **ESLint**: Linter tool for identifying and fixing code issues.
- **React Helmet**: Document head manager for React.

## Features

- **Fully Featured Shopping Cart**: Add, update, and manage cart items.
- **Product Reviews and Ratings**: Users can leave reviews and rate products.
- **Top Products Carousel**: Highlight popular products in a carousel.
- **Product Pagination**: Paginate product listings for better navigation.
- **Product Search Feature**: Search products by name or category.
- **User Profile with Orders**: Manage personal information and view order history.
- **Admin Product Management**: Admin interface for adding, updating, and deleting products.
- **Admin User Management**: Admin interface for managing user accounts.
- **Admin Order Details Page**: View and manage order details.
- **Mark Orders as Delivered Option**: Update order status to delivered.
- **Checkout Process**: Streamlined checkout process including shipping and payment methods.
- **Database Seeder**: Populate database with initial product and user data.



## Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm (Node Package Manager)

### Create Accounts and Obtain Credentials

1. **MongoDB**: 
   - Create a MongoDB database and obtain your `MongoDB URI` from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register).

2. **PayPal**: 
   - Create a PayPal account and obtain your `Client_ID` from [PayPal Developer](https://developer.paypal.com/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/adityaongit/ebuy.git
   ```

2. Install server dependencies:
   ```bash
   npm install
   ```

3. Install client dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

4. Create a `.env` file in the root directory of the backend and add the following configurations:
   ```
   PORT=5000
   MONGO_URI=<your_mongo_uri>
   JWT_SECRET=<your_jwt_secret>
   PAYPAL_CLIENT_ID=<your_paypal_client_id>
   PAYPAL_APP_SECRET=<your-paypal-app-secret>
   PAYPAL_API_URL=<https://api-m.sandbox.paypal.com>
   PAGINATION_LIMIT=8
   ```

## Sample User Logins

| Type     | Email              | Password |
|----------|--------------------|----------|
| Admin    | admin@email.com   | 123456   |
| Customer | john@email.com    | 123456   |
| Customer | jane@email.com    | 123456   |


## Learnings

Developing eBuy Shopping has provided valuable insights into building scalable and maintainable web applications using modern technologies. Key learnings include:

- **Backend Development**: Creating RESTful APIs with Node.js and Express, integrating MongoDB for data storage, and implementing secure authentication with JWT and Bcrypt.
- **Frontend Development**: Building a responsive and interactive user interface with React.js, managing state efficiently with Redux, and enhancing UI with React Bootstrap.
- **Code Quality**: Maintaining high code quality using Prettier for formatting and ESLint for identifying and fixing issues.
- **Full-Stack Integration**: Seamlessly integrating frontend and backend components, handling API requests with Axios, and ensuring a smooth user experience.

## Future Work

To further enhance eBuy Shopping, the following features and improvements are planned:

- **Enhanced Payment Integration**: Reintroduce PayPal and integrate additional payment gateways.
- **Order Tracking**: Implement real-time order tracking for users.
- **Wishlist Feature**: Allow users to add products to a wishlist for future purchases.
- **Product Recommendations**: Use machine learning to recommend products based on user behavior.
- **Multi-language Support**: Add support for multiple languages to cater to a global audience.
- **Performance Optimization**: Continuously optimize performance to handle high traffic and large datasets.
- **Security Enhancements**: Implement additional security measures to protect user data and prevent vulnerabilities.

## Contact

For inquiries, reach out at: [Aditya Jindal](https://adysfolio.vercel.app/)
