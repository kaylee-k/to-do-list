# TodoList Project 📝

<img width="808" alt="Screenshot 2024-07-23 at 3 37 42 PM" src="https://github.com/user-attachments/assets/3c40efb1-24d4-4ffa-b923-e3ff355e0366">
<img width="826" alt="Screenshot 2024-07-23 at 3 37 49 PM" src="https://github.com/user-attachments/assets/fb7abed2-c05b-4421-ac78-63d5444db28f">

Click here to view the live project deployed on Netlify. ➡️  https://todolistkaylee.netlify.app/ 

## Description

Welcome to the TodoList Project! This application, built with React, allows you to efficiently manage your daily tasks with features such as adding, updating, and deleting todos, as well as filtering them based on their status. The project also includes a dark mode feature for a better user experience.

## Features

- Add Todos: Quickly add new tasks to your todo list.
- Update Todos: Mark tasks as completed or active.
- Delete Todos: Remove tasks that are no longer needed.
- Filter Todos: Filter tasks by all, active, or completed status.
- Dark Mode: Toggle between light and dark mode for a better visual experience.
- Persistent Storage: Your todo list is saved in the browser's local storage. Even if you refresh the page or close and reopen the browser, your todos will remain intact.

## Components
### 1. AddTodo
The `AddTodo` component allows users to add new tasks to their todo list. It includes an input field for entering the task description and a button to submit the task.

### 2. Header
The `Header` component displays the filter buttons and the dark mode toggle button. It allows users to switch between different task views (all, active, completed) and toggle the application theme.

### 3. Todo
The `Todo` component represents an individual task in the todo list. It includes a checkbox to mark the task as completed or active, and a delete button to remove the task.

### 4. TodoList
The `TodoList` component displays the list of tasks. It allows users to add, update, and delete tasks. The tasks are filtered based on the selected filter (all, active, completed).

## Context

### DarkModeContext
The `DarkModeContext` provides the current theme (light or dark) and a function to toggle between themes. This context is used by the Header component to toggle the application theme.

## Styling


The application uses `CSS modules` for component-specific styling. The styles are defined in separate CSS files and imported into the corresponding components. The dark mode styles are applied conditionally based on the current theme.

