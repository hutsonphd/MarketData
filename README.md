# Market Data Web App
## What is it?
This is a simple templated site to use as a foundation for getting started with any Django web app. It uses Postgresql instead of the standard SQLLite and the All Auth package for authenticating regular accounts and social media accounts. I used a free template built with Bootstrap 5 as the foundation allowing for ready-to-go responsive design.  Finally, it show cases Chart.js on the home page to demonstrate a dashboard layout. 

## Deploy for Docker
1. Install Docker
2. Run docker-compose from the root directory
3. You’re done!

## Deploy without Docker
1. Download and Install Postgresql
2. Configure your user name and password
3. Update settings.py accordingly
4. Run `source bin/activate`
5. Run `pip install -r requirements.txt`
6. Run `python manage.py runserver`

## Tech Stack
- Python
- Django
- All Auth
- Bootstrap 5
- Chart.js
- Postgresql
- Docker
