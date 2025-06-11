# Django First Project

This project follows the [official Django tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/).

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd django-first
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install Django:**
    ```bash
    pip install django
    ```

4. **Run migrations:**
    ```bash
    python manage.py migrate
    ```

5. **Start the development server:**
    ```bash
    python manage.py runserver
    ```

## Resources

- [Django Documentation](https://docs.djangoproject.com/en/stable/)
- [Django Tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/)

## Project Structure

- `manage.py` - Django project management script
- `mysite/` - Main project settings and configuration
- `polls/` - Django app created during the tutorial

## License

This project is for learning purposes following the Django tutorial.