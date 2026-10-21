# LinkUp

A Django REST Framework social application focused on user accounts and friendships, with chat functionality planned/in progress.

## Tech Stack
- Python
- Django
- Django REST Framework
- SimpleJWT (authentication; verify current configuration in settings)

## Setup
1. Create and activate a virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure environment variables and development settings.
4. Run migrations and start the server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

## Database
The local SQLite database is excluded. Use migrations to initialize your own database.

## Security
Never commit secret keys, tokens, user data, or local database files.
