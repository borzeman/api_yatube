# api_final
## Описание
Прикручиваем API ко всем моделям приложения posts

## Задействованные технологии
asgiref==3.5.2
attrs==22.1.0
Django==3.2
djangorestframework==3.12.4
iniconfig==1.1.1
packaging==21.3
Pillow==9.3.0
pluggy==0.13.1
py==1.11.0
pyparsing==3.0.9
pytest==6.2.4
pytest-django==4.4.0
pytest-pythonpath==0.7.3
pytz==2022.6
sqlparse==0.4.3
toml==0.10.2

## Инструкция по запуску
- Склонируйте репозиторий в локальное хранилище:
```
git clone <repository_link>
```
- Создайте и активируйте виртуальное окружение:
```
python3 -m venv venv
source venv/bin/activate
```
- Обновите пакетный менеджер до последней версии:
```
pip install --upgrade pip
```
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
```
- Сформируйте и проведите миграции из папки, содержащей manage.py
```
python manage.py makemigrations
python manage.py migrate
```
- Проект можно запускать следующей командой:
```
python manage.py runserver
```