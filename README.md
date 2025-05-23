# Weather_App

A modern Django-based weather application that provides real-time weather information with a beautiful, responsive UI.

## Features..

- Real-time weather data from OpenWeatherMap API
- User authentication and profile management
- Save favorite locations
- Hourly and weekly forecasts
- Dynamic UI that changes based on weather conditions
- Dark/Light mode toggle
- Responsive design for all devices
- Weather alerts and notifications
- Location-based weather suggestions

## Setup Instructions..

1. Clone the repository
```bash
git clone <repository-url>
cd weather-app
```

2. Create and activate virtual environment
```bash
python -m venv venv
source venv/bin/activate  
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Create .env file in the root directory with the following variables:
```
SECRET_KEY=your_django_secret_key
DEBUG=True
OPENWEATHER_API_KEY=your_openweather_api_key
```

5. Run migrations
```bash
python manage.py migrate
```

6. Install and build Tailwind CSS
```bash
python manage.py tailwind install
python manage.py tailwind build
```

7. Run the development server
```bash
python manage.py runserver
```

Visit http://localhost:8000 to see the application.

## Tech Stack..

- Backend: Django 5.0
- Frontend: HTML, Tailwind CSS, HTMX
- Database: PostgreSQL/SQLite
- API: OpenWeatherMap
- Task Queue: Celery + Redis
- Deployment: Docker ready

## Contributing..

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



#   W e a t h e r _ A p p  
 