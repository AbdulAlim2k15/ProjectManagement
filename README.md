# Project Management API

This project provides a RESTful API for managing users, projects, tasks, and comments. It uses Django and Django REST Framework to create the backend, and it supports JWT (JSON Web Token) authentication for secure access to the API endpoints.

## Features

- **User Authentication**: Users can register, log in, and authenticate using JWT tokens.
- **Project Management**: Create, update, delete, and list projects.
- **Task Management**: Create, update, delete, and list tasks associated with projects.
- **Comment Management**: Add, edit, delete, and view comments on tasks.
- **JWT Authentication**: Access to most API endpoints requires valid JWT tokens.





### Steps to Set Up

1. **Create and open a folder and  Create a virtual environment inside that folder **:
     ```bash
    python -m venv venv
    ```
2. **Activate the virtual environment**:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```
3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Clone the repository**:
   ```bash
    git clone https://github.com/AbdulAlim2k15/ProjectManagement.git
    ```
5. **navigate to the ProjectManagement folder**:
   ```bash
    cd projectmanagement
    ```
6. **Database migrations**:
      ```bash
      python manage.py makemigrations
      python manage.py migrate
      ```

7. **Create a superuser (optional, for admin access)**:
    ```bash
    python manage.py createsuperuser
    ```

8. **Run the development server**:
    ```bash
    python manage.py runserver
    ```



