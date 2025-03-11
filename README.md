React Hooks Assignment 3
This is my React Hooks Assignment project that demonstrates the use of all major React Hooks combined in a single functional application. The project is a fully functional Task Manager Application, where users can add, edit, delete, complete, and filter tasks. It also includes features like Dark Mode toggle and task autosaving to local storage for persistence.

Features Implemented:

Add, Edit, Delete Tasks
Mark Tasks as Completed/Incomplete
Filter Tasks (All, Completed, Incomplete)
Dark/Light Mode Toggle (Saved using localStorage)
Autosave Tasks to localStorage
Optimized Filtering and Performance
Input Auto-focus on Load
User Notifications on Actions
React Hooks Used in This Project:

useState - Manage input fields, task list, notifications
useEffect - Side effects like saving to localStorage, showing notifications
useContext - Global Dark Mode state management
useReducer - Complex state management for tasks (add, delete, edit, toggle)
useRef - Directly access and focus input fields
useMemo - Optimize task filtering (performance boost)
useCallback - Memoize handlers to prevent unnecessary re-renders
Technologies Used:

React.js (Functional Components)
React Hooks
CSS for Styling
LocalStorage (for data persistence)
Project Setup & Installation:

Clone the repository: git clone https://github.com/MeetSutariya2/-React_Hooks_Assignment_3.git

Navigate to project directory: cd React_Hooks_Assignment_3

Install dependencies: npm install

Start the project: npm start

How to Use the App:

Add a Task: Type task name in the input and click Add Task.
Edit a Task: Click Edit, update the title, and Save.
Delete a Task: Click the Delete button next to a task.
Mark Complete: Click on a task name to mark it complete/incomplete.
Filter Tasks: Use the dropdown to filter tasks.
Toggle Dark Mode: Use the Dark/Light mode switch to toggle themes.
Project Structure:

/src

App.js (Main React component with all hooks)
App.css (Styling for the app)
index.js (Entry point to render App)
What I Learned:

Through this project, I learned how to implement and combine all important React Hooks to create a functional and optimized application. I practiced managing complex state using useReducer, handling side effects with useEffect, creating a global context for dark mode with useContext, and optimizing performance using useMemo and useCallback. I also learned to use useRef to handle input fields efficiently without unnecessary re-renders. This project gave me practical experience in building a real-world React app using functional components and hooks.
