# Ejemplo Django Project

A Django project configured for GitHub Codespaces development.

## Getting Started with Codespaces

This project is configured to work seamlessly with GitHub Codespaces. To start developing:

1. Click on the "Code" button in the GitHub repository
2. Select the "Codespaces" tab
3. Click "Create codespace on main" (or your desired branch)

The development environment will automatically:
- Set up Python 3.9
- Install all dependencies from `requirements.txt`
- Configure VS Code with Django-specific extensions
- Forward port 8000 for the Django development server

## Development

Once your Codespace is ready, you can:

### Run the Django development server:
```bash
python manage.py runserver
```

### Run tests:
```bash
python manage.py test
```

## VS Code Extensions

The following extensions are automatically installed:
- Python
- Pylance
- Black Formatter
- Pylint
- Django
- Jinja

## Features

- **Python 3.9** development environment
- **Automatic dependency installation** from requirements.txt
- **Port forwarding** for Django dev server (port 8000)
- **Pre-configured linting and formatting** tools
- **Django-specific** VS Code extensions
