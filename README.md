# Shopp-e

Shopp-e is a full-stack e-commerce application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to browse products, add them to their cart, make purchases, and manage their orders.


## Table of Contents

1. [Features](#features)
2. [Technologies](#technologies)
3. [Installation](#installation) 
4. [API Endpoints](#api-endpoints)
5. [License](#license)


## Features

- User authentication and authorization
- Product browsing and search functionality
- Cart management and checkout process
- Order history and tracking
- Payment processing with Braintree integration
- User profile management


## Technologies

### Backend

- Node.js: JavaScript runtime environment.
- Express.js: Web application framework for Node.js.
- MongoDB with Mongoose: NoSQL database and ODM for interacting with MongoDB.
- bcrypt: Library for hashing passwords.
- Braintree: Payment gateway integration for processing payments.
- JSON Web Tokens (JWT): Authentication mechanism.
- Morgan: HTTP request logger middleware.
- Slugify: Library for generating URL-friendly slugs.

### Frontend

- React.js: JavaScript library for building user interfaces.
- React Router DOM: Routing library for React.
- Ant Design: UI library with React components.
- Axios: Promise-based HTTP client for making API requests.
- Braintree Web Drop-In React: React component for integrating Braintree payment UI.
- Moment.js: Library for parsing, validating, manipulating, and formatting dates and times.
- React Helmet: Library for managing document head metadata in React.
- React Hot Toast: Library for toast notifications in React.
- React Icons: Library of popular icons for React applications.
- React Toastify: Library for toast notifications in React applications.


## Installation

### Install backend dependencies: 
- `cd shopp-e`
- `npm install`

### Install frontend dependencies:
- `cd client`
- `npm install`


## API Routes

The backend API provides the following routes:

- `/api/v1/auth`: Routes for user authentication and authorization.
- `/api/v1/product`: Routes for managing products.
- `/api/v1/cart`: Routes for managing categories.
- `/api/v1/order`: Routes for managing orders.



## License

This project is licensed under the MIT License.


