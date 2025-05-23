# MERN CRUD Website

This project is a simple CRUD (Create, Read, Update, Delete) web application built using the MERN stack (MongoDB, Express.js, React, Node.js).

## Features

- Add new items to the database
- View a list of all items
- Edit existing items
- Delete items

## Tech Stack

- **Frontend:** React
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB
- React

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Sriramsr3/CRUD-MERN.git
    cd CRUD-MERN
    ```

2. **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies:**
    ```bash
    cd ../frontend
    npm install
    ```

4. **Start MongoDB:**  
    Make sure MongoDB is running locally or update the connection string in `backend/config`.

5. **Run the backend server:**
    ```bash
    cd ../backend
    nodemon index.js
    ```

6. **Run the frontend app:**
    ```bash
    cd ../frontend
    npm start
    ```

