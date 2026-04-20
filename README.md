# TaskMaster Pro

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

TaskMaster Pro is a modern, lightweight task management application designed to help you organize, prioritize, and track your daily tasks with ease. Whether you're managing your personal to-do list or collaborating with a team, TaskMaster Pro provides an elegant interface and powerful features to enhance your productivity.

## Features

- Create, edit, and delete tasks with deadlines and priorities
- Organize tasks into customizable categories and projects
- Drag-and-drop task ordering
- Mark tasks as completed and view progress stats
- Filter and search tasks quickly
- Responsive design for desktop and mobile use

## Tech Stack

- React.js for the frontend interface
- Node.js and Express for backend API
- MongoDB for data storage
- JWT for authentication
- Tailwind CSS for styling

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/henry89b/taskmaster-pro.git
   ```

2. Navigate to the project directory:

   ```bash
   cd taskmaster-pro
   ```

3. Install dependencies for the backend and frontend:

   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. Create a `.env` file in the `backend` directory with your environment variables (e.g. MongoDB URI, JWT secret).

5. Start the backend server:

   ```bash
   cd backend
   npm start
   ```

6. Start the frontend development server:

   ```bash
   cd ../frontend
   npm start
   ```

Visit `http://localhost:3000` to use TaskMaster Pro.

## Usage

- Sign up or log in to start managing your tasks.
- Use the sidebar to create projects or categories.
- Add new tasks with deadlines and priorities.
- Drag tasks to reorder or move between categories.
- Mark tasks as completed to track progress.

## Screenshots

![Dashboard view](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

![Task creation form](https://via.placeholder.com/800x400?text=Task+Creation+Form)

![Mobile view](https://via.placeholder.com/400x800?text=Mobile+View)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository from [henry89b's GitHub](https://github.com/henry89b/taskmaster-pro).
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

Please ensure your code follows the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

© 2024 Henry89b | [GitHub](https://github.com/henry89b)
