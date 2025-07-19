# Workasana Frontend

Workasana is a project and team management web application built with React. This frontend connects to a backend API for authentication, project, team, and task management.

## Features

- **User Authentication**
  - Login functionality with token storage
  - Secure access to dashboard and management screens

- **Dashboard**
  - Overview of projects, teams, and tasks
  - Quick navigation to management screens

- **Project Management**
  - Create, view, and manage projects
  - Assign teams and owners to projects
  - Add tags and due dates

- **Team Management**
  - Create and manage teams
  - Add new members
  - View team details

- **Task Management**
  - Create, view, and update tasks
  - Assign tasks to teams and owners
  - Mark tasks as complete
  - View task details including project, team, owners, tags, due date, and estimated time

- **Reports**
  - View reports on projects, teams, and tasks

- **Search**
  - Search functionality for quick access to projects, teams, and tasks

- **Modals and UI Components**
  - Add new members, create teams, manage projects and tasks via modals
  - Sidebar navigation

## Folder Structure

```
frontend/
├── public/
│   └── ...
├── src/
│   ├── App.js
│   ├── config.js
│   ├── useFetch.js
│   ├── components/
│   │   ├── AddNewMemberModal.jsx
│   │   ├── CreateNewTeamModal.jsx
│   │   ├── ProjectModal.jsx
│   │   ├── SideBar.jsx
│   │   ├── TaskModal.jsx
│   │   └── TaskModalforProject.jsx
│   ├── contexts/
│   │   └── SearchContext.jsx
│   ├── pages/
│   │   ├── DashboardScreen.jsx
│   │   ├── LoginScreen.jsx
│   │   ├── ProjectManagementScreen.jsx
│   │   ├── ReportsScreen.jsx
│   │   ├── TaskDetailsScreen.jsx
│   │   ├── TeamDetailsPage.jsx
│   │   └── TeamManagementScreen.jsx
│   └── ...
├── package.json
└── README.md
```

## Environment Setup

- Configure the backend API URL in `.env`:
  ```
  REACT_APP_BACKEND_URI=https://your-backend-url
  ```
- Install dependencies:
  ```bash
  npm install
  ```
- Start the development server:
  ```bash
  npm start
  ```

## Usage

- Login with your credentials
- Manage projects, teams, and tasks
- View reports and search for items

## Technologies Used

- React
- React Router
- Fetch API
- CSS

## Contributing

Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the MIT License.
