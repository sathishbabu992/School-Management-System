 # School-Management-System

## How To Setup On Windows
1. Download & unzip `sms` project
2. Go To Project Directory `cd sms `
3. Create a Virtual Environment `python -m venv venv`
4. Activate Virtual Environment ` venv/scripts/activate`
5. Install Requirements Package `pip install -r requirements.txt`
6. Migrate Database `python manage.py migrate`
7. Create Super User `python manage.py createsuperuser`
8. Finally Run The Project `python manage.py runserver`
