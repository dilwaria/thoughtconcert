web: gunicorn config.wsgi:application
worker: celery worker --app=thoughtconcert.taskapp --loglevel=info
