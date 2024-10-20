
# Task Organizer

This repository contains the solution for a **Task Organizer** project, built using Django.

## Project Structure

The project is organized into separate folders for each component. Each folder contains the necessary files for a specific functionality, such as models, views, templates, and static files.

### Task Organizer Application Structure

```
To_Do_List_Application/
├── env/
├── To_Do_List/
│   ├── tasks/
│   │   ├── __pycache__/
│   │   ├── migrations/
│   │   ├── templates/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── forms.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── To_Do_List/
│   │   ├── __pycache__/
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── db.sqlite3
│   └── manage.py
```

## Getting Started

### Cloning the Repository

To get a local copy of this project, clone it using git:

```bash
git clone https://github.com/Gaganjeet15/Task_Organizer.git
cd Task_Organizer
```

### Installation

For the **Task Organizer*, you need to follow these steps:

1. Navigate to the To-Do List application folder:
   ```bash
   cd path/to/Task_Organizer/To_Do_List_Application
   ```

2. Create and activate a virtual environment:
   - On Windows:
     ```bash
     env\Scriptsctivate
     ```
   - On macOS and Linux:
     ```bash
     source env/bin/activate
     ```

3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` doesn't exist, you can generate it by running:
   ```bash
   pip freeze > requirements.txt
   ```

### Database Setup

The SQLite database (`db.sqlite3`) is already included in the project. If you need to apply any new migrations or create a superuser, follow these steps:

1. Apply migrations:
   ```bash
   python manage.py migrate
   ```

2. (Optional) Create a superuser to access the Django admin interface:
   ```bash
   python manage.py createsuperuser
   ```

## Usage

To run the To-Do List application:

1. Ensure you're in the directory containing `manage.py` (To_Do_List_Application/To_Do_List/).
2. Run the following command to start the Django development server:
   ```bash
   python manage.py runserver
   ```
3. Open a web browser and go to `http://127.0.0.1:8000/` to access the To-Do List application.

## Features

- View a list of all tasks
- Add new tasks
- Mark tasks as complete

## Dependencies

- Python 3.12.1
- Django

## Contributing

This project is a personal project, and it is not currently open for contributions.

## License

This project is for personal and educational use.
