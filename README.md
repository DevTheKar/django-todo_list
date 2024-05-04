# Django Todo List

This is a simple Todo List application built with Django. It allows users to create, read, update, search, and delete tasks they need to complete.

## Features

- User authentication: Users can sign up, log in, and log out.
- Create tasks: Users can add new tasks with a title and description.
- Update tasks: Users can mark tasks as completed or edit task details.
- Delete tasks: Users can remove tasks from their list.
- Search tasks: Users can search for a specific task from their list.
- Responsive design: The application is designed to work seamlessly across different devices.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/DevTheKar/django-todo-list.git
   ```

2. Navigate to the project directory:

   ```bash
   cd django-todo-list
   ```

3. Apply migrations:

   ```bash
   python manage.py migrate
   ```

4. Run the development server:

   ```bash
   python manage.py runserver
   ```

5. Access the application in your web browser at [http://localhost:8000](http://localhost:8000).

## Usage

- Sign up for a new account or log in if you already have one.
- Once logged in, you'll be redirected to the dashboard where you can view, add, edit, search, or delete tasks.
- To add a new task, click on the "Add Task" button and fill in the details.
- To mark a task as completed, click on the checkbox in the task editor.
- To edit a task, click on the task title and update the details.
- To delete a task, click on the "X" icon next to the task.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License
