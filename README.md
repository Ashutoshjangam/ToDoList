
# Todo App - Enhanced UI

## Overview
This project is a simple Todo application with an updated user interface (UI) to enhance usability and visual appeal. The design includes:
- Modern colors and typography.
- Smooth hover effects and transitions.
- A responsive layout that works well across various screen sizes.

---

## Features

### UI/UX Enhancements
- **Colors**: A clean, modern palette with accent colors for key actions.
- **Typography**: Uses the "Roboto" font for a professional look.
- **Hover Effects**: Interactive buttons and todo items provide feedback to the user.
- **Box Shadows**: Adds depth to elements for a polished appearance.

### Functionality
- **Add Todo**: Users can add tasks via the input field and "Add" button.
- **Delete Todo**: Each task includes a delete button to remove it from the list.
- **Mark Complete**: Tasks can be marked as completed by checking a checkbox, with a visual indication (strikethrough text).
- **Persistence**: Tasks are saved in the browser's local storage, allowing them to persist between sessions.

---

## File Breakdown

### index.html
Contains the structure of the application. Key elements include:
- A header (`<h1>`) for the title.
- A form with an input field and button for adding tasks.
- An unordered list (`<ul>`) for displaying todos dynamically.

### style.css
Defines the styling for the application. Key sections include:
- Root variables for consistent colors and spacing.
- Flexbox-based layout for alignment.
- Transitions and hover effects for interactivity.

### app.js
Implements the app's interactivity. Key functions include:
- **`addTodo`**: Adds a new task to the list.
- **`deleteTodoItem`**: Removes a task from the list.
- **`updateTodoList`**: Updates the displayed list after any action.
- **`saveTodos` and `getTodos`**: Manage local storage for persistence.

---

![Screenshot 2025-01-13 110639](https://github.com/user-attachments/assets/edf7acb8-e790-4bb6-b854-8501bade38de)


