# BookStore Management Webapp with Django

A Django-based web application for managing a bookstore, providing functionalities such as adding, editing, and deleting books, as well as user authentication.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add, edit, and delete books.
- User authentication for secure access.
- View and search the bookstore inventory.

## Installation

Ensure you have Python and pip installed on your system. Create and activate a virtual environment to keep your project dependencies isolated.

### Create a virtual environment (Linux/macOS)
```
python3 -m venv venv
```

### Activate the virtual environment (Linux/macOS)
```
source venv/bin/activate
```
### Create a virtual environment (Windows)
```
python -m venv venv
```
### Activate the virtual environment (Windows)
```
.\venv\Scripts\activate
```

### Install the project dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Before running the project, apply migrations to set up the database:

```bash
python manage.py migrate
```

### Create a superuser account for admin access:

```bash
python manage.py createsuperuser
```

### Start the development server:

```bash
python manage.py runserver
```

Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your web browser to view the project.

## Usage

1. Log in using the admin account created during the superuser creation.
2. Navigate to the "Books" section to manage the bookstore inventory.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
