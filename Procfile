web: gunicorn --bind 0.0.0.0:6379 app:app
worker: rq worker -u $REDIS_URL app-tasks