# Todo List App

This repository contains a simple Todo List application built with MERN stack (MongoDB, Express, React, Node.js). The application allows users to add, edit, and delete tasks, providing a basic interface for managing their to-do items.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features
- Add new tasks to the todo list.
- Mark tasks as done or undone.
- Delete tasks from the todo list.
- Responsive and user-friendly interface.

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/todo-list-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd todo-list-app
    ```

3. Install server-side dependencies:
    ```bash
    npm install
    ```

4. Install client-side dependencies:
    ```bash
    cd client
    npm install
    ```

5. Create a MongoDB database and update the connection string in `server.js` with your database credentials.

## Usage
1. Start the server:
    ```bash
    npm start
    ```

2. Open a new terminal and navigate to the `client` folder:
    ```bash
    cd client
    ```

3. Start the React development server:
    ```bash
    npm start
    ```

4. Open your browser and go to [http://localhost:3000](http://localhost:3000) to use the Todo List application.

## API Endpoints
- `GET /get`: Retrieve all tasks from the database.
- `POST /add`: Add a new task to the database.
- `PUT /update/:id`: Toggle the completion status of a task by its ID.
- `DELETE /delete/:id`: Delete a task from the database by its ID.

## Contributing
Contributions are welcome! Feel free to open issues or pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
