# Task Manager Frontend

This is the frontend of the Task Manager application, built with React and Tailwind CSS.

## Features

- User Registration: Users can register with their username and password.
- User Login: Registered users can log in to their accounts.
- Task Creation: Logged-in users can create tasks by providing a task title and description.
- Task Listing: Users can view a list of their created tasks.
- Task Deletion: Users can delete a task from their task list.

## Prerequisites

Before running the frontend, make sure you have the following:

- Node.js installed on your machine.

## Getting Started

1. Clone the repository: `git clone <frontend-repo-url> task-manager-client`
2. Navigate to the frontend directory: `cd task-manager-client`
3. Install dependencies: `npm install`
4. Start the developement server: `npm start`

## Configuration

Before starting the frontend, you may need to configure the backend API URL. By default, the backend server is running at `http://localhost:8000`. If your backend server is running on a different URL, update the configuration in `src/config.js` file.

```javascript
const API_URL = 'http://localhost:8000'; // Update this URL with your backend server URL
