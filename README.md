# django_rest_api


rm -f db.sqlite3
rm -r snippets/migrations
python manage.py makemigrations snippets
python manage.py migrate

python manage.py createsuperuser
python manage.py runserver