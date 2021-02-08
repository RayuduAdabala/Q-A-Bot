web: gunicorn --bind 127.0.0.1:6379 app:app
worker: rq worker -u $REDIS_URL app-tasks