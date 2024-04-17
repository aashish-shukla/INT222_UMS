# 🚀 User Management System

A simple user management system built with Node.js, Express, MongoDB, and Axios.

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- Add new users with name, email, and password.
- View a list of existing users.
- Update user information.
- Delete users from the system.

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/user-management-system.git
   ```

2. **Install dependencies:**

   ```bash
   cd user-management-system
   npm install
   ```

3. **Set up MongoDB:**

   - Create a MongoDB Atlas account or set up a local MongoDB instance.
   - Update the MongoDB connection string in `index.js` to connect to your database.

4. **Run the application:**

   ```bash
   npm start
   ```

## 📝 Usage

Once the application is running, you can access the user management system through your web browser or API client. The frontend interface allows you to add, view, update, and delete users.

## 🔗 Endpoints

The following endpoints are available:

- `GET /users`: Retrieve a list of all users.
- `POST /users`: Add a new user.
- `PUT /users/:id`: Update an existing user by ID.
- `DELETE /users/:id`: Delete a user by ID.