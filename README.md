# Django Girls Tutorial Project

This is a simple blog website built by following the [Django Girls Tutorial](https://tutorial.djangogirls.org/en/).  
It was created as a learning exercise to understand the basics of web development using Python and Django.

## Features

- Blog post creation (admin interface)
- Homepage that displays blog posts
- Basic templating with Django
- Simple styling with CSS
- Deployed with PythonAnywhere (optional)

## How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone <your-repo-url>
   cd <your-project-folder>
   ```
2. **Create a virtual environment:**

    ```
    python -m venv myvenv
    source myvenv/bin/activate  # On Windows: myvenv\Scripts\activate
    ```
3. **Install requirements:**

    ```
    pip install -r requirements.txt
    ```
4. **Apply migrations:**

    ```
    python manage.py migrate
    ```
5. **Create a superuser (for admin access):**

    ```
    python manage.py createsuperuser
    ```
6. **Run the server:**

    ```
    python manage.py runserver
    ```
    
**Open your browser and go to:**
http://127.0.0.1:8000/ — to view the site
http://127.0.0.1:8000/admin/ — to access the admin panel

**Notes**
This project was built step-by-step using the Django Girls Tutorial.

It is intended for learning purposes and may not include advanced features or best practices.