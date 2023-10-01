# DRF Pastebin Application

## Overview

This is a simple implementation of a Pastebin-like application using Django Rest Framework (DRF). It allows users to create, retrieve, update, and delete code snippets or "pastes" via a RESTful API.

## Features

- Create and store code snippets.
- Retrieve and list existing code snippets.
- Update and delete code snippets.
- Browsable API for easy testing and interaction.

## Getting Started

Follow these steps to set up and run the application:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/tarunkeshukumar/django-rest-framework-snippet-app.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Apply database migrations:

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Create a superuser account to access the admin panel:

   ```bash
   python manage.py createsuperuser
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

## API Endpoints

- `GET /pastes/`: List all pastes.
- `POST /pastes/`: Create a new paste.
- `GET /pastes/<int:pk>/`: Retrieve a specific paste.
- `DELETE /pastes/<int:pk>/`: Delete a specific paste.

## Contributing

Contributions are welcome! If you'd like to improve this project or add new features, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by the Pastebin service.
- Built using Django and Django Rest Framework.

---
