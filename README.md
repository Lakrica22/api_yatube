# *API для Yatube *
Реализован API для всех моделей ранее написанного приложения Yatube.

# **Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:Lakrica22/api_yatube.git
```
```
cd api_yatube
```
Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
```
```
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
Выполнить миграции:
```
python3 manage.py migrate
```
Запустить проект:
```
python3 manage.py runserver
```

