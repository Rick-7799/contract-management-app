# Contact Management App

A simple yet powerful contact management application built with React for the frontend and Node.js for the backend. This app allows users to efficiently manage their contacts by adding, editing, deleting, and viewing contact information.

## Features

- **User-Friendly Interface**: Built with Material UI for a modern and responsive design.
- **Contact Form**: Easily add new contacts with essential details.
- **Contact Table**: View all contacts in a sortable and paginated table.
- **CRUD Operations**: Create, Read, Update, and Delete contacts seamlessly.
- **Error Handling**: Robust error handling for form submissions and API calls.

## Tech Stack

- **Frontend**: React, Material UI
- **Backend**: Node.js, Express
- **Database**: MongoDB (using Mongoose for object modeling)

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (v6 or later)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Rick-7799/contract-management-app
    ```

2. **Navigate to the backend directory**:
    ```bash
    cd contact-management-app/backend
    ```

3. **Install backend dependencies**:
    ```bash
    npm install
    ```

4. **Navigate to the frontend directory**:
    ```bash
    cd ../frontend
    ```

5. **Install frontend dependencies**:
    ```bash
    npm install
    ```

### Running the Application

1. **Start the MongoDB server**

2. **Start the backend server**:
    ```bash
    cd backend
    node server.js
    ```

3. **Start the frontend application**:
    ```bash
    cd ../frontend
    npm start
    ```

The application will be accessible at `http://localhost:3000`.

## API Endpoints

| Method | Endpoint           | Description                             |
|--------|--------------------|-----------------------------------------|
| POST   | /contacts          | Add a new contact                       |
| GET    | /contacts          | Retrieve all contacts                   |
| PUT    | /contacts/:id      | Update a specific contact               |
| DELETE | /contacts/:id      | Delete a contact                        |
