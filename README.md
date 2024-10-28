# ToDo-List
This HTML code creates a simple Todo List application with a minimalistic design. The app allows users to add tasks, mark them as completed, and delete them. Here’s a breakdown of how it works and its features:

Key Features
Add Todos: Users can type a task into the input field and press Enter to add it to the list.
Mark as Completed: Left-clicking on a task toggles its completion status, adding a strikethrough effect to signify completion.
Delete Todos: Right-clicking on a task removes it from the list.
Data Persistence: Todos are saved to localStorage, so they persist even after refreshing or closing the browser.
Code Breakdown
HTML Structure:

The <h1> element serves as the title.
The <form> contains an input field for entering new tasks.
The <ul> element with the class todos holds the list of tasks, added dynamically using JavaScript.
The <small> element provides user instructions.
CSS Styling:

A linear gradient background gives the page a visually appealing look.
Responsive design is achieved by centering content vertically and horizontally.
Each todo item has a hover effect and a completed style with a line-through to signify completion.
JavaScript Functionality:

When the form is submitted, addTodo() is called, which creates a new <li> element for the todo.
The updateLS() function saves the list of todos to localStorage in JSON format.
Todos are loaded from localStorage when the page loads, allowing them to persist across sessions.
Event Listeners:
click event on each <li> toggles the completed class.
contextmenu event (right-click) removes the todo from the list.
How It Works
Adding a Todo: When a user submits the form, addTodo() is called. If there is text in the input field, a new list item is created and added to the <ul>.
Marking Complete/Incomplete: Left-clicking on a todo toggles the completed class, which applies a line-through style.
Deleting a Todo: Right-clicking removes the todo from the DOM and updates localStorage.
Local Storage: Todos are stored in the browser’s localStorage, so they persist across sessions.
This Todo List app is a practical example of managing state with localStorage, basic form handling, and creating interactive UI elements with JavaScript.






