# 📝 To-Do List Web Application

This is my first project!

A simple, clean, and user-friendly To-Do List application built with **Django** and styled with **Bootstrap**. It allows users to manage daily tasks efficiently through a simple web interface.

---

## ✅ Features

- **Create, Read, Update, Delete (CRUD) Operations:**
  - ➕ **Add Tasks**: Add tasks using a simple input form.
  - 📋 **View All Tasks**: Display a list of current tasks.
  - ✅ **Mark as Complete**: Completed tasks are visually struck through.
  - 🗑 **Delete Tasks**: Remove tasks when no longer needed.

- **Modern UI**:
  - Built with **Bootstrap 5** for responsive, mobile-first design.
  - Clean card-based layout enhances user experience.

- **Dark/Light Mode Toggle**:
  - Theme switcher for light/dark mode.
  - Saves user’s preference using `localStorage`.

- **Developer Credit**:
  - Footer includes a link to the [developer's GitHub profile](https://github.com/iankit-sachan)

---

## 🔧 Technologies Used

- **Backend**: Python, Django  
- **Frontend**: HTML5, CSS3, JavaScript  
- **Styling**: Bootstrap 5  
- **Database**: SQLite 3 (default)

---

## 🚀 Setup and Installation

To get a local copy up and running, follow these steps:

### 🔹 Prerequisites

- Python 3.x  
- pip (Python package installer)

### 🔹 Installation

Clone the repository:

```bash
git clone https://github.com/iankit-sachan/To-Do-List.git
cd To_do_list

python -m venv venv
venv\Scripts\activate

python3 -m venv venv
source venv/bin/activate

pip install Django

python manage.py migrate

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

🧑‍💻 Author
Developed by Ankit Sachan

