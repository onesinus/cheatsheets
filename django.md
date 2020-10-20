# Django Cheatsheets

| Description                                 | Version | Command                                                   |
|-------------                                |---------|---------                                                  |
|Membuat virtual ENV                          |3        |python3 -m venv venv                                       |
|Menjalankan server                           |2        |python manage.py runserver                                 |
|Membuat Project Baru                         |2        |python manage.py startproject [nama_project]               |
|Membuat App Baru                             |2        |python manage.py startapp [nama_app]                       |
|Masuk ke shell                               |2        |python manage.py dbshell                                   |
|Membuat migration                            |2        |python manage.py makemigrations [nama_app]                 |
|Melihat bentuk sql yang akan dimigrate       |2        |python manage.py sqlmigrate [nama_app] [migration_code]    |
|Menjalankan migration                        |2        |python manage.py migrate                                   |
|Menambahkan superuser                        |2        |python manage.py createsuperuser                           |
