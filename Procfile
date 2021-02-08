web: gunicorn --bind 0.0.0.0:$PORT app:app
worker: rq worker -u $REDIS_URL app-tasks