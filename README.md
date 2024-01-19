# Django To-Do List App

A simple to-do list web application built using Django.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Django project is a basic to-do list application that allows users to create, update, and delete tasks.

## Features

- Create tasks with a title.
- Mark tasks as completed.
- Update and delete tasks.
- Responsive design for various screen sizes.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/django-todo-list.git
    ```

2. Navigate to the project directory:

    ```bash
    cd django-todo-list
    ```

3. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

5. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

7. Create a superuser account:

    ```bash
    python manage.py createsuperuser
    ```

8. Run the development server:

    ```bash
    python manage.py runserver
    ```

9. Access the application at [http://localhost:8000](http://localhost:8000) in your web browser.

## Usage

- Visit the admin interface at [http://localhost:8000/admin/](http://localhost:8000/admin/) to manage tasks.
- Create a new task by visiting the home page and using the "Create Task" form.

## Contributing

Contributions are welcome! If you find a bug or have a feature suggestion, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
