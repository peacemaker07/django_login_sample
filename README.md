# django_login_sample
Djangoのログイン関連のサンプル

## Requirement

- python 3.7

## Install

### clone

```
$ git clone https://github.com/peacemaker07/django_login_sample.git
```

### create env and activate

```
$ cd django_login_sample
$ python3.7 -m venv env
$ source env/bin/activate
```

### install django and migrate

```
(env) $ pip install -r requirements.txt
(env) $ python manage.py migrate
```

### create superuser

```
(env) $ python manage.py createsuperuser
```

## Usage

