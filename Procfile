web: newrelic-admin run-program gunicorn --pythonpath="$PWD/sherlock" wsgi:application
worker: python sherlock/manage.py rqworker default