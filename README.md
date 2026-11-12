# Django online course application

An IBM Developer Skills Network coursework starter for an online course catalogue with user accounts, lessons and enrolment.

## Implemented structure

The `onlinecourse` app contains:

- Instructor, learner, course, lesson and enrolment models.
- Registration, login and logout views.
- Course list/detail views and an enrolment flow.
- Django templates and static assets.

## Assessment exercise

The original course asks students to add questions, choices, submissions and exam results. In this snapshot those models and views remain instructions and commented examples. The assessment feature is unfinished, and `onlinecourse/tests.py` is still a placeholder.

## Layout

- `manage.py` — Django management commands.
- `myproject/` — project configuration.
- `onlinecourse/` — models, views, routes and templates.
- `static/` — course images and other assets.

## Development setup

The pinned Django, Pillow and Gunicorn versions come from the original course environment. Use a compatible isolated environment when working with this historical snapshot.

```sh
python -m venv .venv
. .venv/bin/activate
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Dependency updates, the assessment feature and meaningful automated tests are follow-up work.

## Attribution

Forked from [IBM Developer Skills Network](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database). The original [Apache 2.0 licence](LICENSE) is retained.
