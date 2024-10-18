Day 1: Project Setup and Basic Task Management
Setup Project:

Create a GitHub repository to track your progress.
Set up your project structure with HTML, CSS, and JavaScript files.
Build a simple UI with a task input field and a task list display.
Basic Task Features (Core JavaScript):

Implement functionality to add tasks, display them in a list, and delete tasks using JavaScript.
Use DOM manipulation for real-time task updates.

Day 2: Object-Oriented Programming (OOP)
Implement Task Class:

Create a Task class with properties like name, description, status, and dueDate.
Task Manager Class:

Implement a TaskManager class to handle the task list, including methods for adding, deleting, and editing tasks.
Use this, bind, call, and apply:

Add functions to the TaskManager class and use bind, call, and apply for handling task ownership or advanced event binding.
Day 3: Polyfills & Deep/Shallow Copy
Write Polyfills:

Implement polyfills for call, bind, and apply. Use these methods in your TaskManager for task manipulation.
Deep and Shallow Copy:

Implement functions for deep copy and shallow copy of task objects and task lists. Create buttons to duplicate tasks and see the effect of deep vs shallow copies.
Day 4: Arrays and Higher-Order Functions (HOFs)
Array Methods (HOFs):
Use methods like map, filter, and reduce to implement features such as:
Filtering tasks by status (e.g., completed, pending).
Mapping task names to display them in uppercase.
Reducing task durations to calculate total time spent on tasks.
Day 5: Closures and Object Freezing
Closures:

Use closures to encapsulate task properties, making certain details private and only exposing specific methods for manipulation (e.g., allow task editing but prevent deleting).
Object Freezing:

Use Object.freeze to freeze completed tasks so they can no longer be edited.
Day 6: Asynchronous JavaScript: Event Loop, Promises, and Async/Await
Event Loop & Callbacks:

Simulate a delayed task reminder or notifications using setTimeout or setInterval to understand how the event loop works.
Add callbacks to handle saving tasks to local storage or any async operations.
Promises:

Fetch data from an external API (e.g., a to-do list API) using Promises.
Chain promises to simulate a sequence of asynchronous events (e.g., loading tasks, updating the UI, and then saving them).
Async/Await & Error Handling:

Convert promise-based code to use async/await.
Add error handling to gracefully deal with issues such as network errors during the API fetch.
Day 7: ES6 Features & Final Touches
ES6 Data Types:

Refactor your code to use let, const, arrow functions, and destructuring where appropriate.
Modularization:

Split your code into modules:
Create separate files for Task, TaskManager, and utility functions.
Use import and export to manage modules.
Final Touches:

Add comments and refactor code to improve readability.
Style your application with CSS to make the UI presentable.
Test all functionalities to ensure everything works smoothly.
