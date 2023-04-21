```
pip3 install 'django<4' gunicorn

pip3 install dj_database_url==0.5.0 psycopg2-binary

pip3 install dj3-cloudinary-storage

pip3 freeze --local > requirements.txt

pip show django

export PATH=$PATH:/Users/sergeykostanets/Library/Python/3.11/bin

django-admin --version

django-admin startproject codeblog .

python3 manage.py startapp blog
```

Add app to installed apps in settings.py

```
python3 manage.py migrate --plan

python3 manage.py migrate

python3 manage.py runserver
```