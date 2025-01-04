React Task Management App

This project is a Task Management web application built with React. It supports user authentication, task management, and dynamic routing. The app interacts with a backend server using Axios for API calls and uses React Router for navigation.

Features

User Authentication: Login and register functionality with session persistence.

Task Management: Add, view, and manage tasks dynamically.

Responsive Design: Fully responsive UI with a navbar for easy navigation.

Notifications: Integrated toast notifications using react-hot-toast.

Tech Stack

Frontend: React, React Router, React Hot Toast

HTTP Client: Axios

Backend API: Expected to run on http://localhost:4000 with endpoints for user authentication and task management.

Components

1. App.js

The root component that integrates the routing and state management.

Manages authentication state and user information.

2. Home.js

Displays the list of tasks and task-related actions.

3. Navbar.js

Navigation bar with links to Home, Register, Login, and Profile.

4. Register.js

Handles user registration.

5. Login.js

Manages user login.

6. Profile.js

Displays user information for authenticated users.

Installation and Setup

Clone the repository:

git clone https://github.com/your-repo-url/react-task-app.git

Navigate to the project directory:

cd react-task-app

Install dependencies:

npm install

Run the application:

npm start

Backend Setup:
Ensure the backend server is running at http://localhost:4000 and exposes the following endpoints:

GET /api/v1/user/me: Fetch authenticated user details.

Other necessary endpoints for authentication and task management.

Folder Structure

react-task-app/
|-- public/
|-- src/
|   |-- components/
|   |   |-- Home.js
|   |   |-- Navbar.js
|   |   |-- Register.js
|   |   |-- Login.js
|   |   |-- Profile.js
|   |-- App.js
|   |-- index.js
|-- package.json
|-- README.md

Environment Variables

Create a .env file in the root directory with the following variables:

REACT_APP_BACKEND_URL=http://localhost:4000

Dependencies

react: Frontend framework.

react-router-dom: For routing.

axios: For API calls.

react-hot-toast: For notifications.

Usage

Navigate to /register to create a new account.

Log in at /login to access the task management features.

View and manage tasks on the home page (/).

Access user details at /profile.

Contributing

Fork the repository.

Create a new feature branch.

Commit your changes and push them.

Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For issues or inquiries, please contact [kamalpandey9993@gmail.com].

