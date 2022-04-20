# Diary Snack
* This a personal diary for your personal environment.

## Tools used:
* [Django](https://www.djangoproject.com/)
* [Sqlite](https://www.sqlite.org/index.html)
* [Git](https://git-scm.com/)

## Get Started
* **NB**: Run commands in the terminal (linux).

* Clone project & change into cloned folder project
```
git clone https://github.com/Xerrex/diary-snack.git

cd diary-snack
```

* Create virtual environment & activate.
```
python3 venv venv

source venv/bin/activate
```

* Install dependancies
```
pip install -r requirements.txt
```

## Running Project
* Create a Super User **for access to your diary**.
```
python manage.py createsuperuser
```

* Run the project
```
python manage.py runserver
```

* View the diary in the browser.
open [localhost:8000](http://127.0.0.1:8000/)

