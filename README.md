# Django To-Do List

A simple and intuitive to-do list application built with Django. This project demonstrates the core functionalities of a task management app, including creating, updating, and deleting tasks, as well as marking tasks as complete or incomplete.

## Features

- **Create Task**: Add new tasks to your to-do list.
- **View Tasks**: See all your tasks in a list.
- **Update Task**: Edit existing tasks.
- **Delete Task**: Remove tasks from your list.
- **Complete/Incomplete**: Mark tasks as complete or incomplete.

## Technologies Used

- Django
- Python
- SQLite (default database)
- HTML/CSS (for front-end)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SuhailAhmedd/django-todolist.git
   cd django-todolist
   ```

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for accessing the Django admin interface):**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

7. **Open your browser and go to:** `http://127.0.0.1:8000/`

## Usage

- **Home Page**: Displays all tasks.
- **Add Task**: Navigate to `/tasks/new/` to add a new task.
- **Edit Task**: Click on a task to edit it.
- **Delete Task**: Click on the delete button next to a task to remove it.
- **Mark as Complete/Incomplete**: Use the checkbox to mark tasks as complete or incomplete.

## Project Structure

- `myapp/` - The Django app containing core functionality.
  - `models.py` - Defines the data models for tasks.
  - `views.py` - Contains logic for handling requests and responses.
  - `urls.py` - Maps URLs to views.
  - `templates/` - Contains HTML templates.
- `django_todolist/` - The project directory.
  - `settings.py` - Configuration settings for the Django project.
  - `urls.py` - Project-level URL routing.
- `manage.py` - A command-line utility for administrative tasks.
- `db.sqlite3` - SQLite database file (default).

## Contributing

Feel free to submit issues or pull requests. If you have any suggestions or improvements, they are more than welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
