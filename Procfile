web: gunicorn genevieve_client.wsgi --log-file -
worker: celery -A genevieve_client worker -l info
