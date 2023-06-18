# Task Manager Backend

This is the backend of the Task Manager application, built with Node.js, Express.js, MySQL, and Sequelize.

## Features

- User Registration: Users can register with their username and password.
- User Login: Registered users can log in to their accounts.
- Task Creation: Logged-in users can create tasks by providing a task title and description.
- Task Listing: Users can view a list of their created tasks.
- Task Deletion: Users can delete a task from their task list.

## Prerequisites

Before running the backend, make sure you have the following:

- Node.js installed on your machine.
- MySQL server running on your machine.

## Database Configuration

1. Make sure your MySQL server is running.
2. Create a new MySQL database for the Task Manager application.
3. Update the database configuration in `config/config.js` file.

```javascript
module.exports = {
  development: {
    username: 'your-username',
    password: 'your-password',
    database: 'task_manager_db', // Update with your database name
    host: 'localhost',
    dialect: 'mysql',
  },
};
```
## Getting Started

1. Clone the repository: `git clone <frontend-repo-url> task-manager-client`
2. Navigate to the frontend directory: `cd task-manager-client`
3. Install dependencies: `npm install`
4. Start the developement server: `npm start`

The backend server should now be running on http://localhost:8000.

## API Endpoints
The following API endpoints are available:

- POST /api/v1/user/register: `Register a new user`.
- POST /api/v1/user/login: `Log in with a registered user`.
- POST /api/v1/tasks: `Create a new task`.
- GET /api/v1/tasks: `Get the list of tasks for the logged-in user`.
- DELETE /api/v1/tasks/:taskId: `Delete a specific task`
