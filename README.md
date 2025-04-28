# Advanced To-Do List

This is an advanced To-Do List web application built with React and Vite. It features task management with due dates, priorities, editing, filtering, and dark mode support. The app saves tasks and user preferences in local storage for persistence.

## Features

- Add tasks with description, due date, and priority (Low, Medium, High).
- Edit existing tasks.
- Mark tasks as complete or incomplete.
- Delete tasks.
- Filter tasks by All, Active, or Completed.
- Dark mode toggle for better user experience.
- Responsive design with animations.
- Tasks and preferences saved in local storage.
- Accessible UI with keyboard navigation and ARIA labels.

## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to start the development server.
5. Open the provided localhost URL in your browser.

## Project Structure

- `src/App.jsx`: Main React component managing state and rendering UI.
- `src/components/TaskForm.jsx`: Form component for adding new tasks.
- `src/components/TaskList.jsx`: Component to list tasks based on filter.
- `src/components/TaskItem.jsx`: Individual task item with edit, delete, and toggle functionality.
- `src/index.css`: Styling including dark mode and animations.
- `index.html`: HTML entry point.
- `package.json`: Project dependencies and scripts.
- `vite.config.js`: Vite configuration.

## Usage

- Use the input form to add new tasks.
- Click task text or checkbox to toggle completion.
- Use edit button to modify task details.
- Use delete button to remove tasks.
- Use filter buttons to view all, active, or completed tasks.
- Toggle dark mode using the button at the top.
- Your tasks and preferences are saved automatically.

## Author

ISAAC GRIFFIN

## License

This project is open source and free to use.
