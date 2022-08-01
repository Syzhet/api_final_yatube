# REST API Yatube
API включает в себя посты, комментарии, подписчиков и группы. Авторизация реализованна через JWT-токен.

## Стек технологий 

<div>
  <a href="https://www.python.org/">
    <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  </a>
  <a href="https://www.djangoproject.com/">
    <img src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain.svg" title="Django" alt="Django" width="40" height="40"/>&nbsp;
  </a>
  <a href="https://github.com/">
    <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" title="GitHub" alt="GitHub" width="40" height="40"/>&nbsp;
  </a>
</div>

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```sh
git clone git@github.com:yandex-praktikum/api_final_yatube.git
```

Перейти в диреторию
```sh
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:
```sh
python -m venv venv
```
```sh
source venv/Scripts/activate
```

Обновить pip:
```sh
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:
```sh
pip install -r requirements.txt
```

Выполнить миграции:
```sh
python manage.py migrate
```

Создайте суперпользователя
```sh
python manage.py createsuperuser
```

Запустить проект:
```sh
python manage.py runserver
```

## Документация
Чтобы открыть документацию, запустите сервер и перейдите по ссылке:
http://127.0.0.1:8000/redoc/
