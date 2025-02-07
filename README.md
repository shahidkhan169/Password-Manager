# Password Manager with Browser Extension

## Description
A secure and efficient password manager with a browser extension to store, manage, and autofill credentials securely. The extension integrates with a web app that provides encryption, user authentication, and password generation features.

## Features
- Secure password storage using AES-256 encryption
- Browser extension for seamless autofill
- Strong password generator
- User authentication with JWT-based login
- Data stored in MongoDB
- Multi-factor authentication (MFA) support
- Password strength analysis


## Tech Stack
### Frontend
- **React.js** – UI for web application
- **Tailwind CSS** – Styling
- **Manifest V3** – Chrome extension framework

### Backend
- **Node.js & Express.js** – API development
- **MongoDB** – Database for storing encrypted passwords
- **bcrypt** – Hashing user credentials
- **jsonwebtoken (JWT)** – Authentication

### Security
- **AES-256** – Password encryption
- **bcrypt** – Secure hashing
- **Helmet.js** – Security middleware for HTTP headers
- **Rate Limiting** – Prevent brute-force attacks

## UI Layouts

<img src="docs/UI Layout.png" />
