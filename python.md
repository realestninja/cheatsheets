## django
```bash
# install dependencies
pip3 install Django pylint pylint-django

# create new project
django-admin startproject '<PROJECT_NAME>'

# add sub-app to project
python3 manage.py startapp '<APP_NAME>'

# start server
python3 manage.py runserver

# create migration
python3 manage.py makemigrations

# migrate db
python3 manage.py migrate

# create superuser for admin panel
python3 manage.py createsuperuser

# collect static files into one folder
python3 manage.py collectstatic
```

## gunicorn
```bash
# restart a gunicorn service
sudo systemctl restart gunicorn
```

## twine
```bash
# generate distribution files (from within project's root folder)
python -m build # requires build package - pip install build

# upload generated distribution files to pypi
twine upload '<DIST_FOLDER_WITH_GENERATED_PACKAGES>'/*
```