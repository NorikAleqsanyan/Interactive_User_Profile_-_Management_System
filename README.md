# Real-Time User Management System

A full-stack **web application** built using **Express.js**, **Socket.IO**, **Passport.js**, and **Handlebars**. The app features **role-based authentication** (user, manager, admin) and allows users to update their profiles, including uploading avatars and editing personal details. Additionally, it incorporates **real-time communication** via **Socket.IO** for live updates and notifications.

## Features

- **Role-Based Authentication:**
  - Different user roles with distinct access: users, managers, and admins.
  - Uses **Passport.js** for secure login and session management.

- **Real-Time Communication:**
  - **Socket.IO** enables instant updates and notifications for real-time user interaction.

- **Profile Management:**
  - Users can update personal details (name, surname, age) and upload their avatars.

- **Session Management:**
  - Sessions are managed using **express-session** for secure, persistent logins.

- **Custom Middleware:**
  - **isLogin**, **isLoginManager**, and **isLoginAdmin** middleware are used to ensure that users can access routes based on their roles.

## Technologies Used

- **Express.js** - Backend framework for routing and server-side logic.
- **Socket.IO** - Real-time communication for live interactions between users.
- **Passport.js** - Authentication middleware for secure login and role management.
- **Handlebars (hbs)** - Templating engine for rendering views.
- **express-session** - Session management for user authentication.
- **dotenv** - Secure management of environment variables.

## Installation

Follow these steps to get the application running on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NorikAleqsanyan/Interactive_User_Profile_-_Management_System.git
