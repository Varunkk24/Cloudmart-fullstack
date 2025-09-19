# Cloudmart Fullstack Application

This repository contains the fullstack application for Cloudmart, an e-commerce platform.

## Project Structure

The project is divided into two main parts:

### Frontend (`frontend/`)

This directory contains the client-side application built with React. It provides the user interface for browsing products, managing the cart, placing orders, and interacting with the AI assistant.

**Key Technologies:**
- React (for building the UI)
- Vite (as a build tool)
- Tailwind CSS (for styling)
- Axios (for API requests)

**Features:**
- Product listing and details
- Shopping cart functionality
- User authentication and profiles
- Order management
- Admin panel for product and user management
- AI assistant for product recommendations and support

### Backend (`backend/`)

This directory contains the server-side application built with Node.js and Express. It provides the RESTful API for the frontend, handling product data, user authentication, order processing, and AI integration.

**Key Technologies:**
- Node.js (runtime environment)
- Express.js (web framework)
- MongoDB (database - *assumption, might need to verify*)
- Mongoose (ODM for MongoDB - *assumption, might need to verify*)
- JWT for authentication (JSON Web Tokens)
- AWS Lambda (for serverless functions, e.g., `list_products`)

**Features:**
- Product API (CRUD operations for products)
- User API (registration, login, profile management)
- Order API (creating, viewing, updating orders)
- AI integration (via `aiService.js` and `aiController.js`)
- Authentication and authorization
