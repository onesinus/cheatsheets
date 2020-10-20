# Django Cheatsheets

| Description                                 | Version | Command                                                   |
|-------------                                |---------|---------                                                  |
|Cek versi                                    |2        |python -m django --version                                 |
|Membuat virtual ENV                          |3        |python3 -m venv venv                                       |
|Masuk virtual ENV                            |2        |source venv/bin/activate atau . venv/bin/activate          |
|Keluar virtual ENV                           |2        |deactivate                                                 |
|Install django                               |2        |pip install django                                         |
|Menginstall dependensi yang dibutuhkan django|2        |pip install -r requirements.txt                            |
|Cek package yang terinstall di virtual env   |2        |pip freeze                                                 |
|Menjalankan server                           |2        |python manage.py runserver                                 |
|Membuat Project Baru                         |2        |django-admin startproject [nama_project]                   |
|Membuat App Baru                             |2        |python manage.py startapp [nama_app]                       |
|Masuk ke shell                               |2        |python manage.py dbshell                                   |
|Membuat migration                            |2        |python manage.py makemigrations [nama_app]                 |
|Melihat bentuk sql yang akan dimigrate       |2        |python manage.py sqlmigrate [nama_app] [migration_code]    |
|Menjalankan migration                        |2        |python manage.py migrate                                   |
|Menambahkan superuser                        |2        |python manage.py createsuperuser                           |
|Menjalankan test                             |2        |python manage.py test [nama_app]                           |
