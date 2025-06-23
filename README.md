# To-Do-List
This is the my first project

To-Do List Web Application
A simple, clean, and user-friendly To-Do List application built with Django and styled with Bootstrap. This project allows users to manage their daily tasks efficiently through an intuitive web interface.

'''Features
◽Create, Read, Update, Delete (CRUD) Operations:
   ▪ Add Tasks: Quickly add new tasks through a simple input form.
   ▪ View All Tasks: See a list of all current tasks.
   ▪ Mark as Complete: Mark tasks as completed, which visually strikes them through.
   ▪ Delete Tasks: Remove tasks that are no longer needed.
◽Modern User Interface:
   ▪Styled with Bootstrap 5 for a responsive and mobile-first design.
   ▪Features a clean card-based layout for better user experience.
◽Dark/Light Mode Toggle:
   ▪ Includes a theme switcher to toggle between light and dark modes.
   ▪ Saves the user's theme choice in the browser's localStorage for persistence across sessions.
◽Developer Credit:
   ▪ Contains a footer acknowledging the developer with a link to their GitHub profile.
🔗Technologies Used
   ▪ Backend: Python, Django
   ▪ Frontend: HTML5, CSS3, JavaScript
   ▪ Styling: Bootstrap 5
   ▪ Database: SQLite 3 (default)

◽Setup and Installation
   To get a local copy up and running, follow these simple steps.

Prerequisites
- Python 3.x
- pip (Python package installer)
- Installation
- Clone the repository:

Bash

git clone https://github.com/iankit-sachan/your-repository-name.git
cd To_do_list
Create and activate a virtual environment:

Bash

# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
Install the required packages:
(It's recommended to create a requirements.txt file by running pip freeze > requirements.txt)

Bash

pip install Django
Apply database migrations:
This will create the db.sqlite3 file and set up the Task model schema.

Bash

python manage.py migrate
Run the development server:

Bash

python manage.py runserver
Open your web browser and navigate to http://127.0.0.1:8000/.
'''
Project Structure
<pre><code>
To_do_list/
├── todo/                     # Main Django app
│   ├── migrations/           # Database migration files
│   ├── templates/            # HTML templates
│   │   └── todo/
│   │       └── index.html    # Main page template
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py              # Contains the TaskForm
│   ├── models.py             # Defines the Task model
│   ├── tests.py
│   ├── urls.py               # App-specific URLs
│   └── views.py              # Application logic (index, delete, complete)
├── To_do_list/               # Django project directory
│   ├── settings.py           # Project settings
│   ├── urls.py               # Project-level URLs
│   └── ...
└── manage.py                 # Django's command-line utility
   </code></pre>
