# Создание пустого проекта.

Python-Terminal-Command Prompt

# Переход на директорию для создания там будущего проекта
cd D:\

# Установка Django
pip install django

# Создание нового проекта
django-admin startproject first_django_project

# Переход в папку с созданным проектом
cd first_django_project

# Создание приложения
python manage.py startapp first_app

# Запуск миграции
python manage.py migrate

# Запуск сервера
python manage.py runserver
