# django_rest_api


rm -f db.sqlite3 <br>
rm -r snippets/migrations <br>
python manage.py makemigrations snippets <br>
python manage.py migrate <br>

python manage.py createsuperuser <br>
python manage.py runserver <br>
