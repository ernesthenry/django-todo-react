## Introduction

This is a simple Todo application built using Django, including the Django REST Framework for API CRUD operations, and React for the frontend. The app allows users to create, read, update, and delete tasks, and also filter them based on their completion status.

## Requirements

- Python 3.x
- Pipenv (for managing Python dependencies)
- Node.js and npm (for managing React dependencies)

## Getting Started

Follow these steps to set up the project on your local machine:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/<account_name>/django-todo-react.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd django-todo-react
    ```

3. **Activate the virtual environment:**

    ```bash
    pipenv shell
    ```

4. **Install Python dependencies:**

    ```bash
    pipenv install
    ```

5. **Navigate to the frontend directory:**

    ```bash
    cd frontend
    ```

6. **Install React dependencies:**

    ```bash
    npm install
    ```

## Running the Application

You will need two terminals to start both the backend and frontend servers.

1. **Start the backend server** from the `backend` directory:

    ```bash
    python manage.py runserver
    ```

    Ensure that you are within the virtual environment when running this command.

2. **Start the frontend development server** from the `frontend` directory:

    ```bash
    npm start
    ```

    The frontend will be available at [localhost:3000](http://localhost:3000).

## Built With

- [React](https://reactjs.org) - A JavaScript library for building user interfaces.
- [Python](https://www.python.org/) - A versatile programming language.
- [Django](https://www.djangoproject.com/) - A high-level Python web framework that encourages rapid development and clean, pragmatic design.

## Creator Credit

- Kato Ernest Henry
