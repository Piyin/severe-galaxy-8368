web: python piyin/manage.py run_gunicorn -b "0.0.0.0:$PORT" -w 3
worker: python piyin/manage.py celeryd -E -B --loglevel=INFO
