# ToDoList

ToDoList is a web application that allows you to create and manage your personal tasks. You can add, edit, delete, and mark tasks as done. You can also create custom lists for different categories of tasks.

## Features

- Create and delete tasks
- Mark tasks as done or undone
- Edit task names
- Create custom lists with different names
- Store tasks and lists in MongoDB database
- Use Node.js and Express for backend
- Use EJS for templating
- Use Bootstrap for styling

## Installation

To run this project locally, you will need to have Node.js, npm, and MongoDB installed on your machine.

1. Clone this repository or download the zip file.
2. Navigate to the project folder and run `npm install` to install the dependencies.
3. Start your MongoDB server by running `mongod` in your terminal.
4. Run `node app.js` to start the application.
5. Open your browser and go to `http://localhost:3000` to view the app.

## Usage

To use the app, you can follow these steps:

- To add a new task, type the task name in the input field and press the "+" button or hit enter.
- To mark a task as done or undone, click on the checkbox next to the task name.
- To edit a task name, double-click on the task name and type the new name. Press enter to save or escape to cancel.
- To delete a task, hover over the task name and click on the trash icon that appears.
- To create a new list, type the list name in the URL after a slash. For example, `http://localhost:3000/work` will create a new list named "work".
- To switch between lists, click on the list name in the navigation bar or type the list name in the URL.
