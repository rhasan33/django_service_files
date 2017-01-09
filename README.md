# Django Services
To run a django application in server we may need to run some `systemd` service commands.
Here are those:

1. `celery.service`
2. `celerybeat.service`
3. `emperor.uwsgi.service`

# Where to save the files
1. `/etc/systemd/system/emperor.uwsgi.service`
2. `/etc/systemd/system/celery.service`
3. `/etc/systemd/system/celerybeat.service`
