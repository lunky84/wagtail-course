# Wagtail course

### Setup codebase

```shell
cd ~/projects/personal
git clone git@github.com:lunky84/wagtail-course.git
cd wagtail-course
```

### Run vscode dev container

```shell
devcontainer open
```

### Run the server
```shell
python manage.py runserver
```

View the site at http://127.0.0.1:8000/

### Make migrations

```shell
python manage.py makemigrations polls
```

### Run migrations

```shell
python manage.py migrate
```