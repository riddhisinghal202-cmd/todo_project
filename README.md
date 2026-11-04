 Django To-Do List Web Application

A simple and interactive **To-Do List Web Application** developed using Python and Django. This project helps users organize their daily activities by creating, managing, updating, and tracking tasks through a clean and user-friendly interface.

Project Overview

The Django To-Do List Application provides an easy way to manage everyday tasks. Users can add new tasks, view all existing tasks, update task details, mark tasks as completed, and delete tasks when they are no longer needed.

The application uses SQLite to store task information, making task management simple and efficient.

Features

- **Add Tasks:** Create new tasks with a title and description.
- **View All Tasks:** Display all tasks in an organized table.
- **Edit Tasks:** Update existing task details.
- **Delete Tasks:** Remove tasks that are no longer required.
- **Mark as Completed:** Mark tasks as done using a checkbox.
- **Task Creation Date:** View when each task was created.
- **Database Integration:** Store task information using SQLite.

Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Django | Web application framework |
| HTML | Web page structure |
| CSS | Styling and layout |
| SQLite | Database management |

 Project Structure

```text
todo_project/
│
├── tasks/
│   ├── migrations/
│   ├── templates/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── todo_project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── static/
├── templates/
├── db.sqlite3
└── manage.py
```

Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/django-todo-list.git
```

### 2. Navigate to the project directory

cd django-todo-list


### 3. Create a virtual environment


python3 -m venv venv


### 4. Activate the virtual environment

source venv/bin/activate


### 5. Install dependencies

pip install -r requirements.txt


### 6. Apply database migrations

python manage.py migrate


### 7. Run the development server

python manage.py runserver

 Database

This application uses SQLite as its database.

Task records include:
- Task ID
- Title
- Description
- Completion status
- Creation date and time

Learning Outcomes

Through this project, I gained practical experience in:

- Django project structure and application development.
- Creating models and managing databases.
- Implementing CRUD (Create, Read, Update, Delete) operations.
- Handling URL routing and views.
- Working with HTML templates.
- Integrating SQLite with Django.
- Running and testing a local development server.


 Author

**Riddhi Singhal**

